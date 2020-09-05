# CoronaVis: A Real-time COVID-19 Tweets Analyzer

The goal of ConronaVis is to use tweets as the information shared by the people to visualize topic modeling, study subjectivity and to model the human emotions during the COVID-19 pandemic. The main objective is to explore the psychology and behavior of the societies at large which can assist in managing the economic and social crisis during the ongoing pandemic as well as the after-effects of it. In this paper, we describe the CoronaVis Twitter dataset (focused on United States) that we have been collecting from early March 2020. We would like to share this data with the hope that it will enable the community to find out more useful insights and create different applications and models to fight with COVID-19 pandemic and the future pandemics as well. 
The paper is available at [arXiv](https://arxiv.org/pdf/2004.13932.pdf)

## Data Description
We are continuously collecting the data since March 5, 2020 and will keep fetching the tweets using [Twitter Streaming API](https://developer.twitter.com/en/docs/tutorials/consuming-streaming-data). We have collected around 700GB of raw data until April 24, 2020 and saved this data as JSON files. However, we dynamically process this data in real-time for the [CoronaVis](https://mykabir.github.io/coronavis/) application. We processed several features from the tweets such as (Tweet ID, Tweet Text, User Location if available, User Type), etc. We will keep collecting the data and update this data repository once in every week. 

This repository contains two different folders. One is the "data" folder containing the tweeter data and another is a "src" folder which contains some basic code presenting the way to read the data and some basic data analytics. The "data" folder contains the data in CSV file format for each day from 5th March 2020 to till date and named by the particular date with the format YEAR-MONTH-DATE. If you have any suggestions or concern, please send an email at mkabir@mst.edu or madrias@mst.edu.

### Data attributes
#### tweet_id 
Unique ID of a tweet.

#### created_at 
Creation time of a tweet.

#### loc
State level user location.

#### text
Processed tweet text. All the text are in small letters, non-English characters and few stop words are removed. 

#### user_id
Pseudo user id. The exact user name is transformed to a anonymous id to preserve the privacy of the user. 

#### verified
Denotes whether the tweet post is verified or not (1 or 0). 
0 --> Not Verified.
1 --> Verified.


### Use Policy
This dataset is released in compliance with [Twitter’s Developer Terms & Conditions](https://developer.twitter.com/en/developer-terms/agreement-and-policy). The data repository will be continuously updated every week. The data repository, containing codes, and [CoronaVis](https://mykabir.github.io/coronavis), 2020 W2C lab, Missouri University of Science and Technology, all rights reserved, can be used for educational, academic, and government research purposes with proper citation (Please cite [this paper](https://arxiv.org/abs/2004.13932)). Any commercial use of any materials is strictly prohibited. Taking and sharing a screenshot is allowed with appropriate citation.  

@misc{kabir2020coronavis,
    title={CoronaVis: A Real-time COVID-19 Tweets Analyzer},
    author={Md. Yasin Kabir and Sanjay Madria},
    year={2020},
    eprint={2004.13932},
    archivePrefix={arXiv},
    primaryClass={cs.SI}
}