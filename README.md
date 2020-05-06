# Lab | Avila Bible

<img src="https://media.giphy.com/media/h8HgkqabhYyq8iRSp0/giphy.gif" alt="alt text" width="200" height="200">


## Introduction

Avila bible is one of the largest and most spectacular codices in the Spanish National Library. The ornamentation features contrasting Italian and Spanish styles. The Italian decoration depicts the authors of the books and contains numerous capitals, either illuminated or coloured in red, blue, yellow and dark green on lighter backgrounds in the same tone. The colours change in the Spanish decoration, which also has exceptional intertwined initials and whole-page figurative illustrations of subjects such as Noah's Ark, the symbols of the evangelists and scenes from the life of Christ.

![avila-bible](https://cadenaser.com/emisora/imagenes/2016/12/20/ser_avila/1482250694_869096_1482253032_noticia_normal.jpg)

## Data Description

The Avila data set has been extracted from 800 images of the the "Avila Bible", a giant Latin copy of the whole Bible produced during the XII century between Italy and Spain.  
The palaeographic analysis of the  manuscript has  individuated the presence of 12 copyists. The pages written by each copyist are not equally numerous. 
Each pattern contains 10 features and corresponds to a group of 4 consecutive rows.

The prediction task consists in associating each pattern to one of the 12 copyists (labeled as:  Marcus, Clarius, Philippus, Coronavirucus, Mongucus, Paithonius, Ubuntius, Esequlius).
The data have has been normalized, by using the Z-normalization method, and divided in two data sets: a training set and a test set.

## Getting Started

Open the `main.ipynb`. Read the instructions carefully and provide your answer beneath it.

## Deliverables

- Predictions will be sent in the format indicated in the `sample_submission.csv` file in the data section.
- `main.ipynb` including the requirements below. 

## Requirements

- Train a minimum of 4 different models
- Perform a minimum of 4 Feature Extraction and Engineering techniques
- Must contain a summary of the machine learning tools and algorithms
- and the results or the score obtained with each of them

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.

## Resources

https://apila-bible.herokuapp.com/

## Citation

If you want to refer to the Avila data set in a publication, please cite the following paper:

C. De Stefano, M. Maniaci, F. Fontanella, A. Scotto di Freca,
Reliable writer identification in medieval manuscripts through page layout features: The "Avila" Bible case, Engineering Applications of Artificial Intelligence, Volume 72, 2018, pp. 99-110.
