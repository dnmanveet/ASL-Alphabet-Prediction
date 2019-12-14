# ASL-Alphabet-Prediction-(American Sign Language)

This model is built using fastai library and tarined on a kaggle dataset.

### [ASL Alphabet](https://www.kaggle.com/grassknoted/asl-alphabet)

The data set is a collection of images of alphabets from the American Sign Language, separated in 29 folders which represent the various classes.

![ASL-hands](https://user-images.githubusercontent.com/29728855/70845276-7bc78600-1e72-11ea-8e8a-7038726aa7ed.jpg)

The training data set contains 87,000 images which are 200x200 pixels. There are 29 classes, of which 26 are for the letters A-Z and 3 classes for SPACE, DELETE and NOTHING. These 3 classes are very helpful in real time applications, and classification. The test data set contains a mere 29 images, to encourage the use of real world test images

![Screenshot from 2019-12-14 13-10-26](https://user-images.githubusercontent.com/29728855/70845318-293a9980-1e73-11ea-8bdb-06f55c231cb4.png)

The dataset is trained on resent34  and resnet50 can managed to get and accuracy of **99.9%**

## Predictions:

![Screenshot from 2019-12-14 00-30-16](https://user-images.githubusercontent.com/29728855/70845360-ad8d1c80-1e73-11ea-8694-8e47c5f44e33.png)

![Screenshot from 2019-12-14 00-30-36](https://user-images.githubusercontent.com/29728855/70845361-ad8d1c80-1e73-11ea-882b-232b4a953980.png)

![Screenshot from 2019-12-14 00-31-04](https://user-images.githubusercontent.com/29728855/70845362-ae25b300-1e73-11ea-9f0d-55b8cd831e80.png)
