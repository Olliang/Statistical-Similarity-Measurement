# Statistical Similarity Evaluation Metrics for Tabular data



## Introduction:

This github is triggered by a research project that I have been working on this spring for a healthcare company. Because of the industry itself, data privacy policy has hindered data from being shared and used efficiently for further analytics and innovation. The business goal of the project is to solve the conflict between data privacy and data sharing. In other words, *how can we generate synthetic data that is as similar and useful as original data for the intended use?* 

Apart from developing powerful synthetic data generating techniques using cutting-edge deep learning algorithms such as GAN (Generative adversarial network), one of important topics in this project is **designing  similarity evaluation metrics to evaluate whether the synthetic data generated is statistical and structurally similar as the original data**.

Measurement of similarity is a widely desired in real business, especially on tabular data. For example, how do we evaluate the similarity between the forecasting sales and  the actual sales in order to improve our forecasting model? Can we come up with a score that quantify the level of similarity for management to make better decisions? What if we also need to capture the similarity on the relationships across multiple variables?

If you are facing similar problems or are interested in similarity measurement on tabular data (even though the concept of yours might be slightly different from measuring the similarity of synthetic data), I hope these metrics I tailored for my project can benefit you to some degree.


## Main Files:

`Statistical Similarity Methodology.md` - Main file that documenting the methodology and result

`column-wise evaluation.ipynb`- Main notebook script that implement the column-wise evaluation

`table-wise evaluation.ipynb`- Main notebook script that implement the table-wise evaluation

`Clustering_LOS.ipynb`- Main notebook script that implement clustering metric for 'Length of Stay' use case

`Clustering_Mortality.ipynb`- Main notebook script that implement clustering metric for 'Mortality' use case

## Datasets Overview

![datasets](https://github.com/Olliang/Statistical-Similarity-Measurement/blob/master/images/DATASET.PNG)


## Reference:

https://blog.keras.io/building-autoencoders-in-keras.html

https://towardsdatascience.com/deep-inside-autoencoders-7e41f319999f



## Contact:

If there is anything to be corrected or you have any thoughts to share with me on this topic, please feel free to reach out! It's always pleasure to learn more.
>Email: olivia.liang032@gmail.com

