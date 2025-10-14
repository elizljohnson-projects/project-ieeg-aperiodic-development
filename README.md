## The development of aperiodic neural activity in the human brain

Aperiodic activity reflects neural noise, with flatter slopes indexing increased noise and excitability. Using direct brain recordings in a large sample of neurosurgical patients aged 5-54 years (i.e., intracranial EEG/iEEG), we discovered that aperiodic slopes in both association and sensorimotor cortices flatten with age into young adulthood. This finding challenges models of early sensorimotor development based on brain structure. In an association region called the prefrontal cortex, attentional state modulates age effects, and age effects explain age-related improvements in memory. Findings establish how aperiodic activity develops in localized brain regions and illuminate the development of prefrontal control during adolescence in the development of attention and memory. Press release by [Medical Xpress](https://medicalxpress.com/news/2025-07-brain-neural-noise-childhood-adulthood.html).

Our research aims to uncover mechanistic explanations of the neural basis of human behavior, that is, move from where to how. Our goals are multifaceted: (1) advance fundamental science by discovering new knowledge using rigorous, reproducible methods; and (2) advance translational applications in neurotechnology, precision medicine, and product development that are grounded in rigorous science. In this project, the first in a series from the preregistered study, [_Mapping human brain development in high definition using invasive electrophysiology_](https://doi.org/10.17605/OSF.IO/GSRU7), we showcase how approaching neuroscience as data science - with neurophysiological, neuroimaging, behavioral, and demographic datasets representing diverse data types, and analytics spanning signal processing and hierarchical modeling - can address outstanding questions about brain development. Understanding how the human brain develops is a prerequisite to understanding healthy and disordered behavior across the lifespan.

These scripts produce the results reported in:
- Cross, ZR, Gray, SM, Dede, AJO, Rivera, YM, Yin, Q, Vahidi, P, Rau, EMB, Cyr, C, Holubecki, AM, Asano, E, Lin, JJ, Kim McManus, O, Sattar, S, Saez, I, Girgis, F, King-Stephens, D, Weber, PB, Laxer, KD, Schuele, SU, Rosenow, JM, Wu, JY, Lam, SK, Raskin, JS, Chang, EF, Shaikhouni, A, Brunner, P, Roland, JL, Braga, RM, Knight, RT, Ofen, N, Johnson, EL. The development of aperiodic neural activity in the human brain. _Nature Human Behaviour_ (2025). [DOI](https://doi.org/10.1038/s41562-025-02270-x)

Project data are available on [OSF](https://osf.io/fx6ke/); download Preprocessed_data and volume_stats. The iEEG and MRI data were prepared for analysis using the [pipeline for iEEG data curation](https://github.com/elizljohnson-projects/pipeline-ieeg-data-curation.git). Project data include aperiodic slope, gray matter volume, memory task performance, and demographic data.

Publications or other papers using these scripts and/or data should cite the publication above.

### Run using Python and R:
Python:
- Software: Python 3.12.12
- Environment: Google Colab
- Package versions:
  - NumPy 2.0.2
  - Pandas 2.2.2
  - Matplotlib 3.10.0
  - MNE 1.10.2
  - YASA 0.6.5
- Notebook: aperiodic_irasa.ipynb  

R:
- Software: R 4.3.3
- Environment: Anaconda - [download](https://www.anaconda.com/download)
  - Setup using the Anaconda command line:
    - `conda create -n r-env r-base=4.3 python=3.11 -c conda-forge`
    - `conda activate r-env`
    - `conda install -c conda-forge jupyterlab r-irkernel`
    - `conda install -c conda-forge r-tidyverse r-rcolorbrewer r-broom r-lme4`
    - `jupyter lab`  
- Package versions:
  - tidyverse 2.0.0
  - RColorBrewer 1.1.3
  - broom 1.0.9
  - lme4 1.1.37
- Notebooks:
  - slope_models.ipynb
  - memory_models.ipynb
  - gmv_models.ipynb

Notes:
- Run IRASA on a sample dataset using `aperiodic_irasa`. The sample dataset is from the [working memory delayed match to sample experimental paradigm](https://github.com/elizljohnson-projects/paradigm-working-memory-dms.git).
- Run the modeling scripts to reproduce published results (`slope_models`, `memory_models`, and `gmv_models`).
- The original scripts used to generate and model project data are in [Zachariah_Cross/Aperiodic-development-iEEG](https://github.com/Zachariah-Cross/Aperiodic-development-iEEG.git).
