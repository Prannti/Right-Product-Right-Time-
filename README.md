# Amazon Product Recommendation System
## Project Authors: Ms.Prannti Agnihotri, Mr.Nandit Sharma, Ms.Ashna Santosh Tandon and Mr.Anirudh Gupta

This project is a **Product Recommendation System** built using Python. It utilizes **k-Nearest Neighbors (k-NN)** for recommending similar products based on features like price and rank. The project also includes a **search functionality** and a GUI interface for user interaction.

## Features
- **Data Preprocessing**:
  - Extracts relevant fields from the dataset.
  - Handles missing values by imputing median values for missing `price` and `rank`.

- **Search Functionality**:
  - Allows users to search for products by their title.
  - Provides suggestions if no exact matches are found.

- **Recommendation Engine**:
  - Recommends similar products using `k-NN` based on price and rank.

- **GUI Interface**:
  - Users can search for products, view results, and get recommendations through an intuitive GUI built with **Tkinter**.

---

## Dataset
The dataset used is **meta_All_Beauty_sample.json**, a sample JSON dataset containing product details such as:
- `asin`: Amazon Standard Identification Number
- `title`: Product title
- `brand`: Product brand
- `price`: Price of the product
- `rank`: Product rank
- `description`: Product description
- `image`: Image URL of the product

---

## Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required Python libraries:
  - `pandas`
  - `scikit-learn`
  - `numpy`
  - `tkinter` (comes pre-installed with Python)

Install any missing libraries using:
```bash
pip install pandas scikit-learn numpy
