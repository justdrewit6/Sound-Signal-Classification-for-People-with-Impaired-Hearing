# Sound-Signal-Classification-for-People-with-Impaired-Hearing

### Proposed Method

The proposed method as shown in the figure below , is comprised of five major stages, namely noise cancellation, pre-processing, MFCC feature extraction, CNN model training and classification, respectively. The noise cancellation phase involves determination of a noise gate/profile, then this obtained noise profile in applied throughout the signal. In the pre-processing phase conversion of stereo signals to mono signal takes place and enhancement of sound signal is done and are stored in a list. This is followed by the feature extraction of MFCC where features are extracted iterating through each sound file and are label encoded. The training of the CNN model takes place with the features that are extracted, with the use of machine learning algorithms. At the end using an activation function the sound signal provided is successfully classified.

![bitmap](https://user-images.githubusercontent.com/81764309/224734158-e42e3c7a-56fd-47b2-9529-3acd3f7f4276.png)
