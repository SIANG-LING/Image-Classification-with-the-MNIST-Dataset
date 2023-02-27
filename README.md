# Nvidia-Online-Course-Project

The original lecture is from NVIDEA's online course - Getting Started with Deep Learning. https://courses.nvidia.com/courses/course-v1:DLI+S-FX-01+V1/about I make some changes on codes and markdown to learn more about Deep Learning. 

In this project, I used MNIST Dataset to train 4 neural network models with different opimizers to show their difference. 
Steps: 
1.	Data Collection and Pre-processing: 
    By loading data from Keras API. 
    Including: Flattened the image data, normalized the image data and Categorizing the labels.
    
2.	Create 4 neural network model and compile the models
    They all have 3 layers, with 512, 512 and 10 nodes. Apart from the original model, I created other 3 models with different optimizers- “Adam”, “SGD”, and “RMSprop” to see if the optimizer would affect model’s performance.
  
3.  Results:
    The project shows that different optimizers will lead to a different result. If we want to deploy model, we want to choose a stable one. In this case, the ‘sgd’ optimizer with epoch = 7 is the best model.
    
If you want to see more detail description, you can find code and report in the file.



