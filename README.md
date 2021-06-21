Table of Content
================
* [Climate_Speeches](#Climate_Speeches)
  * [Description](#description)
  * [Datasets](#datasets)
  * [Results](#results)
  * [Installation Requirements](#installation-requirements)
  * [Licensing](#licensing)
  * [Author](#Authors)

# Climate Speeches


## Description
This is a project developed at the CRI Université de Paris in the second semester of the Master of Digital Science, within the Challenge Hub program. the project is the sentiment analysis of 16 speeches delivered by the famous activist greta thunberg, who has given speeches in different places, with different audiences.
In addition, the analysis of each of the speeches will be made to see if they are positives or negatives and all those are based on opinions or facts. the speeches were realized in 2018, 2019 and 2020.
It is clarified that they are not all the speeches made by the activist in those years.

## Datasets
The dataset is developed by me, I base myself on the book "No one is too small to make a difference" and the article "[Greta Thunberg – the future speaks](https://www.environmentshow.com/greta-thunberg-speeches/)" to do so the data was taken and for the part of the transcriptions it was done three different ways: first the articles where the transcripts of the speeches, second for those who do not have a transcription in an article, the transcription option of the page [youtube](https://www.youtube.com/)  was used and if this was in the book it was compared with the text of the book, for which it was not verified that the transcription is as accurate as the speech itself.

* Speeches.csv

Columns in the datasets:

- `Title`: Title of the speech.
- `Event`: identifies the event of the speech.
- `Location`: the city on the Earth's surface.
- `Date`: the date of each speech.
- `Link Video`: identifies the link video of the speech on the platform  [youtube](https://www.youtube.com/) 
- `Trascript from`: it is the link to the webside of the trascription of each speech. 
- `Script`: it is the trascription of each speech. 
- 
## Results
The first part of the project cleans the column of the transcription of 18 speeches, of which 5 are from the year 2018, 9 from the year 2019 and 2 from the year 2020. For this, the repetitive and worthless words were eliminated to be able to count, analyze, to this will have two final results shown below:

<img src="image/leaf_words.png" width="600"/>
Inside the graph of the leaf, it has the most repeated words in the 16 speeches by repetition ranking, the "lemmatized" technique was used, the results are:
climate, people, year, crisis, emission, change, world, need, time, future.

<img src="image/sun_words.png" width="600"/>
Inside the graph of the sheet, it has the roots of the most repeated words in the 16 speeches by repetition ranking, the "stemmed" technique was used, the results are:
climat, peopl, year, chang, need, crisi, emiss, us, world, polit.

Comparing the two graphs shows us that the results in the ranking change, leaving words like: time, future, but including the root of the word polit.

Now, in the second part we want to solve two questions, if the speeches are based on facts or opinions? and you have the perseption by the news that greta's speeches are negative, then the serious question are the speeches positive or negative?

Polarity: How positive or negative a word is. -1 is very negative. +1 is very positive.
Subjectivity: How subjective, or opinionated a word is. 0 is fact. +1 is very much an opinion.

As you can see, there is a graph with the titles of the speeches on two axes.
the X axis is the one that shows whether the speeches are positive or negative, the Y axis is the one that shows whether each of the speeches is based on opinions or facts.

As you can see of the 16 speeches, only one has more opinions than facts, all the others are below 0.5, which shows that they are mainly based on facts.
on the other axis if the story is different, since the polarity of the 16 speeches is more varied, of which 5 are negative, one can be considered neutral "Save the World by Changing the Rules" and 11 are positive.

As can be seen in the graph, most of the negative speeches occurred in 2018, this may be due to an evolution in the elaboration of the speeches and, therefore, it should be understood that the result sought is to commit actions to the leaders of the most industrialized countries.

Now, an additional analysis can be done with all the speeches and it is to divide them to make an analysis in their parts in their polarity. what was found is very interesting, despite the fact that the speeches have the same objective and present the same arguments, the speeches are not the same and have their own dynamics.
Therefore, most have changes between negative and positive parts, there is only one exception "You are Acting Like Spoiled Irresponsible Children" which is positive all the time.

## Installation Requirements
- Download Zip
```
Code - Download ZIP
```

- Clone this repository with this command
```
git clone https://github.com/Eli-2020/climate_speeches.git
```
- Install the project dependencies run pip install -r requirements.txt
```
pip install -r requirements.txt
```
- Requirements includes:
```
pandas == 1.2.4
plotly==4.14.3
```

## Licensing
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Author:

* **Eliseo Baquero** [@Eli-2020](https://github.com/Eli-2020)
