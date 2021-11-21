<h1> Summarize your data. </h1>
 
<h2> Description</h2>

I had made an interactive web app so as to summarize your data

You will be given an option to choose number of lines, if you choose number of lines more than required lines error will be shown
<br>
<h2> LIVE LINK : https://summarize-data-by-vipul.herokuapp.com/ </h2>
<br>
 <h2>Concepts used</h2>
 
- Preprocessing using NLTK.
- Vectorization and Cosine similarity.
- Ranking of sentences assigned by similarity matrix and then sort the matrix in order to get top sentences.
- Output text using NLTK.

<br><br>
<h2> Dataset for testing </h2>
I picked few lines from : https://en.wikipedia.org/wiki/Text_(literary_theory) and then used the concept of text summarization on that data.
<br>
<br>
<h2> FLOW CHART </h2>

![WhatsApp Image 2021-11-21 at 21 00 42](https://user-images.githubusercontent.com/56962974/142768296-a63ef3e1-fbc5-4f9e-ae6a-ad1b514ab4a9.jpeg)


<br>
<h2> Dependencies</h2>

For this project, the following tools were used:
- [NLTK](https://www.nltk.org/) To preproces data for vectorization
- [Numpy](https://numpy.org/) for working with arrays
- [Matplotlib](https://matplotlib.org/) for visualizing the data
- [Flask](https://flask.palletsprojects.com/en/1.1.x/) for implementing the server side

<br><br>
<h2>IO Screenshots</h2>

![image](https://user-images.githubusercontent.com/56962974/142768305-4af96d7d-ce32-4c15-9c98-848cf1b4c182.png)
![image](https://user-images.githubusercontent.com/56962974/142768338-5eea948b-6a70-48ac-97dd-cd403e8899bc.png)
![image](https://user-images.githubusercontent.com/56962974/142768374-b5eb346f-b136-47e1-bb14-0ec39a0fabbc.png)


<br>

<h2> Install and run on local host</h2>

<h4>To install and run local host:</h4>

```bash
git clone https://github.com/Vipul1947/summarize_data_by_Vipul.git
cd summarize_data_by_Vipul
pip install -r requirements.txt
python app.py
```
