# Detection-of-Alzheimer-s-disease-using-speech-patterns
This project focuses on early detection of Alzheimer's disease (AD) using advanced deep learning techniques to analyze speech patterns. The goal is to create a robust model that can identify subtle linguistic changes indicative of AD onset, enabling timely intervention and improved patient outcomes.

#
**1) INTRODUCTION**
The project aims to develop an  model for early Alzheimer's disease (AD) detection using
speech analysis. The critical challenge addressed is the need for accessible and timely methods of
identifying AD onset, considering the significant impact of delayed diagnosis on patient outcomes.
By leveraging advanced deep learning algorithms, the model seeks to analyze subtle linguistic
changes in speech patterns that may signify the early stages of AD, thus enabling accurate diagnosis
and timely intervention. This initiative responds to the urgent need for innovative approaches to AD
detection, aiming to revolutionize early diagnosis practices and ultimately improve patient care and
quality of life.


#
**2) DATASET DESCRIPTION**
For Dementia Diagnosis: This involves a supervised learning task, with the dataset sourced from
TalkBank's Pitt Dementia dataset. The dataset consists of both control samples and dementia patient
samples. Audio files are manually transcribed, containing specific characters indicating pauses,
stutters, and other speech patterns, meticulously documented by TalkBank. Transcripts also include
assessor's lines, parts of speech transcripts, and time stamps.



![Screenshot 2024-06-22 173447](https://github.com/SIMRAN1256/Detection-of-Alzheimer-s-disease-using-speech-patterns/assets/101476806/15c06dda-02b7-4b76-9dd8-755e31ec1d29)

**3) DETECTION MODELS**

Model Summary:
Model: "sequential_4"
_________________________________________________________________
Layer (type) Output Shape Parameters
=================================================================
dense_25 (Dense) (None, 256) 11520
batch_normalization_19 (Ba (None, 256) 1024
tchNormalization)


dense_26 (Dense) (None, 256) 65792
batch_normalization_20 (Ba (None, 256) 1024
tchNormalization)



dense_27 (Dense) (None, 128) 32896
dropout_10 (Dropout) (None, 128) 0
batch_normalization_21 (Ba (None, 128) 512
tchNormalization)



dense_28 (Dense) (None, 128) 16512
dropout_11 (Dropout) (None, 128) 0
batch_normalization_22 (Ba (None, 128) 512
tchNormalization)




dense_29 (Dense) (None, 64) 8256
dropout_12 (Dropout) (None, 64) 0
batch_normalization_23 (Ba (None, 64) 256
tchNormalization)




dense_30 (Dense) (None, 32) 2080
dropout_13 (Dropout) (None, 32) 0
batch_normalization_24 (Ba (None, 32) 128
tchNormalization)



dense_31 (Dense) (None, 16) 528
batch_normalization_25 (Ba (None, 16) 64
tchNormalization)



dense_32 (Dense) (None, 6) 102

=================================================================



Total params: 141206 (551.59 KB)


Trainable params: 139446 (544.71 KB)


Non-trainable params: 1760 (6.88 KB)
_________________________________________________________________
The model aims to learn complex patterns from the data with a combination of dense, dropout, and batch normalization
layers, facilitating efficient training and improved generalization performance.




![Screenshot 2024-06-22 174133](https://github.com/SIMRAN1256/Detection-of-Alzheimer-s-disease-using-speech-patterns/assets/101476806/c3df5cbd-3f04-4757-b94b-6ac27a9bc09e)

![Screenshot 2024-06-22 174352](https://github.com/SIMRAN1256/Detection-of-Alzheimer-s-disease-using-speech-patterns/assets/101476806/6cbcd4ff-e9f3-46a0-9dfd-30884d5c7654)
