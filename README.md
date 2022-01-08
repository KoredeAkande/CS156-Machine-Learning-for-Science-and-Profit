# CS156: Machine Learning for Science and Profit
Select coding assignments and exercises from the CS156: Machine Learning for Science and Profit class, taken in Fall 2021. The course covered a range of core machine learning techniques — such as *classification, expectation maximization, regression, perceptron, neural networks, support vector machines, hidden Markov models*, and *nonparametric models of clustering* — as well as fundamental concepts such as *feature selection, cross-validation,* and *over-fitting*.

Course Highlights
------------
1. Built and trained a lightweight-GAN to generate cityscape images, achieving an FID score of 119.49 after 20,000 training steps. This project–which served as my course final project–involved data extraction and curation, image preprocessing using numpy, (image) data cleaning using an unsupervised neural network called CLIP (Contrastive Language-Image Pre-Training) and hyperparameter optimization, among multiple other processes. The project report can be found [here](https://github.com/KoredeAkande/CS156-Machine-Learning-for-Science-and-Profit/blob/main/-Final%20Project%20GAN%20Cityscapes/CS156%20Final%20GAN%20Cityscapes.pdf) and images of final results can be viewed below.
2. 82% and 93% accuracy in classifying jersey and shirt images, using an SVM (with RBF kernel) and a fine-tuned VGG16 model, respectively (see [here](https://github.com/KoredeAkande/CS156-Machine-Learning-for-Science-and-Profit/blob/main/A6-%20SVM%20vs%20VGG16%20(Fashion%202.0).ipynb)).
3. Built two neural network models using keras to classify the moons and circles datasets, achieving perfect accuracy on both (see [here](https://github.com/KoredeAkande/CS156-Machine-Learning-for-Science-and-Profit/blob/main/Exc11-%20Feedforward%20Neural%20Networks.ipynb))
4. Massaged literature corpus data into a suitable format then trained a Latent Dirichlet Allocation (LDA) model to find interesting topics (and words) that occured across chapters (see [here](https://github.com/KoredeAkande/CS156-Machine-Learning-for-Science-and-Profit/blob/main/Exc14-%20Topic%20Modeling%20with%20LDA.ipynb)).
5. Digit classification using k-nearest neighbor (kNN) algorithm, achieving 97.2% accuracy (see [here](https://github.com/KoredeAkande/CS156-Machine-Learning-for-Science-and-Profit/blob/main/A1-%20Linear%20Regression%20%26%20KNN/Moores%20Law%20%26%20MNIST%20Digits.ipynb))
6. Explored using linear discriminant analysis (LDA) and LDA with principal component analysis (PCA) for jersey vs. shirts classification, achieving 77% accuracy after data curation (see [here](https://github.com/KoredeAkande/CS156-Machine-Learning-for-Science-and-Profit/blob/main/Ex4-%20PCA%20%26%20LDA.ipynb)).
7. Built a markov model for language detection, utilizing Baye's rule to classify strings into most probable (dummy) language. Similarly, a hidden markov model was built to determine which of three speakers was most probably speaking at a particular point in time given a sequence of phonemes (among other pieces of information) (see [here](https://github.com/KoredeAkande/CS156-Machine-Learning-for-Science-and-Profit/blob/main/A7-%20Hidden%20Markov%20Model%20for%20Speech%20Recognition.ipynb)).
8. Implemented Expectation Maximization algorithm to estimate the biases and probabilities of two coins, given data on the number of heads obtained from a corresponding number of throws (see [here](https://github.com/KoredeAkande/CS156-Machine-Learning-for-Science-and-Profit/blob/main/Ex7-%20Expectation%20Maximization.ipynb))

GAN-generated Cityscapes   |  Speaker Identification | Topic Modeling | PCA vs. LDA 
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![GAN Cityscapes](figures/gan_cityscapes.jpeg? =100x20)  |  ![Speaker Identification](figures/hmm.png?raw=true "Title") | ![Topic Modeling](figures/latent_dirichlet_allocation.png?raw=true "Title") | ![PCA vs LDA](figures/pca_vs_lda.png?raw=true "Title") 







