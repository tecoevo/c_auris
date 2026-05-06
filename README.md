# *Candidozyma auris* (*Candida auris*) as a Harbinger of Novel Fungal Diseases
This repository contains the data and code used to produce the figures in the manuscript:

> Schuh CE, Gokhale CS. *Candidozyma auris* (*Candida auris*) as a harbinger of novel fungal diseases. (submitted).

The code is written in [Wolfram Language](https://www.wolfram.com/language/) (Mathematica).

---

## Repository Structure

```
c_auris/
├── Figure1/        # Code and assets for Figure 1
├── Figure2/        # Code and data for Figure 2
├── LICENSE         # MIT License
└── README.md
```

### Figure 1

A conceptual diagram summarising the hypothesised environmental influences that shaped *C. auris* into the pathogen observed today. The figure illustrates three nested levels of causation: pressures acting in the natural habitat (global environmental change, microbial competition, agricultural antifungal use), the pre-adaptive traits these pressures selected for (evolvability, stress tolerance, antimicrobial resistance, hospital persistence, opportunistic pathogenicity), and the resulting clinical phenotype of an unprecedented nosocomial pathogen.

### Figure 2

A two-panel figure combining:

- **Top panel:** Global land surface air temperature anomalies relative to the 1961–1990 reference period, derived from the CRUTEM5 dataset (Osborn et al. 2021, *Journal of Geophysical Research: Atmospheres*; [doi:10.1029/2019JD032352](https://doi.org/10.1029/2019JD032352)).
- **Bottom panel:** Earliest known *C. auris* isolate per country, plotted by year of sample collection (not year of discovery), colour-coded by continent. Data include both retroactively identified historic isolates and newly reported clinical cases. The underlying case data were compiled with reference to Jones et al. 2024 (*Journal of Medical Microbiology*; [doi:10.1099/jmm.0.001820](https://doi.org/10.1099/jmm.0.001820)).

---

## Requirements

- [Wolfram Mathematica](https://www.wolfram.com/mathematica/) (version 13 or later recommended), **or**
- [Wolfram Engine](https://www.wolfram.com/engine/) (free for developers) with the Wolfram Language kernel

No additional packages beyond the standard Mathematica installation are required.

---

## Usage

Open the notebook (`.nb`) inside `Figure1/` or `Figure2/` in Mathematica and evaluate all cells. Figures are exported as PDF at their intended publication size.

For Figure 2, the temperature anomaly data file should be placed in the `Figure2/` directory before running the notebook; see the comments inside the notebook for the expected filename and format.

---

## Data Availability

All data underlying Figure 2 are included in this repository. The CRUTEM5 temperature anomaly data are publicly available from the [Met Office Hadley Centre](https://www.metoffice.gov.uk/hadobs/crutem5/). The *C. auris* emergence dataset was compiled from primary literature; sources are cited in the manuscript and noted in the folder.

---

## Citation

If you use the data or code from this repository, please cite the manuscript:

```
Coming soon %% (to be edited)
```

---

## Authors

- **Carla E. Schuh** — Chair for Computational and Theoretical Biology, University of Würzburg
- **Chaitanya S. Gokhale** — Chair for Computational and Theoretical Biology, University of Würzburg; Joint Institute for Individualisation in a Changing Environment (JICE), Universities of Münster and Bielefeld

Correspondence: [chaitanya.gokhale@uni-wuerzburg.de](mailto:chaitanya.gokhale@uni-wuerzburg.de)

Group website: [https://tecoevo.github.io](https://tecoevo.github.io)

---

## License

This repository is released under the [MIT License](LICENSE).
