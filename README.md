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
- [ADD HERE]


### Analysis
- [radio-astro-tools](https://radio-astro-tools.github.io) -- spectral-cube, radio-beam, pvextractor, casa-formats-io
- [bettermoments](https://bettermoments.readthedocs.io/en/latest/)
- 

  
## Methods, Techniques, and Tutorials

- [radio-astro-tools tutorials](https://radio-astro-tools.github.io/tutorials/) -- tutorials on using spectral-cube, fitting with spectral-cube, parallelization with dask, creating position-velocity diagrams, signal masking and moment map creation, cube reprojection
- [Visread: Examining DSHARP AS 209 Weights and Exporting Visibilities](https://mpol-dev.github.io/visread/tutorials/rescale_AS209_weights.html) -- uses CASA tools to examine the visibilities, visibility residuals, and weights of a real multi-configuration dataset from the DSHARP survey.
- [auto_selfcal](https://github.com/jjtobin/auto_selfcal) -- automated continuum self-calibration for ALMA and VLA data
- [Introduction to version control in Git for scientists](https://laserkelvin.github.io/blog/2021/10/contributing-github/) -- a nice little blog post with the basics how-to for git. Explains basic git terms and how version control works - with visuals!

## Visualization

- 


# Contributing to this list

- [git resources via astropy](https://docs.astropy.org/en/latest/development/workflow/development_workflow.html#new-to-git)
- [Pull request workflow overview](https://blog.mergify.com/understanding-the-github-pull-request-workflow/)

  1. Make your own fork of this repository: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/1f56e24e-f112-4dd7-9aa0-b449b03c7025)
  2. Add new entries to the list, either on your own machine (make a local clone), or directly on github by pressing the pencil on the upper-right of the README file: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/7bcf4785-2d26-42d3-ae38-9a56a80c3e76)
  3. Commit your new entries to your forked repository: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/d75b04a0-4729-474c-832a-67f8c2a788f2)
  4. Create a new pull request (PR) from your fork to the main branch: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/93c17ecd-17fe-4b39-97a2-46cbeb1caf07)
  5. After the PR is merged into the main repository, update your forked repository before adding new entries. Use the "Sync fork" button here: ![image](https://github.com/RMS-Interferometric-Data-Analysis/Interferometry-Community-Software/assets/3255771/d8392c4f-5ece-4a74-858b-6a2d7bbc8805)







