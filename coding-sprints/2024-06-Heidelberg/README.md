# Gammapy Coding Sprint, May 2024

* Start: Monday, June 10th, 2024 at 2 pm
* End: Friday, June 14th, 2024 at noon
* Location: MPIK (Heidelberg, Germany)
* Contacts: [QRemy](https://github.com/QRemy), [registerrier](https://https://github.com/github.com/registerrier)

This meeting is a "coding sprint" for people that **want to work on the development** of Gammapy
(http://gammapy.org/). You're very welcome if you're new to coding or haven't contributed to
Gammapy yet. But note that this is **not** a workshop on how to use Gammapy.

Ideally all participants can dedicate most of their time to work on Gammapy during the week and make sure they are available for spontaneous discussions on Slack and remote meetings via Zoom.

The usual Zoom room of the dev calls will be open the full week.
https://u-paris.zoom.us/j/83737925932?pwd=TTJnVkJQRGtTSEppODFjMFlVNkV0QT09

Github project for the coding sprint : https://github.com/orgs/gammapy/projects/15/views/1

## Local Logistics

## Group Photo


![coding-sprin-group-picture](https://github.com/gammapy/gammapy-meetings/assets/3715928/9a503c9f-aeb5-466b-8cc0-d67ec039603b)


## Agenda


### Monday
##### Afternoon session (2 pm): Kick-off
- Introduction - Objectives of the week (Régis) [slides](slides/coding_sprint_intro.pdf)
- Gammapy usage in SWGO (Laura) [slides](slides/gammapy-swgo-coding-sprint.pdf)
- Thoughts / ideas on Jax for Gammapy (Axel) [thoughts](slides/gammapy-jax.pdf)
- Using Gammapy with e-Rosita data? (Katharina)
- Pulsar analysis tools - update (Maxime) [slides](slides/pulsar_status.pdf)

### Tuesday

- LST-1 data access update (Daniel)
- Time variability update (Claudio)[slides](slides/Variability_Gammapy_coding_sprint.pdf)

- 11:00 am : Discussion on events types with Juan Bernette and Tarek Hasan
- 2:00 pm : Co-working / hacking on Jax for Gammapy
  - build a 1D fit from scratch with JAX [Notebook](notes/jax-gammapy-from-scratch.ipynb) (Axel, Max, Fabio)
  - Get NPred as JAX array [PR #5302](https://github.com/gammapy/gammapy/pull/5302) (Atreyee, Claudio, Alessandro)
  - Trying to adapt the Map framework to JAX arrays [PR #5318](https://github.com/gammapy/gammapy/pull/5318) and [notebook](notes/map_with_jax.ipynb) (Régis, Kirsty) 

-
### Wednesday

- 10:30 am : Co-working on I/O for DL3 and CTAO observations
- 2:00 pm : Remaining issues with covariance handling (Atreyee)
  - covariance setter necessary on `CompoundSpectralModel` https://github.com/gammapy/gammapy/issues/5218#issuecomment-2163275732
  - Access only `FitResult.models`. Expose this consistently in the tutorials (https://github.com/gammapy/gammapy/issues/5306)
  - An individual `Parameter` object is handled correctly between multiple datasets, that should be passed to `fit.stat_contour` rather than accessing it through `datasets.parameters`. Clarify in the documentation (https://github.com/gammapy/gammapy/issues/5291)
- 3:00 pm : Improve performance of PSFkernel computations
  - energy dependent kernel max width and upsampling factor (Quentin)
  - allows MapEvaluator to accept a PSFkernel and precompute it on the dataset (Quentin)
  - use making instead of slicing  when we energy range to compute the flux points in order to avoid reset the models/psf convolution cache

  
### Thursday
- 10 am : A possible approach for DL3 IO classes. See draft PR [#5313](https://github.com/gammapy/gammapy/pull/5313)

- 2:00 pm : Issues and missing features for joint analyses (Quentin)
  - https://github.com/gammapy/gammapy/discussions/5307
- 3:00 pm : Fermi-LAT analysis - issues etc (Fabio Acero)

### Friday

- 10:30 : Quick look at the slides for CRIS-MAC (Claudio)
- 11:00 : short wrap-up
  - a prototype for CTAO-like observation handling
    - see the [repo](https://github.com/gammapy/ctao_data_model/)
    - An example [notebook](https://github.com/gammapy/ctao_data_model/blob/main/data_reduction_4D.ipynb)
   
- 2:00 pm: final discussion
  
## Participants

### On-site

1. Quentin Remy, MPIK, Heidelberg, Germany ([QRemy](https://github.com/QRemy))
2. Régis Terrier, APC Paris, France ([registerrier](https://github.com/registerrier))
3. Kirsty Feijen, APC Paris, France ([Astro-Kirsty](https://github.com/Astro-Kirsty))
4. Claudio Galelli, LUTh Meudon, France ([cgalelli](https://github.com/cgalelli))
5. Bruno Khélifi, APC Paris, France ([bkhelifi](https://github.com/bkhelifi))
6. Atreyee Sinha, UCM/IPARCOS Madrid, Spain ([AtreyeeS](https://github.com/AtreyeeS))
7. Georg Schwefer, MPIK, Heidelberg, Germany ([gschwefer](https://github.com/gschwefer))
8. Laura Olivera Nieto, MPIK, Heidelberg, Germany ([LauraOlivera](https://github.com/LauraOlivera))
9. Alessandro Montanari, LSW, Heidelberg, Germany ([A_Montanari](https://github.com/alessandromontanari))

X. Please add your name and GitHub name here...

### Online

1. Fabio Pintore, INAF/IASF Palermo, Italy ([fabiopintore](https://github.com/fabiopintore))
2. Daniel Morcuende, IAA-CSIC Granada, Spain ([morcuended](https://github.com/morcuended))
3. Tim Unbehaun, FAU Erlangen, Germany ([tunbehaun273](https://github.com/tunbehaun273))
4. Katharina Egg, FAU Erlangen, Germany ([k-egg](https://github.com/k-egg))
5. Maxime Regeard, APC, Paris, France ([MRegeard](https://github.com/MRegeard))
6. Axel Donath, CfA, Cambrige MA, US ([adonath](https://github.com/adonath))
7. Matthias Fuessling, CTAO ([MatthiasFuessling](https://github.com/MatthiasFuessling))
