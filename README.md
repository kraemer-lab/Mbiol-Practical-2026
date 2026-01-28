# Mbiol-2026 Practical on Epidemiological surveillance and modelling as part of Year 2 Genomics and Host-microbe Interactions.

Practical I: Epidemiological surveillance and modelling(non-spatial) - handouts are available in this repository.

Dates: January 29th/30th, 14:00-17:00, Life and Mind Building, South Parks Road

In this first practical the student is expected to learn about epidemiological case count data and standard techniques to visualise and analyse them. The student will learn estimating the time-varying reproduction number (Rt) using the R-package ‘EpiEstim’. Further, the student is expected to reflect on the issues these data present and provide a perspective on how to improve disease surveillance in order to better estimate epidemiological parameters in the future. Students may also learn about the evolution of variant replacement and genetic viral diversity in the bonus question.

Practical II: Epidemiological surveillance and modelling (spatial) - handouts are available in this repository.

Dates: February 2nd/3rd, 14:00-17:00, Life and Mind Building, South Parks Road

Pathogens move between different geographical units because of movements of animals or humans or other hosts. Spatial patterns of infectious disease transmission arise from heterogeneity in the landscape in which transmission occurs. In large and dense cities for example transmission intensity tends to be higher compared to rural areas. Spatial dispersal in ecology and epidemiology is often approximated by an exponential (probability of dispersal at a distance follows  dispersal ∝ exp(-d/ɑ), where ɑ is the range, or Gaussian kernel (dispersal ∝ exp(-(d/ɑ)2).
 
For human infectious diseases the process of dispersal rarely follows a continuous spatial expansion but rather spread is better approximated by the spatial organisation of cities and towns. For example, emerging infectious diseases appear first in large urban agglomerations that are connected via air travel and then follow human movements from there to other larger cities or rural counties. The SARS-CoV-2 Omicron variant for example first spread in London where most travellers from abroad arrived.

In this practical we will learn about continuous spatial spread using spatial kernels before investigating the impact of human mobility on spatial dispersal of infectious diseases.

### File structure of this repository is as follows:
```
.
├── Data
│   ├── daily_import_proportions.csv
│   ├── daily_lineage_freqs.csv
│   └── nation_newCasesBySpecimenDate.csv
├── Figures
│   └── plant_with_rust.png
├── Questions
│   ├── Practical-1
│   │   ├── practical-1-bonus-question.Rmd
│   │   ├── practical-1-bonus-question.html
│   │   ├── practical-1-bonus-question.pdf
│   │   ├── practical-1-questions.Rmd
│   │   ├── practical-1-questions.html
│   │   └── practical-1-questions.pdf
│   └── Practical-2
│       ├── practical-2-questions.Rmd
│       ├── practical-2-questions.html
│       └── practical-2-questions.pdf
├── README.md
└── Slides
    ├── Practical-1-Slides.pptx
    └── Practical-2-Slides.pptx
```
