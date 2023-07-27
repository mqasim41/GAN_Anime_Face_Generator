# GAN_Anime_Face_Generator
Creating Anime Faces using GANS

Given the https://www.kaggle.com/splcher/animefacedataset dataset. I have created a DCGAN network to generate images of the faces of anime characters.

GAN Architecture invloves the use of two neural networks. A discriminator network which tells apart AI generated images from real images and a generator 
network which given the feedback from the discriminator network learns to generate a more and more realistic image. 

Diagram of GANs architecture:

![image](https://github.com/mqasim41/GAN_Anime_Face_Generator/assets/114048264/e5fc5196-7d2a-4b24-90aa-dea9c2db2fb4)


Real Images:

![image](https://github.com/mqasim41/GAN_Anime_Face_Generator/assets/114048264/a0d58a19-4f27-457b-9ddd-51a6519914b5)

AI Generated Images after 1 epoch:

![image](https://github.com/mqasim41/GAN_Anime_Face_Generator/assets/114048264/f3b6036b-6dad-4947-8732-f5663518d303)


AI generated Image after 25 epochs:

![image](https://github.com/mqasim41/GAN_Anime_Face_Generator/assets/114048264/b1b50806-bfa2-4ba5-86f1-5354a44ab5d1)

Model Losses:

![image](https://github.com/mqasim41/GAN_Anime_Face_Generator/assets/114048264/6f47fa85-2e0c-43e6-81a9-2f0ee8323bf6)





