## Update V3.0: 
1. Tweet IDs now avilable from Match 5th 2020 to December 31st 2020.
2. In the next week we will update state wise tweet IDs with masked user IDs. 


# CoronaVis: A Real-time COVID-19 Tweets Analyzer

The goal of ConronaVis is to use tweets as the information shared by the people to visualize topic modeling, study subjectivity and to model the human emotions during the COVID-19 pandemic. The main objective is to explore the psychology and behavior of the societies at large which can assist in managing the economic and social crisis during the ongoing pandemic as well as the after-effects of it. In this paper, we describe the CoronaVis Twitter dataset (focused on United States) that we have been collecting from early March 2020. We would like to share this data (Tweets ID) with the hope that it will enable the community to find out more useful insights and create different applications and models to fight with COVID-19 pandemic and the future pandemics as well. 
The paper is available at [arXiv](https://arxiv.org/pdf/2004.13932.pdf)

## Data Description
We are continuously collecting the data since March 5, 2020 and will keep fetching the tweets using [Twitter Streaming API](https://developer.twitter.com/en/docs/tutorials/consuming-streaming-data). We have collected around 700GB of raw data until April 24, 2020 and saved this data as JSON files. However, we dynamically process this data in real-time for the [CoronaVis](https://mykabir.github.io/coronavis/) application. 

This repository contains two different folders. One is the "data" folder containing the tweeter data and another is a "src" folder which contains some basic code presenting the way to read the data and some basic data analytics. The "data" folder contains the data (Tweets ID) in CSV file format for each day from 5th March 2020 to till date and named by the particular date with the format YEAR-MONTH-DATE. If you have any suggestions or concern, please send an email at mkabir@mst.edu or madrias@mst.edu.



### Use Policy
This dataset is released in compliance with [Twitter’s Developer Terms & Conditions](https://developer.twitter.com/en/developer-terms/agreement-and-policy). The data repository will be continuously updated every week. The data repository, containing codes, and [CoronaVis](https://mykabir.github.io/coronavis), 2020 W2C lab, Missouri University of Science and Technology, all rights reserved, can be used for educational, academic, and government research purposes with proper citation (Please cite [this paper](https://www.sciencedirect.com/science/article/abs/pii/S2468696421000197)). Any commercial use of any materials is strictly prohibited. Taking and sharing a screenshot is allowed with appropriate citation.

@article{kabir2021emocov,
  title={EMOCOV: Machine learning for emotion detection, analysis and visualization using COVID-19 tweets},
  author={Kabir, Md Yasin and Madria, Sanjay},
  journal={Online Social Networks and Media},
  volume={23},
  pages={100135},
  year={2021},
  publisher={Elsevier}
}

### Related Articles

- [EMOCOV: Machine learning for emotion detection, analysis and visualization using COVID-19 tweets](https://www.sciencedirect.com/science/article/abs/pii/S2468696421000197)
- [CoronaVis: a real-time COVID-19 tweets data analyzer and data repository](https://arxiv.org/abs/2004.13932)
- 
