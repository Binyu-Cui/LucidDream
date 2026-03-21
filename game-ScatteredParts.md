**Scattered Parts** 
---
[DEMO VIDEO](https://youtu.be/peDyuQK-cqY)
## Overview & Project Description
Scattered Parts is a Unity-based playable experience built from the “Collection of Objects” starter scene. The player embodies a disassembled organism whose vital body parts—brain, heart, eyes, and legs—have been scattered throughout a surreal landscape. The objective is to recover all missing organs while avoiding patrolling cleaning robots and reach the final location to restore the full body. Movement is controlled via keyboard, while a custom-built Arduino capacitive touch sensor functions as the primary interaction mechanism. When the player approaches an organ, they must physically touch the sensor to collect it, triggering a unique sound effect that confirms successful interaction. The exit path only becomes available after all organs have been collected. The touch controller is essential to gameplay and turns each act of recovery into a symbolic, embodied gesture.

---
## Supplies & Materials

### Components Used
**Hardware Components**
- Arduino Leonardo
- Touch Sensor 
- Jumper wires
- USB cable
- Cardboard for controller housing

**Software Tools:**
- Unity 2022.3.56f1
- Arduino IDE
- Visual Studio Code
- SerialPort library  (Arduino-Unity integration)

**Downloaded Assets**
- Audio Assets: [freesound](https://freesound.org/)

### Images
<img width="1442" height="755" alt="11" src="https://github.com/user-attachments/assets/6fdae4c4-8da9-40ef-b97b-8511c7d17f89" />


---

## Process
![22](https://github.com/user-attachments/assets/8f31f376-6c6e-4080-940e-79d82b37de4b)
![33](https://github.com/user-attachments/assets/24d6d562-d487-4a01-8f7c-78b38895a48a)


---

## Final Images
<img width="3024" height="1684" alt="44" src="https://github.com/user-attachments/assets/fff5792e-5700-4c76-b934-3a4b1207556b" />
<img width="3024" height="1688" alt="55" src="https://github.com/user-attachments/assets/642d0b3d-eef4-4fa7-bb2b-e48ee9d09efa" />
![66](https://github.com/user-attachments/assets/956a577c-7e28-44a8-9841-1ac871e0bc43)

---

## Arduino Code
[Arduino code](https://git.arts.ac.uk/24014203/Xiaoya_FAN-Responsive-Environments-Blog-2024/tree/main/Arduino%20code)

## Link to Unity Files
[Unity files](https://drive.google.com/drive/folders/1KPrUd_OQXnXdjCwk7a4nOKKWTrd2EEKT)

---

## Design Justification 
The concept for Scattered Parts was driven by a personal interest in exploring the human will, individuality, and the process of self-reconstruction. Rather than creating a mechanically driven collection game, We wanted to embed meaning into every interaction. The act of collecting organs represents the reclaiming of one’s identity, piece by piece.

The use of a touch sensor as the Arduino controller was not only a technical choice to meet Sprint 1 requirements but also a conceptual one. Touch, as a direct and intentional gesture, mirrors the player’s active engagement in regaining control of the self. It transforms a mechanical input into a symbolic action. Each touch becomes a decision to rebuild.

Visually, the game adopts a torn-paper aesthetic to emphasize themes of fragmentation and recovery. The rolling form of the player character, gradually assembling limbs and facial features, creates a visual metaphor for personal growth and reconstruction.

This design philosophy creates a cohesive experience where players do not simply collect objects. They actively participate in a metaphorical journey of self-restoration through deliberate, tactile interaction. Every element, from the controller input to the visual language, was chosen to reinforce the narrative of a fragmented self striving toward wholeness.
