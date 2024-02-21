# Classification-of-Urban-Sounds



Classification of
audio signals are employed using convolutional neural network and VGG-16 for the and dataset used for the implementation is the UrbanSound8K. As a
result of  model’s output, an input audio file will be classified into one of the
ten classes: Air Conditioner, Car Horn, Children Playing, Dog Bark, Drilling, Engine
Idling, Gun Shot, Jackhammer, Siren, and Street Music. The most important priority
in audio processing is feature extraction, and Mel Frequency Cepstral Coefficient
(MFCC) is employed as a feature space for sound samples.
![image](https://github.com/Divyanshi-Bhojak/Classification-of-Urban-Sounds/assets/34389241/9129747f-a62c-48e3-88ee-96178dadade8)


Dataset
The UrbanSound8k dataset contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren, and street_music. The classes are drawn from the urban sound taxonomy.All excerpts are taken from field recordings uploaded to www.freesound.org.
8732 audio files of urban sounds (see description above) in WAV format. The sampling rate, bit depth, and number of channels are the same as those of the original file uploaded to Freesound (and hence may vary from file to file).
The UrbanSound8k dataset used for model training, can be downloaded from the following link: https://urbansounddataset.weebly.com/

Features Extracted
Librosa was used for data preprocessing and feature extraction.

MEL Features
MFCC
In sound processing, the mel-frequency cepstrum (MFC) is a representation of the short-term power spectrum of a sound, based on a linear cosine transform of a log power spectrum on a nonlinear mel scale of frequency.
Mel-frequency cepstral coefficients (MFCCs) are coefficients that collectively make up an MFC. They are derived from a type of cepstral representation of the audio clip (a nonlinear "spectrum-of-a-spectrum").
![image](https://github.com/Divyanshi-Bhojak/Classification-of-Urban-Sounds/assets/34389241/eda578b5-491f-4701-aaa7-cd4efb694ccc)

Results
Test Accuracy for CNN Model using original data: 47.0339%
Test Accuracy for CNN Optimised Model using original data: 93.1598%
Test Accuracy for CNN-V 16 Model using augmented data: 92.9177%

Future Work
Extend data more by using different parameters for augmentation
Apply Hyperparameter optimization and test different architectures






