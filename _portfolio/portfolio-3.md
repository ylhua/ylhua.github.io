---
title: "HeyDancing: An AR/VR-Based Dancing Coach"
excerpt: "Dance like you're in the studio—right from home, with pro instructors leading the way!<br/><img width='600' src='/images/dancing.png'>"
date:
collection: portfolio
---

<p align="center">
  <iframe width="560" height="315" 
          src="https://www.youtube.com/embed/pMr3i27rvCM" 
          title="YouTube video player" frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
          allowfullscreen>
  </iframe>
</p>



## Dance Anytime, Anywhere – Immersive Learning with VR/AR, HeyDancing!

**Motivation**  
Imagine turning your living room into a high-tech dance studio! This project brings professional dance training home using cutting-edge VR/AR, letting you groove with a virtual coach and get real-time guidance—no commute, no pressure, just pure rhythm.

**Objectives**  
- **Recreate the Studio Vibe:** Simulate tutor–learner interaction in a fully digital, immersive space  
- **Level Up Faster:** Get instant, real-time feedback on every move to sharpen your skills  
- **Put You in Control:** Learn at your own pace, your own way—with tech that adapts to your needs


**System Design**  

<p align="center">
  <img src="../../images/sysdance.png" alt="System Design" width="500">
</p>

- **Real-Time Motion Capture:** Markerless 3D pose estimation from video input  
- **Data Communication Module:**  
  - Uses **Mosquitto** to stream motion data from capture system to PC  
  - Employs **WebSockets** to sync motion data between Unity and the VR headset  
- **Animation & Feedback Engine:**  
  - Visualizes the user’s avatar and virtual coach in real-time  
  - Provides **instant feedback** on body part accuracy  
- **VR & AR Display Module:**  
  - Combines **VR for deep immersion**  
  - Integrates **AR for real-world practice** with virtual guidance

**The Future of Learning is Here—And It's Got Rhythm.**  
Want to dive deeper? Check out the [full paper here (PDF)](https://ylhua.github.io/files/paperar.pdf).

