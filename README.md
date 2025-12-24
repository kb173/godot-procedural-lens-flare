<img width="45%" alt="image" src="https://github.com/user-attachments/assets/1e167da2-1aff-4886-b49a-c7288efa5c34" /> <img width="45%" alt="image" src="https://github.com/user-attachments/assets/e306dffd-c19d-4c58-bb7c-9084fd33d938" />


Lens flare implemented as a CompositorEffect, based on [John Chapman's Pseudo Lens Flare](https://john-chapman-graphics.blogspot.com/2013/02/pseudo-lens-flare.html).

Instead of positioning shapes based on a sun position, this effect relies only on the color buffer. Whatever is bright on the rendered image is turned into a lens flare, meaning that any light, glowing object, specular highlight, etc. can produce lens flares.

**WIP: the code is a bit of a mess, unoptimized, and customization options aren't yet exposed**
