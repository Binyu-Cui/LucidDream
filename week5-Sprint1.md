# Sprint 1 Documentation
Student name: Binyu Cui<br>
Group members - Binyu Cui(24007733), Xiaoya Fan(24014203)

**Project Title - Scattered Parts** 
---

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
![Image 1](https://git.arts.ac.uk/24014203/Xiaoya_FAN-Responsive-Environments-Blog-2024/assets/1366/969c8e46-f44e-4a9e-b201-2ae778bb57cd)



---

## Process
![Instagram post - 4](https://git.arts.ac.uk/24014203/Xiaoya_FAN-Responsive-Environments-Blog-2024/assets/1366/e3ad329b-5217-46a4-bbbc-5617ef5e8bea)

![Instagram post - 5](https://git.arts.ac.uk/24014203/Xiaoya_FAN-Responsive-Environments-Blog-2024/assets/1366/c8d98d91-0515-4c28-9c26-2bc2e5ca5ba3)

---

## Video Demonstration


https://git.arts.ac.uk/24014203/Xiaoya_FAN-Responsive-Environments-Blog-2024/assets/1366/c04ce6b1-752c-4a7b-a442-19d019830a19


---

## Final Images
<img width="1512" alt="final 1" src="https://git.arts.ac.uk/24014203/Xiaoya_FAN-Responsive-Environments-Blog-2024/assets/1366/ae3e981e-8168-4989-9c2e-7a8a97adec14">
<img width="1512" alt="final 2" src="https://git.arts.ac.uk/24014203/Xiaoya_FAN-Responsive-Environments-Blog-2024/assets/1366/75167aff-528f-4e01-ad1f-f2bc4ba948f7">

![fig 3](https://git.arts.ac.uk/24014203/Xiaoya_FAN-Responsive-Environments-Blog-2024/assets/1366/42acb081-fc1b-40c4-b8c7-365e32a1f51d)


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
