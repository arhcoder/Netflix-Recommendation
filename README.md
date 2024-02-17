# 📚 DATOS MASIVOS II
## 💻 Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas
## 🏫 Universidad Nacional Autónoma de México

<hr>

### 🎬 Caso Netflix
### 🍿 Sistema de Recomendación de Contenido
#### 🚻 Método de Filtrado Colaborativo

<br>

#### Realizado por:
#### Iván Alejadro Ramos Herrera
#### 💜 [@arhcoder](https://github.com/arhcoder)


# 📓 Selección de Dataset

## Netflix Prize data
### Fuente: https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data/
### Información del dataset:
> Netflix held the Netflix Prize open competition for the best algorithm to predict user ratings for films. The grand prize was $1,000,000 and was won by BellKor's Pragmatic Chaos team. This is the dataset that was used in that competition.

> TRAINING DATASET FILE DESCRIPTION
The file "training_set.tar" is a tar of a directory containing 17770 files, one
per movie. The first line of each file contains the movie id followed by a
colon. Each subsequent line in the file corresponds to a rating from a customer
and its date in the following format:

> CustomerID,Rating,Date
MovieIDs range from 1 to 17770 sequentially.
CustomerIDs range from 1 to 2649429, with gaps. There are 480189 users.
Ratings are on a five star (integral) scale from 1 to 5.
Dates have the format YYYY-MM-DD.
MOVIES FILE DESCRIPTION
Movie information in "movie_titles.txt" is in the following format:

> MovieID,YearOfRelease,Title
MovieID do not correspond to actual Netflix movie ids or IMDB movie ids.
YearOfRelease can range from 1890 to 2005 and may correspond to the release of
corresponding DVD, not necessarily its theaterical release.
Title is the Netflix movie title and may not correspond to
titles used on other sites. Titles are in English.
QUALIFYING AND PREDICTION DATASET FILE DESCRIPTION
The qualifying dataset for the Netflix Prize is contained in the text file
"qualifying.txt". It consists of lines indicating a movie id, followed by a
colon, and then customer ids and rating dates, one per line for that movie id.
The movie and customer ids are contained in the training set. Of course the
ratings are withheld. There are no empty lines in the file.
…

> To calculate the RMSE of your predictions against those
ratings and compare your RMSE against the Cinematch RMSE on the same data. See http://www.netflixprize.com/faq#probe for that value.