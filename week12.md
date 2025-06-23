# Week 12

### Labs

After learning and exploring this area in more depth, I’ve gained a more concrete understanding of how shaders are used in TouchDesigner. Previously, I only saw shaders as abstract tools for generating visuals, but I now realize they function more like programmable brushes that directly manipulate pixels and vertices. Unlike traditional graphic software that relies on dragging elements in a GUI, shaders require me to write precise code to tell the GPU how to render each frame.

I’m especially drawn to the concept of fragment shaders—they allow control over each individual pixel on the screen. This functional way of "constructing images" made me realize that visuals don't have to be static assets; they can be generated in real time and respond dynamically to input. This aligns well with my interest in interactive art, and it’s made me wonder whether shaders could be used to express more abstract sensations, such as fluctuations in physiological states or changes in environmental feedback.

That said, I’ve run into several challenges while working with them. For one, GLSL syntax and its underlying mechanisms are not yet intuitive for me. Things like normalized uv coordinates, the use of time variables like uTime, or the mixing of vec3 and vec4 data types all feel a bit overwhelming. Many effects that look simple—like ripples or noise—are actually built on complex mathematical logic, and my current understanding of math and spatial reasoning sometimes struggles to keep up.

Additionally, integrating GLSL into TouchDesigner requires deeper understanding of how it connects with other node types. For instance, passing CHOP data (like from sensors or audio) into a shader, or managing input and output through TOPs, involves working across data types that I’m still getting familiar with.

Despite these hurdles, I still see shaders as a highly worthwhile area to explore. They offer an incredible degree of creative freedom and also help me understand the deeper logic behind graphics. I hope to develop a more intuitive grasp of GLSL through continued hands-on experimentation, studying more example projects, and connecting with other artists who work in this space.


---

### Reading & Reflections

Worldbuilding frameworks reshaped how I view my organ-collecting game—particularly Le Guin's Carrier Bag Theory, which perfectly reframes our "body part scavenging" as an act of cooperative knowledge-gathering rather than heroic conquest. Where I once focused on visual cohesion (floating islands vs. memory fragments), I now see deeper alignment possibilities: the "cardiac arrest" mechanic could mirror Severance's temporal fractures if we add heartbeat-synced time distortions during organ loss. The epistemology section hit hardest—our touch-sensor activation currently feels like a "weaponized" interaction (press-to-conquer), but redesigning it as a "listening gesture" (hold-to-attune) would better reflect Carrier Bag's relational philosophy. I'm stealing the infrastructure critique too: those cleanup drones shouldn’t just be obstacles; they’re capitalist enforcers erasing biological "mess," which adds ideological weight. Biggest revelation? Persistence through player-generated content—imagine letting players design mutant organs with Arduino bio-sensors, turning our unfinished undergrad prototype into a true "world-engine."

---

### Peer Support

Our team of four has finalized the core project direction after a 3+ hour video call.

