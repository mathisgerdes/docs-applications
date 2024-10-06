# Aims

A **research statement** is a broad overview of your past, present, and future research.

**Content**:

- **Past Work**: It summarizes your previous research contributions and their impact.
- **Current Work**: It outlines your ongoing research projects, methodologies, and key questions.
- **Future Work**: It describes your long-term research goals and directions, focusing on broad themes rather than specific projects.

**Essay detailing proposed research** during a Pappalardo Fellowship [**Important**: Faculty reviewers stipulate a maximum length of two-pages, single-sided, using an 11 or 12 point font size and 1.5 or double spacing for **optimal legibility** for the multiple faculty readers. References and graphics are **not** necessary, but if included, should be contained within this two-page limit.]



# Research Statement

Frame as generally interested in theoretical physics and quantum field theory.

I have in particular the tools of advanced computation, which I have thus used to address questions in this field.

Need to make sure I stress I'm interested in theoretical physics. That I have done meaningful projects. That I have many ideas of things I want to work on. But at the same time that I'm pliable. E.g. that I have followed discussions in journal clubs etc on conformal bootstrap 



As machine learning continues to drive remarkable advances across science and society, computational methods are playing an increasingly central role. My research focuses on applying and advancing these techniques at the intersection of physics and mathematics to tackle fundamental challenges in theoretical physics.

### Past and ongoing work

- I have a strong background in both theoretical physics and computer science. Within a growing network of collaborators, I have developed expertise at the intersection of theoretical physics and machine learning in a wide range of aspects in lattice quantum field theory, Calabi-Yau metrics and simulation based inference.

#### Lattice quantum field theory

- I have lead the development of a state of the art continuous normalizing flow for scalar field theories. This was enabled by parametrizing an ordinary differential equation as a neural network, which was made to respect the physical symmetries of the theory. Building on these innovations we could scale to larger lattice sizes and obtain higher sampling qualities than previously published results. Our methods were used by other groups to study the string tension of the strong interaction.

- I have extended the idea of continuous normalizing flows to gauge theories. This involved overcoming significant technical challenges, arising from degrees of freedoms being Lie group valued in stead of scalar. I have implementing a general algorithm that can compute gradients for any such continuous transformation of matrix group manifolds. We have leveraged these technical achievements by designing a gauge equivariant ODE architecture, which has again achieved state of the art sampling quality. We are currently exploring new and recently proposed ways of using and training normalizing flow architecrtures in this context, including multi-scale generation, transfer learning, and stochastic normalizing flows.

#### Calabi-Yau metrics

- In earlier work begun as my MSc project but continued afterwards with further collaborators, I applied machine learning to the approximation of Ricci-flat metrics on Calabi-Yau manifolds. 
- Using an algebraic ansatz that guarantees the Kähler condition, my approach offers more efficient and accurate approximations compared to Donaldson’s algorithm, while also capturing the moduli dependence of the metrics. 
- This work, and especially the paper published with collaborators giving an overview and comparing machine learning approaches to this problem, continues to inspire further research in the field.

#### Diffusion models and renormalization group flow

- Interest and experiments in how to learn real space RG transformation for Monte Carlo RG have led us to explore the connection betwen RG and diffusion models. 
- Ongoing collaboration with computer scientists, in particular with Max Welling and his group.

- Also during my PhD, I have applying simulation based inference methods relying on machine-learning to analzye astrophysical observations, specifically stellar streams, with the aim of learning about the potential dark matter subhalo distribution in the Milky Way.

#### Simulation based inference and stellar streams

- I have implementing an efficient simulator for stellar streams in a newtonian gravitational potential with possible interactions with dark matter subhalos.
- We have leveraged that and combined it with the flexible machine-learning framework for simulation based inference of my supervisor Christoph Weniger, to show how it can be used to conduct detailed statistical analyses that can faithfully take into account a large number of nuisance parameters. 
- This project has given me exposure to how ML is used in the data analysis side, connecting astrophysical observations to theoretical models.
- Following on from this project, I have deepened my knowledge about coverage intervals, and in we are now, in particular, working on an application of machine learning which can reconcile certain differences between frequentist and Bayesian coverage intervals.

### Future research direction

- Having worked in these different machine learning applications to solve theoreticl physics problems, I have gained significant experience.
  - The wide spectrum of computational techniques developed in machine learning. How to identify the right ideas for the physics problem at hand. How to innovate and adapt them for the specific scientific challenges, going far beyond using "off the shelf" methods.
  - The ability to very quickly implement highly efficient code and quickly experiment, thus allowing for quick iteration in our projects.

Why MIT would be a great fit:

- Access to a much larger set of collaborators on lattice machine learning work, including Phiala Shanahan and her group.
- Large set of people interested in different aspects at the intersection between ML and physics. 
  - This includes Prof. Slatyer who has applied advanced computational methods to study astrophysical data, which connects to my experience in simulation based inference for stellar streams. 
  - Both Jesse Thaler and Philip Harris are also working on machine learning for collider physis, and it would be exciting to explore if there are interesting overlaps.
  - As for AI for physics, like the diffusion model work, is similar to Max Tegmark's work, in particular Poisson Flow Generative Models.
- The rich possiblity for collaborations will allow me to leverage and build on top of my existing network of collaborators to develop new research directions, as well as directly continue working on many ideas I have gathered.