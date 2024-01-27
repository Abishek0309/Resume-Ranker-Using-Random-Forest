
# Resume Ranker 

## Overview
This project aims to match resumes with a given job description using Natural Language Processing (NLP) techniques. It leverages TF-IDF cosine similarity and a Random Forest Regressor to score resumes based on their relevance to the provided job description.

## Requirements
- Python 3.x
- Required Python libraries: pandas, numpy, nltk, scikit-learn, gradio

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Abishek0309/Resume-Ranker-Using-Random-Forest.git
   cd Resume-Ranker-Using-Random-Forest

## Install the required dependencies
    pip install -r requirements.txt

## Usage
 Prepare your dataset: Ensure you have a CSV file containing resume data. Columns like 'name', 'degree', 'links', and 'work_experience' are expected.

 Data Preprocessing: The script performs various data preprocessing steps, including handling missing values and extracting relevant information from the dataset.

 TF-IDF Cosine Similarity: Resumes are scored based on their similarity to a provided job description using TF-IDF cosine similarity.

 Model Training: The Random Forest Regressor is used to predict resume scores based on encoded features.

 Gradio Interface: Launch the Gradio interface to upload a job description file and get the top 10 matching resumes.

## File Structure
├── Resume Ranker
│   ├── Job Description.txt   
|   ├── Resume Ranker.ipynb
│   └── Data Set.csv             

## Results
The Gradio interface provides an interactive way to upload job descriptions and receive the top 10 matching resumes along with their scores.

## Acknowledgments
The project uses the Gradio library for creating an interactive interface.
Special thanks to the contributors and maintainers of the open-source libraries used in this project.




