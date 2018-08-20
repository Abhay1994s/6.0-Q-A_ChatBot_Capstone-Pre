# 5.0-Q-A_ChatBot_Capstone-Pre

# Word2Vec
It shows the usage of word2vec in converting words into vectors for processing in ML Models.
FILES: Word2Vec.ipynb

# Word-Movers-Distance
This repo shows us how to use WMD Model to predict semantic similarity between two sentences. Sentence 1 will contain the input sentence(query) and sentence 2 will contain a list of sentences in a document (sent_tokenize(doc)).
1. Download a Google Pretrained Model of Weight Vectors.
2. Load the model.
3. Load a document.
4. Input your query.
FILES: Word2Vec.wmdistance.ipynb

# Doc2Vec
It shows us how to compute similarity between two documents. 
Documents can be of any length or in some specifc case, one document can contain a user's query and other documents can be text files from where the query will be asked and Doc2Vec can be used to show the similarity between that query and other documents.
FILES: Doc2Vec.ipynb

# TF-IDF
It shows us how to compute similarity between two documents. 
Document 1 can be a query and document 2 can be a list of other documents.
FILES: TF-IDF.ipynb

# BM-25
It shows us how to compute similarity between two documents. 
Document 1 can be a query and document 2 can be a list of other documents.
FILES: BM_25.ipynb

# Sentence-Paragraph_Similarity
This repo shows us how to check the similarity between a Sentence(query) and paragraphs. This also explains how to point to a particular paragraph in a document from where the question(query) was asked.
1. Extract the file from the squad_train_doc.json folder.
2. Load the JSON file.
3. Run all the approaches and compare the results.
FILES: Sentence-Paragraph Similarity.ipynb

# Sentence Document Similarity
Document giving the best score on similarity index as according to different models (BM_25, TFIDF, Doc2Vec, WMD) will be the actual document from where the Sentence has been taken.
FILES: Merged Document Similarity.ipynb
