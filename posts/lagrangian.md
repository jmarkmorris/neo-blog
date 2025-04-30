---
title: "Lagrangian"
date: 2022-12-24
categories: 
  - "nature"
tags: 
  - "linked"
  - "priority"
---

> working draft

_**Background : I eschew infinities. Physically, infinities are nonsense for any local process or observation, where local can be as large as the observable universe. Nature has a physical implementation, it is geometrically beautiful, and does not have infinities and singularities.**_

> _In physics, Lagrangian mechanics is a formulation of classical mechanics founded on the least-action principle Lagrangian mechanics describes a mechanical system with a pair (M,L), consisting of a configuration space M and a smooth function L called a Lagrangian. By convention, L = T - V, where T and V are the kinetic and potential energy of the system, respectively._
> 
> _The least-action principle requires that the action functional of the system derived from L must remain at a stationary point (a maximum, minimum, or saddle) throughout the time evolution of the system. This constraint allows the calculation of the equations of motion of the system using Lagrange's equations._
> 
> Wikipedia

How shall we approach the Lagrangian? My intuition says that solving the general cases of two opposite point charges or two like point charges with arbitrary path history at T0 would, by the principle of superposition, be the most general solution. Once we solve the problem for any two point charges, including the case of a point charge and itself, we can use the principle of superposition to additively solve pairwise for any arbitrary system of point charges.

![](images/one-equation-2.png)

As we bootstrap from first principles, proving the general solution in fundamental absolute math could springboard into optimized mathematics and simulation for assemblies and reactions of assemblies. We'll start by looking at cases where the two point charge path histories are entirely |v| < @, i.e., sub-field speed. The cases where one or both point charges are at velocities |v| = @ or |v| > @ will be considered next. There are special cases that are point, line, and planar as well as the general time + 3D space case.

- time + 1D point solution :
    - **opposites** or **likes** at the same absolute location with path history in that spot forever. : No motion, no force, no energy, nothing happens.

- time + 2D line solution :
    - **opposites** with separation r and no transverse path history and speed s at T0. : Force of attraction on each translates to work done and acceleration. PE and KE are trading.
    
    - **likes** with separation r and no transverse path history and speed s at T0. : Force of repulsion on each translates to work done and acceleration. PE and KE are trading.

- time + 2D plane solution :
    - **opposites** with separation r and no non-planar path history and speed s at T0. : Hyperbolic acceleration apart.
    
    - **likes** with separation r and no non=planar path history and speed s at T0. : Elliptical orbit forms. Identical path.

- time + 3D space solution : |v| < @, i.e., sub-field speed :
    - **opposites** with separation r and path history and speed s at T0. : Do PE and KE trade between the charges to arrive at a common orbital plane?
    
    - **likes** with separation r and path history and speed s at T0. : Force of repulsion on each translates to work done and acceleration. PE and KE are trading.

Looking at the 2D linear cases they are simple linear systems of attraction or repulsion where action occurs on a 1/r Dirac sphere. The forces are along the line on with no shear from the emitter or receiver. Here are some scenarios.

- **opposite** charges at large r with a path history and potential stream

- **like** charges start at small r with a path history and potential stream

- and so on, calculating T and V at all points along the path.

The 2D orbiting binary should be modeled over the full range from 1 Hz to Planck frequency. In isolation, this would be an unchanging elliptical orbit. For illustration purposes and first pass math, circular orbits are shown. For the most general case, the orbits are assembly-native wave equations. At this point we are only examining isolated two-charge systems since we can arrive at any assembly level behaviour via superposition.

- Does this task require an electrostatics or electodynamics solution?
    - It's kind of both in a way. I think careful study is required.
    
    - Each point charge always experiences a constant and unchanging Dirac sphere stream from it's partner, less any external perturbations.
    
    - In this sense the position is static from the point of view of calculating potential energy, right?
    
    - But since the point charges really are moving physically there will be shear in the Dirac sphere stream both at the emitter and at the receiver.
    
    - The shear affects the shape of the perceived potential field and therefore the forces and therefore the steady state at that frequency.
    
    - But does the shear affect the kinetic energy?
    
    - I guess it comes down to asking whether we need to tally up based on all the forces or do we tally up only after the superposition? I should probably know all this. Doh.

- V = Potential energy
    
    - We know the closest orbit radius and therefore we can calculate the attractive potential energy.
    
    - How much potential energy is in the attractive bond?
        - Do we consider the energy on the basis of each point charge or the bond?
        
        - The energy should be considered at the points of action, which are at each point charge.
        
        - We can aggregate later to the bond if that is convenient and well defined.
    
    - Distinguish between attractive and repulsive potential energy?
        - How to model attractive and repulsive potential energy?
        
        - We might consider using sign.
            - Is attractive potential energy positive or negative and why?
            
            - Is this convention helpful for superposition or does that not make sense like it does with the potential field. I can't think of why it would make sense, but let's consider a while longer.

- T = Kinetic energy
    - We know the frequency and the radius, therefore we can calculate the kinetic energy of each point charge.
    
    - We don't need to worry about centripetal force, right?

- The binary changes state with energy.
    - State includes frequency and radius.
    
    - Each cycle presumably corresponds to h-bar j-s.

- With L = T - V, kinetic energy minus potential energy, how is energy conserved?

- I've never quite understood that when it comes to Lagrangians.

- Kinetic and potential are trading off, but are we guaranteed T + V is a constant in classical mechanics?

- When you think about potential energy of point charges, there is attractive potential energy and repelling potential energy.

- Yet I don't see that in the equations for potential energy.

- Is it not necessary to distinguish attractive vs. repelling potential energy?

- I'm wrestling with how to define the mass of a point charge or an orbiting binary. Is it E = q@2 ?

- In my theory there is apparent energy which maps to mass, and energy shielded by superposition which is not included in mass.

- When giving an assembly (particle) a group velocity, the Noether core reveals more shielded energy as velocity increases thus increasing apparent energy and mass.

- As v approaches @ many assemblies will decay before reaching @.

- Thus the Lorentz factor doesn't blow up to infinity for those assemblies — they decay before reaching v = @ (field speed).

- This is important because with a physical implementation reactions will occur near some of these boundary conditions — which is unlike pure math — which I think is a good thing for my theory.

- Alas, energy at this decay is too high to be testable.

- I presume an individual point charge reveals all its energy as mass.

- Does an isolated orbiting binary reveals all it's energy as mass? There is superposition occurring so I think a virtual observer would not detect all of the energy.

- I'm also wondering if I add T + V to get apparent energy.

- There are a lot of things to consider because the design must also map to the effective theories of present day physics.

> - Attractive vs. repelling potential energy is generally handled as a sign convention. E.g., for the Newtonian 2-body problem you have the idea of orbital energy which is conserved (loosely speaking the combined kinetic and potential energy of the 2 celestial bodies, intentionally neglecting the rest mass of those bodies)
> 
> - Typically, the reference 0 gravitational potential energy is chosen to be at radius r=infinity, with the usual limit procedure.
> 
> - Since kinetic energy has to be provided to convert from an elliptical to a hyperbolic orbit, empirically attractive potential energy has a negative sign, while repulsive potential energy has a positive sign.
> 
> - With this empirical sign convention: elliptical orbits have a negative orbital energy, while hyperbolic orbits have a positive orbital energy. (Parabolic orbits have exactly 0 orbital energy, which suggests they are numerically unstable and are easily perturbed into one of the other geometric categories.)
> 
> - Yes, total energy is conserved in classical mechanics (both Newtonian and Special Relativistic), and is defined as the sum of kinetic and potential energy. Changes in apparent rest mass (either from motion, or from changes in temperature) mostly show up on the kinetic energy side, with a lesser effect on the potential energy side.
> 
> - Once you start accounting for causality-speed c lags, you're close to General Relativity territory. (E.g., when Special-Relativity modeling the solar system the direction of the gravitational pull for Jupiter on Earth is along the light-rays from Jupiter to Earth, not the coordinate-now position of Jupiter. Systematically doing this causes some non-conservation issues, and ends up approximating both gravitational waves and General Relativistic orbital precession.)
> 
> Interlocutor on PBS Space Time Discord

Re: _"changes in temperature"_ — it is really interesting that you mentioned that. I realize that in the back of my mind there is a little voice saying, "hey what about the energy of the six personality charges in the Noether core poles?" I've been repressing that voice because I would think it minor in comparison to the Noether core binary energies. But, if I am going to be true to my "we don't need renormalization assertion" then we really can calculate all this stuff exactly down to h-bar in the Noether core and then whatever T and V the personality charges have. It also fits with the idea that the personality charges in the poles can be transducers of energy between external stimuli and the Noether core. Ahh, so much to think about.

https://videopress.com/v/Ev4pYz0T?resizeToParent=true&cover=true&autoPlay=true&controls=false&posterUrl=https%3A%2F%2Fvideos.files.wordpress.com%2FEv4pYz0T%2Ffermion\_mov\_std.original.jpg&preloadContent=metadata&useAverageColor=true

The animation covers all the fermions, so that includes the electron and the quarks that make protons and neutrons. So pretty much your every day mass. It also covers neutrinos, but I think neutrinos are really a special case of a less energetic oscillating precursor to a photon. Thus neutrinos are part way between Bose-Einstein 2D form and Fermi-Dirac 3D form and the oscillation of the assembly also oscillates the proportions of apparent (massy) and shielded energies.

It still kind of blows my mind that there is not much online about orbits of point charges. They are so much cooler than gravitational orbits. There is a lot more going on! And everyone knows Coulomb's law is dualistic with the law of gravitation. Likewise, Conway's game of life seems like it would be a LOT more fun with point charges and continuous motion. Can't find anything on that either. Why is that? It really makes me wonder about human creativity that this isn't a well explored subject area.

Even a high energy reaction could throw off products with super low energy that would quickly join the spacetime aether. I'm talking product assemblies here. Regarding ephemeral ghost particles near standard matter, we already know that the fields of high energy triply nested binaries in standard matter excite the nearby Higgs aether, which makes total sense considering the vortices from each binary.

* * *

It's taking a while to get back to Lagrangians, but we really need to understand how nature operates before we can hope to get our mathematics to work properly and efficiently. To that end, let's talk about potential.

A key characteristic about the unit potential point charges, the electrino and the positrino, are that they emit their spherical potential continuously at a constant rate. There is apparently nothing in the universe that changes this behaviour as far as I can tell at this point :-). We often think about point charges emitting a spherically expanding potential. Another way to think about it, and I presume this is not original, is to think of the positrino as emitting a spherically expanding positive potential and the electrino consuming a spherically draining negative potential. A spherical faucet and a spherical drain, each behaving as a strictly defined geometrical point in time and space (t,x,y,z). The temptation is to think of the source and sink in a one to one relationship, whereby nearby opposite point charges would produce potential which would flow into the consuming partner. I think this is the wrong way to think about it, because there is no evidence so far that spherical potential can be absorbed and cease expanding. Instead it is better to think of potential purely in the spherically expanding sense. Another way to think about this is that potential doesn't have provenance. However, the producers and consumers are balanced in the universe and the sum of potential over large scale volumes approaches zero.

I suppose one could imagine some geometrical concept like planes or pools of positive and negative potential. Do we need that level of abstraction? I haven’t seen such a need so far, but it’s worth noting in case we run into a problem or observation it would solve. I think it suffices at this point to simply think of immutable distinct point like sources and sinks of potential.

How would nature behave when opposite point charges occupy the same point in time and space? The source and sink each operate at the identical constant rate. They are perfectly balanced. It doesn’t seem to me as if superposition of the two would be a problem ab initio. I suppose it leaves open the question of whether those two point charges remain intact with provenance or whether they magically annihilate or coalesce. Interestingly it may be plausible to separate them because potential action operates on them in the opposite vector directions.

Let’s turn to the case of like point charges, i.e., **electrino:electrino** or **positrino:positrino**. Now what happens? We know that the action caused by each potential on the other charge is causing a force that pushes away from each other. As in my prior thought experiments, it is my great preference to assign minimum functionality to time and space. Therefore, time and space would not impose any limitation to the density of like charges including those occupying the same point in time and space. If that were the case, then it is really a question of whether enough work could be done on the two like point charges to colocate them.

There are probably some amazing mathematical proofs here because if you think about it, work can only be caused by the potential emitted by point charges. I suppose one could say that if it were possible for like point charges to occupy the same point and have the same velocity, then it would follow that they could never diverge, because they would always behave identically in response to any incoming potential. Yet if it were possible for like point charges to converge and never diverge then nature would appear to present many point charge magnitudes. I haven’t seen any reason to model nature with that feature, therefore I am inclined to think it is not possible for like point charges to converge at a point and have the same velocity.

We still need to consider the case of like point charges passing through the same point on different paths before and after. Let's first consider two like point charges on a line. We already have stipulated that there is no limit to the speed of an individual point charge. The next step is to develop the equations of motion for two like point charges a distance r apart with approaching velocities v. This must include the regime where v is greater than field speed @.

* * *

Another topic is how spin relates to temperature. I was thinking about the personality charges as possibly implementing temperature. However, spin could be quite high for the Noether core (spin 1/2). That is a lot of kinetic energy. Also, we don't yet know if the personality charges are truly locked into their polar locations or if they can follow a wave function pattern generating path in concert with the spinning Noether core. We also need to understand exactly how we are increasing energy in units of h-bar j-s. What is the dynamical geometry of the assembly for each quantum level of energy?

This raises the question of the relationship of shielded (i.e., cancelled by superposition) potential and kinetic energy. Is there apparent kinetic energy and shielded kinetic energy? I suppose that makes sense. If the only way we have to sense the kinetic energy is the potential stream (not the photon at this level of nature). Wow, fascinating, so of course there must be apparent and shielded kinetic energy. How does this relate to the Lagrangian? Considering shielded potential energy and shielded kinetic energy, how does the Lagrangian know what is going on? Does the Lagrangian apply at all scales of interaction (all gauges?). What are the laws and equations when written in terms apparent(PE), shielded(PE), apparent(KE), and shielded(KE)?

The Lagrangian for quantum field theory includes components for each field which means all particles involved as well as the force carrying particles of the interaction. QFT doesn't know about point charges and shielding of PE and KE. It's clear that NPQG will be much simpler mathematically and also provide far more information about the particle assemblies. That makes sense since NPQG models the entire path of each point charge and their provenance in reactions.

Note to file elsewhere : With our model of continuous constant rate spherical emission tapering at 1/r we must now come to realize that all point charges in the universe are in causal contact with each other, even though the absolute time from emission to reaction (r1/@ = t) may be quite lengthy given there is no known beginning nor end to absolute time or absolute space. Likewise for r2 and the return trip. This is true no matter the velocity of point charge and would also be true in the Planck core of an SMBH. If our model is that point charge potential emissions are not changed by passing through point charges, then this is the consequence. That said, these potentials fall off at 1/r. On the other hand when we consider the excitement of the Higgs spacetime aether assemblies, then it is a whole Noether ball game.

Another note: The velocity of the point charge plays a role in the magnitude of the emitted potential along the path. I presume the relationship is q/|v|. In other words we divide the unit potential by the magnitude of the velocity.
