# How Confident Was Your Reviewer? Estimating Reviewer Confidence From Peer Review Texts 


# Requirement

1. Python 3.6
2. Tensorflow 2.x
3. Transformer
4. Sentence Transformer

# Content

1. All the Machine Learning models are in ml_algos_DT.ipynb, ml_algos_linearregression.ipynb, ml_algos_svm.ipynb. 
2. proposed_model.ipynb contains model with BERT sentence embedding.

In this research, we emphasise reviewed research papers and present results from experimental studies to see how well an state of art model can replicate existing peer reviewer confidence scores prediction. To accomplish so, we used a collection of submitted reviews at the ICLR conference from the years 2018, 2019 and 2021, to train the framed architecture.

Interestingly, the proposed architecture was often able to predict the peer review confidence score reached as a result of human reviewers confidence score, even when only using simple but effective methods to perform the training. To put it another way, there was a strong link between contextual representation, comprehensibility, and confidence scores and the overall evaluation of the review process. This link between confidence measures is intriguing and warrants more research.

How to run it ... ? We recommend using google colab to run it. (provided how to run on google colab plateform , running in terminal will be similar) Step 1 Click that Git Bash icon that will open a terminal window. Step 2 Optionally create a directory and change into it, for example: Step 3 mkdir dev cd dev Step 4 This command will clone the repository from GitHub: git clone https://github.com/PrabhatkrBharti/Rev.Conf
