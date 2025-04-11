### 🎬 Movie Recommendation System using Transformers
This project demonstrates a Movie Recommendation System built using Transformer architectures, leveraging the power of deep learning to provide personalized movie suggestions based on user preferences, descriptions, and metadata.

### 🚀 Overview
Traditional recommendation systems rely heavily on collaborative filtering or content-based filtering. This project enhances the approach by applying Transformer-based models to capture semantic understanding from movie plots, genres, and user histories for better recommendations.

### 📌 Features
- Movie recommendations based on plot summaries and user preferences.

- Utilizes pre-trained Transformer models (e.g., BERT) for encoding movie data.

- Cosine similarity between embeddings to recommend similar movies.

- Scalable and adaptable to new data.

- Clean, modular code for future enhancements.

### 🧠 Model Used
 - BERT (Bidirectional Encoder Representations from Transformers)

 - DistilBERT

 - Custom Transformer Encoder


#### 📂 Dataset
- Movies Metadata: Kaggle TMDB 5000 Movie Dataset or your own curated dataset.

- Columns used: title, overview, genres, tags.

### 🛠️ Tech Stack
- Python

- Hugging Face Transformers

- Scikit-learn

- Pandas & NumPy


### 📈 How It Works
- **Data Preprocessing:** Clean and merge movie information.

- **Text Embedding:** Use Transformer models to generate embeddings for movie descriptions.

- **Similarity Computation:** Calculate cosine similarity between embeddings.

- **Recommendation Engine:** Suggest top-N similar movies.
