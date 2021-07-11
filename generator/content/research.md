+++
title = "Research"
+++

_Summer/Fall 2021: I'm on the job market for algorithms/methods/theory related postdocs and full-time research roles_ 
[(Resume/CV)](https://drive.google.com/file/d/10htJNeyPrewHVEymIfwwnPHj9m69EXCt/view?usp=sharing)

## Research
<!-- 
Current interests: 
* Agents, Games & Reinforcement Learning
* Recurrent Neural Networks & Dynamical Systems
* Inverse problems in Learning & Control
* Self-organization and brain/biology/nature inspired algorithms
* Statistical Neuroscience 
 -->
### PhD (2017 - 2021/expected)
* PhD at the University of Washington (Seattle), at the intersection of ML/RL and Computational Neuroscience. 
* Working with [Bingni W Brunton (UW Neurobiology)](https://www.biology.washington.edu/people/profile/bing-w-brunton) and [Rajesh PN Rao (UW Computer Science)](https://www.cs.washington.edu/people/faculty/rao).

#### Understanding biological plume tracking behavior using deep reinforcement-learning (Ongoing)

Abstract: The ability to track odor plumes in dynamic environments is critical for flying insects following attractive odors to localize food or mates. This remarkable tracking behavior requires multimodal integration of odor, vision, and wind sensing, is robust to variations in plume statistics and wind speeds, and can often be performed over large distances. Therefore, it is challenging to study in confined experimental settings. Here we describe ongoing work to explore the space of policies effective to accomplish plume tracking, leveraging the reproducibility and interpretability of artificial agents trained in biologically motivated simulations. Specifically, we trained neural-network (NN) agents with deep reinforcement learning to locate the source of a patchy simulated plume, while varying their capacity to store past sensory stimuli. We analyzed the behavior of trained agents by inspecting successful trajectories. We then interrogated the input-output maps learned by the NNs, uncovering interpretable differences in control strategies introduced by varying sensory memory. We believe that our simulation-based approach can generate novel testable hypotheses to guide the development of targeted neuroethological experiments, as well as provide a pathway towards a mechanistic understanding of the key multimodal computations required for plume tracking.

![Constant Wind Plume Tracking](/oldparams-cropped.gif)


[Singh et al, 2020 (ALIFE Conference 2020 Abstract)](https://direct.mit.edu/isal/proceedings/isal2020/32/750/98465) 

Also presented at:
* [NAISys 2020](https://meetings.cshl.edu/abstracts.aspx?meet=naisys&year=20) 
* [IROS 2020 Robot inspired Biology Workshop](http://gravishlab.ucsd.edu/iros2020/)

(Full paper in preparation)


#### Mining naturalistic human behaviors in long-term video and neural recordings

Abstract: Recent technological advances in brain recording and artificial intelligence are propelling a new paradigm in neuroscience beyond the traditional controlled experiment. Rather than focusing on cued, repeated trials, naturalistic neuroscience studies neural processes underlying spontaneous behaviors performed in unconstrained settings. However, analyzing such unstructured data lacking a priori experimental design remains a significant challenge, especially when the data is multi-modal and long-term. Here we describe an automated approach for analyzing simultaneously recorded long-term, naturalistic electrocorticography (ECoG) and naturalistic behavior video data. We take a behavior-first approach to analyzing the long-term recordings. Using a combination of computer vision, discrete latent-variable modeling, and string pattern-matching on the behavioral video data, we find and annotate spontaneous human upper-limb movement events. We show results from our approach applied to data collected for 12 human subjects over 7--9 days for each subject. Our pipeline discovers and annotates over 40,000 instances of naturalistic human upper-limb movement events in the behavioral videos. Analysis of the simultaneously recorded brain data reveals neural signatures of movement that corroborate prior findings from traditional controlled experiments. We also prototype a decoder for a movement initiation detection task to demonstrate the efficacy of our pipeline as a source of training data for brain-computer interfacing applications. Our work addresses the unique data analysis challenges in studying naturalistic human behaviors, and contributes methods that may generalize to other neural recording modalities beyond ECoG. We publicly release our curated dataset, providing a resource to study naturalistic neural and behavioral variability at a scale not previously available.

![Right Wrist](https://raw.githubusercontent.com/BruntonUWBio/mining2021/master/right_only_1x4_boomerang.gif)

[Singh et al (Journal of Neuroscience Methods, Apr 2021)](https://www.sciencedirect.com/science/article/pii/S0165027021001345)
([Preprint](https://arxiv.org/abs/2001.08349)) ([Code, data & more videos](https://github.com/BruntonUWBio/mining2021)) 

This paper's data generating pipeline and dataset were the foundation for additional papers:
* [Peterson, SP and Singh, SH, et al (eNeuro, May 2021)](https://www.eneuro.org/content/early/2021/05/21/ENEURO.0007-21.2021.abstract) (Joint 1st authorship)
* [Peterson et al (Journal of Neural Engineering, March 2021)](https://iopscience.iop.org/article/10.1088/1741-2552/abda0b/meta) (Not a co-author; only contributed data)

[#tweeprint](https://twitter.com/tweetsatpreet/status/1276201158575452160) on this paper:  
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Our new preprint titled “Investigating naturalistic hand movements by behavior mining in long-term video and neural recordings” is now online: <a href="https://t.co/46FsBMFnV1">https://t.co/46FsBMFnV1</a><br>Joint work with <a href="https://twitter.com/stevenmpeterson?ref_src=twsrc%5Etfw">@stevenmpeterson</a>, <a href="https://twitter.com/RajeshPNRao?ref_src=twsrc%5Etfw">@RajeshPNRao</a> &amp; <a href="https://twitter.com/bingbrunton?ref_src=twsrc%5Etfw">@bingbrunton</a> <br>1/4 <a href="https://t.co/6360Dw8TMs">pic.twitter.com/6360Dw8TMs</a></p>&mdash; Satpreet Singh (@tweetsatpreet) <a href="https://twitter.com/tweetsatpreet/status/1276201158575452160?ref_src=twsrc%5Etfw">June 25, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

#### Non-Negative Matrix Factorization Game

Abstract: We present a novel game-theoretic formulation of Non-Negative Matrix Factorization (NNMF), a popular data-analysis method with many scientific and engineering applications. The game-theoretic formulation is shown to have favorable scaling and parallelization properties, while retaining reconstruction and convergence performance comparable to the traditional Multiplicative Updates algorithm.

[Unrefereed Preprint/Extended Project Report](https://arxiv.org/abs/2104.05069)


### Before PhD 

* [Cerenkov: Computational elucidation of the regulatory noncoding variome, ](https://par.nsf.gov/biblio/10049769) at the 8th ACM International Conference on Bioinformatics, Computational Biology,and Health Informatics (2017)
* [Visualization and Analysis of Sensor Data for Detecting Microclimate Cold Air Pools](https://ir.library.oregonstate.edu/concern/graduate_thesis_or_dissertations/k0698d22b) Oregon State University MS Thesis (2017) 

Abstract: Cold air pools are spatiotemporal phenomena that occur when cold air from higher elevations roll down the slope to accumulate in lower elevations. Behaviors like this lead to microclimate anomalies such as the city of Corvallis (Oregon) experiencing persistent cold weather even on a sunny day. We analyze multivariate temperature time-series data and associated covariates from about 160 sensors from the HJ Andrews Research Forest (Oregon) through visualization and modeling to study this phenomenon. We develop detectors to localize cold air pools in both time and space, and carry out simulation studies to assess their performance under different microclimatic and sensor-performance conditions.
![Nonlinear dashboard](https://github.com/satpreetsingh/osu-cap/raw/master/animations/gpInflectionLapseAnimation_2011-12-12.fullday.gif)

* [Hydro-NEXRAD-2: real-time access to customized radar-rainfall for hydrologic applications](https://iwaponline.com/jh/article/15/2/580/3447/Hydro-NEXRAD-2-real-time-access-to-customized) Journal of Hydroinformatics (2013)

### Industry
* List of patents applied and granted can be found on [Google Scholar](https://scholar.google.com/citations?user=S6wyhngAAAAJ&hl=en). 