# University-Projects

The various Python projects I have completed during my degree at Queen Mary University of London. This includes the code for visualisations I used in my Master's disseratation, discussing the impact on the Cosmic Microwave Background (CMB) as a result of varying the level of dark matter in the Universe. There are also projects I submitted as part of coursework for computational modules.

<details>
<summary><h3>Thesis - "Modelling the Effects of Dark Matter on the Cosmic Microwave Background"</h3></summary>

I simulated CMB maps for varying levels of dark matter using the Code for Anisotropies in the Microwave Background (CAMB). Following this, I compared these maps to the CMB map generated from theoretical data obtained from the Planck 2018 mission.

<!---
I explored how varying levels of dark matter influence the Cosmic Microwave Background (CMB). Using the Code for Anisotropies in the Microwave Background (CAMB), I simulated theoretical CMB maps and compared them to Planck 2018 observational data. The project demonstrates my ability to combine theoretical physics with computational tools to study complex cosmological phenomena.
-->

## Key Features:

- Simulated CMB power spectra and maps for varying dark matter densities.
- Compared theoretical simulations to Planck 2018 datasets to identify discrepancies.
- Used Python libraries like `camb`, `healpy`, and `matplotlib` to process data and visualise results.

## Results:

- Successfully generated CMB maps that reflected the influence of varying dark matter densities.
- Followed [Wayne Hu's lecture notes](https://arxiv.org/abs/0802.3688) to visualise the effects of dark matter on the third peak of the CMB power spectrum. This emphasised the work from [Hu's 2001 paper](https://arxiv.org/abs/astro-ph/0006436) which explained the change in the height ratios of the second and third peaks due to decay in the gravitational potential during radiation domination.
- Identified consistent patterns between the simulated maps and Planck data, validating the CAMB-based modelling approach.
- Highlighted discrepancies that could point to additional factors or alternative models influencing the CMB.

## Applications:

- Analysing dark matter’s role in shaping the early universe.
- Supporting cosmological studies by combining observational data and simulations.
- Providing a foundation for further research into alternative dark matter models and their observational signatures.

## Potential Extensions:
This work can be extended by:

- Exploring alternative dark matter hpotheses using `camb`, such as Weakly Interacting Massive Particles (WIMPs) or Primordial Black Holes.
- Incorporating datasets from WMAP and upcoming Simons Observatory data, with a particular focus on connecting CMB observations to gravitational wave studies.
- Refining the simulation process by applying machine learning techniques to extract features, detect anomalies, and improve parameter estimation.

</details>

<details>
<summary><h3>MCMC Doppler analysis</h3></summary>

This project focuses on detecting and characterising extrasolar planets using radial velocity data obtained through the Doppler technique. I used a variant of the Metropolis-Hastings algorithm to fit circular orbital models to real data, extracting key planetary and orbital parameters.

## Key Features:

- Translated orbital mechanics equations into code and implemented MCMC methods for parameter estimation.
- Analysed real radial velocity datasets from stars like 51 Pegasi to infer planetary characteristics.
- Visualised phase-folded radial velocity data to identify trends and features.

## Results:

- Successfully detected exoplanetary signatures from radial velocity datasets, including identifying potential orbital periods and planetary masses.
- Demonstrated that the Metropolis-Hastings algorithm can effectively estimate parameters with reasonable computational efficiency.
- Highlighted the strengths of the Doppler technique, particularly for characterising larger, closer planets with significant gravitational influence.

## Applications:
This project fits into the broader context of missions like Kepler, TESS, and the James Webb Space Telescope, which aim to characterise exoplanetary systems. Through this project and the 4th-year module 'Extrasolar Planets and Astrophysical Discs' I later took, I learned more about (and was able to demonstrate):

- A method for refining orbital parameters like semi-major axis, period, and planetary mass.
- The ability to compare the Doppler technique to other detection methods, such as the transit method and direct imaging.
- Insights into planetary system diversity and habitability.

## Future Improvements:

- Add interactivity to the notebook, allowing users to adjust orbital parameters via sliders and visualise how changes affect radial velocity curves.
- Extend the analysis to multi-planet systems and non-circular orbits for more complex scenarios.

</details>

<details>
<summary><h3>Comparing ODE solvers for 2- and 3-body systems</h3></summary>

I simulated the orbital dynamics of two- and three-body systems, specifically the Earth-Sun and Mercury-Earth-Sun systems. I implemented and compared three numerical integration methods: the fourth-order Runge-Kutta (RK4) method, `scipy.integrate.ode`, and `scipy.integrate.odeint`.

## Key Features:

- Translated the equations of motion for gravitational interactions in two- and three-body systems into code.
- Implemented multiple numerical integrators to solve ODEs.
- Visualised orbital trajectories, energy and angular momentum, and evaluated the accuracy of each method.

## Results:

- Found that the RK4 method provided high accuracy but required careful step-size adjustment to maintain stability.
- Observed computational efficiency advantages in scipy.integrate.ode and odeint, particularly for longer simulations.
- Demonstrated how different numerical methods yield varying trade-offs between accuracy and computational efficiency.

## Applications:
This project has real-world relevance in:

- Space mission planning, satellite trajectory design, and spacecraft navigation.
- Studying planetary stability, orbital resonance, and gravitational interactions in multi-body systems.
- Understanding celestial mechanics for applications like asteroid deflection or interplanetary travel.

## Future Improvements:

- Include more complex scenarios, such as non-circular or eccentric orbits.
- Compare numerical methods using additional metrics, such as energy conservation and computational efficiency.
- Implement advanced integrators, like symplectic methods, for better long-term stability in simulations.

</details>
