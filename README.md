## Predict Earthquake rupture using machine learnig approach

### Basic Information:
Dynamic rupture propagation is a challenging problem due to uncertainty regarding the underlying physics of earthquake slip, and the stress conditions and frictional properties of fault are not well constrained. These unknown initial stresses and friction combine with fault geometry to control the rupture process and determine the dynamics of slip and the resulting ground motions. However, because the earthquake rupture problem is highly nonlinear, determining parameter values is often done by making simplifying assumptions combined with trial and error, which computationally and numerically expensive. To improve our ability to determine reasonable friction and stress parameters, we use machine learning methods to develop models to predict if rupture can break through a fault with geometric heterogeneities. We create two models using the artificial neural network (ANN), and the random forest decision tree (RFD) algorithms. We train the models using a database of 1000 dynamic rupture simulations with varying fault geometry, stress conditions, and friction parameters. We also rigorously validate and test the predictive power of the models using additional simulations. Both RFD and ANN models can predict if a rupture can break through the geometric complexity with 82% accuracy on our test simulations, and require significantly fewer computational resources to predict rupture characteristics once the models have been trained. The model parameters that are determined through machine learning are also useful in determining what the most important physical parameters that control rupture propagation, providing new insights into the highly nonlinear process of fault rupture.

### Paper:
https://arxiv.org/abs/1906.06250

### Codes and Libraies
All of the projects 
requires Python 2.7 or 3 I have Used python 3.0. The following Python libraries are also required:

<li> NumPy
<li> Pandas
<li> matplotlib
<li> scikit-learn
<li> Keras

### Datasets 
Datasets are included in the data folder.

### Published Poster :
<a>https://s3-us-west-2.amazonaws.com/files.scec.org/s3fs-public/publication_7759.pdf</a>

### Contributors

Me and Eric daub worked on the project.

### License

MIT
