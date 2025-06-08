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

**The first step was to find high-resolution, background-free reference images. I gathered over thirty mythical creatures from the Shan Hai Jing, and selected a few that were the most iconic and visually striking.**

![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/8bddc10b-d19d-4f32-9715-8b6e5140a683)

I used the AI model TRIPO to quickly convert 2D images of the creatures into 3D models, laying the groundwork for bringing them to life in TouchDesigner.
![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/a98c57d1-2243-4754-9e81-5bc917ea820c)
