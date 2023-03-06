# case-basedosdados
Dataviz case using basedosdados, bigquery and geopandas.

## Investigating a possible aspect of the relationship between nature and mental health
I have always found being in contact with nature to be beneficial to my wellbeing, and I began to wonder if there might be a correlation between the presence of nature and overall wellbeing. To explore this idea, I decided to use forest area as a proxy for nature presence, and suicide rates as a potential negative proxy for wellbeing. While suicide rates are a poor measure of overall wellbeing due to their low resolution, I believe that this approach may help shed some light on the relationship between nature and mental health. 

- Making this question more exact: 
  - [Is there a correlation between the extent of forested land in an area and the incidence of suicide?](notebooks/1_case_suicide_forest.ipynb) Well, apperently not (yey science!). 

  - 🇧🇷 (PT-BR): [Existe alguma relação entre área de mata e incidência de suicídio nos municípios brasileiros?](notebooks/br_municipios_suicidio_floresta_20220824.ipynb) (não tem).

### Project Organization

    ├── LICENSE
    ├── README.md                  <- The top-level README for developers using this project (also know as this file!)
    ├── data
    │   ├── input                  <- Data for analysis
    │   └── output                 <- Products of the analysis
    ├── notebooks                  <- Jupyter notebooks
    │   └── drafts                 <- Draft jupyter notebooks
    └── requirements.txt           <- Packages used in the code

### Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

#### Prerequisites

You need to have the packages on `requirements.txt` installed. To do that, open the terminal and run:

```
pip install -U -r requirements.txt
```
### Authors

* **Daniel Brito** - *Code maker* - [@dbs-97](https://github.com/dbs-97)

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

### Acknowledgments
* This README was adapted from [*A template to make good README.md*](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* The structure of this repository was adapted from [*Fast Project Templates*](https://github.com/JoaoCarabetta/project-templates)

