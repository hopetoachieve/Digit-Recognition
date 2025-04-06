
# Digit_Recognition_Web_App
 link : https://github.com/hopetoachieve/Digit-Recognition
<br>
<h3>Structure of App</h3>
<h2> keras - > Tensorflow.js ->(html + css + javascript)->github pages</h1>
  <h3>Handwritten Digit Recognition!</h3>
 <h2>Aim:</h2> To make a convolution neural network to recognise handwritten digits by training the model on MNIST dataset available in keras.
 <br>
 <h2>MNIST DATASET:</h2>The training dataset contain 60000 images and testing contain 10000 images .Each image is 28x28 pixel and grey scale.
  <br>
 <h2>CNN MODEL Summary:</h2>
 <br>1. It is a 17 layer model with Conv2D,MaxPooling2D,BatchNormalization,Dense,Flatten and Dropout layer combination.
 <be>2. Input layer has 32 neuron and output layer has 10 neurons as 10 different clases exsist.
 <br>3. 30 epochs are used.
 <br>4. Categorical_loss is loss function and adam is used for optimization.
 <br>5. Model gives 99.15% accuracy.
<h2>For Deployment:</h2>Save model using tensorflowjs converters as json file and weight as .h5 file.Use Tensorflow.js to load model and predict in javascript file

