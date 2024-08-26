# Shopee Sentiment Analysis Competition

## Overview 
This project focuses on building a sentiment analysis model that classifies user comments into categories such as Positive, Negative, Neutral, or Spam. Sentiment analysis is a key tool in understanding user feedback, enhancing customer satisfaction, and improving products or services based on the sentiments expressed in user-generated content
## Project Structure
1) 'data' : in the file Cung_cap_HV_ShopeeFood
2) Notebook.ipynb : contain code for preprocessing, model and evaluation
## Getting Started
1) Python 3.6
2) Jupyter Notebook
3) Python packages list (scikit-learn, lightGBM, pandas, numpy)
## Installation
1) Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ShopeeSentimentAnalysis.git
   cd ShopeeSentimentAnalysis
2) pip install -r requirements.txt
3) jupyter notebook or google colab
## Usage
1) Open notebook.ipynb in JupyterNotebook or Google Colab
2) Follow the steps in the notebook
3) Randomly back-testing to see the positive or negative comment of a restaurant
## Features
1) Data-processing :
   - Text cleaning and normlization
   - Handling special characters, stopword removal and lemmatization
   - Using specific Vietnamese package for text processing include : underthesea and pyvi
2) Sentiment Classification :
   - Classification of comments into predefined categories ( Positive,Negative, Neutral , Spam)
   - Ultllizes advanced machine learning technique like lightGBM for efficient and scalable model
   - Custom handling of spam comments to ensure they are properly filterd and treated separately
3) Model Evaluation  :
   - Performance metrics such as Accuracy, Precision, Recall , Validation, AUC-ROC
## Result 
Our model achieved an AUC 0.93, indicate a strong performance of classifying positive, negative instant. The model is also affective filtering out spam comments which could help viewers or readers understand about the restaurant before they book a reservation.
## Dataset 
The data used in this project is sourced from ShopeeFood Machine Learning Competition in Vietnam 'Cung_cap_HV_ShopeeFood'. Includes user comments has been pre-labeled into categories used in this analysis.
## Contributing
We welcome contributions to this project. To contribute:
- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes and commit them (git commit -m 'Add new feature').
- Push to the branch (git push origin feature-branch).
- Create a pull request.
## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License - see the LICENSE file for details.
## Contact 
For any question or inquiries, please reach out to danhdanhtuan0308@gmail.com.
