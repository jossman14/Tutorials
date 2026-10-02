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

Model hasil training (`*.h5`/`*.hdf5`, mis. `Keras-Tutorials/6. Sentiment Analysis/sentiment_analysis.h5`, `mnist_model.h5`, `stock_prediction.h5`, `Recommendation System/regression_model*.h5`, `Keras-Tutorials/4. LSTM Text Generation/weights.hdf5`, serta model ML.NET `CreditCardFraudDetection/assets/model.zip`) dan dataset besar **tidak disertakan** di repo. Model dibuat ulang dengan menjalankan notebook/skrip terkait (kode menyimpan model via `model.save(...)` bila file belum ada).

Dataset yang perlu diunduh sendiri:

- **Wine Reviews** (`winemag-data-130k-v2.csv`, untuk *Introduction to Data Visualization in Python*): https://www.kaggle.com/zynicide/wine-reviews — letakkan di folder notebook tersebut.
- **MNIST**: diunduh otomatis lewat `keras.datasets.mnist.load_data()`.
- **Iris** (tutorial Hyperparameter Tuning): dibaca langsung dari https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data
- **goodbooks-10k** (*Recommendation System*): `ratings.csv`, `book_tags.csv`, `to_read.csv` tidak disertakan (ukuran besar); URL sumber tidak tercatat di notebook, nama folder di kode: `goodbooks-10k/`.
- **Credit card fraud** (`creditcard.csv`, tutorial ML.NET `CreditCardFraudDetection`, diletakkan di folder `assets/`): sumber tidak tercatat. `model.zip` dibuat ulang dengan menjalankan program tersebut.

Dataset kecil yang masih ada di repo: `iris.csv`, `Keras-Tutorials/6. Sentiment Analysis/Tweets.csv` (Twitter US Airline Sentiment), `Keras-Tutorials/5. .../AAPL_data.csv`, serta sebagian kecil goodbooks-10k di `Recommendation System/` (`books.csv`, `tags.csv`).
