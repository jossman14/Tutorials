# Tutorials

This repository contains the code for all my articles and video series.

## Getting Started

Clone the wanted part of the repository and run jupyter notebook

### Prerequisites

You need to have [Python](https://www.python.org/) install.  
As well as either [Tensorflow](https://www.tensorflow.org/install/) or [Theano](http://deeplearning.net/software/theano/install.html) as a backend for Keras.  

## Author
 **Gilbert Tanner**
 
## Support me

<a href="https://www.buymeacoffee.com/gilberttanner" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Dataset & Artefak

Model hasil training (`*.h5`, mis. `Keras-Tutorials/6. Sentiment Analysis/sentiment_analysis.h5`, `mnist_model.h5`, `stock_prediction.h5`, `Recommendation System/regression_model*.h5`) dan dataset besar **tidak disertakan** di repo. Model dibuat ulang dengan menjalankan notebook/skrip terkait (kode menyimpan model via `model.save(...)` bila file belum ada).

Dataset yang perlu diunduh sendiri:

- **Wine Reviews** (`winemag-data-130k-v2.csv`, untuk *Introduction to Data Visualization in Python*): https://www.kaggle.com/zynicide/wine-reviews — letakkan di folder notebook tersebut.
- **MNIST**: diunduh otomatis lewat `keras.datasets.mnist.load_data()`.
- **Iris** (tutorial Hyperparameter Tuning): dibaca langsung dari https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data

Dataset kecil yang masih ada di repo: `iris.csv`, `Keras-Tutorials/6. Sentiment Analysis/Tweets.csv` (Twitter US Airline Sentiment), `Keras-Tutorials/5. .../AAPL_data.csv`, serta file goodbooks-10k di `Recommendation System/` (`books.csv`, `ratings.csv`, `book_tags.csv`, `tags.csv`, `to_read.csv`).
