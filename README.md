

## Biography

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/fig1.jpeg" width="250" />
</div>

Hey there!

I am Alex Doak, and I work in the Department of Mathematical Sciences at the University of Bath as a National Fellow in Fluid Dynamics. My research interests include free-surface and interfacial flows, internal waves, and electrohydrodynamics. See below for a list of my current and old projects.

As well as getting on with my own research, I enjoy facilitating the research of the postgraduate students at Bath. A particular highlight are the Integrative Think Tanks, a biannual event hosted by the SAMBa Centre for Doctoral training (https://samba.ac.uk/), where industrial partners present challenges they are facing. The students are tasked with formulating the problems mathematically, and these are always very interesting events. 

I co-organise the Applied and Interdisciplinary Mathematics Seminar (https://bath-aims.github.io/). If you are interested in giving a talk, please do not hesitate to get in touch 


## Research

### Mode-1 and mode-2 internal waves
<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/mode1_internalwave.png" width="250" />
</div>

Working with Ricardo Barros (Loughborough), Paul Milewski (Penn State), and Wooyoung Choi (NJIT), we have been looking at the global bifurcation structure of three-layer mode-1 internal solitary waves. Through critical point analysis of an asymptotic model to the full Euler equations, we are able to separate regions of parameter space where there exist either depression or elevation waves, or both. The story is very rich, the spontaneous emergence of critical points being the complicating factor, resulting in interesting solutions such as pyramidal solitons.

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/mode2_internalwave.png" width="250" />
</div>

On mode-2 solitary waves, we were the first to demonstrate, through numerical computations, that so called *embedded solitary waves* exist in a three-layer stratification. These solitary waves are unique in that they exist in a parameter space with co-dimension 1 to that of mode-1 solitary waves. In a sense, they are needles in a haystack, where an additional degree of freedom in the parameter-space is spent finding them along branches of   *generalised solitary waves* (solitary waves with oscillatory tails). Embedded solitary waves have been shown to not exist for a variety of wave problems in the Euler equations: to my knowledge this is the first example of them.

More recently, we have been exploring these waves in continuosly stratified fluids, motivating and motivated by an experimental campaign (being led by Magda Carr and Niraj Prasad at Newcastle), to explore their generation and stability. 

Finally, I have explored the solution space for mode-1 and mode-2 periodic solutions in a three-layer flow, in work led by Xin Guan (Imperial), along with Paul Milewski and Jean-Marc Vanden-Broeck (UCL).




Papers:
* [A classification of mode-1 internal solitary waves in a three-layer fluid (2025, in review for JFM)](https://arxiv.org/abs/2509.24669)
* [Large mode-2 internal solitary waves in three-layer flows (2022, JFM)](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/abs/large-mode2-internal-solitary-waves-in-threelayer-flows/9EC866BEE0DBAB79CC906785B79CCE8B)
* [Nonlinear travelling periodic waves for the Euler equations in three-layer flows (2024, JFM)](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/nonlinear-travelling-periodic-waves-for-the-euler-equations-in-threelayer-flows/61E0844B01BCF8DD23B94106FF6F41C3)


### Internal Tides 
<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/internal_tide.jpg" width="600" />
</div>
At the 2024 NFFDy summer workshop at Leeds university, working with Lois Baker (Edinburgh) and Dianfang Bi (Surrey), we found evidence of baroclinic internal tide resonances in MIT's global ocean ciruclation model LLC4320. Theoretical papers demonstrate that it is possible that, near the equator, near resonance of a mode-1 internal tide with itself can transfer energy to its superharmonic via a triad near-resonance. This comes from the fact that, when the coriolis parameter is small, the dispersion relation $\omega(k)$ satisfies approximately $\omega(k)+\omega(k)\approx \omega(2k)$. We wanted to validate this theory by finding such energy exchanges in ocean models. Despite the fact that the MITgcm model is hydrostatic, dispersion still occurs due to the inclusion of the Coriolis term in the momentum equation.

We processed this data set to obtain a north-east travelling internal tide beam generated at the French Polynesian Islands. The energy corresponding to the parent mode and its superharmonic were recovered, and we found that the energy transfer is of the same order as expected by the theoretical models, providing validation of the simplified two-dimensional model.

Papers:
* [Near-Resonant Generation of Internal Tide Superharmonics: Comparing Theoretical Predictions With a Global Ocean Model (2025, Geophysical Research letters)](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2024GL114226)



### Cyclostratigraphy
Following an industrial think tank hosted by the SAMBa CDT at Bath, I have been working with Veronica Raffetto (Bath), Matthias Ehrhardt (Bath), and Kathryn Leeming (British Geological survey) on the field of cyclostratigraphy. The goal is to date rock samples by correlating astronomical signals (which influence the climate on Earth) with geological signals such as chemical traces in the rock. The challenge is that this is a highly nonlinear inverse problem: one must map from the spatial coordinate of the geological signal to the time coordinate of the astronomical signal, and then minimise a suitable loss functional relative to this mapping.

This work is ongoing, but promising advances have been made through signal processing techniques and non-convex optimisation strategies.


### Vorticity waves
<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/vort_2.png" width="400" />
</div>
Working with Jean-Marc Vanden-Broeck (UCL) and Vera Hur (Illinois Urbana-Champaign), we have been exploring a numerical method to compute free-surface waves with an arbitrary distribution of vorticity in the fluid bulk. The numerical scheme utilises a framework developed by [Wahlen \& Weber (2023)](https://academic.oup.com/imrn/article/2023/20/17377/6760808), in which the flow domain is conformally mapped to a rectangular domain. Due to the non-constant vorticity, one cannot use the tools of complex analysis to solve the field equation exclusively using values on the boundary. Hence, the field equation is solved in the bulk of the fluid. These computations are the first for waves with non-constant vorticity which allow for internal stagnation and overhanging streamlines.

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/vort_3.png" width="400" />
</div>

While co-supervising Jonty Sewell's PhD, alongside Miles Wheeler and Karsten Matthies, we looked at the global bifurcation of waves propogating at a vorticity interface. Near-limiting profiles were recovered, and surprisingly a complete sweep of parameter space revealed no overhanging streamlines!

Papers:
* [Stokes waves in rotational flows: internal stagnation and overhanging profiles (2025, JFM)](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/stokes-waves-in-rotational-flows-internal-stagnation-and-overhanging-profiles/AC1C809BEDABC7C1198BE50107FE2F1D)
* [Large-amplitude periodic solutions to the steady Euler equations with piecewise constant vorticity (2025, in review for Stud. App. Math.](https://arxiv.org/abs/2506.17002)





### River bathymetry reconstruction

### Gravity currents
<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/GC.png" width="600" />
</div>

At the 2023 NFFDy summer workshop at Cambridge university, working with Edward Skevington (Hull), Charlie LLoyd (Hull), and Amir Atoufi (Cambridge), we explored the long-time steady state of a sloped stratified flow exchange under a gate. This was done through reduced order modelling, in particular a two-layer shallow water model with an additional drag force to allow for a flat far-field behaviour, and data processing of full three-dimensional Navier-Stokes simulations. Spectral proper orthogonal decomposition of span-averaged data demonstrated wave-like instabilities at the density interface as the gravity current propogated down the slope.

Papers:
* [Instabilities in downslope propagating gravity currents (2023, Proceedings of the NFFDy Summer Programme on ‘Data in Fluids’)](https://doi.org/10.17863/CAM.107271)




### Interfacial electrohydrodynamical waves
Working with Tao Gao (Essex) and Jean-Marc Vanden-Broeck (UCL), we have explored free-surface waves to a variety of electrohydrody

### Axismmetric potential flows
During my PhD at UCL, working with my supervisor Jean-Marc Vanden-Broeck, we found numerical solutions to axismmetric potential flow problems. We explored solution selection of Taylor bubbles, and waves on a ferrofluid jet. In both cases, a hodograph transformation was used to solve the steady-state flow in the potential space. The Stokes' streamfunction, unlike the streamfunction for classical two-dimesional potential flow, does not satisfy the Laplace equation. Hence, tricks from complex analysis must be replaced with other methodologies. For this purpose, we solve the flow equation in the potential space with finite differences, using a classical trick by Woods called 'function splitting' to handle boundary singularities.
<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/bubble2.png" width="300" />
</div>

Taylor bubbles are long bubbles rising in a tube. They can be generated by pulling the bottom out of a cyclidrical tank of fluid: after an initial unstable phase, a finger of air will start to rise up the tank as the water travels downwards. These bubbles are dominated by gravity, but one finds an infinite set of possible solutions for a range of Froude numbers $F\in[0,F_c]$ when considering only gravity acting on the free-surface. Inclusion of surface tension makes this infinite set discrete, and furthermore the branches of solutions appear to converge to a given value $F=F^*$ as surface tension is taken to zero. We provide numerical evidence of this for axisymmetric Taylor bubbles. 

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/f_jet.png" width="600" />
</div>

A column of fluid is famously unstable to the Plateau–Rayleigh instability. This can be stabilised if the column of fluid is a ferrofluid, subjected to an external azimuthal magnetic field, which can be generated by running a current through a copper wire which the ferrofluid coats. This stabilised column of fluid can support wave propogation, such as the solitary waves found experimentally by [Bourdin et al](https://doi.org/10.1103/PhysRevLett.104.094502). We expanded on initial steady state computations by [Blyth and Părău ](https://doi.org/10.1017/jfm.2014.275) by including the density of the second fluid (non-magentisable freeon of equal density to that of ferrofluid). A variety of bifuraction branches were found, including generalised solitary waves, solution multiplicity, and stationary waves. 


Papers
* [Solution selection of axisymmetric Taylor bubbles (2018, JFM))](https://doi.org/10.1017/jfm.2018.156)
* [Travelling wave solutions on an axisymmetric ferrofluid jet (2019, JFM)](https://doi.org/10.1017/jfm.2019.60)

### Two-dimensional free-surface flows
