# Week 15

### Labs

This week’s lab was focused on AI navigation and raycasting. The terms sound technical, but once I started working with them, I realized it’s basically about controlling how characters move and how players interact with the world. Raycasting, for example, is just sending an invisible line from the mouse into the scene to detect what was clicked. It’s simple in theory, but took time to understand how it actually works in a 3D space. It felt like I was trying to develop a kind of spatial intuition that doesn’t come from real-world experience.

The AI navigation part was more challenging. We had to mark parts of the scene as walkable so the character could move automatically. I thought it would feel natural, but the movement sometimes looked strange or got stuck. I realized that the system follows logic and efficiency, not intention. It goes for the shortest path, even when that path feels wrong or awkward. That disconnect between system behavior and design intention made me rethink what it means to control a character. It’s not just storytelling—it’s about setting up rules.

We also implemented a simplified “need system,” similar to the Sims, where a value like hunger goes down over time and changes when the character interacts with certain objects. It made me think about how human states can be reduced to numbers. That’s common in games, but doing it myself made it feel a bit mechanical. I started wondering how this kind of data could represent emotions—not just as stats, but as something that actually reflects change or mood. It raised more questions than answers.

One reference that stuck with me was *We Feel Fine* by Jonathan Harris. It’s not built in a game engine, and it doesn’t use characters, but it collects phrases from people around the world starting with “I feel…” and turns them into floating particles. Each one represents a real emotion. It made me think that interaction doesn’t always need to be logical or precise—it can also be about creating space for people to feel something. That’s something I’d like to explore more.
![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/50697781-36e8-46a6-92ec-c47aba50ae03)

Overall, the lab helped me understand Unity’s behavior systems more clearly, but also exposed how little I’ve thought about interaction as a system. A lot of the work is less about designing scenes and more about building rules. And I’m not sure yet what kind of rules I want to build. Right now, I think I need to spend more time figuring that out before jumping straight into making things.


### Project Development

After weeks of repeated deliberation, we have made the latest progress on the original recent project definition, making the original story clearer and more grounded. This is what mainly happened this week.

## Project Overview

**Project Title:** Lucid Dream

**Research Focus:** 
I'm interested in how social norms influence personal identity, and how dreams can reveal the tension between who we are and who we are expected to be. I want to explore the internal conflicts that arise from navigating between self-perception and societal expectations.

## Technical Implementation

**Development Tools:**
- Unity (Primary development platform)
- Small sensors (For external input detection)

## Interaction Design

**Core Gameplay Mechanics:**

The player repeatedly assumes the role of the same first-person character within a looping dream, presented through a consistent 3D environment from a first-person perspective. Each time the dream begins, the setting closely resembles reality in structure, yet always conceals subtle—or at times uncanny—anomalies. Through micro-interactions such as text-based choices or quick-time events (QTEs), the player can respond to these irregularities: either by ignoring them (conforming to socially assigned roles), or by correcting them (attempting to break the illusion of the dream and reclaim their sense of self-identity).

Each act of confrontation contributes to an accumulating value that reflects the player's proximity to a deeper "truth" or their persistence in affirming self-awareness. These choices are made through external sensor input (specific sensors will be selected following preliminary technical research). As the dream repeats, this value gradually increases; once it reaches a critical threshold, the dream will terminate, triggering the final ending.

Throughout this process, the player's behavior symbolizes the tension between self-expectation and societal expectation. Every seemingly ordinary yet subtly distorted detail in the dream world becomes a moment of decision: to turn a blind eye, or to question the reality.

## Visual Style

**Aesthetic Direction:**
3D Dreamcore, Backrooms, Liminal space, Surrealism, Muted Reality + Glitch, Hyperrealism + Micro-Abnormality

## Project Themes

- **Identity vs. Conformity:** The tension between personal authenticity and social expectations
- **Dream Logic:** Using the dream state as a metaphor for navigating reality's contradictions
- **Incremental Awakening:** Progressive awareness building through repeated cycles
- **Micro-Resistance:** Small acts of defiance against imposed normality
