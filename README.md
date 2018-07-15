# TV-channels-logo-detection-and-localization
1. We need data. There are 2 ways that we can utilize to obtain appropriate data:

    1.1. Design and implement a method to take shot of every frame of a TV channel and somehow label it.
  
    1.2. on ImageNet dataSet, randomly put the logo of each channel on a random position of a random image. Meanwhile, we are labeling images.
  
2. train a Convolutinal Neural Netwok on this newly created dataset.
3. Finetune the netwoek parameters.
4. Check the result.

Classification Task:
do a simple cnn classification and alter it somehow that it can produce the bundaries.

Another classification method:
HOG + Linear SVM framework: https://www.pyimagesearch.com/2014/11/10/histogram-oriented-gradients-object-detection/
