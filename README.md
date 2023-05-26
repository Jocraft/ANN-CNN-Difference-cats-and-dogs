# ANN-CNN-Difference-cats-and-dogs
a repo to show the significant difference between ANN and CNN for an image-based model using cats and dogs grayscale images
> model to predict/recognize animal images (cats,dogs) <br><br>
> the model is based on tensorflow keras api <br><br>

working with 30k grayscaled images of cats and dogs<br><br>
### part of the data 0 indicates a cat , 1 indicates a dog<br><br>
![image](https://github.com/Jocraft/ANN-CNN-Difference-cats-and-dogs/assets/47274049/ed158c31-3e14-4392-b64a-214698529061)<br><br>
##ANN
we have an ANN model with 2 hidden layers that uses relu and an output layer with single node that uses sigmoid activation function<br>
complineg it adam optimizar , binary_crossentropy for the loss function and "accuracy" as ametrics <br>
we used "EarlyStopping" and "reduce learning rate" methods to have better accuracy<br> 

###Classification Report:<br><br>
![image](https://github.com/Jocraft/ANN-CNN-Difference-cats-and-dogs/assets/47274049/36660eb4-b836-4db6-8241-6b8310fe9507)<br><br>
###confusion_matrix:<br><br>
![image](https://github.com/Jocraft/ANN-CNN-Difference-cats-and-dogs/assets/47274049/9ad8a374-3e22-4e7b-b835-7241ef1bc587)<br><br>

##CNN
we have tried three differant models before we settled on a one <br>
the none-commented one is the one you should run <br>
we have conv2d input layer then another 5 hidden layers of "MaxPool2D" and Conv2D then a dense layer , all conv2d and dens  having relu as there their activation function<br>
and we have one output layer with single node having sigmoid as there it's activation function<br>
complineg it adam optimizar , binary_crossentropy for the loss function and "accuracy" as ametrics <br>
we used "EarlyStopping" and "reduce learning rate" methods to have better accuracy<br> 

###Classification Report:<br><br>
![image](https://github.com/Jocraft/ANN-CNN-Difference-cats-and-dogs/assets/47274049/f7108544-1e19-44e8-a75d-d9c3d45a3e79)<br><br>
###confusion_matrix:<br><br>
![image](https://github.com/Jocraft/ANN-CNN-Difference-cats-and-dogs/assets/47274049/53ede75c-a868-4f55-a39c-cde80f05c729)<br><br>
<br><br>
##then lastly predicting from an outer images
i tried the model on my cat "Pooh"<br><br>
![image](https://github.com/Jocraft/ANN-CNN-Difference-cats-and-dogs/assets/47274049/a33948fd-ab49-4d92-ae58-1a721f65362f)

