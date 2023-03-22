# CrossMediaRecs: Merging Interests for Tailored Movie Recommendations

CrossMediaRecs is a powerful movie recommendation system that utilizes machine learning to provide personalized movie suggestions to users based on their preferences for TV series, subscriptions to YouTube channels, and favorite subreddits. This project aims to recommend feature films, documentaries, and platform-specific movies that cater to users' unique tastes by analyzing their interests across multiple media platforms.

## Features

* Personalized movie recommendations based on user preferences
* Machine learning algorithms to analyze user interests in TV series, YouTube channels, and subreddits
* Support for feature films, documentaries, and platform-specific movies
* Seamless integration with popular streaming platforms (Netflix, Amazon Prime Video, Hulu, etc.)

## Getting Started

### Prerequisites

Ensure you have Python 3.x and the following libraries installed:

* pandas
* numpy
* scikit-learn
* nltk
* joblib

You can install the libraries using the following command:

``` 
pip install pandas numpy scikit-learn nltk joblib
```
### Dataset
To build this recommendation system, you need datasets containing:

1. Movie metadata
2. TV series metadata
3. YouTube channel metadata
4. Subreddit metadata

These datasets should include features such as genres, directors, cast members, and plot descriptions.

### Usage

1. Clone this repository to your local machine.
2. Update the dataset paths in the code as necessary.
3. Run the cross_media_recs.py script to train the model and generate recommendations.

```
python cross_media_recs.py
```

## Project Structure

* cross_media_recs.py: Main script to preprocess the data, train the model, and generate movie recommendations.
* data_preprocessing.py: Helper script for data preprocessing and feature extraction.
* similarity.py: Helper script to compute similarity scores between movies and user interests.
* recommendations.py: Helper script to generate personalized movie recommendations.
* datasets/: Folder containing sample datasets.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss a new feature or bug fix.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
