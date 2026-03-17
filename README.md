ALD Process Visualizer
An interactive browser-based particle simulation that conceptually visualizes Atomic Layer Deposition (ALD) — a thin film deposition technique in which materials are built up one atomic layer at a time through sequential, self-limiting surface reactions.

What it shows
The simulation models the alternating precursor exposure cycles central to ALD:

A base layer of blue particles represents the substrate surface
Red particles flow in from the left, representing the first precursor gas. They bounce around the chamber and adsorb onto the surface with a configurable probability, forming a self-limiting monolayer
Blue particles then flow in, representing the second precursor. They react with the adsorbed red layer, again forming a self-limiting monolayer
This cycle repeats, building up alternating layers until the chamber fills — mimicking the layer-by-layer growth characteristic of ALD
The self-limiting nature of each deposition step is captured by the sticking probability mechanic: once a layer is fully covered, remaining particles can no longer adsorb and are purged from the chamber through the right edge.

Features
Real-time 2D particle physics with elastic collisions
Fully configurable simulation parameters via on-screen controls:
Maximum and minimum particle speeds
Precursor entry zone and angle range
Number of particles per cycle
Adsorption (sticking) probability
Precursor exposure duration
Automatic cycle repetition and restart
Smooth canvas-based rendering with per-particle radial gradients
Usage
No dependencies or build steps required. Just open index.html in any modern browser.
