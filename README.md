This project provides a Machine Learning algorithm to match the profiles of applicants against the keywords of a job description. The algorithm is based on NLP (Natural Language Processing). 
First of all, the text of 'job_title' for each candidate in the given dataset was pre-processed to expand the abbreviations, making spelling corrections and changing all alphabets to lower characters. Then a pipleline was used to tokenize and lemmatize the text before using Word2Vec to calculate 'Cosine Similarity' between this text and the keywords of job requirements. 
In the last step, the same steps were repeated to calculate the 'Cosine Similarity' between the candidates' job titles against one of the shortlisted candidate's job title. 
