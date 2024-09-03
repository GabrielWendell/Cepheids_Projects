# Cepheids Research Projects 🌌🔭
## Overview
Welcome to the Cepheid Research Projects Repository, a comprehensive collection of ongoing projects dedicated to the development of research projects in Astrophysics involving Cepheid (and possibly RR Lyrae) variable stars.

### Motivation
Cepheids and RR Lyrae are pulsating stars whose pulsation period is strongly correlated with their mean absolute magnitude. Traditionally, these stars are part of the "distance scale", being crucial to calibrate type Ia supernovae and, therefore, to derive the expansion rate of the universe. The calibration procedure requires that the period-luminosity relation be universal, i.e., valid in all galaxies.

This repository is organized into individual projects, each exploring a unique aspect of Cepheid star research. Below, you will find a brief description of each project along with links to their respective folders for more detailed information.

---

## Projects
### 1. Hierarchical Models Applied to the $(P-L)$ Relationship
This project aims to explore the universality of the Period-Luminosity $(P-L)$ relationship across different galaxies using hierarchical models. By employing the Monte Carlo Markov Chain (MCMC) method with the Metropolis-Hastings (MH) algorithm, we analyze the $(P-L)$ relationship parameters in various galactic environments. The goal is to determine whether these parameters remain consistent and potentially universal, thus providing insights into the broader applicability of the $(P-L)$ relationship in cosmic distance measurements.

#### References
> [Riess et al. 2011](https://ui.adsabs.harvard.edu/abs/2011ApJ...730..119R/abstract)

You can check project updates here : [Log 1](https://github.com/GabrielWendell/Cepheids_Projects/blob/main/Project_1/README.md)


### 2. Neural Networks to Applied to Cepheids Fundamental Parameters
In this project, we develop an Artificial Neural Network (ANN) designed to predict the fundamental parameters of Cepheid stars based on their pulsation periods and light curve structures. The ANN is trained using a combination of theoretical pulsation models and observational data. The objective is to enhance the accuracy of stellar parameter predictions by leveraging the strengths of both theoretical models and empirical data.

#### References
> [Bellinger et al. 2020](https://academic.oup.com/mnras/article/491/4/4752/5645255)

You can check project updates here : [Log 2](https://github.com/GabrielWendell/Cepheids_Projects/blob/main/Project_2/log_project2.md)

---

## Installation
First you need to check if you have git software installed on your machine. You can check by typing the following in your terminal:
```terminal
git --version
```

If no version appears, then you will need to download it. Depending on your operating system, you can install it as follows:

I. **Mac OSX**
- Install the package from [https://git-scm.com/download/mac](https://git-scm.com/download/mac).

II. **Linux** \
Depending on your distribution:

- Debian and Ubuntu-based distros:
```terminal
sudo apt-get install git
```
- Red-Hat-based distros:
```terminal
sudo yum install git
```

Once done, from a new terminal create a directory dedicated for this tool with the name `Cepheids_Projects`, and from it, clone this github files and intall the necessary components:
```
git clone https://github.com/GabrielWendell/Cepheids_Projects/Cepheids_Projects.git
cd Cepheids_Projects
pip install -r requirements.txt
```
This will download the code and instructions.


### Repository Structure
```bash
├── Project_1/                      # Folder for Project 1
│   ├── data/                       # Data files related to Project 1
│   ├── notebooks/                  # Jupyter Notebooks for Project 1
│   ├── src/                        # Python scripts for Project 1
│   ├── Plots/                      # Plots related to Project 1
│   ├── logs/                       # Logs from the analysis
│   ├── README.md                   # Detailed README for Project 1
├── Project_2/                     # Folder for Project 2
│   ├── data/                      # Data files related to Project 2
│   ├── notebooks/                 # Jupyter Notebooks for Project 2
│   ├── Plots/                     # Plots related to Project 2
│   ├── src/                       # Python scripts for Project 2
│   ├── logs/                      # Logs from the analysis
│   ├── README.md                  # Detailed README for Project 2
└── README.md                      # General README (this file)
```

### Contributing
We welcome contributions from the academic and scientific communities. If you are interested in collaborating or have any suggestions for improving the projects, please refer to the individual project folders for specific guidelines or reach out via the contact information provided below.

### License
This repository is distributed under the [GNU v.3.0 License](https://github.com/GabrielWendell/Cepheids_Projects/blob/main/LICENSE). Please refer to the license file for more information.

### Contact
For any inquiries related to this repository or ongoing research, please contact:
- **Project Members**
> - [Gabriel Wendell Celestino Rocha](http://lattes.cnpq.br/0049111339899544)
> - [Leonardo Almeida de Andrade](http://lattes.cnpq.br/7812463045514059)
- **GitHub :octocat:**
> - [GabrielWendell](https://github.com/GabrielWendell)
> - [TitanUFRN](https://github.com/titanufrn)

---

### Have fun 😄
