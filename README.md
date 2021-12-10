# m1-datascience
Just a requirements.txt that contains all python data science packages that work with the default python installation of macOS Monterey on M1 / Apple Silicon.

Will update this whenever new packages can be installed out of the box :)

## Most Important Packages 

* numpy 
* pandas 
* scipy
* scikit-learn
* torch
* fastai
* spacy 
* nltk
* beautifulsoup4
* matplotlib
* seaborn
* plotly
* networkx
* folium
* imblearn
* streamlit


## Installation and Starting

Open "terminal" app and run:

    mkdir m1ds
    cd m1ds
    python3 -mvenv .
    source bin/activate
    git clone https://github.com/fdewes/m1-datascience
    pip install -U pip
    pip install -r m1-datascience/requirements.txt
    jupyter lab

## To Deactivate the Environment, Run

    deactivate

## To Activate the Environment Again, just Run

    source m1ds/bin/activate
    jupyter lab

    
