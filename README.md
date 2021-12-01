# m1-datascience
Just a requirements.txt that contains all python data science packages that work with the default python installation of macOS Monterey on M1 / Apple Silicon.

Open "terminal" app and run:

    mkdir m1ds
    cd m1ds
    python3 -mvenv .
    source bin/activate
    git clone https://github.com/fdewes/m1-datascience
    pip install -U pip
    pip install -r m1-datascience/requirements.txt
    jupyter lab
