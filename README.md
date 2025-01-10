# Fashion Recommender System

This project is a **Fashion Recommender System** that uses a deep learning model for image feature extraction and nearest neighbor search for recommending visually similar fashion items. The application is built using **Streamlit** for a user-friendly interface.

---

## Features

- **Deep Learning-Based Feature Extraction**:
  - Utilizes a pre-trained ResNet50 model to extract features from images.
  - Images are processed into embeddings stored for efficient retrieval.

- **Visual Similarity Recommendations**:
  - Users can upload an image to receive recommendations for similar fashion items.

- **Interactive Interface**:
  - Built with Streamlit for easy navigation and seamless user experience.

---

## Installation

### Prerequisites

- Python 3.7+
- The following Python libraries:
  - `tensorflow`
  - `streamlit`
  - `numpy`
  - `Pillow`
  - `scikit-learn`
  - `tqdm`
  - `pickle`

### Steps

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
2. Create a directory named images and add fashion item images for data set:
   https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset
3.Generate embeddings:
  python app.py
4.Run the Streamlit app:
  streamlit run main.py
  Access the app in your browser at http://localhost:8501.
