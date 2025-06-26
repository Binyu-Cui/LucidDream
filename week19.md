# Week 19

### Labs

# Unity教室互动游戏完整架构图

```mermaid
flowchart TD
    Start([游戏开始]) --> MainHub[MainHub场景<br/>主场景入口]
    
    MainHub --> C1[Classroom1场景<br/>教室互动]
    MainHub --> C2[Classroom2场景<br/>教室互动]
    MainHub --> C3[Classroom3场景<br/>教室互动]
    MainHub --> C4[Classroom4场景<br/>教室互动]
    
    C1 --> |选择+1/-1| DataManager{GameDataManager<br/>数据管理}
    C2 --> |选择+1/-1| DataManager
    C3 --> |选择+1/-1| DataManager
    C4 --> |选择+1/-1| DataManager
    
    C1 --> |完成后| MainHub
    C2 --> |完成后| MainHub
    C3 --> |完成后| MainHub
    
    C4 --> |第4个教室完成| Decision{分数判断}
    
    Decision --> |分数≥0| PositiveEnding[PositiveEnding场景<br/>正分结局视频]
    Decision --> |分数<0| NegativeEnding[NegativeEnding场景<br/>负分结局视频]
    
    PositiveEnding --> |按任意键| FinalEnding[FinalEnding场景<br/>最终结局视频]
    NegativeEnding --> |按任意键| FinalEnding
    
    FinalEnding --> |按任意键| GameEnd([游戏结束])
    
    %% 样式定义
    classDef sceneBox fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000
    classDef scriptBox fill:#f3e5f5,stroke:#4a148c,stroke-width:2px,color:#000
    classDef dataBox fill:#e8f5e8,stroke:#1b5e20,stroke-width:2px,color:#000
    classDef videoBox fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000
    
    class MainHub,C1,C2,C3,C4 sceneBox
    class PositiveEnding,NegativeEnding,FinalEnding videoBox
    class DataManager,Decision dataBox
```

###  场景结构
```
Unity教室互动游戏
├── MainHub场景 (主入口场景)
├── Classroom1场景 (教室1)
├── Classroom2场景 (教室2)  
├── Classroom3场景 (教室3)
├── Classroom4场景 (教室4)
├── PositiveEnding场景 (正分结局)
├── NegativeEnding场景 (负分结局)
└── FinalEnding场景 (最终结局)
```

### 核心脚本依赖

| 场景类型 | 主要脚本 | 作用 |
|---------|----------|------|
| **MainHub** | `ClassroomEntrance.cs` | 教室入口按钮控制 |
| **Classroom1-4** | `ClassroomController.cs` | 教室内音频UI交互 |
| **所有场景** | `GameDataManager.cs` | 全局数据和场景管理 |
| **结局场景** | `EndingVideoController.cs` | 视频播放和跳转控制 |

### 游戏流程

```
开始游戏 → MainHub显示4个教室按钮
       ↓
选择教室 → 进入对应Classroom场景
       ↓  
播放音频 → 显示UI → 玩家选择(+1/-1) → 返回MainHub
       ↓
重复流程直到完成4个教室
       ↓
触发结局 → 根据总分播放对应结局视频
       ↓
按任意键 → 播放最终结局视频
       ↓
按任意键 → 游戏结束
```

