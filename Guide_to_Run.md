#Steps to Run Code
#1. Web Scraping for News Headlines
•	Run news Headlines_Webscrapping.ipynb to scrape Economic Times website for news data.
•	Make sure to install the Beautiful Soup library using pip install beautifulsoup4.
#2. Merging Data
•	Execute merging_data.ipynb to merge the dataset collected from the NSE website for Nifty50 data and the scraped news data.
•	The Nifty 50 dataset is named NIFTY50.csv, and the code will generate a CSV named output.csv.
#3. Fine Tune BERT Model
•	Run LLM_Project_Training.ipynb on Google Colab to fine-tune the BERT model.
•	Install the Transformers library using pip install transformers.
•	For pretraining, use the dataset all-data.csv containing financial news headlines and their respective sentiments.
•	The pre-trained model will be saved on Google Drive.
#4. BERT Inference
•	Execute BERT_Inference.ipynb to perform sentiment analysis on the pretrained BERT model and update the CSV files by adding a feature of sentiment to the dataset.
#5. Train and Test the ML Model
•	Use Machine_Learning_Model.ipynb to train and test the machine learning model.
•	The code includes two case studies for verification.
Make sure to follow the order mentioned above for smooth execution of the code.
