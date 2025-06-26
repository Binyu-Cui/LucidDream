# Unity Classroom Interactive Game Complete Architecture

```mermaid
flowchart TD
    Start([Game Start]) --> MainHub[MainHub Scene<br/>Main Entry Scene]
    
    MainHub --> C1[Classroom1 Scene<br/>Classroom Interaction]
    MainHub --> C2[Classroom2 Scene<br/>Classroom Interaction]
    MainHub --> C3[Classroom3 Scene<br/>Classroom Interaction]
    MainHub --> C4[Classroom4 Scene<br/>Classroom Interaction]
    
    C1 --> |Choose +1/-1| DataManager{GameDataManager<br/>Data Management}
    C2 --> |Choose +1/-1| DataManager
    C3 --> |Choose +1/-1| DataManager
    C4 --> |Choose +1/-1| DataManager
    
    C1 --> |After Completion| MainHub
    C2 --> |After Completion| MainHub
    C3 --> |After Completion| MainHub
    
    C4 --> |4th Classroom Complete| Decision{Score Decision}
    
    Decision --> |Score ≥ 0| PositiveEnding[PositiveEnding Scene<br/>Positive Score Ending Video]
    Decision --> |Score < 0| NegativeEnding[NegativeEnding Scene<br/>Negative Score Ending Video]
    
    PositiveEnding --> |Press Any Key| FinalEnding[FinalEnding Scene<br/>Final Ending Video]
    NegativeEnding --> |Press Any Key| FinalEnding
    
    FinalEnding --> |Press Any Key| GameEnd([Game End])
    
    %% Style definitions
    classDef sceneBox fill:#e1f5fe,stroke:#01579b,stroke-width:2px,color:#000
    classDef scriptBox fill:#f3e5f5,stroke:#4a148c,stroke-width:2px,color:#000
    classDef dataBox fill:#e8f5e8,stroke:#1b5e20,stroke-width:2px,color:#000
    classDef videoBox fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000
    
    class MainHub,C1,C2,C3,C4 sceneBox
    class PositiveEnding,NegativeEnding,FinalEnding videoBox
    class DataManager,Decision dataBox
```

## Game Overall Architecture

### Scene Structure
```
Unity Classroom Interactive Game
├── MainHub Scene (Main Entry Scene)
├── Classroom1 Scene (Classroom 1)
├── Classroom2 Scene (Classroom 2)  
├── Classroom3 Scene (Classroom 3)
├── Classroom4 Scene (Classroom 4)
├── Classroom...
├── PositiveEnding Scene (Positive Score Ending)
├── NegativeEnding Scene (Negative Score Ending)
└── FinalEnding Scene (Final Ending)
```

### Core Script Dependencies

| Scene Type | Main Script | Purpose |
|------------|-------------|---------|
| **MainHub** | `ClassroomEntrance.cs` | Classroom entrance button control |
| **Classroom1-4** | `ClassroomController.cs` | In-classroom audio UI interaction |
| **All Scenes** | `GameDataManager.cs` | Global data and scene management |
| **Ending Scenes** | `EndingVideoController.cs` | Video playback and transition control |

### Game Flow

```
Start Game → MainHub displays 8 classroom buttons
       ↓
Select Classroom → Enter corresponding Classroom scene
       ↓  
Play Audio → Show UI → Player Choice (+1/-1) → Return to MainHub
       ↓
Repeat process until 8 classrooms completed
       ↓
Trigger Ending → Play corresponding ending video based on total score
       ↓
Press Any Key → Play final ending video
       ↓
Press Any Key → Game End
```

### Technical Features

- **Singleton Pattern**: GameDataManager cross-scene data persistence
- **Audio Control**: UI appears after classroom audio playback completion
- **UI Interaction**: Code-based button event binding with hide/show support
- **Video Playback**: RenderTexture method for fullscreen ending video playback
- **State Management**: Real-time tracking of classroom completion status and score accumulation
- **Debug System**: Complete keyboard shortcut testing functionality
