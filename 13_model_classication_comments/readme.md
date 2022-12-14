# 13. Модель классификации комментариев

**Задача**

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
Модель классификации комментариев на позитивные и негативные позволит найти негативные для отправки их на модерацию. 
Построим разные модели и выясним какая дает значение метрики качества F1 не меньше 0.75.

**Данные**

Имеется набор данных с разметкой о токсичности правок.
Столбец text содержит текст комментария, а toxic — целевой признак.

**План**

1.	Загрузка и подготовка данных.
2.	Обучение различных моделей.
3.	Выводы.

**Инструменты**

Python, Pandas, Numpy, предобработка данных, Bert, nltk, tf-idf, catboost, transformers, pytorch, tokenize, stopwords, wordnet, SnowballStemmer, WordNetLemmatizer, TfidfVectorizer, sklearn, train_test_split, GridSearchCV, TimeSeriesSplit, cross_val_score, KFold, compute_class_weight, f1_score, LogisticRegression,LogisticRegressionCV, DecisionTreeClassifier, RandomForestClassifier, DummyClassifier, CatBoostClassifier, shuffle

**Статус**

Закончен. Возможно улучшение и оптимизация.