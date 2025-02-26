# Movie Recommendation System

## Image
<img width="412" alt="Screenshot 2025-02-22 at 7 21 34 PM" src="https://github.com/user-attachments/assets/e11750e4-0cb7-441a-b1fd-52d21b3dbc1f" />
![alt text](https://www.upgrad.com/blog/create-your-own-movie-recommendation-system-using-python/)
## Overview
The **Movie Recommendation System** is a machine learning-based project that suggests movies to users based on their preferences. This project leverages Python, machine learning algorithms, and Scikit-learn to provide personalized recommendations.

## Features
- Content-based filtering using movie metadata
- Collaborative filtering based on user ratings
- Hybrid recommendation combining both approaches
- Scalable and efficient implementation using Scikit-learn

## Tech Stack
- **Programming Language:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy
- **Dataset:** [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Download the dataset and place it in the project directory.

## Usage
1. Run the script to preprocess the data:
   ```sh
   python preprocess.py
   ```
2. Train the recommendation model:
   ```sh
   python train.py
   ```
3. Get movie recommendations:
   ```sh
   python recommend.py --movie "Inception"
   ```

## Project Structure
```
movie-recommendation-system/
│── data/              # Dataset storage
│── models/            # Trained models
│── notebooks/         # Jupyter notebooks for analysis
│── scripts/
│   ├── preprocess.py  # Data preprocessing
│   ├── train.py       # Training models
│   ├── recommend.py   # Recommendation system
│── requirements.txt   # Dependencies
│── README.md          # Documentation
```

## Algorithms Used
- **Content-Based Filtering:** Uses TF-IDF and cosine similarity to recommend similar movies.
- **Collaborative Filtering:** Uses matrix factorization techniques (SVD, KNN) to recommend movies based on user behavior.
- **Hybrid Approach:** Combines both content and collaborative filtering for better accuracy.

## Dataset
- **Source:** [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- **Contains:** Movie metadata, user ratings, genres, etc.

## Future Enhancements
- Integration with a web-based UI for real-time recommendations
- Deep learning-based recommendation using neural networks
- Deployment using Flask or FastAPI

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.
