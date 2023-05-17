# Event-Extraction-from-Tweets

This repository contains code for extracting events from tweets using Named Entity Recognition (NER). The goal is to identify and classify specific events mentioned in the tweets. The code is implemented as a Flask API, allowing users to interact with the event extraction model.
I have used 2 datasets. One larger(234MB) another smaller(1.54MB).
Dataset links:
https://drive.google.com/file/d/1MJzDAArvN5_sCTqqmyyQRE7--sR2ygRA/view?usp=share_link

https://drive.google.com/file/d/1vs-tJM7hN9YPyLlB25Gil4e2RTO5_Lch/view?usp=share_link

To run the code in the Jupyter Notebook file Event_Ext.ipynb, follow the instructions below:
Clone the repository:
git clone https://github.com/Shubhendra284/Event-Extraction-from-Tweets.git
cd Event-Extraction-from-Tweets

Install the dependencies:
Ensure you have the necessary dependencies installed. You can install them using the following command:
pip install -r requirements.txt

Download the dataset:
Place your tweet dataset in CSV format as tweets.csv in the project directory. The dataset should contain a column named "text" that contains the tweet texts.

Launch Jupyter Notebook:
Launch Jupyter Notebook using the following command:
jupyter notebook

Open the Jupyter Notebook file:
In the Jupyter Notebook interface, navigate to the cloned repository directory and open the Event_Ext.ipynb file.

Run the code cells:
The notebook is divided into cells, and you can run each cell individually by clicking on it and pressing Shift + Enter. Make sure to run the cells in sequential order as some cells may depend on the output of previous cells.

Follow the code instructions:
The notebook provides instructions within the code comments to guide you through each step of the event extraction process. Make sure to read the comments and execute the code accordingly.

By following these steps, you should be able to run the code in the Jupyter Notebook and perform event extraction from tweets.
