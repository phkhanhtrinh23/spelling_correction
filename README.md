# Spelling Correction


## About The Project


### Introduction

My project is called **Spelling Correction**. This is a model which helps a person correct a sentence with spelling mistakes.


### Built With

My application is built with these frameworks and tools:
* [Google Colab Notebook](https://colab.research.google.com/)
* [GPU Tesla K80](https://www.nvidia.com/en-gb/data-center/tesla-k80/)
* [Tensorflow 2.6.0](https://github.com/tensorflow/tensorflow/releases/tag/v2.6.0)
* [Python 3.7.12](https://www.python.org/downloads/release/python-3712/)


## Getting Started

To get started, you should have prior knowledge on **Python** and **Tensorflow** at first. A few resources to get you started if this is your first Python or Tensorflow project:

- [Tensorflow: Guide](https://www.tensorflow.org/guide)
- [Python for Beginners](https://www.python.org/about/gettingstarted/)


## Installation and Run

1. Clone the repo

   ```sh
   git clone https://github.com/phkhanhtrinh23/spelling_correction.git
   ```
  
2. Use any code editor to open the folder **spelling_correction**.


## Outline

- Input: [`fra.txt`](http://www.manythings.org/anki/) a French-English Dictionary.

- Output:
1. `spelling_correction_v1` is the first version of my work. The model is based on **Encoder-Decoder** and both Encoder and Decoder are **Bi-directional LSTM**. It is fast in training and inference but the performance was extremely bad with long sentences.

2. `spelling_correction_v2` is the second version of my work. The model is based on **Bi-directional Encoder-Decoder** as before but it is upgraded with **Bahdanau Attention**, which considerably improves the performance of model on long and complex sentences with errors.


## Results
- Results of `spelling_correction_v1`:
<img src="https://github.com/phkhanhtrinh23/spelling_correction/blob/main/results/output_2.png">

- Results of `spelling_correction_v2`:
<img src="https://github.com/phkhanhtrinh23/spelling_correction/blob/main/results/result_4.png">


## Contribution

Contributions are what make GitHub such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the project
2. Create your Contribute branch: `git checkout -b contribute/Contribute`
3. Commit your changes: `git commit -m 'add your messages'`
4. Push to the branch: `git push origin contribute/Contribute`
5. Open a pull request


## Contact

Email: phkhanhtrinh23@gmail.com

LinkedIn: https://www.linkedin.com/in/trinh-pham-3103081a0/

Project Link: https://github.com/phkhanhtrinh23/spelling_correction.git
