# NLP-on-Amazon-Review-data

https://drive.google.com/file/d/1Y0NnlPG0CEjHEMp_EPcPR8lXaDI-iyQx/view?usp=sharing

<h1>Sentiment Analysis in Python using Amazon Reviews</h1>

<p>This project focuses on performing sentiment analysis using Python, leveraging libraries such as NLTK, PyTorch, SciPy, and Pandas. It employs two Natural Language Processing (NLP) transformers: VADER and RoBERTa, a pre-trained model. The dataset comprises original Amazon product <a href="https://drive.google.com/file/d/1Y0NnlPG0CEjHEMp_EPcPR8lXaDI-iyQx/view?usp=sharing">(link)<a> reviews containing various columns like product ID, rating, comments/text, and others, totaling 568,454 rows. The data preprocessing involves cleaning and manipulation through SQLite.</p>

<h2>Project Goals</h2>

<p>The primary goal of this project is to extract sentiments from customer reviews for in-depth product analysis. By utilizing NLP techniques, the project aims to identify key phrases and trends within the reviews, enabling the identification of underlying product issues and trends.</p>

<h2>Challenges Faced</h2>

<p>The dataset encountered several challenges, including a significant skew towards higher ratings, with approximately 80% of the data rated at 5. Additionally, the dataset exhibited seasonality and variability in the time series visualization. To address this, time series techniques such as moving averages were employed to mitigate the effects of seasonality and variability.</p>

<h2>Results and Comparison</h2>

<p>Upon analysis, the pretrained model, RoBERTa, demonstrated superior performance compared to traditional methods. This outcome underscores the value of leveraging pre-trained models, highlighting their ability to capture nuanced sentiments effectively.</p>
