# Week 6

### Labs

This week I finally started learning TouchDesigner—a highly anticipated step for me. I believe its node-based programming allows creating stunning interactive effects quickly through simple node operations, without needing coding skills. The real-time rendering enables instant visual/audio feedback, perfect for experimental projects. During undergrad, I used its audio interaction plugin for a ‘sound waterfall’ project (showcasing cross-media integration), so I already grasp the basics.  
This is an unfinished undergrad project I'd like to refine during the course. Having these files helps me quickly get back into TouchDesigner for revisions.

![演示_0002](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/5b952f83-7819-4516-9a4d-a0cb88ab10ab)
![演示_0001](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/b5f81bab-6e1f-476e-b179-5fbc565def0f)

This project, built in TouchDesigner, visualizes a flow-based emotional ecosystem. A constant stream of lines, representing human emotions, cascades like a waterfall and converges into a central triangular structure—the energetic core of this imagined world.

The triangle serves as a symbolic “engine of transformation,” where collective emotional input is processed and transmuted into pulses of light, particles, and spatial distortions. These forms suggest a continuous conversion of affect into energy, feeding the surrounding space with motion and intensity.

The result is a self-sustaining emotional-energy feedback loop: a dynamic system where feelings are gathered, condensed, and released as new energetic matter. Surrounding line frameworks and flickering particles emphasize the density and tension of this flow, creating a meditative, data-poetic environment that breathes with the invisible currents of inner life.

---

### Reading & Reflections

In Chapter Five of Speculative Everything, “A Methodological Playground: Fictional Worlds and Thought Experiments,” Dunne and Raby explore how fictional worlds can be used in design not just to solve problems, but to ask questions. Like in science or philosophy, they talk about how designers can create fictional setups as thought experiments—scenarios that may seem strange or impossible at first, but are actually logical and self-contained. These imagined worlds help us step back from our everyday assumptions and rethink the systems, beliefs, and technologies we take for granted. Instead of offering answers, these fictional worlds open up space for speculation, reflection, and dialogue.

This made me think about my own undergraduate graduation project, Snowmouse. The idea for the project originally came from the "Universe 25" mouse experiment and the history of ancient Rome’s decline. I was struck by how both societies, although different in context, collapsed in surprisingly similar ways. Inspired by this, I created a fictional mouse society—a world that looks stable on the surface but slowly falls apart due to wealth inequality, low birth rates, and excessive media consumption. Through storytelling, interactive devices, and visual design, I built a space where audiences can explore this world freely. But the story doesn’t have a clear ending, and that’s intentional. Like our real future, the world of Snowmouse is uncertain, and I wanted viewers to feel that uncertainty and think about what it means.

After reading this chapter, I realized more clearly that what I’ve created is a kind of design-based thought experiment. I’m not just imagining a future world—I’m using that world to question the one we live in now. For example, when I designed a device that uses liquid to show class divisions, I didn’t care whether such a thing could exist in real life. What mattered was the question it raised: Do we already have invisible systems today that separate people in similar ways? The book reminded me that design can be a way of asking deep questions, not just telling stories or offering solutions. In the end, Snowmouse isn’t about giving people answers—it’s about creating a space where they can stop, wonder, and maybe see their own world a little differently.

What also stood out to me in this chapter was how Dunne and Raby describe the designer not as a problem-solver, but as a rule-maker and world-builder. They see design as a kind of “thought playground,” where people can temporarily suspend the logic of the real world and engage with alternative possibilities. This idea resonated deeply with me. Sometimes, creating a fictional world is not about simulating the future, but about building a mirror that reflects our present, in unfamiliar and slightly distorted ways. I found that when I exaggerated or abstracted aspects of reality—like creating a class system based on fluid, or hinting at fertility control through symbolic visuals—these speculative elements actually brought people closer to recognizing truths they may have otherwise ignored.

I also appreciated how the chapter emphasizes that speculative design doesn’t need to provide a solution. We are often trained to fix problems in design, but sometimes, asking the right question can be more powerful than pretending to have the answer. Snowmouse was never about saving a collapsing world. It was about presenting a world that feels eerily close to our own, and leaving people with the quiet discomfort of uncertainty. I learned that confusion can be productive—it encourages people to think more deeply. This is the kind of design that doesn’t preach, but invites. It doesn’t declare the truth, but creates space for people to find their own. For me, that’s what makes speculative design meaningful, especially in today’s complex, fast-changing reality. Creating a space where people can pause and reflect may, in the end, be more necessary than providing any single, fixed answer.

![research](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/376635ae-b9de-4335-84b2-f215c270ca86)
*My undergraduate FMP research*


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
