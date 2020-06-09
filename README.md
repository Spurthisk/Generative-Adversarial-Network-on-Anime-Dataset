# Generative-Adversarial-Networks-on-Anime-Dataset
GAN is one of the Deep Learning technique used to generate some new data from scratch. It runs in unsupervised way meaning that it can run without labelled by human. It will make the data based on the pattern that it learns. 

# Dataset
https://drive.google.com/drive/u/0/folders/1BIqpOZj6hLCbfIJtmnn7kftyMphPBuei

# Fully trained GAN Model
https://drive.google.com/drive/u/0/folders/14RpZsc0COYfDptSkW41JhGy0-kl3TUiL

# GAN 
• Generate random noise in a probability distribution such as normal distribution. 
• Make it as an input of Generator neural network. It will output generated fake data. 
• Generated fake data is combined with the data that is sampled from the dataset which is real data. This is made as input of Discriminator.  It is noted as D. Discriminator will try to learn by predicting whether the data is fake or not. Train the neural network by doing forward pass and followed by back propagation. Updates the D weights. 
• Generator is needed to be trained. The fake data generated is made as input of the D. It should be noted that this steps only input the fake data into the discriminator. Forward pass the fake data in D. By using the Discriminator neural network, on doing forward pass, predict whether the fake data is fake or not. Then back propagation is done where only the G weights are updated. 
• These steps are repeated until the generator provide good fake data or maximum iteration has been reached. 

# Training 
Training of DCGAN: 
• Iterate until max iterations the following steps 
• Generate random noise in a probability distribution such as normal distribution. 
• Combine the generated fake data with the data that is sampled from the dataset. 
• Add noise to the label of the input 
• Train the Discriminator 
• Train the Generator 
• Update the start index of the real dataset 
 
# Conclusion 
The interesting characteristic of GAN is its latent vector showing the data distribution learned by the generator. It shows that It can form a data distribution. The latent vector can be linear algebra operated. It can also be manipulated to change the face based on the changed element in the latent vector. GAN can be used to create new characters in the field of Cartoon so as to generate new faces which can be used in Comics and Screenplays as well.
