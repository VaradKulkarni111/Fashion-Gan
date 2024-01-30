# Generative Machine Learning Project using fashion_mnist Tensorflow Dataset

Steps Involved:

1.Setting up your environment
    
        a.Importing Dependencies and Data
        
          tensorflow 
          tensorflow-gpu 
          matplotlib 
          ensorflow-datasets 
          
        b.Using tensorflow api to bring data source
  
2.Building a data pipeline

        a.Visualizing Data and Build Dataset

          Data Transformation
          setup iterator
          getting data from pipeline
          setting up subplot formatting
    
3.Creating a generator & discriminator

        a.Importing modelling components
        
          sequential api for generator and discriminator
          creating layers for neural network

        b.Build Generator

        c.Build Discriminator
        
4.Building a custom training loop

      a.Setup Losses and Optimizers
      
        Adam optimizer 
        BinaryCrossentropy for losses

      b.Build Subclassed Model

        base class to subclass 

      c.build callback

      d.Training model
      
5.Generating new images.

      a.saving model
