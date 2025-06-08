# Week 9

### Labs

Analysis of the reasons why Matt's rejected proposal

1. The proposal requires participants to stand alone on a virtual stage and receive applause—a setup that inherently places individuals in a high-pressure "performance" scenario. For introverts, elements like spotlights, simulated audience cheers, and a stage manager’s guidance could trigger social anxiety rather than fostering self-acceptance. Relying on external applause to validate self-worth contradicts the project’s goal of promoting internal satisfaction. If one’s value hinges on approval from a virtual crowd, it risks replacing material consumption with emotional consumption. Introverts might benefit more from low-exposure interactions, such as anonymous feedback or nature-inspired metaphors, rather than being thrust into the spotlight.

2. The €20,000 budget prioritizes costly temporary setups—custom wooden structures, high-end lighting rentals, and complex tech like motion tracking. Yet these resources serve only a short-term exhibition. The wooden stage is dismantled post-event, rented equipment loses value after return, and technical glitches could undermine immersion. This “disposable” approach clashes with STRP’s sustainability ethos and fails to address how art can drive lasting behavioral change. Investing in modular designs or community co-creation might yield deeper, longer-lasting impact.

3. The proposal aims to combat consumerism through “applause therapy” but lacks a clear logical bridge between the two. The stage experience functions more as a psychological Band-Aid than a tool for critical reflection. Moreover, while STRP 2022 emphasizes a “decelerated digital society,” the proposal relies heavily on projectors and tracking systems—ironically promoting tech dependency. Shifting focus from solo performance to collaborative acts (e.g., requiring groups to sustain a light-balance through slow movement) could reduce costs and align with the theme. True sustainability lies in human connection, not technological spectacle.

---

### Peer Support

My partner and I divided up the work, planning to merge our individual effects in TouchDesigner at the end. I'm mainly responsible for the main subjects in the interactive visuals - the dynamic creatures - while she's creating the background effects for the "world of mountains and seas," designing the mystical scene atmosphere.

---

### Project Development
The MediaPipe plugin is divided into tracking different parts of the human body, with the most important being face-tracking and hand-tracking. The body parts that the plugin recognizes will be highlighted, and you can also turn off the ones you don't need to avoid overloading your computer.
<img width="967" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/cce519da-b09e-4fee-b550-10f792ac03e9">
Import the previously made particle ply files, add pointtransform and other components to recognize RGB colors, and adjust the position and size of the creatures following the face display on screen.
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/37be2b58-5049-44c4-a990-f6d37aeebc32">
Add spheres to make them into very tiny particles that become the building blocks of the particle cloud.
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/f4104ec0-5952-429e-9879-79e9cd4c18ba">
In the Metric section, we replaced the official default mask model with our own model.
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/c4830881-ab6c-4fda-ba58-3a0a30ce6801">
Use hand gesture recognition to control the particle recombination and switching of four model groups, extracting values from the hand-tracking section to export null8, then controlling it through the keyboard.
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/48804d94-1f11-462b-8a79-bd073f9e9603">
<img width="1512" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/2b7ba1e2-e2c7-4b5d-9881-5241a6fd96c9">
In hand-tracking, you can see that the recognition results can be freely selected.
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/9688f2e8-25ce-40f5-9c6c-b9f0357c50a3">
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/2dd2a74d-778d-4c4b-bacd-a73517163720">
To show the audience the hand movements that are being detected, I need to add white lines connecting the selected two points (thumb and index finger).
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/4c1eef0a-2919-4206-88a5-313dd51cfc29">
I quickly created an animation in AE to enrich the background, inserting animations of other creatures with different movement trajectories to represent the active scenes of the world of mountains and seas.
![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/5b4646ae-8a7c-474e-ad0b-bf55fd434c32)
![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/d6f2314c-27ea-4acc-aff3-81eaf7fdf5e3)
Combine the animation with facial recognition particle model switching, hand gesture recognition control, and reality - all three elements together in one comp.
<img width="1624" alt="image" src="https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/c3fef74c-baa6-461e-a8d9-d93668a0ee39">

Finally, let's take a look at the completed effects at this stage. I set the camera feed to transparent so only the main 3D particle models and 2D background animation remain on screen. After repeated debugging, I finally settled on this gesture interaction - when one hand is detected by the audience, it switches the main model; when a second hand is detected (both thumbs and index fingers appear simultaneously on screen), the particles scatter and the main model disappears; when the second hand is no longer detected, the particles reaggregate.

https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/18de1f47-f722-49a7-ab10-12692386116c

