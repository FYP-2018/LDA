# LDA
thorough implementation of LDA using gensim package

1. install packages  
if preprocessed data, then no need to import spacy or going through the first part in __main__ anymore

2. download file http://mallet.cs.umass.edu/dist/mallet-2.0.8.zip  
it is located in the folder mallet-2.0.8 already, but need to change the path of os.environ['MALLET_HOME'] and mallet_path accordingly

3. LDA_gensim_visualization.py  
uncomment pyLDAvis.show(vis) in LDA(lda_model) function if want to see the visualization of clustering, go to your browser to see the generated visualization  
  comment pyLDAvis.show(vis) if you want to continue execution
  
 4. LDA_mallet_coherence_plot.py  need to adjust step, begin, limitation to adjust parameters (#of topic)
 
 5. LDA_mallet_find_topic.py  there are 2 things achieved in this file:  finding the topic of each doc  finding the most representative doc in each topic in the form of pandas.df

