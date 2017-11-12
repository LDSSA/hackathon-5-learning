# hackathon-5-learning

## Description

As the internet has ever growing amounts of text it is crucial to be able to categorize and filter it. In this hackathon we will look at the problem of attributing a category to a piece of text. This problem is often called **text classification**.

We will start with a general introduction to text data and how to apply data science concepts and algorithms to such a peculiar kind of data. 

Then, you will presented with specific tools and workflows to easily perform text classification with satisfying results. 

Lastly, we will dig deeper into some advanced techniques.

You can find a more detailed description here:

https://docs.google.com/document/d/1-ljpn0qGMqPj1dHxeEA4xa7K8Gf5wywCvZvGFjeeftg/edit?usp=sharing


## Special installation instructions

Though you don't need the nltk dependencies for the first learning unit, please be aware
of the following:

1. If you are OSX, you will need to use python 3.5
    - The docker image already has this into account
1. If you are using regular python virtual environments, execute the following
    - `python -m nltk.downloader popular`
    - This will take a long time and will download more than is necessary but
      it will ensure that you don't need to download datasets any more
