# Title: On Study of Optical Characteristics of Water Waves

## Abstraction
---
Omnipresent water has been well studied for its physical, chemistry and biological property. Besides, its electric polarity also equipped water with unique optical characteristics. I believe anyone here has ever saw the glittering drops on petals, colored rainbow after the watery sky, and using tranquil lake us mirror. However, the water is not always flat, many times, mostly powered by wind, and something like the shake of the earth, we “see” water wave. Well, the weird thing comes here, we did not actuary “see” the water, but we see the optical effect of water, like distortion, reflection, or refraction. Mind that we didn’t mention the diffusion here, as any object that not emitting visible light themselves are visible most because of diffusion. In this paper, we focused on the spacial and time-domain periodicity of water wave, and study it’s optical characteristics from a reflection event happened at a place for a single light to the water wave as a whole.

## Introduction
---

## Naive Model
Properity(qualitatively):
### Periodic 
---
The photographed one( considering single parallel light)
- While the sad thing is multi-reflection is unable to be eliminated there.
- Inspiration: the core of this model is not to calculate the boundary of wave, but to show us properities of wave wave.
	- Time domain, regradless of reflection times.
	- Space domain, here we introduce the image-object model.  
	Considering parallel light on a piece of circle:
	$
	\begin{aligned}
&\frac{l}{sin[\frac{\pi}{2}-\theta-d\theta]}=\frac{d\theta}{sin(2d\theta})\\
&l =\frac{1}{2}r\cos{\theta}
\end{aligned}
$
### Calculation
---
1. from eye to object
2. from object to eye
3. eye-to-object and object-to-eye, and search until they match
**Ray-tracing algorithm**
	- gemometry
	- electronic-maganitic( polarized and intensity)
- considering the image of sky, using len model
	- In this way, we no more need to consider the multi-flections scenerio,instead, we consider the image of other lens( semi-circle)
	- And the boundarg calculation is simpilified, as long as there is light that can enter the lens, there will be an image.  
Difference:
1. sky/moon/sun: Celestial light, parallel.
2. polarization and intensity.
3. refraction, just cal
4. dispersion, R,G,B seperation

The core idea is that we first consider the single lights way; then we consider the intergral model as image. (Which is physical, and the essence of other paper, besides other ideas is light projection and image projection function.)
On subject, we first consider paralled light, then we extend it to any form of subject.

## Model Refinement
---

## Water Simulation and Re-visualization System
### Source
---
- Geometry
- Optic
	- Angular Intensity Distribution
	- Polarization
	- RGB

### Water Wave(Singal Transformation Function)
---
- Geometry
- Electromagnetic

### Water Wave & Source Interaction
---
- Fresnel formula
	- Intensity
	- Polarization
- Method
	- From eye to space projection & reflection marking(ray-tracing)
    - Local Area Lens Simulation
- Level Up
	- $G$ function
	- $F$ function

### Receptor/Human Eyes
---

### Object Space
---

### Time Average
---
$E(F) = G$

### Re-visualization System
---
- if the water is stastic, then $G_s$ is simply a reflection function.
- $\lim_{A=0} F = G_s$
- Time average of $F$ is $G$
## Direct Time Average and Re-Visualization Algorithm
---

## Field Measure and Model Evaluation
---

## Summary
---
