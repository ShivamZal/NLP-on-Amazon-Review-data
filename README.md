# NLP-on-Amazon-Review-data

<h1>Sentiment Analysis in Python using Amazon Reviews</h1>

<p>This project focuses on performing sentiment analysis using Python, leveraging libraries such as Huggingface, NLTK, PyTorch, SciPy, and Pandas. It employs two Natural Language Processing (NLP) transformers: VADER (Valence Aware Dictionary and Sentiment Reasoner) and RoBERTa, a pre-trained model. The dataset comprises original Amazon product <a href="https://drive.google.com/file/d/1Y0NnlPG0CEjHEMp_EPcPR8lXaDI-iyQx/view?usp=sharing">(link)<a> reviews containing various columns like product ID, rating, comments/text, and others, totaling 568,454 rows. The data preprocessing involves cleaning and manipulation through SQLite.</p>

<h2>Project Goals</h2>

<p>The primary goal of this project is to extract sentiments from customer reviews for in-depth product analysis. By utilizing NLP techniques, the project aims to identify key phrases and trends within the reviews, enabling the identification of underlying product issues and trends.</p>

<h2>Challenges Faced</h2>

<p>The dataset encountered several challenges, including a significant skew towards higher ratings, with approximately 80% of the data rated at 5. Additionally, the dataset exhibited seasonality and variability in the time series visualization. To address this, time series techniques such as moving averages were employed to mitigate the effects of seasonality and variability.</p>

<p align="center">
  <img src="https://github.com/ShivamZal/NLP-on-Amazon-Review-data/blob/main/1.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p><b>Fig 1:/b>Count of reviews by stars</p>

<p align="center">
  <img src="https://github.com/ShivamZal/NLP-on-Amazon-Review-data/blob/main/2.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p><b>Fig 2:/b>Compound score by VADER which is in the range of -1 to 1</p>

<p align="center">
  <img src="https://github.com/ShivamZal/NLP-on-Amazon-Review-data/blob/main/4.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p><b>Fig 3:/b>Seasonality and randomness issues for a product</p>


<p align="center">
  <img src="https://github.com/ShivamZal/NLP-on-Amazon-Review-data/blob/main/5.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p><b>Fig 4:/b>Moving average smoothing applied for randomness</p>

  
<h2>Results and Comparison</h2>

<p>Upon analysis, the pretrained model, RoBERTa, demonstrated superior performance compared to traditional methods. This outcome underscores the value of leveraging pre-trained models, highlighting their ability to capture nuanced sentiments effectively.</p>

<p align="center">
  <img src="https://github.com/ShivamZal/NLP-on-Amazon-Review-data/blob/main/3.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p><b>Fig 5:/b>Count of positive, negative and neutral sentiments showing a correlation for positive and negative sentiment whereas neutral sentiment is almost flat for VADER</p>

<p align="center">
  <img src="https://github.com/ShivamZal/NLP-on-Amazon-Review-data/blob/main/6.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p><b>Fig 6:</b>Count of positive, negative and neutral sentiments showing a correlation for positive and negative and neutral sentiment's peak at rating 3 is justified for Roberta</p>

<p align="center">
  <img src="https://github.com/ShivamZal/NLP-on-Amazon-Review-data/blob/main/7.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p><b>Fig 7:/b>A small comparison between results of both NLP transformer by a single-random sample</p>

