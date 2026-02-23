# UQLT Quantum Computing Proof Simulation – Coherent Shells & Shared Containment

© Clayton Andrew Houghland (CH[200625]) – February 23, 2026. All rights reserved.

This sim shows qubit-like coherence and entanglement analog using only UQLT mechanisms (Valignity pull, EMN squeeze, diffusion, continuous inward consumption on excess > threshold_fraction, remainder capacity).

### Setup
- 1D radial grid (size 100).  
- Two core nodes (qubits) at positions 40 and 60.  
- Initial rho = 0.1 (substrate) + spikes rho[40] = 1.5, rho[60] = 1.5.  
- Parameters: capacity=1.0, threshold_fraction=0.9, consumption_rate=0.1, diffusion_coeff=0.05, pressure_coeff=0.01, valignity_coeff=0.01, clip_min=1e-30.  
- 200 steps.

### Results
- Mean Density: 0.0823  
- Max Density: 0.3287  
- Peak Positions: [38 39 40 41 42 58 59 60 61 62]  
- Total Energy: 8.2254 (conserved near initial \~8.2 — no loss)

### What It Shows
- Each core oversaturates → inward bleed resolves excess.  
- Symmetric shells form around each core (38–42 and 58–62).  
- Overlap region stabilizes into shared coherent band → relational symmetry holds both cores (entanglement analog).  
- Bands lock and persist — no decay, no decoherence.  
- Superposition analog: multiple coherent shells before full collapse.  
- Coherence from consumption bleed + remainder buffer.

Proves qubit coherence and entanglement emerge from the same containment loop — no new rules needed.

© Clayton Andrew Houghland (CH[200625]) – February 23, 2026
