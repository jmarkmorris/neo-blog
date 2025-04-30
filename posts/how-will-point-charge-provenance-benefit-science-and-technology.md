---
title: "Point Potential Provenance, Simulation, and Technology"
date: 2022-01-20
categories: 
  - "nature"
tags: 
  - "linked-refreshed-2024-q2"
---

https://youtu.be/D-wzdsSiemU

I enjoyed this very cool PBS Space Time video about simulations at various scales. I have unearthed a parsimonious model of nature based upon point potentials. There is a convincing pattern of evidence — based upon reasoning, logic, and geometry — which is strongly consistent with the hypothesis that the point potential model is isomorphic to the standard model, meaning a direct mapping back and forth. The point potential model is extremely parsimonious. It is incredibly easy to understand and simple to reason with to solve problems.

Point potentials were once a darling of physics but were set aside due to concerns with opposite point potentials approaching each other infinitely closely. I made a wild guess that nature might implement a rule that point potentials are immutable and/or that no two point potentials could get any closer than something around the Planck length at ~10\-35 meters. The implication is that point potentials are immutable, i.e., cannot be destroyed. I've actually found that there is a maximum curvature to a point charge binary using geometry and physics that had not previously been considered.

https://youtu.be/5gZHvrKyNkw

Point potentials are indestructible so we can imagine tracking and modeling each and every single point potential and trace the provenance or accumulated history of that point potential in every structure and reaction it ever participates in. I think it will be difficult to observe, even indirectly, except perhaps in very special small-scale situations. However, in simulations, we really could track every single point potential. We call this concept provenance or path history. It means the virtual observer knows the precise path history of every potential. This information has also been emitted and is traveling through the universe as it continuously fades at 1/radius but never reaches zero.

Imagine applying the knowledge of point potential provenance to the balancing equations of galaxy scale processes. We know that the point potentials that are the inputs to any reaction must be present in the outputs of the reaction. This leads to new areas of research where we ensure that we know the precise reactions underlying each observation, including when spacetime aether assemblies contribute to a reaction or are products of a reaction. This includes cases where there are more exotic subassemblies that fly off and have a reaction chain that leads to equilibrium. Present day science has no awareness of the assembly architecture nor the opportunities it presents.

- For each reaction producing photons what is the exact step by step process in the interaction with a spacetime assembly?

- What are the detailed temporal demographics of the point potential flow galaxy?
    - naked immutable point potentials
    
    - spacetime assemblies,
    
    - photons,
    
    - neutrinos,
    
    - other standard model assemblies + exotics,
    
    - groupable by causing process,

- Data science to develop understanding and models, simulation, and theory

- What are the big outflows?
    - Where do photons (6:6) and neutrinos (wobbly 6:6) rank on outflow?
    
    - What happens when dissipating spacetime assemblies from multiple galaxies meet?
        - Diffusion?
        
        - Outflow?
        
        - Inflow?
        
        - Depends on the history of the galaxy and when and where it emitted spacetime assemblies from the SMBH, etc.
    
    - What about SMBH jets? What percentage of that energy and those point potentials escape the galaxy and where does that process rank, periodic though it is?

- Does the point potential inflow of discharged assemblies to a (supermassive) black hole ultimately match the outflow of point charge plasma via the jets and stealth Noether cores emitted through the SMBH surface? This should be a ripe area for research.

I'm using Manim for the visualization of my simulations and animations. Manim was originally developed by Grant Sanderson of 3Blue1Brown. The API is not intuitive to me. I'm visualizing red and blue spheres following the evolution equation along a continuous path in R4. The fast-moving point potentials will need a fine-grained time step. Slow movers could be optimized with less frequent updates. I need to figure out and optimize the intersection operator between potential spheres and point potential paths. I want to have the ability for point potential "trails" so you can see some portion of the recent path with it dynamically fading with time. I want to have tracer potential emission spheres, recalculated periodically so we can see them expanding, and they need to fade with radius to illustrate the 1/r potential. I'll start with 2D space, but longer term I imagine 3D space where the virtual camera can fly around and reorient and also zoom in and out by many orders of magnitude. Also, some cool labeling would be great to indicate distance and time scales, and to indicate position and velocities of point potentials. Each point potential could have its own floating instrument panel with position, velocity, PE, KE, and net force. And provenance! We can label and track each and every point potential in a reaction! One could really go to town designing the simulation and visualization.

What could we practically simulate at the point potential level with the best available hardware and optimized simulation software? Consider that we only need track the paths of every point potential. Protons have 36 and so do neutrons. Electrons have 12. What industrial technologies could we model at the point potential provenance, assembly, reaction, and process levels? A bacterium? A virus? What scales and problems would benefit from understanding the **provenance** of point potentials? I am very interested in whether **provenance** of immutable point potentials is helpful for advancing simulations of nature. Certainly, if we can learn how to simulate reactions at this fundamental level it will lead to opportunities that we can exploit, just as we tap into other natural resources. Industry will press for lower cost and more efficiency and ultimately technology will be able to tap into the spacetime aether as a source of point potentials and energy to fabricate standard model matter at will.

I'll hazard a guess that the simple ideas in the paragraphs above foreshadow several Ph.D. theses as well as start-ups addressing the point potential simulation market. If you are a student of point potentials, like I am, and see what I see, you will realize that market is quite sizable. I can easily imagine point potential simulation technology startups achieving valuations in the hundreds of millions, if not billions, of $USD. Simulation is the tip of the iceberg. Imagine startups that vend an integrated collection of point potential related technologies. Imagine the Google, Apple, Microsoft, or Tesla of the point potential era. Now we are talking trillions.

I can look at reactions in PDG and tell if they don't balance in point potentials. By applying provenance, it is extremely clear that many reactions documented in the PDG are not properly accounting for inputs and outputs of very low apparent energy structures. The reacting particle is typically an assembly from the spacetime aether, which may be a Higgs that transforms into a W or Z boson in an intermediate stage of the reaction.

Perhaps in an assembly we might analytically calculate the expected idea path, adjust it for velocity and orientation, and then keep track of the differences. However, that sounds like it might be more complicated than simply keeping track of the path itself!

Point charge era science and technology development requires a rich set of simulation capabilities often customized for particular research and applications. Here are several tactical and strategic ideas related to the scope of simulation technologies needed for the NPQG era.

- The storage and processing of paths are likely to be important factors that constrain the simulation scale.

- A path could be implemented as a series of <t,x,y,z,> tuples. Alternately (t, r, theta, phi)
    - If we use 64 bit data types, each tuple is 32 bytes
    
    - the granularity of the simulation may need to be at incredibly fine grained time
    
    - simply storing the path tuples may be inefficient
    
    - we must also consider the computations that use path information
    
    - there is clearly an opportunity to research efficient methods to compute based on paths.
    
    - it may be more efficient to store something akin to arc segments described analytically, i.e., given a starting (t,x,y,z) then a function f(t) models the path backward.
    
    - the path forward is unknown, but the path history is really the key element to computational simulation, since we need to know any intersecting point charges in any @ t sphere for all past t where the magnitude is significant.
    
    - There is an opportunity to develop technology for efficient storage and processing on that path history.
    
    - Simulations of the extreme fine-grained nature of point potentials will require maximum efficiency.

- I presume there are advanced technologies available for storage and processing of Euclidean paths that could be used or enhanced for point charge simulation.
    - There may be a range of technologies depending on the application being simulated.

- For now, we will use the simple canonical data type of a path.

- Likewise, there may be optimizations for various proximities, velocities, or energies of point potentials.
    - We may change simulation parameters per sub-assembly.
    
    - Efficiency is critical when spanning vast scales in frequency, velocity, and radius.
    
    - Distant point potentials might be approximated by a randomized floating potential ground.
    
    - There could be a rich set of potential generators for simulation of external interactions.

- At the highest level, for every simulation time step we must identify all action from the entire path history of all point charges in the simulation.
    - The velocity of the emitter and the velocity of the receiver are factors in the action
    
    - Net action is the superposition of all action.

Optimizing simulations for broad and niche applications will be lucrative for technology startups.

**_J Mark Morris : Boston : Massachusetts_**
