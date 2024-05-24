# Sentiment Analysis on the 2020 presidential elections using AWS

## Data
Kaggle dataset link: https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets?resource=download

## Architecture:
This is the architecture for monitoring and analyzing social sentiments in real-time using AWS, specifically focusing on the Twitter dataset for the 2020 presidential elections. This architecture incorporates Amazon SageMaker, Amazon S3, Amazon Comprehend, and Amazon QuickSight for a comprehensive solution.
1. Twitter Dataset on Amazon S3:
The Twitter dataset for the 2020 presidential elections is stored in Amazon S3. This highly scalable and durable object storage service serves as the central repository for the raw Twitter data.
2. Amazon Comprehend for Sentiment Analysis:
The textual content of tweets is processed through Amazon Comprehend, a natural language processing service. Comprehend performs sentiment analysis, classifying each tweet into sentiment categories (positive, negative, neutral) and providing an overall sentiment score.
3. Amazon SageMaker for Customized Model Training and Deployment:
Amazon SageMaker is utilized for custom model training and deployment. This involves developing machine learning models tailored to the nuances of the Twitter dataset, enabling more accurate sentiment analysis. The trained models are deployed on SageMaker for real-time processing of incoming tweets.
4. Amazon QuickSight for Real-time Visualization:
Amazon QuickSight is employed for real-time visualization of sentiment trends. QuickSight creates interactive dashboards and reports that provide stakeholders, such as political analysts and campaign strategists, with up-to-the-minute insights into the changing sentiments expressed on Twitter during the 2020 presidential elections.
