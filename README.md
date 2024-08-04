# Mini-Project-Plagiarism_Checker

We are not installing the modules form pypi.org because they are pre-installed in Google Colab.

Making a list of all the text files(having the .txt extension)
Next, we open the text files one by one and copy the data in student_notes.

Machine learning models can only take input of numeric data, so in order to train them for the textual data we use a vectorizer.
A vectorizer converts the numeric data to textual format.(using a mathematical function in the backend)
Here the vectorizer is used is the tfidfvectorizer.

cosine_similarity is a mathematical formula that finds the similarity between the two vectors.(this is further used to check the plagiarism)

The text file is converted to numerical value using the vectorize function which is then added to a list.
Each vector is copied adnd it's current index is compared using cosine similarity and then the vector is deleted to save memory.  

In the end you can check the plagiarism percentage between the two text files.
