 # NLP
T5 Project proposal

Topic Modeling and Clustering 

News-Articles-and-Essays

# Students:
* Nasser Alshehri
* Abdullah Bushnag
* Abdulrhman Alqurashi

# OVERVIEW
News come in different formats, different types and different categories. Here we attempt to use Topic modeling and Clustering to get answers on what each content containt based on its content and then we try to do it based only on its title.

The process would be: We load the data. Keep what we need from the data. Clean the text(ex:stopwords).

Build the bag of words for all documents. Build the bag of words for each document.

Vectorize the data. Run the LDA model. Run the model on all data and save the output to dataframe

Run the Clustering algorithm. Save the data to csv. Make the charts.

# Data
The data is acquired from: https://components.one/datasets/all-the-news-articles-dataset

The Raw data containts 12 features: id, title, author, date, content, year, month, publication, category, digital, section, url.

The features we are using are only the 'title' and 'content'.

The data we are not interested in will be dropped/ignored.

The 'title' is the headling/name/title of the news/Article/Essay.
The 'Content' is the body/content/Essay/Article/News itself.

# TOOLS
Pandas
Numpy
Scikit-learn
Matplotlib
Seaborn
nltk
gensim
