# capstone-design

## Topic
Sentimental Analysis on COVID-19 Headline Keywords

## Data
Crawled 462,567 headlines from [NAVER news](https://news.naver.com/)
- Keywords: '코로나', '우한 폐렴'
- Date: 2020.1.10 ~ 2020.5.14 (126 days)

## Sentiment Lexicon
[KNU 한국어 감성어 사전](http://dilab.kunsan.ac.kr/knusl.html)

## Sentiment Indicators
<img src="images/eq1.PNG" width="250">
<img src="images/eq2.PNG" width="250">

## Data Flow
<br />
<p align="center">
  <img src="images/1.jpg" width="500">
</p>

<br />
<br />

<p align="center">
  <img src="images/2(2).jpg" width="600">
</p>

<br />
<br />

<p align="center">
  <img src="images/3(2).jpg" width="800">
</p>

<br />
<br />

<p align="center">
  <img src="images/4.jpg" width="350">
</p>

## Results
### Keyword Information
<p align="center">
  <img src="graph/Keyword_Information.png" width="800">
</p>

### Sentiment Indicators

<p align="center">
  <img src="graph/Polarity.png" width="400">
  <img src="graph/Subjectivity.png" width="400">
  <img src="graph/Pos_Neg_Indicators.png" width="400">
</p>

### Word Cloud
#### Period
<p align="center">
  <img src="graph/period_1.png" width="160">
  <img src="graph/period_2.png" width="160">
  <img src="graph/period_3.png" width="160">
  <img src="graph/period_4.png" width="160">
  <img src="graph/period_5.png" width="160">
</p>

#### Keywords
<p align="center">
  <img src="graph/wordcloud_keyword_1.png" width="160">
  <img src="graph/wordcloud_keyword_2.png" width="160">
  <img src="graph/wordcloud_keyword_3.png" width="160">
  <img src="graph/wordcloud_keyword_4.png" width="160">
  <img src="graph/wordcloud_keyword_5.png" width="160">
</p>

#### Sentiment Words
<p align="center">
  <img src="graph/wordcloud_senti_1.png" width="160">
  <img src="graph/wordcloud_senti_2.png" width="160">
  <img src="graph/wordcloud_senti_3.png" width="160">
  <img src="graph/wordcloud_senti_4.png" width="160">
  <img src="graph/wordcloud_senti_5.png" width="160">
</p>
