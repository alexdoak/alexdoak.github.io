# Alex Doak





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
  <img src="/assets/images/internal_tide.jpg" width="250" />
</div>

At the 2024 NFFDy summer workshop at Leeds university, working with Lois Baker (Edinburgh) and Dianfang Bi (Surrey), we found evidence of baroclinic internal tide resonances in MIT's global ocean ciruclation model LLC4320. Theoretical papers demonstrate that it is possible that, near the equator, near resonance of a mode-1 internal tide with itself can transfer energy to it's superharmonic via a classical triad resonance. This comes from the fact that, when the coriolis parameter is small, the dispersion relation $\omega(k)$ satisfies approximately $\omega(k)+\omega(k)\approx \omega(2k)$. We wanted to validate this theory by finding such energy exchanges in ocean models. Despite the fact that the MITgcm model is hydrostatic, dispersion still occurs due to the inclusion of the Coriolis term in the momentum equation.

We processed this data set to obtain a north-east travelling internal tide beam generated at the French Polynesian Islands. The energy corresponding to the parent mode and its superharmonic were recovered, and we found that the energy transfer is of the same order as expected by the theoretical models, providing validation of the simplified two-dimensional model.

Papers:
* [Near-Resonant Generation of Internal Tide Superharmonics: Comparing Theoretical Predictions With a Global Ocean Model (Geophysical Research letters)](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2024GL114226)



### Cyclostratigraphy
Following an industrial think tank hosted by the SAMBa CDT at Bath, I have been working with Veronica Raffetto (Bath), Matthias Ehrhardt (Bath), and Kathryn Leeming (British Geological survey) on the field of cyclostratigraphy. The goal is to date rock samples by correlating astronomical signals (which influence the climate on Earth) with geological signals such as chemical traces in the rock. The challenge is that this is a highly nonlinear inverse problem: one must map from the spatial coordinate of the geological signal to the time coordinate of the astronomical signal, and then minimise a suitable loss functional relative to this mapping.

This work is ongoing, but promising advances have been made through signal processing techniques and non-convex optimisation strategies.


### Vorticity waves
<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/vort_2.png" width="400" />
</div>
Working with Jean-Marc Vanden-Broeck (UCL) and Vera Hur (Illinois Urbana-Champaign), we have been exploring a numerical method to compute free-surface waves with an arbitrary distribution of vorticity in the fluid bulk. The numerical scheme utilises a framework developed by [Wahlen & Weber (2023)}{https://academic.oup.com/imrn/article/2023/20/17377/6760808}, in which the flow domain is conformally mapped to a rectangular domain. Due to the non-constant vorticity, one cannot use the tools of complex analysis to solve the field equation exclusively using values on the boundary. Hence, the field equation is solved in the bulk of the fluid. These computations are the first for waves with non-constant vorticity which allow for internal stagnation and overhanging streamlines.

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="/assets/images/vort_3.png" width="400" />
</div>

While co-supervising Jonty Sewell's PhD, alongside Miles Wheeler and Karsten Matthies, we looked at the global bifurcation of waves propogating at a vorticity interface. Near-limiting profiles were recovered, and surprisingly a complete sweep of parameter space revealed no overhanging streamlines!

Papers:
* [Stokes waves in rotational flows: internal stagnation and overhanging profiles (2025, JFM)](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/stokes-waves-in-rotational-flows-internal-stagnation-and-overhanging-profiles/AC1C809BEDABC7C1198BE50107FE2F1D)
* [Large-amplitude periodic solutions to the steady Euler equations with piecewise constant vorticity (2025, in review for Stud. App. Math.](https://arxiv.org/abs/2506.17002)


### Internal tide resonances
Working with Lois Baker (Edinburgh) and Dianfang Bi (Surrey), during the NFFDy 2025 summer programme at Leeds we sought out evidence of mode-1 internal tide resonances along a internal tide beam generated at the  French Polynesian Islands. We used data from the MIT Global Ocean Circulation Model (MITGCM),in particular the LLC4320 configuration. We developed a data processing pipeline to provide convincing evidence that superharmonics are resonantly generated via a triad resonance. The results 

Papers:
* [Near‐Resonant Generation of Internal Tide Superharmonics: Comparing Theoretical Predictions With a Global Ocean Model](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2024GL114226)

### River bathymetry reconstruction

### Gravity currents



### Interfacial electrohydrodynamical waves
Working with Tao Gao (Essex) and Jean-Marc Vanden-Broeck (UCL), we have explored free-surface waves to a variety of electrohydrody

### Axismmetric potential flows

### Two-dimensional free-surface flows
