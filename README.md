# Gender Voice Recognition

Data analysis using common Machine Learning algorithms such as Decision Tree Classification and Random Forest Classification

## Getting Started

The dataset was taken from Kaggle, an online community of data scientists and machine learners, owned by Google LLC. Link to the dataset will be provided in the acknowledgement. To be able to run and modify the project, please make sure you have jupyter notebook, python 3, pandas, numpy and sklearn (scikit-learn). These can be done either through pip or conda. See Installing for more detailed information and links.

### Prerequisites

Required stack of programs and libraries are Jupyter notebook, Python 3, Pandas, Numpy and Sklearn (scikit-learn)

### Installing

Make sure to install conda or pip.
I have personally used conda, for which first I had to download Anaconda distribution - The World's most popular Python/R Data science platform, as it is more suitable for data analysis and it includes libraries from other programming languages such as C, C++, R.
Go to terminal

```
conda --version
```

If the code above returns some version you are good to go, otherwise follow the link below to install anaconda:
https://www.anaconda.com/distribution/

After the anaconda installation is complete, open the terminal and follow with the required packages installation

```
conda install -c conda-forge jupyterlab
```

Create a new environment for this project

```
conda create -n yourEnvironmentName
```

Switch to the newly created environment

```
source activate yourEnvironmentName
```

Install required packages

```
conda install python=3.6 numpy pandas scikit-learn
```

After all the above installations are successfully completed clone the repo

```
git clone thisRepoName
```

And finally open the jupyter notebook by just typing

```
jupyter notebook
```

You will see the current folder being opened in the browser, navigate to the gender_voice_recognition.ipynb file and open it.
Click play button to execute each cell of code or comments

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- dataset by Kory Becker: https://www.kaggle.com/primaryobjects/voicegender/download
