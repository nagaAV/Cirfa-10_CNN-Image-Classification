# Cirfa-10_CNN-Image-Classification

Dataset description:
                 Dataset consists of 10 classes of different categories they are(airplanes, background_ google, bonsai, car_ side, faces, faces_ easy, grand_ piano, leopards, motorbikes, watch)  and training data images of 3725.  


Approach:
                 The problem given was to classify ten different classes using CNN model. As we build a basic CNN model one convolution layer with max pooling with sigmoid activation function for 10 epochs. We got an good accuracy for train and validation of both 93%.

Now, to improve the accuracy we tune the model with adding hidden layers with 2 conv and one max pooling. We got an increase in accuracy of train-98%.

Now, then let’s build with pre-trained models using inceptionv3 and tweaking data transformation
For each images apply to this model. We got a very good accuracy of 99.3% on train and 97.14% on validation which shows that the transfer learning is most powerful technique of all time.
