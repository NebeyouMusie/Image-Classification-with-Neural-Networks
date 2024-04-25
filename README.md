# Image Classification with Neural Networks

## What's its use case?
 - The MNIST Fashion dataset itself isn't meant to solve a real-world problem like classifying clothes in a store. It's more like a practice test for your neural network.

 - Here's the analogy:
   - MNIST Fashion is like training wheels for image classification with neural networks.
   - You learn the basics on a simplified dataset before moving on to more complex real-world applications.
 - Those real-world applications could include:
   - Automatic clothing recommendation systems based on user preferences or images.
   - Visual search for fashion items in online stores.
   - Content moderation to identify and remove inappropriate clothing images.
     
## Why Neural Networks?
 - In most classification problems, machine learning algorithms will do the job, but while classifying a large dataset of images, you will need to use a neural network.

## Data Content
 - Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels (see above), and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.
 - You can find other details in the `fashion-classifiation.ipynb` notebook

## Libraries Used
 - Numpy
 - Seaborn
 - Tensorflow
 - Matplotlib

## Installation
 1. Prerequisites
    - Git
    - Command line familiarity
 2. Clone the Repository: git clone https://github.com/NebeyouMusie/Image-Classification-with-Neural-Networks.git
 3. Create and Activate Virtual Environment (Recommended)
    - python -m venv venv
    - source venv/bin/activate
 4. Install Libraries: pip install tensorflow numpy matplotlib seaborn
 5. Open `fashion-classifiation.ipynb` and run all cells
 6. Or you can download the `fashion-classifiation.ipynb` Notebook from the repository, upload the notebook to [Google Colab](https://colab.research.google.com/) then run all the cells in the `fashion-classifiation.ipynb` Notebook

## Acknowledgments
 - I would like to thank [Aman Kharwal](https://www.linkedin.com/in/aman-kharwal)
