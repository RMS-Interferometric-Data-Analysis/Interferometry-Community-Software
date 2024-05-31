# Radio-Millimeter-Submillimeter (RMS) Interferometry-Community-Software
Curated list of interferometric software, methods and techniques

*This list was developed during the 2024 Spatio-spectral Modeling for Interferometric Data Workshop (go.nrao.edu/ssmid)*

### Visibility Handling
- [CASA](https://casadocs.readthedocs.io/)
- [casangi](https://github.com/casangi)
- [pyuvdata](https://pyuvdata.readthedocs.io/en/latest/index.html)
- [casa-formats-io](https://github.com/radio-astro-tools/casa-formats-io)


### Imaging
- [CASA](https://casadocs.readthedocs.io/) - includes [several algorithms in tclean](https://casadocs.readthedocs.io/en/stable/notebooks/synthesis_imaging.html#Other-Algorithms) (Max. Entropy; Adaptive Scale Pixel) 
- [casangi](https://github.com/casangi)
- [MPoL](https://mpol-dev.github.io/MPoL/)
- [MrBeam](https://github.com/hmuellergoe/mrbeam)
- [LibRA](https://github.com/ARDG-NRAO/LibRA)
- [wsclean](https://wsclean.readthedocs.io/en/latest/index.html)
- [IMAGER](https://imager.oasu.u-bordeaux.fr)
- [GILDAS-MAPPING](https://iram.fr/IRAMFR/GILDAS/) - documentation is out of date
- [IRIS (Bayesian Imaging with Score-Based Priors)] (https://github.com/EnceladeCandy/bayesian-imaging-radio)

### Analysis
- [radio-astro-tools](https://radio-astro-tools.github.io) -- spectral-cube, radio-beam, pvextractor, casa-formats-io
- [bettermoments](https://bettermoments.readthedocs.io/en/latest/) -- moment map making, including improved line center methods
- [eddy](https://github.com/richteague/eddy) -- rotation map fitting (protoplanetary disks)
- [gofish](https://github.com/richteague/gofish) --Stack line emission leveraging known structure of a system (protoplanetary disks)
- [velocity_tools](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software) -calculation of Keplerian rotation velocity map -deprojection of relative coordinates for a given inclination and rotation angles and an arbitrary center -calculation of velocity gradient, assuming solid velocity rotation
- [disksurf](https://github.com/richteague/disksurf) - Measure the molecular emission surface of protoplanetary disks
- [FERIA](https://github.com/YokoOya/FERIA) - Flat Envelope model with Rotation and Infall under Angular momentum conservation
- [keplerian_mask](https://github.com/richteague/keplerian_mask) - Make a Keplerian mask for CLEANing with CASA.
- [KeplerFit](https://github.com/felixbosco/KeplerFit) - A small piece of code to fit a Keplerian velocity distribution model to position-velocity data. *Developer is no longer working in astronomy 

  
## Methods, Techniques, and Tutorials

- [python packaging guide](https://packaging-guide.openastronomy.org/en/latest/) -- guide for making Python packages
- [radio-astro-tools tutorials](https://radio-astro-tools.github.io/tutorials/) -- tutorials on using spectral-cube, fitting with spectral-cube, parallelization with dask, creating position-velocity diagrams, signal masking and moment map creation, cube reprojection
- [Visread: Examining DSHARP AS 209 Weights and Exporting Visibilities](https://mpol-dev.github.io/visread/tutorials/rescale_AS209_weights.html) -- uses CASA tools to examine the visibilities, visibility residuals, and weights of a real multi-configuration dataset from the DSHARP survey.
- [auto_selfcal](https://github.com/jjtobin/auto_selfcal) -- automated continuum self-calibration for ALMA and VLA data
- [GALARIO](https://mtazzari.github.io/galario/) - uses GPUs to speed up the computation of the synthetic visibilities given a model image (or an axisymmetric brightness profile) and their comparison to the observations. *Developer is no longer working in astronomy 

## Visualization

- [CARTA](https://cartavis.org/) - Cube Analysis and Rendering Tool for Astronomy: a next-generation image visualization and analysis tool designed for ALMA, VLA, and SKA pathfinders.


# Contributing to this list

- [git resources via astropy](https://docs.astropy.org/en/latest/development/workflow/development_workflow.html#new-to-git)
- [Pull request workflow overview](https://blog.mergify.com/understanding-the-github-pull-request-workflow/)

  1. Make your own fork of this repository: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/1f56e24e-f112-4dd7-9aa0-b449b03c7025)
  2. Add new entries to the list, either on your own machine (make a local clone), or directly on github by pressing the pencil on the upper-right of the README file: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/7bcf4785-2d26-42d3-ae38-9a56a80c3e76)
  3. Commit your new entries to your forked repository: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/d75b04a0-4729-474c-832a-67f8c2a788f2)
  4. Create a new pull request (PR) from your fork to the main branch: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/93c17ecd-17fe-4b39-97a2-46cbeb1caf07)
  5. After the PR is merged into the main repository, update your forked repository before adding new entries. Use the "Sync fork" button here: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/d8392c4f-5ece-4a74-858b-6a2d7bbc8805)







