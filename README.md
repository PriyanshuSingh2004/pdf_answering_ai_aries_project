It's Pdf Answering ai System on short as well as long documents. It can automatically find answers to matching questions directly from documents. The deep learning language model converts the questions and documents to semantic vectors to find the matching answer.<br>
<br>
<br>
Approches:<br><br>
Question Answering System Using Simple Split and Cosine Similarity (Naive Approach)<br>
Question Answering System Using Word2Vec Embedding Technique<br>
Question Answering System Using Glove Embedding Technique<br>
Question Answering System with Fine-Tuned BERT Technique<br>
Question Answering System Using CDQA on Multiple Pdf Files<br><br>
Challenges<br>
Bert is a really powerful model for tackling a question-answering problem. However, it comes up with the limitation of 512 tokens and the documents were really longer than 512 tokens. In order to handle this limitation I wrote the function "expand_split_sentences", which split and expand sentences i.e., it makes paragraphs with lesser than 512 tokens and makes data frames of that paragraph. In this, more than one data frame contains the correct answer so we will find the best answer by finding the max start score.<br><br>
Pretrained Model and Dataset Used<br>
word2vec<br>
glove<br>
bert-large-uncased-whole-word-masking-finetuned-squad<br>
bert-squad_1.1<br>

