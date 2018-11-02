# LDA
thorough implementation of LDA using gensim package

1. install packages  
if preprocessed data, then no need to import spacy or going through the first part in __main__ anymore

2. download file http://mallet.cs.umass.edu/dist/mallet-2.0.8.zip  
it is located in the folder mallet-2.0.8 already, but need to change the path of os.environ['MALLET_HOME'] and mallet_path accordingly

3. uncomment pyLDAvis.show(vis) in LDA(lda_model) function if want to see the visualization of clustering, go to your browser to see the generated visualization  
  comment pyLDAvis.show(vis) if you want to continue execution
 

