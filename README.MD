Please have a look at the Jupyter notebook on [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/github/ajdev-1/corona-press-analysis/blob/master/COVID-19%20GIT.ipynb) since it displays the dynamic LDA Viz component.

# Corona Press Analysis

# Motivation
The past has shown that the press uses exceptional situations,
to bypass our attention filter with emotionalized reports that tend to exaggerate. In the U.S. there has been an increased number of
reports on social consequences in about particular epidemics (swine flu, Zika virus, Ebola). Health aspects have been neglected.

Thus, press articles can give an impression about a pandemic that differs from the actual situation (e.g. growth rate). This
type of reporting could be repeated with COVID-19.
This raises the question of whether emotionality or specific themes of press coverage of COVID-19 correlate with the growth of the virus in a
country.

Within this project I examined whether there is a correlation between
emotionality, used topics of press articles and the growth rate of COVID-19 in a country. Here, countries were examined that had a significant
development of the growth rate (in March/ April 2020): Germany, USA, Spain, Italy,
Great Britain, and France.

# Data
Within this project, I used an open-source dataset from [IEEE DataPort](https://ieee-dataport.org/open-access/free-dataset-newsmessage-boardsblogs-about-coronavirus-4-month-data-52m-posts) that includes news/message and blog entry data. Here I have concentrated on English reports.

# Technology

# Result Examples

### Word clustering 
for one of the countries. This methodology (Latent Dirichlet Allocation in combination with the vizualization tool LDAViz) has been used to identify the different topics within the data corpus.
![image](https://user-images.githubusercontent.com/38671044/119042250-df36db00-b9b7-11eb-9c56-28c03d8542dc.png)

### Probability distribution
One of the probability charts for specific topics for one of the selected countries:
![image](https://user-images.githubusercontent.com/38671044/119042159-c4646680-b9b7-11eb-892e-97207e96df4c.png)

