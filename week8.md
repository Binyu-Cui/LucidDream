# Week 8

### Labs

This week's TouchDesigner session was mainly about projection mapping and post-processing. We learned how to project visuals onto real-world objects using a tool called Kantan Mapper. It was a simple intro—just shaping visuals to fit different surfaces like boxes or walls. We also looked at how to add visual effects (like blur, glow, or motion trails) to make things more dynamic and interesting.

What stood out to me most wasn’t the technical side, but the creative potential. Projection mapping feels like turning everyday objects into part of your artwork—it’s not just digital visuals on a screen anymore, it’s part of the space. It made me realize how much power we have to transform environments and how a technical tool like TouchDesigner can become a real part of artistic expression. Even though the learning curve is steep, it’s exciting to think how this could be used in an exhibition or performance.


---

### Peer Support


My partner took the lead in researching visual materials related to our theme to establish a foundation for it, and also created a simple structural plan and conceptual inspiration for the project.
This collection of images showcases the rich cultural significance of the "Classic of Mountains and Seas" (Shan Hai Jing), an ancient Chinese mythological and geographical text: from vibrant traditional painted illustrations to precious original manuscript pages, from exquisite wooden relief carvings to modern three-dimensional sculptures, and finally to various mythical creature pattern designs, it comprehensively presents the evolutionary journey of the fantastical beasts and mythological world described in the "Classic of Mountains and Seas" from ancient textual records to contemporary artistic interpretations, demonstrating the profound influence and enduring artistic creative value of this classical work in Chinese culture.
![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/de989102-efd5-478b-bdcf-1bf40fd81798)


"Realm of Mountains and Seas" - Lost Ecosystem Revival  
Theme: Biodiversity & Human-Nature Symbiosis  
Concept: Future scenario where mythical creatures from Shan Hai Jing are disappearing. Visitors must "awaken" these beings to restore balance.  
Flow:  
Silent Realm - Enter black/white silent space with still mountain/creature images  
Awakening - Touch walls, step on sensors, call names to summon beasts:  
Kui (thunder beast) → brings storm sounds  
Jumang (spring god) → projects green plants  
Yinglong (winged dragon) → guides to next area


Create Your World - "Release" chosen creature into virtual ecosystem, watch it live on big screen

Core Message: Without action, both mythical and real worlds go silent.

Tech Implementation:

Section 1: Enter the World

TouchDesigner + Kinect for tracking  
Dynamic projection creates Shan Hai Jing landscapes around visitors  
Random creature generation based on position  
Tech: Noise CHOP + GLSL shaders for terrain, Blob Tracking + Instancing  

Section 2: Touch & Connect

Leap Motion/touch sensors detect gestures  
Different touches trigger creature sounds (fire, thunder, wings)  
Tech: OSC mapping, Audio CHOP for reactive visuals  

Ending: Harmony

World becomes vibrant, creatures return to nature  
Tech: LFO CHOP + Particle System, cloud data via WebSocket  

Visual Style:

GLSL + Feedback TOP for ink-wash effects  
Particle SOP for glowing creatures  
3D Depth Mapping for immersive terrain  

---

### Project Development

**After discussing with my partner last week, we decided to change our approach and build an interactive effect that's not just about masks, since that wouldn't have much meaning and would be pretty monotonous. So I started looking for better materials again.**  
The first step was to find high-resolution, background-free reference images. I gathered over thirty mythical creatures from the Shan Hai Jing, and selected a few that were the most iconic and visually striking.

![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/8bddc10b-d19d-4f32-9715-8b6e5140a683)

I used the AI model TRIPO to quickly convert 2D images of the creatures into 3D models, laying the groundwork for bringing them to life in TouchDesigner.
![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/a98c57d1-2243-4754-9e81-5bc917ea820c)
Following the same steps used for making the mask, I completed a similar transformation from the overall design to samples, finishing the final steps before importing into TouchDesigner.
![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/7869a398-dcff-4d10-8d22-0ed19712d2e0)

![image](https://git.arts.ac.uk/24007733/Responsive-Environments-Blog-2024/assets/1326/69699b1e-778f-48bf-85a2-9eb51f71749a)
