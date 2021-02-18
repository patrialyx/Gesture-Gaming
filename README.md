# Follow the Signs - creating Gesture Games using Computer Vision
*Done by: Lim Sheng Jie, Patria Lim Yun Xuan*

During one of my First Year CS projects, we were tasked with a fun game design assignment which allowed us to use default neural network models that could detect facial emotion.

The theme was to design a game application which would be helpful to the community. Instead of using the default AI model options, my teammate and I were intrigued by the idea of gesture gaming and decided to foray into training "Our First Neural Network". 

<h2>Our Expectations</h2>

[video link](https://drive.google.com/file/d/134XAkXqkEmRU1J-HADcqheTiRwjXqce5/view?usp=sharing)
<br> *This is fake*

<h2>Reality</h2>

[video link](https://drive.google.com/file/d/1yMdLtvpYTzwlghFrGx734MBiMvmurrGM/view?usp=sharing)
<br> *This is real*

In an attempt to use ASL (American Sign Language) to control our character sprite, we created a small model architecture of three 2D convolutional layers and 1 fully connected layer. We then trained it on the letters UDLRK (up, down, left, right, kill, nothing) with 2000 images in each class. We hoped that with a small model with fewer classification classes, the accuracy would be better for each alphabet. The results weren't amazing..... but it was the most optimal state achieved in a short timeframe.

Moving forward, within the constraints of a small model, future improvements could include modifying the architecture design of the model, or experimenting with small pretrained models to see if we can further improve performance.
