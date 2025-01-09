# RecoMate: Movie Recommendation System with Sentiment Analysis

RecoMate is a movie recommendation system built using collaborative filtering techniques with the additional feature of sentiment analysis. It predicts movie ratings for users based on their preferences and the opinions expressed in reviews. The system leverages the Surprise library for recommendation and uses natural language processing for sentiment analysis.

## Features

- **Movie Recommendations**: Predicts movie ratings for users and suggests movies they might enjoy.
- **Sentiment Analysis**: Analyzes movie reviews to determine the sentiment (positive/negative).
- **Real-Time Recommendations**: Recommends movies based on user preferences and sentiment analysis of reviews.
- **Streamlit Dashboard**: Interactive dashboard for real-time visualizations and user input.

## Technologies Used

- **Python**: Programming language used for the implementation.
- **Pandas**: Data manipulation and analysis.
- **Surprise**: A Python library for building recommendation systems.
- **NLTK/TextBlob**: Libraries used for sentiment analysis.
- **Streamlit**: For building the web interface.
- **Matplotlib**: For generating visualizations.

## Installation

### Prerequisites

- Python 3.x
- pip

### Steps to Install

1. Clone the repository:
    ```bash
    git clone https://github.com/priyanka-ardu/RecoMate.git
    ```

2. Navigate to the project directory:
    ```bash
    cd RecoMate
    ```

3. Create a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. If you're missing the `requirements.txt` file, install the dependencies manually:
    ```bash
    pip install pandas surprise streamlit nltk matplotlib textblob
    ```

6. Run the app:
    ```bash
    streamlit run main.py
    ```

## Project Structure
RecoMate/ 

│ ├── data/ # Contains datasets (e.g., rating.csv, movies.csv) 

│ ├── recommendation/ # Code for recommendation engine 

│ ├── recommend.py # Functions to handle recommendation logic 

│ ├── model.py # Training and testing the model 

│ ├── sentiment_analysis/ # Sentiment analysis functions 

│ ├── sentiment.py # Functions to perform sentiment analysis on reviews 

│ ├── visualizations/ # Code for visualizing results 

│ ├── visualizations.py # Functions to generate visualizations 

│ ├── main.py # Main script to run the Streamlit app 

├── requirements.txt # List of dependencies 

└── .gitignore # Git ignore file



## Usage

1. **Movie Recommendations**:  
   After running the Streamlit app, you can enter a user ID to receive personalized movie recommendations based on your previous ratings.

2. **Sentiment Analysis**:  
   The system analyzes movie reviews and labels them with sentiments (positive/negative), helping users make better decisions based on movie reviews.

3. **Visualization**:  
   Visualize the number of positive and negative reviews, user preferences, and other statistics about the dataset and recommendations.

## Contributing

Contributions are welcome! If you want to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them.
4. Push to your forked repository.
5. Create a pull request to the `main` branch.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Note:
- The `data` folder is excluded from the Git repository due to its large size. Please ensure you have the required datasets to run the project.

