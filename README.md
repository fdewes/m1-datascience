# m1-datascience
Just a requirements.txt that contains all data science packages that work with macOS Monterey on M1 / Apple Silicon out of the box.

Open "terminal" app and run:

    mkdir m1_dsenv
    cd m1_dsenv
    python3 -mvenv .
    source bin/activate
    git clone https://github.com/fdewes/m1-datascience
    pip install -r m1-datascience/requirements.txt
