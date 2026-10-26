# FA511: Drug Formulation and Production A

Data science material for **FA511 Drug Formulation and Production A** (BSc Pharmacy, University of Southern Denmark). The material shows students how to analyse experimental data in R and write their lab reports in Quarto.

FA511 covers liquid and semi-solid formulations (solutions, suspensions, emulsions, ointments, creams and gels), solubilisation, excipients and small-scale manufacture of extemporaneous preparations. Course description: [FA511 at SDU](https://odin.sdu.dk/sitecore/index.php?a=fagbesk&id=210843&lang=en).

This repository holds the R and Quarto material only. The full course material, including the lab manual, exercise sheets and the course schedule, lives in itslearning. Solutions are not published here.

The guides are written in Danish.

## Data Science Learning Outcomes

The learning outcome from the official course description that this material supports. The student demonstrates the ability to:

- Perform data analysis and visualization in R together with writing reports (R, Quarto document).

## Structure

```
├── intro_r_quarto/                  Exercise class: acid/base functions in R and setting up a Quarto document
├── standard_curves/                 Exercise class: standard curves with linear regression
├── lab/
│   ├── exercise1_solubilisation/    Solubilisation of paracetamol, sulfadiazine and ibuprofen
│   └── exercise2_suspensions/       Sedimentation and redispersibility of sulfur suspensions
├── CITATION.cff
├── LICENSE                          CC BY 4.0 (teaching content)
└── LICENSE-code                     MIT (code)
```

Each folder is self-contained: the guide and the files it needs sit together, so students can download a single folder and work from it.

The reports for exercises 1 and 2 are written in Quarto and handed in as HTML with the code visible. Exercise 3 (semi-solid formulations) is presented as a poster and has no R material.

## Setup

You need:

- [R](https://cran.r-project.org/) (version 4.3 or newer)
- [RStudio](https://posit.co/download/rstudio-desktop/) (includes Quarto)

Install the R packages used in the course:

```r
install.packages(c("tidyverse", "here"))
```

## Versions

The `main` branch holds the material for the current year. When a course run ends, it is archived in a branch named after the year (for example `2025`).

## Citation and license

If you reuse or adapt the material, please cite it using [CITATION.cff](CITATION.cff) (GitHub shows a "Cite this repository" button).

Teaching content is licensed under [CC BY 4.0](LICENSE) and code under [MIT](LICENSE-code).

The material was written by Judith Kuntsche, Gabriela Diana Palkowska and Nadia Skarnager Andersen (University of Southern Denmark).

Part of the [CPDSE](https://github.com/CPDSE-EDUX) teaching material from the Center for Pharmaceutical Data Science Education.
