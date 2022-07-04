# DataScience_Molecular_physics
## Data science in Molecular physics problems  


In this work, we will show the use of data science & machine learning concepts with scikit-learn in various problems mainly in molecular physics area.
First, we will implement the general concepts such as linear, non-linear regression, and classifiction  in context of specific problems. Then we will develop neural network potentials for Lennard-Jones clusters. After that, we will develop a neural network (NN) for the classi cation of local structural environments in bulk phases



- **Regression**:
    - Linear regression
        - Diabetes Dataset evaluation  
   
    - Non-linear regression :
        - Appoximation of a function using
            - Support vector machine + linear kernel
            - Support vector machine + Gaussian kernel
            - Neural network  
        
- **Classification**:
    - Non-linear classification 
        - Solving problem in 2D space
            - Neural network
            - Effects of regularisation
        
- **Project: Neural network potentials for Lennard-Jones clusters**: We develop a neural network (NN) potential for small Lennard-Jones (LJ) clusters. There will be three steps that will be worked on :
    - setting up the LJ clusters and creating several datasets
        - Initial cluster setup
        - Optimising cluster setup
        - Creating datasets using Monte Carlo sampling
            - MC sampling and dataset for 3D LJ cluster
            - MC sampling and dataset for 2D LJ cluster
        
    - optimizing the hyper-parameters and training the NN
        - Network architecture and weight optimization
        - Learning curve with respect to dataset size
        
    - application, transferability, and limitations
        - Use the fitted NN to perform Monte Carlo (MC) sampling of the 3D clusters
        - Transferability of the NN potential 
            - Low and high temperature data
            - Fitting with mixed datasets or including all datasets
            - Transferability from 3D to 2D
            
