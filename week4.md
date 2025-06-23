# Week 4

### Labs

Reflecting on the iterative design approach presented in class, I strongly connect with the "quick failure" philosophy, but implementing it with tools like Unity and Arduino presents unique hurdles. Unity’s allure of polish often tempts me to over-design early prototypes – like spending hours on UI animations only to discover through playtesting that the core mechanic’s feel was wrong and needed a fundamental rethink. Arduino introduces a physical dimension to the challenge: the inherent slowness of building and modifying hardware clashes with the "test fast, fail fast" ideal. When a breadboard connection fails during a crucial user test (as happened with my sensor-based wearable), precious iteration time evaporates into debugging. The core lesson of "playable, not perfect" is vital – I now ruthlessly use Unity primitives for greyboxing and limit Arduino features to one testable element per sprint. However, recruiting unbiased playtesters for physical Arduino projects remains significantly harder than for digital Unity builds shared online. Ultimately, iterative design teaches me that tool constraints shape the process; for future projects, I’m prioritizing Unity’s Package Manager for quick asset swaps and pre-soldering key Arduino modules to avoid jumper wire chaos during critical feedback sessions.

---

### Reading & Reflections

This chapter redefines "sound toys" as playful compositional systems that democratize music creation through interactive audiovisual interfaces. What fascinates me is how they occupy a liminal space between instruments, games, and open-ended compositions—Eno’s Bloom exemplifies this by turning generative music into a tactile experience. The text rightly emphasizes Umberto Eco’s "open work" theory, though I’d argue it underplays how mobile platforms (like RjDj’s AR soundscapes) evolve this concept through real-world context sensitivity. While the composer-designer-player-physics model (Fig 3.1) is useful, its rigidity doesn’t fully capture emergent behaviors in tools like Sonic Wire Sculptor, where user gestures create unintended spectral patterns. The spectral control section resonates strongly—Biophilia’s DNA-like pitch visualizations prove micro-level sound manipulation can be intuitive yet profound. However, the classification continuum (Fig 3.2) feels outdated; contemporary web-based sound toys (e.g., BallDroppings) blur these categories further through crowd-sourced composition. Ultimately, the text’s core insight holds: sound toys reveal composition as a collaborative performance between human and system agency, though modern AI co-creation tools (like AIVA) now push this dynamic into uncharted territory.
<img width="554" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/efa70e04-2047-465d-939a-a283b909baea">


---

### Peer Support  
This week, my teammate and I are planning to create a straightforward game inspired by Mario's gameplay mechanics. The goal is to build an immersive experience where players progress through levels and collect items. We're focusing on adding atmospheric visual elements to enhance the vibe. Since we're still figuring out the technical side, we started by making a basic Mario-style prototype to study its core mechanics. This practice run also helped us get more comfortable with Unity's components, controls, and scripting.  
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/6bd271ad-83cc-497c-ba83-8e739e2429dd">
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/fe4cf1f7-6c3b-4757-9664-795a9a5f6cde">

---

### Project Development

All game textures are ready, and the full structure/plan is finalized:

**Game Title: Organ Dispersal Plan**
-Core Concept

You play as a disassembled biological entity. Your body parts (brain, heart, eyes, legs...) are scattered across surreal environments. Collect them to rebuild yourself—but each recovered organ fundamentally alters your controls:

Missing eyes: Blurred vision + screen shake

Missing hands: Cannot interact with objects

Missing legs: Crawl-only movement

Missing heart: Erratic movement with occasional pauses (simulating cardiac arrest)

-Objectives

Reclaim all organs to restore full functionality

Evade cleanup drones (they identify you as waste)

Reach the reconstruction chamber to win

-Organ Mechanics

Brief sensor press → Temporary organ activation

*3-second sensor hold* → Permanently restore organ

-World Themes

Dream Islands: Ethereal floating realms with soft glows and organic structures

Magic Lab: Fantasy workshop environment with puzzle elements

Memory Realm: Surreal urban landscapes featuring shifting architecture
