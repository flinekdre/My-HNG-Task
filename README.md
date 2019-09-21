# HNG ALPR System
## Automated License Plat Recognition System
## Based on LeNet CNN

The model (licenseplate_not_licenseplate.model) is generated using LeNet architecture and uses Relu activation function.

<code>train.py</code> is used to train the model and also generates a graph indicating the result of the training process.

To use this repository, simply use: 

<code>python test_network.py --model licenseplate_not_licenseplate.model --image examples/flora/platenumbers/FKJ-339XA.jpeg</code>

you can replace the image with any other image source. The test will run the generated model and plot an image of the percentage correlation
to a license plate number or not.

This model was trained using dataset for different countries, license plate types i.e. private, commercial, government plates etc. and also different positions of plate numbers.

This library can also be used to generate a model for other objects as well.

**This code has only been tested using Python 3.5**

You might get different results on different python version.
