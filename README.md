# CIKM AnalytiCup 2017 - Lazada Product Title Quality Challenge
This repo contains my implementation for CIKM AnalytiCup 2017 - Lazada Product Title Quality Challenge. I tried this as a learning excersize and the competition is already concluded. 
Competition Link - https://competitions.codalab.org/competitions/16652

## Model
Initially I have implemented a CNN based model. I use fastText word embeddings and use fastText to generate out of vocab embeddings as well.

## How to run
You have to download the relevant dataset by going to the competition link and signing up. Put the downloaded data into a new directory called training/data/. (You can edit the code to set these directories as you desire.) Then you need to download fastText embeddings and the .bin file and generate the embeddings for the out of vocab (oov) tokens.
Then you can run the Jupyter notebook. 
