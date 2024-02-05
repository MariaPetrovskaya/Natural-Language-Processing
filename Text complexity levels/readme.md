#### Title
- Classification of text complexity levels.
- For movies in English, according to subtitles.
#### Description of the project
- Introduction:
   - Watching films in the original language is a popular and effective method  for training languages skills.
   - It is important to choose a film that suits actual level of difficulty, (possible to understood 50-70% of the dialogues).
   - To fulfill this condition, the expert must watch the new film and decide what level it corresponds to. However, this requires a lot of time.
- Business task
   - Customer of this product: the foreign language courses.
   - Develop an ML solution (multi-class classification) for prediction of difficulty levels for English-language films.
- Dataset:
  - Subtitles of films saved in directories with names as level of difficulty according to the CEFR ([Common European Framework of Reference]('https://ru.wikipedia.org/wiki/%D0%9E%D0%B1%D1%89%D0%B5%D0%B5%D0%B2%D1%80%D0%BE%D0%BF%D0%B5%D0%B9%D1%81%D0%BA%D0%B8%D0%B5_%D0%BA%D0%BE%D0%BC%D0%BF%D0%B5%D1%82%D0%B5%D0%BD%D1%86%D0%B8%D0%B8_%D0%B2%D0%BB%D0%B0%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F_%D0%B8%D0%BD%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%BD%D1%8B%D0%BC_%D1%8F%D0%B7%D1%8B%D0%BA%D0%BE%D0%BC' 'wikipedia'))
  - Movie subtitles in XLSX files containing the name of the movies and the degree of difficulty according to the CEFR scale
  - List of words, according to Oxford level of difficulty
- Classification task
- For customer was important: quality of prediction (F1 metric)

#### Main tools 
- Jupiter notebook, Python and Markdown
####  Machine Learning tools  
- ML models GridSearchCV, CatBoost, MultinomialNB, SGDClassifier
- For text extraction: CountVectorizer, TfidfVectorizer
- ML metrics f1_weighed 
#### Conclusions
- The project is completed
- For searching best hyperparameters used machine learning algorithm with pipeline, GridSearchCV.
- Machine learning models were trained and compared, the best model was selected
- The selected Machine learning model was tested on a test dataset
