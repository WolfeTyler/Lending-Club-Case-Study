# Lending Club Case Study
This project involves a comprehensive Exploratory Data Analysis (EDA) of the Lending Club public loan dataset, looking to uncover insights into how various loan features influence the likelihood of borrowers defaulting on their loans leading to the amount being charged off.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Lending Club is a peer-to-peer lending platform that connects borrowers with investors. The primary objective of this analysis is to identify patterns and factors that contribute to loan defaults, thereby assisting in mitigating credit risk. The dataset used encompasses numerous factors such as loan amounts, interest rates, employment information, credit history, etc. with more than 111 associated features included across 39k loan records.


## Conclusions
- **Grade and Sub-grade**: Lower grades (e.g., D, E, F, G) and their sub-grades were strongly associated with higher default rates. Borrowers in these categories typically face higher interest rates, increasing their risk of default. From the data we can see that customers with a A credit grade only have an ~5% charge-off rate vs. those with a F grade increase up to a ~30% risk.
[Loans Charged Off by Grade](https://github.com/WolfeTyler/Lending-Club-Case-Study/blob/main/LoansChargedOffbyGrade.png)

- **Revolving Credit Utilization**: Borrowers with higher revolving credit utilization (percentage of available credit used) were more likely to default. This indicates financial stress and over-leveraging. From the data we can see that customers with a 10% credit utilization only have an ~10% charge-off rate vs. those with 90% utilization increase up to a ~20% risk.
- **Annual Income**: Borrowers with a lower annual income (<$40,000) exhibited a higher likelihood of defaulting compared to higher income customers.


## Technologies Used
The analysis was conducted using the following technologies:

- Python
- Jupyter Notebook
- Matplotlib
- Pandas version 2.2.2
- NumPy version 1.26.4
- Seaborn version 0.13.2


## Contact
Created by [@WolfeTyler](https://github.com/WolfeTyler) - feel free to contact me!

