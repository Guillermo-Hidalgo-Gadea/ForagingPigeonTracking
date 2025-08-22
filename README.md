# Continuous foraging behavior shapes patch-leaving decisions in pigeons: A 3D tracking study

**Authors:** Guillermo Hidalgo-Gadea, Onur Güntürkün, Mary Flaim, Patrick Anselme

**Status:** Submitting to *Behavior Research Methods*, link: tbd

## Abstract
Optimal foraging behavior is a key component of successful adaptations to natural environments. Understanding how animals decide to stay near food or to leave it for another food patch gives us insights into the underlying cognitive mechanisms that govern adaptive behaviors. 3D pose tracking was used to determine how pigeons exploit a 4 square meter arena with two separate platforms (i.e. food patches) whose absolute and relative elevations were manipulated. Detailed kinematic features of foraging and traveling behaviors were quantified using automated video tracking, without a need for manual coding. Our computational approach captured continuous, high-dimensional movement patterns and enabled precise quantification of travel costs between patches. Combined with mixed-effects survival analysis, our detailed behavioral tracking provided unprecedented insight into the moment-by-moment dynamics of patch-leaving decisions of pigeons. As expected from behavior optimization models, our results showed a preference to visit a ground food platform first, and longer latencies to leave an elevated platform. Foraging activity significantly decreased throughout a session, with shorter visits, less pecks per visit, and a decrease in inter-peck variability. However, a mixed-effects Cox regression modeled pigeons' patch-leaving probability, demonstrating that current and cumulative foraging parameters between patches significantly enhanced the model's predictive power beyond patch accessibility (i.e., beyond travel costs). This suggests that pigeons integrate both current environmental cues and their individual foraging history when making patch-leaving decisions. Our findings are discussed in relation to the marginal value theorem and optimal foraging theory.

## Repository contents
- `analysis/` – R script and data for reproducing analyses in the paper  
- `tracking/` – Python scripts for pose estimation and triangulation  
- `processing/` – Python scripts for behavioral feature extraction  
- `docs/` – Documentation and usage instructions  

## Data availability
Raw video data (~9 TB) is available upon request from our university server [ReSeeD](https://researchdata.ruhr-uni-bochum.de/en/reseed/).

## Contact

For questions, please open an issue or contact <mailto:Guillermo.HidalgoGadea@rub.de>.
