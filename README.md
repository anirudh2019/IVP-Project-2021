# Seizure Detection Tutorials
___
Group-20 IVP

Currently four open-source datasets are used: 

1. The Epileptologie Database<sup>18</sup> 

2. UPenn and Mayo Clinic's Seizure Detection Challenge<sup>21</sup> 

3. CHB-MIT Scalp EEG Database<sup>19</sup>

4. NEDC TUH EEG Seizure corpus<sup>26</sup>

Other databases exist but have their limitations:
    
**Topics covered**

- Biosignal Feature Extraction 
- Feature Pre-Processing
- Supervised Classification
- Model Evaluation
- Hyperparameter Tuning (Gridsearch, Random Search, Bayesian Optimization)
- Ensemble Learning
- Dimensionality Reduction
- Batch Learning
- Multilayer Perceptrons
- Convolutional Neural Networks
- Recurrent Neural Networks


### Prerequisites

The easiest way of interacting with these notebooks is to use [Google Colaboratory](https://colab.research.google.com).

*"Colaboratory allows you to use and share Jupyter notebooks with others without having to download, install, or run anything on your own computer other than a browser"* (https://research.google.com/colaboratory/faq.html).

I recommend Google Colaboratory mostly because of the size of the RAM available and the access to GPU's via the cloud. When working on the later notebooks, which use the TensorFlow package, the notebook will be ran a tonne faster! You can open the notebook in Colaboratory by clicking on the "Open in Colab" button at the top of the notebook.

Another option is to use [Binder](https://mybinder.org/). Binder is a open-source cloud deployment for Jupyter notebooks (see https://mybinder.readthedocs.io/en/latest/ for details). Although completely free it does have relatively limited computational resources, with a maximum of 2GB of RAM. This means some of the later notebooks which use larger datasets will likely not fit into memory.

If you want to interact with the notebooks locally on your machine then I advise you download Anaconda with Python 3 (See http://docs.anaconda.com/anaconda/install/) to get you started. Anaconda makes it easy to create a virtual environment in which to install and manage Python packages. It also provides an easy interface in which to launch the Jupyter Notebook interface (the Anaconda Navigator).

### Installing Packages

The notebooks start with a method to automatically install the required packages and data if using Google Colab. If working on these locally I encourage you to use a virtual environment. All you need to do is create a new environment and launch the Jupyter Notebook application from that environment (See http://docs.anaconda.com/anaconda/navigator/ for more information). 

If you want to install the packages manually from command prompt (or Anaconda prompt) then install the following packages below.

- matplotlib
- pandas 
- numpy 
- scipy 
- scikit-learn
- umap-learn 
- imblearn 
- seaborn 
- mlxtend 
- mne 
- PyWavelets
- Tensorflow




