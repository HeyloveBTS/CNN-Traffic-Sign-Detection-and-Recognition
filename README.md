# CNN-Traffic-Sign-Detection-and-Recognition

My dataset:

Identifying traffic: https://benchmark.ini.rub.de/?section=gtsrb&subsection=news
_J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel. The German Traffic Sign Recognition Benchmark: A multi-class classification competition. In Proceedings of the IEEE International Joint Conference on Neural Networks, pages 1453–1460. 2011._

This dataset I have chosen is a collection of more than 50,000 real-life German traffic signs, and within those images, the traffic signs only occur once. Each image only contains one traffic sign, and is stored in the PPM format. The data I downloaded has already been organized into 43 categories based on the traffic signs. The images are not necessarily square, nor are the traffic signs necessarily centered within the image, which is true for images that are close to the image border in the full camera image. Image size varies from 15x15 to 250x250 pixels.

In this project, I used python and Tensorflow to classify traffic signs. The goal is to explore and build a Convolutional Neural Network to solve this single-image, multiclass classification problem. More info can be see at https://www.sciencedirect.com/science/article/pii/S0893608012000457?via%3Dihub


## Conclusion
I was able to achieve a validation accuracy of 97%+ and a test accuracy of 97%+.
