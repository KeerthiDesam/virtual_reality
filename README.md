# virtual_reality
This repository consists of projects about Virtual Reality

Virtual Reality Simulation
This project, "Ship in an Ocean", was developed as part of the CS6001 – Advanced Virtual Reality course. The goal was to simulate a realistic scene of a ship moving through a dynamic ocean environment using Houdini.

Key Features:
1.Ship Model Integration: Imported a 3D ship model using the Geometry and File nodes; scaled and styled for better visibility.
2.Realistic Movement: Implemented motion along the z-axis and oscillatory shaking using frame-based expressions for natural rocking due to waves.
3.Ocean Simulation: Utilized Houdini’s FLIP Tank to generate a dynamic ocean surface, configuring parameters for wave size, fluid resolution, and interaction with the ship.
4.Wave Effects: Enhanced realism by integrating an Ocean Spectrum and adjusting solver bandwidth and collision settings for fluid interaction.
5.Synchronized Motion: Both ship and water respond to wave dynamics, showing realistic motion propagation through the environment.

Tools Used:
1.Houdini FLIP Fluids
2.Ocean Spectrum Node
3.AutoDOPNetwork for fluid dynamics
4.Frame-based motion expressions
