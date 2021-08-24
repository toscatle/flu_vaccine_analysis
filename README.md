# Flu Vaccine Analysis for the Public Health Institute
Author: Tosca Le

<img src="images/vaccine stock photo.jpeg">


## Overview

This project explores the National 2009 H1N1 Flu Survey (NHFS), which was a phone survey that asked respondents if they received the H1N1 and seasonal flu vaccines, as well as additional questions about their socioeconomic, demographic background, and opinions on illness risks and vaccine effectiveness. 

The Public Health Institute would like to focus their efforts on outreach to communities that would benefit from more vaccine information/resources based on features identified to affect the probability of receiving the vaccine the most.
***

## Business Problem

The goal is to understand what drives the models and which features are important in the prediction of individuals who will get the seasonal flu vaccine or not. The Public Health Institute should be able to use this understanding to minimize the amount of people that could've benefited from vaccine outreach and see what factors might contribute the most to individuals choosing not to receive the vaccine. By knowing this, the Public Health Institute can focus their efforts on specific communities and aid in providing the necessary resources to increase vaccine rates and in return, better understand vaccine effectiveness.
***

## Data

The NHFS data subset includes a features and labels set. The features set contains the different survey questions while the labels set contains the target variables, which are whether the respondents received the vaccines. The dataset contains 26,707 entries. For this analysis, only the seasonal flu label will be used. In addition, specific H1N1 survey features will not be used.

***


## Methods

This project uses regression and classification models. After preparing and preprocessing the data, the dataset is split into train and test subsets for model validation. A pipeline is built out to iterate through the different models.

***


## Results

<!-- News, Documentaries, and Biography genres have higher rated movies. Although, one thing to keep in mind is that these genres don't have as many movies as other genres such as Comedy, Drama, and Thriller.

![graph1](./images/moviesPerGenre.png)

![graph2](./images/ratingsPerGenre.png)

The average runtime for movies is about 100 minutes. On the opposite ends of the range, movies that are less than 30 minutes and over 150 minutes have higher ratings. Again, another thing to consider are the genres and number of movies within each genre. Although there may be fewer movies in genres such as Documentary, there might be a greater likelihood for high reviews. The audience might be more atuned to these genres. Movies above the average 100 minutes, have higher ratings than movies that are shorter.

![graph3](./images/ratingByRuntime.png)

Horror, Mystery, and Thriller have the greatest average return on investment. On the other hand, Reality-TV, War, and Western movies had an overall loss.

![graph4](./images/roiPerGenre.png) -->

***


## Conclusions

<!-- This analysis leads to three recommendations for Microsoft to consider as they begin to develop films under their new movie studio:

* In terms of average rating, movies in News, Documentaries and Biography have higher ratings compared to others. While these genres may not currently have as many films as other genres, it is likely that overall ratings will be high for these genres, potentially bringing in continued viewership and support for Microsoft's movie studio.
* When considering the average runtime, movies longer than 120 minutes will have an overall higher rating than movies shorter than 100 minutes. Movies that are either very short or very long received higher ratings possibly due to the nature of these genres. Microsoft should consider these runtimes when producing specific genres.
* Microsoft can leverage movies in genres such as Horror, Mystery and Thriller to make a greater return on the initial production budget. Reality-TV, War and Western movies should be reconsidered when deciding budget since these genres had an overall loss. -->

***

### Next Steps

* The survey data included H1N1-specific questions as well as whether or not the respondent received the H1N1 vaccine. These are likely to be highly correlated with seasonal flu attitudes and outcomes, which can affect the interpretation of the models. It would be interesting to examine these relationships, especially in the context of how it may affect other vaccines.

* Since there was such a wide range of features, including the categorical features that were not omitted, it might be beneficial to simplify the analysis by examining specific subsets of features and exploring more details about the implications of certain features. In addition, a deeper look into the coded responses for the few categorical features would be useful.

* There are many parameters that could've been tuned or other models to explore. Our understanding of these additional iterations can help the business problem as well.

***

## For More Information

Please review my full analysis in my [Jupyter Notebook](./flu_vaccine_analysis.ipynb) or [presentation](./flu_vaccine_analysis_presentation.pdf).

For any additional questions, please contact me at **toscatle@gmail.com**.

***

## Repository Structure

```
├── images
├── .gitignore
├── LICENSE                          
├── README.md 
├── flu_vaccine_analysis.ipynb                                  
└── flu_vaccine_analysis_presentation.pdf                               
```
