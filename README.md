## Saudi Mood: 
	Real-time visualization of people emotions around the world through sentiment analysis of Twitter data

![alt text](https://github.com/Tahani2015/5Vs/blob/master/8.ProjectDiagrams/SaudiMood%20Website.png "Logo Title Text 1")
							

## Team Members:
	Tahani Almanie | Alanoud Aldayel | Ghaida Alkanhal | Ruba Althunayan | Manal Almutlaq | Lama Alesmail 
 
## Project Objective:
Nowadays Twitter is considered as an expressive platform where people’s thoughts and emotions can be reflected by their tweets. Although there are huge interests, studies and applications of Twitter data analysis, there is still a shortage of applications in analyzing Arabic Tweets. In particular, there is an absence of informative tools that can show how people in Saudi Arabia are feeling according to their tweets taking into account the different dialects. “Saudi Mood” is our proposed solution for the above problem. It is a web-based application aims at providing a real-time visualization of people emotions from different Saudi cities based on mining their current tweets’ text and emojis taking into consideration their different dialects. In order to achieve this solution, we have to apply the following steps:
  1) Creating a dataset of Arabic emotional words taking into account the different Saudi dialects.
  2) Streaming Arabic tweets of Saudi Arabia from Twitter.
  3) Applying sentiment analysis techniques in order to classify the tweets into the relevant emotion (happy, sad, angry, scared,   surprised) based on the dataset.
  4) Visualizing the results through an interactive colorful map of Saudi Arabia in which colors of cities are changing according to the  common emotion.
  5) Presenting the associated trend hashtags for each city along with some related interesting statistical charts.

## Project Tools:
	* Data Source: Twitter Streaming API, PubNub
	* Database: MongoDB
	* Programming Language: Python 3 , Javascript , HTML, CSS, jQuery
	* Visualization: TopoJSON, amChart, CanvasJS
	* Cloud Computing Services : mLab, Bluehost
	* Required Libraries: Twython, NLTK, pymongo 

## Research Paper
  * This project has been presented in the 21st Saudi Computer Society National Computer Conference (NCC) which was conducted on 25-26 April 2018 in Riyadh, Saudi Arabia.
  * This project has been puplished in IEEE Xplore on 31 December 2018 
  * If you are interested, you can find the paper here https://ieeexplore.ieee.org/document/8593165
  
## Project Dataset:
Our dataset is considered as a lexicon or dictionary of different emotion terms used in Saudi Arabia. It has been created manually and consisted of more than 4000 Arabic words taking into account the different Saudi dialects in addition to a set of expressive emojis. The dataset is divided into five categories, each of them represents an emotion and contains words that reflect that emotion. We categorized them into (happy, sad, angry, scared and surprised). The dataset was aggregated from multiple resources. The first resource was Crowdsourcing which is a combination of the words 'crowd' and 'outsourcing'. Crowdsourcing is the process of involving a ‘crowd’ or a group of people for a common goal such as problem solving and supported by social media and Web 2.0 . We created a form and distributed it via social media to Saudi users, asking them to express their emotions using their different dialects. We received 618
responses and collected their words in the dataset. We also used the Almaany Arabic lexicon to collect the Modern Standard Arabic words. The third resource was by reading different tweets on trending hashtags in Saudi Arabia to see which words and emojis people use to express their emotions towards specific events. In addition, for each written word in the dataset, we tried to extract all its possible derivatives. A sample terms from the created dataset is shown here:
![alt text](https://github.com/Tahani2015/5Vs/blob/master/8.ProjectDiagrams/Dataset.jpg "Logo Title Text 1")

	* If you are interested in this dataset, you can download it from here:

## Copyright:
#### Please cite the dataset using the following reference:
	T. Almanie, A. Aldayel, G. Alkanhal, L. Alesmail, M. Almutlaq and R. Althunayan, "Saudi Mood: A Real-Time Informative Tool for Visualizing Emotions in Saudi Arabia Using Twitter", 21st Saudi Computer Society National Computer Conference (NCC), 2018. 

## Contact:
 	If you need to get in touch with us: Talmanie@ksu.edu.sa
 
	
