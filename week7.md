# Week 7

### Labs
- Advanced Visualisation and Computational Environments -- Designing for space, movement + embodiment

  Reading these theories about space, movement, and embodiment made me rethink the idea of the body as a medium. Lefebvre and Laban’s view of space as something dynamic and co-created by the body completely shattered my old assumptions about static environments. Take the Bioscleave House as an example: its slanted floors and warped walls force you to constantly adjust your balance. Every step feels like a negotiation with the space itself—it’s not just a backdrop but an active participant, almost alive, reshaping how you perceive it through physical tension. This made me realize that design isn’t about rigid rules but about sparking a dialogue between people and their surroundings, where interaction becomes the source of meaning. Open-ended play theories hit the same note. When environments let people explore freely, creativity blooms organically. In House of Eternal Return, hidden passages and fragmented stories invite players to physically navigate and piece together narratives. Rules aren’t imposed; they emerge from the chaos of interaction. It makes me wonder if true engagement isn’t about polished design but about embracing uncertainty—like how “distributed coordination” in synchrony studies shows that social bonds form through messy, individual movements, not perfect unison. Maybe good design leans into that chaos. After all, humans aren’t machines. We connect through trial, error, and improvisation, weaving relationships out of what seems like disorder.

  ![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/835dafe5-5da6-440f-bfc7-f417fe37f179)
  *Bioscleave House (Lifespan Extending Villa) East Hampton, New York*


---

### Peer Support

I teamed up with a classmate to work on this project. We brainstormed a lot of ideas and eventually decided to explore one direction she suggested in more depth. Through our discussions, we realized that TouchDesigner is really well-suited for creating surreal themes and bringing imaginative concepts to life.

---

### Project Development

Here is the initial idea of ​​this project using touchdesigner, designed by two people:
Project Concept: Echoes of Shan Hai
Inspiration Source: Classic of Mountains and Seas (Shan Hai Jing)
Shan Hai Jing (circa 4th-2nd century BCE) is an ancient Chinese text documenting mythical geography and supernatural creatures. It depicts a worldview where nature and divinity intertwine: one-legged dragons summon storms, avian deities herald spring, and mountains pulse with spiritual energy. This compendium transcends folklore—it embodies early ecological consciousness, framing nature as sacred living entities rather than resources.

Core Premise
This project reimagines Shan Hai Jing’s vanishing cosmography as an interactive warning. Audiences enter a monochromatic installation where once-vibrant creatures now linger as spectral projections. Through physical engagement—touching walls, vocalizing names, stepping onto responsive zones—participants reactivate these dormant beings. Each interaction restores color, sound, and movement to the space, symbolizing humanity’s capacity to rekindle ecological balance.

Why TouchDesigner?
The software’s capabilities align intrinsically with the mythos:

Fluid Abstraction
Shan Hai Jing’s creatures defy literal representation; they are elemental forces given form. TouchDesigner’s real-time particle systems and GLSL shaders visualize them as evolving ink-wash paintings—organic, transient, and resonating with ancient artistic traditions.

Immediate Embodiment
Myths manifest through action: a shout becomes thunder, a touch summons rain. TouchDesigner’s sensor integration (depth cameras, microphones) translates human gestures into instant audiovisual consequences, making mythical cause-effect tangible.

Dynamic Ecosystems
The narratives require interconnected reactions (e.g., awakening firebirds necessitates summoning rain spirits). TouchDesigner’s node-based workflow models these dependencies, allowing creature behaviors to cascade through the environment.

Experience Narrative
Phase 1: Silence of the Forgotten
Visitors encounter a grayscale landscape. Projections show dormant creatures (Kui the thunder dragon, Chunmang the spring spirit)—their stillness mirroring today’s biodiversity loss.

Phase 2: Ritual of Reawakening
Physical interactions trigger transformations:

Touching a wall ignites Kui’s presence, cracking thunder across the space.

Calling Yinglong (flood-controlling dragon) sends ripples through virtual rivers.

Phase 3: Legacy of Choice
Participants select one creature to release into a procedurally generated habitat. This act concludes the journey, underscoring that ecological continuity demands conscious intervention.

Philosophical Framework
Shan Hai Jing cautioned that neglecting nature’s sanctity invites calamity. This installation extends that warning to the Anthropocene: when myths fade, reality follows. By fusing TouchDesigner’s technological immediacy with Shan Hai Jing’s allegorical depth, we make abstract crises visceral. The project posits that re-enchanting our relationship with nature begins not with nostalgia, but with actionable reverence.

At first, I used C4D to build face masks that matched the look of the creatures, so I could use a plugin in TouchDesigner to attach them to the face in real time.

![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/5d794624-032d-45fe-94de-9c399b071a5d)


**MeshLab** is an open-source software designed for processing and editing 3D mesh models. It’s widely used for tasks like cleaning up scanned data, repairing mesh defects, simplifying high-poly models, and converting between different 3D file formats. With features such as mesh reconstruction, texture mapping, point cloud processing, and topology fixing, MeshLab is especially useful in workflows involving 3D scanning, digital fabrication, or real-time rendering environments like TouchDesigner or Unity. Its lightweight interface and powerful toolset make it ideal for quickly preparing 3D assets for creative or technical use.

Customize the number of samples.
![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/2a3bc91a-bc5d-4366-bc96-bfef578e8aa8)

This process uses a function in MeshLab called “Transfer: Vertex Attributes to Texture,” which converts vertex color (or other attributes like normals or textures) from the mesh into a texture map. In other words, it bakes the visual effect created by vertex coloring into a PNG texture image, making it easier to use in other software with standard UV mapping.
![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/d64b541e-3bd7-4c38-8486-ebddbab565f0)

The MediaPipe plugin in TouchDesigner is an integrated version of Google's MediaPipe framework, designed for real-time computer vision and machine learning tasks. It enables direct pose detection, hand tracking, facial recognition, and gesture recognition within TouchDesigner without requiring additional external software. This plugin is particularly well-suited for interactive installations and live performances because it provides high-precision human keypoint data that can be directly output as TouchDesigner's CHOP or DAT formats, making it easy to connect with other nodes. Compared to traditional Kinect systems, MediaPipe's advantage lies in its ability to achieve accurate tracking using just a regular camera with extremely low latency. Common applications include pose-controlled visual effects, gesture-driven audio synthesis, and facial expression mapping to 3D models in interactive media projects. The plugin supports multi-person tracking simultaneously and allows customization of which body part data to output.

**I tried out the plugin following the official YouTube tutorial and the effects feel like a perfect match for the mask I'm making.**


https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/4a3885f1-8795-4768-95e0-84f839686e1f

This is a demo of some effects achieved using the plugin in TouchDesigner, which utilized several tools from the plugin. However, due to project changes later in the process, this isn't part of the final version, so I'm just keeping this one screen recording of the effect from that time.


https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/140a210c-e13b-4666-9059-ed3d01276f05



