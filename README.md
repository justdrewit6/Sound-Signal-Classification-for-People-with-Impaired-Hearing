# Sound-Signal-Classification-for-People-with-Impaired-Hearing

### Proposed Method

The proposed method as shown in the figure below , is comprised of five major stages, namely noise cancellation, pre-processing, MFCC feature extraction, CNN model training and classification, respectively. The noise cancellation phase involves determination of a noise gate/profile, then this obtained noise profile in applied throughout the signal. In the pre-processing phase conversion of stereo signals to mono signal takes place and enhancement of sound signal is done and are stored in a list. This is followed by the feature extraction of Mel-frequency cepstral coefficients(MFCC) where features are extracted iterating through each sound file and are label encoded. The training of the Convolution Neural Network(CNN) model takes place with the features that are extracted, with the use of machine learning algorithms. At the end using an activation function the sound signal provided is successfully classified.

![bitmap](https://user-images.githubusercontent.com/81764309/224734158-e42e3c7a-56fd-47b2-9529-3acd3f7f4276.png)

### UrbanSound8K Dataset

Get your hand on UrbanSound8K dataset from: https://urbansounddataset.weebly.com/download-urbansound8k.html <br>
Fill the required form fields and proceed donwliading the dataset.

### Run on your machine
Open the ipynb file and install the necessary modules. Download the sample audio file to check if the code is working or not, then start extractiong the MFCC features (this might take some time). Download a test audio that you wish to use for testing purposes in .wav format, edit the filename for your test audio in the code, the noise should get reduced from your audio then classified.
