# Movie Recommendation System

A content-based movie recommendation system that uses TF-IDF vectorization to find movies similar to user queries. The system considers movie titles, overviews, keywords, genres, cast, and directors to make recommendations.

## Dataset
The dataset is retrieved from: [source](https://www.kaggle.com/datasets/utkarshx27/movies-dataset/data). I edited it to contain only 500 rows of movies for demonstration purposes. 
The dataset (`movies_dataset.csv`) contains movie information of:
- Original title
- Overview
- Keywords
- Genres
- Cast
- Director
  etc.

The dataset file is in the directory of the project, so there is no need to do anything as long as you follow the instructions from the [video](https://www.loom.com/share/6ce844759ec14401a231a76370c92a3d?sid=765194c4-a7f3-4da5-8f84-16c309bd8594)

## Setup

### Requirements
- Python 3.8+
- pandas
- scikit-learn

### Installation

1. Create and activate a virtual environment (optional):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```
#### <i> Note: Dependencies are installed within the Jupyter notebook, no need to do additional steps </i>

## Running the System using Jupyter Notebook 
1. Start Jupyter
2. Open `recommendation.ipynb`
3. Run all cells
4. Modify the `user_query` variable to get different recommendations


## Input Data: 
A user query with a movie preference. 
## Output Data: 
A sorted list of movies with a title, a similarity score, an overview, and genres. 
## Example Results

For the query "I love movies with Christian Bale", the system returns:

```
Top 5 Recommendations:
1. Batman Begins (ID: 119, score: 0.1660)
   Keywords: himalaya martial arts dc comics crime fighter secret identity
   Overview: Driven by tragedy, billionaire Bruce Wayne dedicates his life to uncovering and defeating the corruption that plagues his home, Gotham City.  Unable to work within the system, he instead creates a new identity, a symbol of fear for the criminal underworld - The Batman.
   Genres: Action Crime Drama

2. Exodus: Gods and Kings (ID: 157, score: 0.1603)
   Keywords: moses bible ancient egypt 3d ramses
   Overview: The defiant leader Moses rises up against the Egyptian Pharaoh Ramses, setting 400,000 slaves on a monumental journey of escape from Egypt and its terrifying cycle of deadly plagues.
   Genres: Adventure Drama Action

3. 金陵十三釵 (ID: 317, score: 0.1597)
   Keywords: forced prostitution child rape
   Overview: A Westerner finds refuge with a group of women in a church during Japan's rape of Nanking in 1937. Posing as a priest, he attempts to lead the women to safety.
   Genres: Drama History War

4. Terminator Salvation (ID: 43, score: 0.1533)
   Keywords: saving the world artificial intelligence prophecy san francisco cyborg
   Overview: All grown up in post-apocalyptic 2018, John Connor must lead the resistance of humans against the increasingly dominating militaristic robots. But when Marcus Wright appears, his existence confuses the mission as Connor tries to determine whether Wright has come from the future or the past -- and whether he's friend or foe.
   Genres: Action Science Fiction Thriller

5. The Dark Knight (ID: 65, score: 0.1396)
   Keywords: dc comics crime fighter secret identity scarecrow sadism
   Overview: Batman raises the stakes in his war on crime. With the help of Lt. Jim Gordon and District Attorney Harvey Dent, Batman sets out to dismantle the remaining criminal organizations that plague the streets. The partnership proves to be effective, but they soon find themselves prey to a reign of chaos unleashed by a rising criminal mastermind known to the terrified citizens of Gotham as the Joker.
   Genres: Drama Action Crime Thriller

```

The similarity score indicates how well each movie matches the query, with higher scores representing better matches.

## Desired Salary:
$1600/Month = $20/hr
