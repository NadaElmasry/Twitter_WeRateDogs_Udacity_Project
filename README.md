# Twitter WeRateDogs Dataset Udacity Project

This project is part of Udacity Professional Data Analysis nanodegree as part of the Egyptian FWD initiative. 

The dataset used in wrangling, analysis, and visualization is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10 and numerators almost always greater than 10. 

### Included in this repo:
- wrangle_act: jupyter notebook containing all wrangling, analysis, and visualization performed on the dataset.

- wrangle_report: report containing the description and explanation of the data wrangling, analysis, and cleaning processes performed on the dataset.

- act_report: report containing description, explanation, and interpretation of the visualizitons performed on the clean dataset.

- twitter-archive-enhanced: the original WeRateDogs dataset provided by Udacity.

- twitter_archive_clean: the clean version of the twitter-archive-enhanced dataset.

- image-predictions: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

- image_predictions_clean: the clean version of the image-predictions dataset.

- tweet-json: file containing JSON data for tweets. Used to extract features of interest about the tweet then store them in a pandas dataframe.

- twitter_archive_master: master dataset containing the combined version of the twitter_archive_clean dataset, image_predictions_clean dataset, and the dataframe built from tweet-json data.
