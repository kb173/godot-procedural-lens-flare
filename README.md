# Procedural Lens Flare Compositor Effect

<img alt="photo-2026-01-12T16_07_36-(613402 0, 237 0, 515043 0)" src="https://github.com/user-attachments/assets/a9264ff8-bb51-4958-ba84-f19043c41b7b" />

Lens flare implemented as a CompositorEffect, based on [John Chapman's Pseudo Lens Flare](https://john-chapman-graphics.blogspot.com/2013/02/pseudo-lens-flare.html).

Instead of positioning shapes based on a sun position, this effect relies only on the color buffer. Whatever is bright on the rendered image is turned into a lens flare, meaning that any light, glowing object, specular highlight, etc. can produce lens flares.
By varying the number and shape of streaks, you can get a star-shaped glare or an anamorphic glare.

Works with Godot 4.7. Note that earlier versions of Godot require a different push constant padding, see https://github.com/kb173/godot-procedural-lens-flare/commit/aebf4448a6ae32e242b8bafdc79d67260adc781e

<img alt="photo-2026-01-12T16_01_01-(606951 0, 359 0, 515860 0)" src="https://github.com/user-attachments/assets/7da1cc87-921e-4274-88ca-b21291cff17b" />

<img alt="image" src="https://github.com/user-attachments/assets/e306dffd-c19d-4c58-bb7c-9084fd33d938" />
