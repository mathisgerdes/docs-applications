# Project summaries

Projects I have worked on, roughly in chronological order, although some projects overlapped. Later projects are generally more relevant for my applications and current work.

### Bachelor Thesis: Using Hamiltonian Monte Carlo Techniques for Phase Space Sampling

The project focused on improving the **Monte Carlo (MC) techniques** used for generating **phase space events** in **high-energy particle physics**. Traditional **Metropolis-Hastings algorithms** can be computationally expensive and suboptimal for certain distributions encountered in collider physics. By exploring **Hamiltonian Monte Carlo (HMC)** methods within the **multi-channel Markov chain Monte Carlo (MC3)** framework, this research aimed to enhance sampling efficiency and reduce autocorrelation, especially for strongly peaked distributions. These improvements in MC methods are crucial for accurate event generation in simulations used for **collider experiments** and **particle physics research**, directly impacting the precision of theoretical predictions.

- **Institution**: University of Göttingen, 2018
- **Supervisor**: Steffen Schumann (Sherpa project contributor)
- **Key Focus**:
  - Analyzed the feasibility of using **Hamiltonian Monte Carlo (HMC)** within the **multi-channel Markov chain Monte Carlo (MC3)** framework for improving phase space sampling in collider physics.
  - Explored the **application of machine learning surrogates** for density estimation in HMC steps, a novel approach for reducing computational costs associated with gradient calculations.
- **Main Contributions**:
  - Developed and published **reusable, scalable code** on GitHub ([link to repository](https://github.com/mathisgerdes/hep-monte-carlo)).
  - The code was **further developed by a Master's student** in the group, demonstrating its foundational role in ongoing work.
  - First experience in collaborative coding through GitHub, gaining experience in **scientific software development**.
- **Skills Developed**:
  - Advanced **numerical methods** (e.g., numpy optimizations).
  - **Collaborative research**, including weekly progress updates and defining next steps with the supervisor.
  - Applied **Monte Carlo techniques** to high-energy physics and gained deeper understanding of **MCMC methods** in collider physics.
- **Outcome**:
  - Project laid a foundation for further work in **Sherpa-related research** within the group.

### CERN Summer Student Program (2018)

The **AWAKE project** at CERN investigates **plasma wakefield acceleration**, a method that could achieve much higher acceleration gradients than conventional RF accelerators. This approach uses **self-modulated proton bunches** to drive plasma wakefields, which in turn accelerate a trailing electron bunch. Understanding the **transverse profile** of these proton bunches is critical for optimizing the acceleration process. Analyzing their shape and behavior after self-modulation provides insights into the stability and efficiency of the wakefield generation, contributing to the development of next-generation particle accelerators.

- **Institution**: CERN, AWAKE project (Plasma Wakefield Accelerators)
- **Key Focus**:
  - Attended **lectures** on particle physics and plasma accelerators in the first weeks.
  - Assigned to the **AWAKE group**, a smaller team at CERN focused on proton-driven plasma wakefield acceleration.
- **Project**:
  - Analyzed images of **proton bunches** using Python to detect **asymmetries** and **outline patterns**.
  - Developed an algorithm for detecting **outlines** and **radii** of proton bunches.
  - Focused on generating extensive statistics, going beyond the initial task by exploring a variety of **image analysis metrics** and patterns.
- **Main Contributions**:
  - Delivered a well-received presentation to the group, impressing colleagues with the **comprehensive statistical approach**.
  - Demonstrated **independence** and initiative by exploring and analyzing more aspects than initially assigned.
- **Skills Developed**:
  - Advanced **data analysis in Python**, particularly for image processing.
  - **Scientific presentation** skills, presenting findings to senior academics and CERN researchers.
  - Gained exposure to **plasma acceleration techniques** and the **AWAKE experimental setup** at CERN.
- **Outcome**:
  - Successfully implemented the analysis framework for image detection and pattern recognition in the context of plasma wakefield physics.
  - Strengthened skills in **data-driven research** and independent problem-solving.

### MSc Project in AI: Rigorous Mechanization of Minkowski Space Axioms with Isabelle/HOL

The project focused on formalizing aspects of **Minkowski spacetime** in the context of **special relativity** using the **Isabelle/HOL theorem prover**, building on work previously done by Richard Schmoetten in Jacques Fleuriot’s group. By converting the geometric intuitions and axioms from Schutz’s work into rigorous formal proofs, this project advanced the mechanization of **axiomatic systems** for Minkowski space. This work contributed to the broader field of **formal methods** in physics, where ensuring the logical rigor of physical theories is crucial for correctness and reliability. Additionally, the project’s relevance extends to emerging fields like **machine learning for theorem provers**, where automation of formal verification is gaining traction.

- **Institution**: University of Edinburgh
- **Collaborators:** Jacques Fleuriot, Jake Palmer and Richard Schmoetten

**Key Focus**:

- Continued the **mechanization** of an **axiomatic system** for Minkowski spacetime using the **Isabelle/HOL** theorem prover, based on the work of Schutz.
- Focused on translating **geometric intuitions** from Schutz’s work into **rigorous formal proofs**, particularly the **third theorem of collinearity**, and addressing challenges in formalizing geometric concepts.

**Main Contributions**:

- Developed new formal proofs and improved upon **existing partial formalizations**, resolving ambiguities in the original work and formalizing theorems that previously relied on geometric intuition.
- Introduced **new notation and syntax** in Isabelle/HOL that was later adopted in future work by Richard Schmoetten and others in the group.
- Designed techniques to handle **combinatorial complexity** in geometric proofs, ensuring scalability for formalizations of more complex theorems.

**Skills Developed**:

- Gained proficiency in **Isabelle/HOL**, an advanced **theorem proving assistant** used for formal verification.
- Improved understanding of **logical proof structures**, translating informal mathematical reasoning into formalized, computer-verified theorems.
- Worked collaboratively within an **informatics research group**, further enhancing interdisciplinary research skills and adaptability.

**Outcome**:

- The thesis was recognized as an **Outstanding Project Submission** for its technical excellence and contributions to the field of **formal methods**.
- Contributed to the **broader impact** of the mechanization project by establishing reusable syntax and tools for future research in formalized physics.

**Value to Career in Physics and AI**:

- This project strengthened your ability to work on interdisciplinary problems involving **formal methods**, which are gaining relevance in fields like **machine learning** and theoretical physics.
- The experience in **theorem proving** adds a unique skill set to your profile, particularly as **ML for theorem provers** emerges as an active research area.

### MSc Project and Collaborations (Calabi-Yau Metrics with Machine Learning)

The study of **Calabi-Yau metrics** is crucial for understanding **string theory compactifications**, as these metrics influence key aspects of low-energy physics, such as **Yukawa couplings**, the **massless spectrum**, and the **swampland conjectures**. Traditional methods like **Donaldson’s algorithm** are computationally intensive and lack scalability, especially when dealing with moduli dependence. By applying **machine learning techniques** to approximate these metrics, this work provides a scalable alternative, offering more efficient computations across moduli space. This advancement is particularly valuable for **string phenomenology**, enabling deeper insights into field dynamics and complex geometries. The project integrates **deep learning** into a traditionally analytical domain, reducing computational barriers and opening new research avenues in **theoretical physics**.

- **Institutions**:
  - **MSc Thesis (Munich)**: With Sven Krippendorf, LMU Munich, 2020
  - **MSc Continuation (Edinburgh)**: Further development and collaboration, 2021
  - **CYJAX Publication (Amsterdam)**: Expanded project, final code release, 2023
- **Collaborators:** Sven Krippendorf (primarily; MSc supervisor), for the paper: Fabian Ruehle, Lara Anderson, James Gray, and Nikhil Raghuram
- **Key Focus**:
  - **Machine learning-based approach** to approximating **Calabi-Yau metrics**.
  - **Proposed learning the Kähler potential**, as an ML generalization of Donaldson’s Ansatz, improving on existing iterative schemes.
  - Implementation involved switching from TensorFlow and PyTorch to **JAX**, an early adoption of JAX.
- **Main Contributions**:
  - Developed the **JAX-based codebase** for learning Calabi-Yau metrics, which became the foundation for future work in this area and was **published with the CYJAX paper**.
  - Contributed specific sections to the **collaborative paper** (sections 2.3-2.6, specific figures, and appendices), incorporating both personal work and other approaches.
  - The final code was **significantly improved** after the MSc thesis, leading to publication in **Machine Learning: Science and Technology (MLST)** with further experiments and refinements.
- **Collaboration**:
  - Worked with **Fabian Ruehle, Lara Anderson, James Gray, and Nikhil Raghuram** on the **CYJAX paper**; led technical discussions, gave presentations on contributions, and iterated on key mathematical challenges.
  - Contributed to refining the algorithm by critically thinking about own and collaborator's approaches related to patch overlaps, leading to improvements in the overall methodology.
  - Navigated collaboration dynamics, including handling **different work styles**, and **communication methods**, contributing to overall project success.
- **Skills Developed**:
  - **Advanced mathematical understanding** (complex differential geometry, Kähler potentials, Donaldson’s algorithm), and ability to translate these into numerical implementations.
  - Deep experience with **JAX**, implementing custom algorithms (e.g., polynomial root-finding), contributing to **JAX’s official repository**.
  - **Leadership in scientific software development**, as the sole developer and maintainer of the published codebase, which is now used by multiple researchers and collaborators.
- **Community Recognition**:
  - **CYJAX paper** and MSc thesis were well-received, helping kickstart further work in **ML-based approaches to Calabi-Yau metrics**.
- **Outcome**:
  - Published code alongside the CYJAX paper in **MLST** journal, with ongoing usage by **Sven Krippendorf’s group** and others.
  - Strengthened collaboration skills, advanced technical contributions to the field, and established a reputation for integrating ML methods into high-energy physics problems.



### PhD Project: Stellar Streams Project

Stellar streams, formed by the tidal disruption of dwarf galaxies and globular clusters, provide a unique observational probe into the **dark matter distribution** and **gravitational dynamics** within galaxies like the Milky Way. These streams are sensitive to interactions with dark matter subhalos, making them crucial for understanding **dark matter substructure** and its influence on galactic evolution. However, the analysis of stellar streams is computationally challenging due to the complexity of their dynamics and the vast amount of high-quality observational data from surveys like **Gaia**. This project applies **simulation-based inference techniques** to develop a more scalable and accurate framework for analyzing stellar streams, enabling robust inferences about their structure and evolution. By leveraging **machine learning (ML)** and developing new modular dynamical models (e.g., **sstrax**), this work improves the precision of stream modeling, advancing the study of **galactic dynamics** and **dark matter substructure**. The ability to analyze the small-scale features of these streams offers new insights into both **baryonic interactions** and **dark matter properties**, contributing to broader astrophysical research.

- **Institution**: University of Amsterdam, GRAPPA Institute
- **Collaborators:** Christoph Weniger (supervisor) and James Alvey (postdoc)
- **Key Focus**:
  - Applied **simulation-based inference** (SBI) to analyze **stellar streams** in the Milky Way, leveraging a framework based on **ratio estimation** developed by Christoph Weniger.
  - The project focused on simulating the dynamics of stellar streams—gravitationally bound clusters of stars disrupted over time by the Milky Way’s gravitational potential and **dark matter subhalos**.
- **Main Contributions**:
  - Developed an **efficient simulator** that models the evolution of stellar streams in the presence of both **Newtonian dynamics** and potential **dark matter perturbations**, distilling the complex astrophysical problem into a manageable computational framework.
  - Addressed technical decisions regarding the **coordinate system** and the **level of detail** required for realistic stream simulations.
  - Transitioned from **Julia to JAX** for improved performance and scalability, gaining deeper expertise in high-performance computing environments and advanced simulation techniques.
  - Collaborated extensively via GitHub on code development with James Alvey, refining best practices for **collaborative coding** and **efficient data processing** pipelines in astronomy.
- **Skills Developed**:
  - **Simulation and modeling**: Gained expertise in **Newtonian gravitational simulations**, applicable in various theoretical and computational physics contexts.
  - **Data processing in astronomy**: Familiarized with **astrophysical data pipelines** and the use of **simulation-based inference** to efficiently handle large datasets in a research setting.
  - **Collaborative project management**: Worked closely with collaborators on defining project scope, distilling a problem down to its core computational elements, and completing the project under shared leadership.
  - **Learning and adopting tools**: Swiftly transitioned between computational tools (Julia, JAX) and implemented scalable solutions, enhancing versatility in high-performance computation environments.
- **Outcome**:
  - The project, while not focused on novel physics, provided a **proof of principle** for the use of SBI in the analysis of **stellar streams**, contributing to the astrophysics community's ability to model the interaction between dark matter substructure and stellar streams.
  - Co-authored a paper with a focus on the **technical implementation** and efficient simulation of stellar dynamics, which has informed further research in galactic dynamics and dark matter studies.
- **Value to Career in Theoretical Physics**:
  - Strengthened your ability to **distill complex physical problems** into scalable computational frameworks, a skill highly transferable to **theoretical physics research**.
  - The knowledge of **simulation-based inference** and the implementation of high-performance **data analysis pipelines** has broadened your technical skillset, useful in future projects that involve **computational modeling** in fields such as **quantum field theory** or **lattice physics**.
  - Collaboration dynamics with James and Christoph improved your ability to manage **multi-disciplinary research** and balance **technical execution with conceptual problem-solving**, a key trait in academic physics.

### PhD Project: Continuous Normalizing Flows for Lattice Quantum Field Theory

Lattice quantum field theory (LQFT) provides a non-perturbative framework to study quantum field theories such as **Quantum Chromodynamics (QCD)**. However, traditional methods like **Markov Chain Monte Carlo (MCMC)** suffer from critical slowing down near phase transitions and the continuum limit, making computations increasingly expensive. **Normalizing flows** have emerged as a promising alternative for improving sampling efficiency and reducing autocorrelation. This project advances the application of **continuous normalizing flows (CNFs)** to LQFT, ensuring that key symmetries like gauge invariance are maintained while significantly improving computational scalability and efficiency. These advancements are vital for more efficient simulations of complex quantum systems and have broad implications for the study of fundamental particles and forces.

- **Institution**: University of Amsterdam (with collaborators from Imperial College and other institutions)
- **Key Focus**:
  - **Applying machine learning techniques** to tackle computational challenges in **lattice quantum field theory** (LQFT), with the goal of improving sampling efficiency and preserving symmetry in gauge theories.
  - Built on previous work by Pim and collaborators, which proposed a **continuous normalizing flow (CNF)** for **ϕ^4 theory** to enhance the sampling process in LQFT, outperforming traditional deep architectures.
- **Main Contributions**:
  - **Reimplemented the entire framework in JAX** (initially developed in PyTorch) due to Qualcomm IP restrictions, leading to significant performance improvements.
  - Developed innovations such as **non-linear activations**, better **time parametrization**, and scaling the model to **larger lattices** with **parameter-dependent networks**, which drastically improved training time and model performance.
  - Expanded the framework to **gauge-equivariant continuous normalizing flows**, supporting general groups like **SU(2)** and **SU(3)**, outperforming existing methods like those proposed by Bacchio et al.
  - Created a new **Crouch-Grossmann integrator** and implemented a **general adjoint sensitivity method** to extend continuous flows to gauge theories with Lie group degrees of freedoms.
- **Skills Developed**:
  - Advanced understanding of **machine learning for quantum field theory**, specifically in the design and implementation of **continuous flows** that preserve physical symmetries.
  - Expertise in **high-performance computing** using JAX.
  - Strengthened ability to integrate **gauge symmetries** into ML models, essential for QFT research.
  - Improved **collaborative research** skills through work with multiple groups (e.g., Pim, Roberto, Miranda, and other contributors).
- **Outcome**:
  - Published a paper on **continuous flows for LQFT**, which has been presented at multiple conferences and workshops, gaining recognition within the community (see your CV for details).
  - Released the project’s code base, which has been the foundation for **several off-shoot projects** and **master's theses** in your research group.
  - The ongoing project is nearing completion with **SOTA results for SU(2) and SU(3)**, with an upcoming paper focusing on these developments.
- **Value to Theoretical Physics**:
  - This project addresses one of the **central challenges in lattice gauge theory**: overcoming the computational inefficiencies of traditional MCMC methods near phase transitions and in the continuum limit.
  - It lays the foundation for more **scalable methods** in LQFT, contributing to fields such as **Quantum Chromodynamics (QCD)**, and providing the groundwork for future research into more complex gauge groups.
  - **Machine learning techniques**, particularly those involving continuous normalizing flows, are becoming increasingly important for both theoretical and computational physics, with your work representing a critical advancement in the area.

### PhD Project: Learning Real-Space RG Transformations with Diffusion Models

This project investigates the intersection of **diffusion models** and **renormalization group (RG)** concepts in physics. We started with **learning real-space RG transformations** through machine learning, but then pivoted to **applying RG ideas to improving diffusion models**. The RG provides a critical framework in theoretical physics, describing how systems behave across different scales by systematically eliminating irrelevant degrees of freedom. There are notable parallels between this process and diffusion generative models, where noise is progressively added to data and reversed to generate samples. This project builds on these parallels, exploring how key design choices in diffusion models—such as the choice of basis, noise schedules, and scaling—can be optimized by leveraging insights from RG flows. The work aims to bridge generative modeling in machine learning with fundamental ideas from **quantum field theory (QFT)** and **statistical physics**, opening up new avenues for efficient generative processes and RG-inspired architectures.

- **Institution**: University of Amsterdam (with Max Welling's group and collaborations)
- **Collaborators:** Max Welling, Miranda Cheng, more to join.
- **Key Focus**:
  - Developing a flexible **diffusion generative model framework** inspired by **renormalization group (RG)** concepts from physics.
  - The framework allows for experimentation with various **linear component bases**, **component-wise noise schedules**, and different **scalings** corresponding to prior distributions for diffusion models, making it highly flexible and adaptable to different applications.
- **Main Contributions**:
  - **Implemented the entire framework from scratch**, including score matching models and an efficient solver for the reverse generative model as both **ODE** and **SDE**.
  - Developed a flexible, modular system that can accommodate any **linear basis**, along with customizable **component-wise schedules** and scaling.
  - The project has progressed to **regular collaborative meetings** with Max Welling’, with expectations for further expansion as more students join the collaboration.
- **Skills Developed**:
  - Advanced proficiency in implementing complex **diffusion models**, including both **stochastic and deterministic formulations** (SDE and ODE).
  - Significant experience working with **machine learning** techniques in combination with **theoretical physics** concepts, particularly the **renormalization group**.
  - Built extensive experience in **interdisciplinary collaboration**, bridging physics and machine learning communities.
- **Outcome**:
  - A **highly flexible diffusion framework** that allows for novel generative processes, with the potential to generate images hierarchically or sequentially.
  - Ongoing development of this framework is expected to produce advancements in **machine learning** generative models, with initial results forming the basis of a paper under preparation for **ICLR**.
  - The project is the foundation of a **long-term collaboration**, with more PhD students and collaborators expected to join and extend the work into more detailed investigations of real-space RG flows.

### PhD Project: High Likelihood Coverage Intervals at the Bayesian-Frequentist Crossroads

**NOT YET PUBLISHED** ; must not reveal too many details of the ideas here.

Statistical inference, particularly in the construction of **coverage intervals**, is central to modern physics, where experiments rely on rigorous methods to quantify uncertainty. Traditional approaches, including **Bayesian credible intervals** and **frequentist confidence intervals**, offer different perspectives on how to construct these intervals, each with distinct advantages and limitations. This project bridges these two statistical frameworks by exploring new methods for constructing **coverage intervals** that combine the strengths of both approaches. Specifically, it investigates the use of **likelihood-ordered intervals** and develops a novel type of **high-likelihood coverage interval (HLDI)** that maximizes coverage. This research offers a unified perspective on interval construction, applicable across many fields of experimental physics, and opens new possibilities for reconciling Bayesian and frequentist methods.

- **Institution**: University of Amsterdam (with Christoph Weniger)
- **Key Focus**:
  - Developing a novel approach to **coverage intervals**, reconciling **Bayesian credible intervals** and **frequentist confidence intervals** through a unified framework.
  - Proposed a new method for constructing **high-likelihood density intervals (HLDI)**, which improves coverage by ordering intervals according to likelihood while still maintaining Bayesian coverage guarantees.
  - Framework for learning coverage using machine learning, optimizing coverage metrics.
- **Main Contributions**:
  - Developed **machine learning methods** to refine the statistical framework, adding flexibility in exploring coverage intervals under varying assumptions about the prior and likelihood distributions.
  - Explored the use of **orderings based on likelihood ratios**, with applications to both experimental and theoretical physics, providing a versatile tool for accurate interval estimation in a wide range of use cases.
- **Skills Developed**:
  - Deepened expertise in **statistics** methods, particularly in **Bayesian and frequentist principles** for constructing coverage intervals.
  - Further strengthened **collaborative research skills**, particularly in driving forward innovative projects and expanding traditional methods in statistics with new computational tools.
- **Outcome**:
  - Developed a more general approach to interval estimation that extends beyond traditional Bayesian and frequentist frameworks.
  - Laid the groundwork for further research on the intersection of **statistics and machine learning**, with broad applications in physics, particularly in data-driven experiments.
  - The project continues to develop, with the potential for future publications.

### Smaller and Ongoing Projects Overview

- **Learning Real-Space RG Transformations (with Ying-Jer Kao and Max Welling)**
  - Focused on applying machine learning techniques like **normalizing flows**, **restricted Boltzmann machines (RBMs)**, **variational autoencoders (VAEs)**, and **mutual information** to learn **real-space renormalization group (RG) transformations**.
  - Explored different models for reconstructing the RG flow and transforming high-dimensional data.
  - **Status**: Project is currently suspended, but could potentially be resumed in the future.
- **Upscaling Normalizing Flows (with Kim Nicoli)**
  - Investigating methods for **upscaling normalizing flows**, inspired by **inverse RG flows**.
  - Current work involves incorporating **wavelet transforms** into **hierarchical normalizing flows** for **scalar field theories**, providing a multi-resolution approach to generating field configurations efficiently.
  - **Status**: Ongoing work, with promising early progress.
- **BI MC Sampling and Latent Space Dynamics (with G. Bruno De Luca and Eva Silverstein)**
  - Initial discussions on incorporating **Microcanonical Hamiltonian Monte Carlo sampling methods** with **normalizing flows** e.g. to explore the **latent space dynamics** of Monte Carlo simulations.
  - Investigated how MC sampling could be enhanced by latent space transformations for efficient sampling in high-dimensional spaces.
  - **Status**: Project did not proceed beyond initial discussions but remains open for potential future collaboration.