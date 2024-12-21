# Lending Club Case Study
This project involves a comprehensive Exploratory Data Analysis (EDA) of the Lending Club public loan dataset, looking to uncover insights into how various loan features influence the likelihood of borrowers defaulting on their loans leading to the amount being charged off.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Lending Club is a peer-to-peer lending platform that connects borrowers with investors. The primary objective of this analysis is to identify patterns and factors that contribute to loan defaults, thereby assisting in mitigating credit risk. The dataset used encompasses numerous factors such as loan amounts, interest rates, employment information, credit history, etc. with more than 111 associated features included across 39k loan records.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- **Grade and Sub-grade**: Lower grades (e.g., D, E, F, G) and their sub-grades were strongly associated with higher default rates. Borrowers in these categories typically face higher interest rates, increasing their risk of default. From the data we can see that customers with a A credit greade only have an ~5% charge-off rate vs. those with a F grade increase up to a ~30% risk.
- **Revolving Credit Utilization**: Borrowers with higher revolving credit utilization (percentage of available credit used) were more likely to default. This indicates financial stress and over-leveraging. From the data we can see that customers with a 10% credit utilization only have an ~10% charge-off rate vs. those with 90% utilization increase up to a ~20% risk.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
The analysis was conducted using the following technologies:

- Python
- Jupyter Notebook
- Matplotlib
- Pandas version 2.2.2
- NumPy version 1.26.4
- Seaborn version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@WolfeTyler](https://github.com/WolfeTyler) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->