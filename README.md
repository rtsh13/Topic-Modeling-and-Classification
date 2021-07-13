# Topic-Modeling-using-LDA

This script performs *Topic Modelling* and uses the algorithms mentioned below

## Algorithms used
* Latent Dirichlet allocation(LDA)
* LDA Mallet Model - a Toolkit 


> To use LDA Mallet Model, download the zip file from : http://mallet.cs.umass.edu/download.php.
> Once installed and unzipped, set the environment variable %MALLET_HOME% to the point to the MALLET


## Libraries Needed
1. gensim
2. mltk
3. spacy
4. pyLDAvis
5. matplotlib
6. numpy, pandas

## Pipeline

![Pipeline Overview](images/Capture.JPG)

## Walkthrough
- Import the Libraries
- Discover the Dataset
- Clean the dataset
- Preprocess : 
  - Tokenise
  - Build Bigram and Trigram Models
  - Remove stopwords and Lemmatize
  - Create Dictionary and corpus
- Topic Modelling 
  - LDA
  - Visualise the Topics discovered
  - LDA Mallet if your Coherence Value is < 0.5

