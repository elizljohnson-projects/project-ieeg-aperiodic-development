# project-ieeg-aperiodic-development
The development of aperiodic neural activity in the human brain

**CODE AND DATA COMING SOON**

Aperiodic activity reflects neural noise, with flatter slopes indexing increased noise and excitability. Using direct brain recordings in a large sample of neurosurgical patients aged 5-54 years (i.e., intracranial EEG/iEEG), we discovered that aperiodic slopes in both association and sensorimotor cortices flatten with age into young adulthood. This finding challenges models of early sensorimotor development based on brain structure. In an association region called the prefrontal cortex, attentional state modulates age effects, and age effects explain age-related improvements in memory. Findings establish how aperiodic activity develops in localized brain regions and illuminate the development of prefrontal control during adolescence in the development of attention and memory. Press release by [Medical Xpress](https://medicalxpress.com/news/2025-07-brain-neural-noise-childhood-adulthood.html).

These scripts produce the results reported in:

Cross, ZR, Gray, SM, Dede, AJO, Rivera, YM, Yin, Q, Vahidi, P, Rau, EMB, Cyr, C, Holubecki, AM, Asano, E, Lin, JJ, Kim McManus, O, Sattar, S, Saez, I, Girgis, F, King-Stephens, D, Weber, PB, Laxer, KD, Schuele, SU, Rosenow, JM, Wu, JY, Lam, SK, Raskin, JS, Chang, EF, Shaikhouni, A, Brunner, P, Roland, JL, Braga, RM, Knight, RT, Ofen, N, Johnson, EL. The development of aperiodic neural activity in the human brain. _Nature Human Behaviour_ (2025). [DOI](https://doi.org/10.1038/s41562-025-02270-x)

Project data are available on OSF. The iEEG and MRI data were prepared for analysis using the [pipeline for iEEG data curation](https://github.com/elizljohnson-projects/pipeline-ieeg-data-curation.git). Project data include the processed aperiodic slope, gray matter volume, memory task performance, and demographic data.

Publications or other papers using these scripts and/or data should cite the publication above.

Software:
- Python 3.10.6
- Spyder 6.0.1
- R 4.2.3 "Shortstop Beagle"

Notes:
- Project data contain the aperiodic slopes generated using the Python scripts (mem_block_irasa, mem_trial_irasa, rest_irasa).
- Run the R scripts (slope_models, memory_models, gmv_models) to reproduce the published results.
