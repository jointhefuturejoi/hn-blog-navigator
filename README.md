# Singularity Simulator

An interactive, mesmerizing particle simulation that visualizes the technological singularity -- starting from simple particles in chaos and evolving through emergent complexity to a beautiful, hypnotic crescendo of intelligence.

## Try It Live

**[https://jointhefuturejoi.github.io/singularity-simulator/](https://jointhefuturejoi.github.io/singularity-simulator/)**

## What It Does

Watch as 350+ particles evolve through 6 eras of increasing complexity:

1. **Primordial Chaos** (2024) - Random motion, maximum entropy, quantum fluctuations
2. **Molecular Chemistry** (2027) - Attraction emerges, molecular bonds form, electron orbits
3. **Emergence of Life** (2030) - Self-organization, flocking, cell division, DNA helixes
4. **The Awakening Mind** (2034) - Neural pathways, consciousness pulses, thought bubbles
5. **Global Network** (2039) - Hyperconnection, signal propagation, aurora effects
6. **The Singularity** (2045) - Gravitational lensing, galaxy spirals, transcendence

## Features

### Visual Effects
- Canvas 2D particle physics with spatial grid optimization
- 3-segment gradient trail rendering with color transitions
- Era-specific visual effects (molecular bonds, DNA helix, thought bubbles, consciousness pulses, floating neural words, aurora, galaxy spirals, gravitational lensing, time crystals)
- Additive blending bloom in late eras
- Parallax background stars with depth-based coloring
- Film grain, color grading overlay, vignette
- Screen shake on era transitions
- Dimensional glitch/tear during singularity
- Chromatic aberration and interference patterns
- Speed lines when fast-forwarding
- Quantum entanglement visualization

### Audio
- Evolving drone synthesizer (4 oscillators with reverb)
- Lowpass filter sweep (400Hz to 4000Hz across eras)
- Pentatonic chime sounds on milestones
- Singularity finale chord progression

### Interaction
- Click to attract particles
- Double-click to create explosions
- Drag to guide evolution
- Timeline scrubbing and dragging
- Hub particle pulse on click (Network+ eras)
- Touch support with haptic feedback

### Controls
- **Space** - Pause/Resume
- **S** - Cycle speed (0.25x, 0.5x, 1x, 2x, 4x, 8x)
- **P** - Perturb (creates shockwave)
- **T** - Toggle trails
- **D** - Cycle density (Sparse/Normal/Dense/Packed/Max)
- **R** - Reset simulation
- **M** - Toggle sound
- **F** - Fullscreen
- **1-6** - Jump to specific era
- **?** - Toggle keyboard shortcuts
- **Enter** - Start simulation
- **Escape** - Dismiss completion overlay

### Quality of Life
- Adaptive FPS-based quality scaling
- Auto-pause when tab is hidden
- Returning visitor detection
- Mobile responsive (768px, 400px breakpoints)
- Prefers-reduced-motion support
- 30+ quotes from famous thinkers
- 17 progress milestones

## How to Run

Simply open `index.html` in any modern browser. No dependencies, no build step, no server needed.

```bash
open index.html
```

Or visit the live version: https://jointhefuturejoi.github.io/singularity-simulator/

## Technical Details

- Single HTML file (~97KB, ~2250 lines)
- Pure HTML5 Canvas 2D (no WebGL, no libraries)
- Web Audio API for sound generation
- Spatial grid-based O(n) physics calculations
- requestAnimationFrame game loop with delta time
- Adaptive quality based on FPS monitoring

## Inspired By

The conversation about the technological singularity on X.
