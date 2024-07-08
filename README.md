
## Muscle Fiber Simulation
<img src="https://github.com/Cannon-Lab/Muscle_Fiber_Simulation/blob/main/images/Muscle_Fiber_Sim.png" width="486" height="337">
Simulate electrical properties of skeletal muscle.

Original Model: &nbsp;&nbsp;&nbsp;&nbsp; Cannon et al. **Biophys J** 65:270-288, 1993 <br>

Currrent Model: &nbsp;&nbsp;&nbsp; 2024-July. &nbsp;&nbsp;&nbsp; (see [*Simulated Muscle Fiber*](https://github.com/Cannon-Lab/Muscle_Fiber_Simulation/blob/main/docs/Simulated%20Muscle%20Fiber.pdf) for details)

- Two membrane compartments: sarcolemma and transverse tubule <br>
   T-tubule is a single, lumped compartment, not a radial shell <br>
   
- Ion Channels <br>
   Nav, Kir, Kdr, KCNQ, ClC-1 <br>
   Optional mutations: NaV altered gating, gating pore leak<br>
   
- Pump <br>
   Na,K-ATPase - two isoforms with high-K and low-K affinity (alpha1 and alpha2) <br>
    
- Cotransporter <br>
   NKCC1

Application:  Muscle_Sim.exe
- Compiled from FreeBASIC.
- Runs in Windows, any version.
- Menu-driven GUI, Parameters specified from excel data file.
- Video Resolution.  Horizontal: 85% of screen, Vertical: 90% of screen (fixed).
  
