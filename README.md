# Exploration of Mental health survey Dataset

There is an increase in cases of mental illness on a global scale. Mental health problems are slowly becoming one of the top contributors for disease and disability across the world. Cases of mental illness can be found across developing as well as developed nations. They are present among the across different age groups, social strata as well as gender. Tech companies are rapidly growing in number and size and this means there is more pressure on it's workers to perform. This pressure could have negative implications on a few individuals and before they realize could lead to mental illness.

In this analysis I look at mental health survey data of workers across the globe to determine if the tech companies are doing enough to ensure mental wellbeing of their workers. This includes a positive working environment, right tools to cope with stress and awareness of mental illness and it's symptoms.

## Dataset

The dataset is obtained from a survey by [OSMI](https://osmihelp.org/)(Open Source Mental Illness). This survey was conducted in 2016 and had 1433 people responding to 63 questions. I was able to download this data from [Michael Rosenberg's](https://github.com/PLBMR) repository, as I could not find a way to encrypt the API key I obtained from data world, which also has the dataset. In the future I will be using the API provided by this site to download the data. Codebook containing variable descriptions can be found [here](https://github.com/abimur-123/Mentalhealth_project/blob/master/docs/Codebook.csv).

## Hypothesis

My hypothesis for this analysis is -
- **Null hypothesis**: Tech companies are well equipped to handle mental illness among their employees.
- **Alternate hypothesis**: Tech companies are not well equipped to handle mental illness among their employees.

## Why this analysis?

There is a boom in the number of startups in the tech industry, as well as growth of the existing tech giants. They are looking to outdo each other and hire workers who can get them to the top. This sometimes comes at a cost of the mental health of it's employees. As someone who is aspiring to work for a tech company I want to analyze the response of these companies to mental illness.

## Visualizing the dataset

There are multiple questions regarding company policy towards mental illness which are simply have Yes/No/Maybe answers. This can be visualized by the use of a bar plot. Also looking at the relation between family history of mental illness might help determine the role of tech companies in mental health. Future implementation could include sentiment analysis on the comments of the employee and geographic aspect to this.
