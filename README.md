# hackathon-5-learning

## Special installation instructions

Though you don't need the nltk dependencies for the first learning unit, please be aware
of the following:

1. If you are OSX, you will need to use python 3.5
    - The docker image already has this into account
1. The docker image is REALLY large this time around... ~4GB because it has all of the nltk datasets downloaded
1. If you are using regular python virtual environments, execute the following
    - `python -m nltk.downloader all`
    - This will take a long time and will download more than is necessary but
      it will ensure that you don't need to download datasets any more
