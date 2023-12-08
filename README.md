## Fashion Recommendation System

## Overview

The application of a deep learning-based fashion recommendation system may be found in this repository. For thorough fashion product recommendations, the system makes use of Python, TensorFlow, Keras, Convolutional Neural Networks (CNNs), ResNet-50 architecture, and web scraping.


## Introduction

Based on image input, the fashion recommendation system seeks to offer customized outfit recommendations. It analyzes an extensive dataset of more than 45,000 fashion photos using deep learning techniques, such as the K-Nearest Neighbors algorithm and the ResNet-50 architecture. The method generates the top 5 closest matches to user-supplied photos by combining similarity search with transfer learning for effective feature extraction.



# Dataset has been used:

 - [High Resolution Dataset link](https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset)
 - [Low Resolution Dataset link](https://www.kaggle.com/paramaggarwal/fashion-product-images-small)

## Methodology

The approach combines Annoy for K-Nearest Neighbors, transfer learning, and ResNet-50 architecture. Customized fashion recommendations are made possible by the system's ability to extract information from a large dataset. The study places a strong emphasis on CNNs, transfer learning, and similarity search's versatility and efficacy.

## Web Scraping

Databases for the recommendation system are created by webpage scraping. The main focus is on pictures of models with clothes that were taken by web scraping methods from several sources.

## Recommendation Engine

Sklearn Nearest Neighbors is used in the implementation of the recommendation engine. To offer individualized outfit recommendations, it collects user data, examines past activity, and filters the information. Items that are comparable to the user's tastes are recommended using content-based filtering.

## Image Pre-processing

One important phase is picture pre-processing, which involves flattening, segmenting, and resizing user-provided photos. This guarantees compatibility with the model that was trained using a 224 × 224 standard input scale.

## Convolutional Neural Networks (CNNs)
CNNs—the ResNet-50 architecture in particular—are used to handle visual input. Neural networks are trained by transfer learning, and further layers are added to the model to make it as efficient as possible under the conditions.

## Related Work

The system incorporates findings from previous research on fashion suggestion systems, referencing papers like "Decomposition of Style Features in a Deep Fashion Recommendation System" and "Intelligent Clothes Suggestion System."
## Result

The web application allows users to upload photographs and receive recommendations for things that have comparable visuals. The overall experience of discovering products is improved by the interface's user-friendly design.

## Conclusion

The system for recommending fashion offers a useful way to make clothing recommendations based only on looks. It is proposed that future study be conducted to increase accuracy and the overall experience of fashion discovery.

## Usage

Refer to the [Usage] section of the documentation for instructions on how to use the fashion recommendation system

## Contributing

Contributions are always welcome! If you would want to help with the fashion suggestion system's development, kindly refer to our [contribution rules] (CONTRIBUTING.md).







