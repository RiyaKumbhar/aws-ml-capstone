# ML Video Content Search Dashboard                                                                                                                                                                         
                                     
  Capstone project for AWS Academy Machine Learning for Natural Language Processing.
                                                                                    
  ## What It Does
  An end-to-end NLP pipeline that transcribes 46 ML course videos and builds an interactive search dashboard — students can find video content by keyword or topic instantly.
                                                                                                                                                                             
  ## Pipeline                                                                                                                                                                                                 
  1. Source 46 videos from Amazon S3
  2. Transcribe audio using ffmpeg + SpeechRecognition                                                                                                                                                        
  3. Normalize text with NLTK (tokenization, stopwords, lemmatization)
  4. Extract 10 topics using Amazon Comprehend batch topic modeling   
  5. Interactive search dashboard with keyword highlighting and topic filters                                                                                                                                 
                                                                             
  ## Tech Stack                                                                                                                                                                                               
  Amazon S3 · Amazon Comprehend · Amazon SageMaker · ffmpeg · SpeechRecognition · NLTK · scikit-learn · pandas · matplotlib · Python 3.12
                                                                                                                                                                                                              
  ## Results                                                                                                                                                                                                  
  - 46/46 videos transcribed
  - 10 topics extracted via Amazon Comprehend                                                                                                                                                                 
  - Live keyword search with topic filtering 
                                           
