<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

Final project for the Building AI course

## Summary
In the nordics it can be difficult to get enough vitamin D from the sun during the winter periods. The AI project is about creating an app that will help the user get more sun exposure in order to make sure they get enough vitamin D. 

## Background

Vitamin D deficiency is one of the most common medical problems in the world. Getting it from our diet is not enough is not sufficient comparing to the recommended levels. Vitamin D has a big role in our body and is most known for it's role in the bones but symtoms such as fatigue and getting sick easily is also common. Furthermore, one can think that sunlight exposure is bad and it might not be worth it due to it being associated with aging, wrinks and skin cancer. Therefore, it's important to always wear sunscreen and if possible sunglasses (and a hat). By using AI we can for instance make sure that the user is not outside when the sunlights are too strong and when the chance of sunburn is high.

## How is it used?

The AI app will ask the user how much vitamin D the user wants and how much time the user is willing to be outside. Also, it will also ask during which time of the day the user can be outside and what parts of the body is exposed to the sun such as face, hands and/or legs. Then it will suggest a time of the day the user should be outside and for how long. Also, it will also record the user when it's outside to see how much the user is exposed to the sun. The solution is for everyone who wants to get a better understanding of their vitamin D levels, sun exposure and who want to control control their vitamin D levels.

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?


## Data sources and AI methods
The data will be collected directly from the user and also throughout using the AI app it will collect GPS data from the user. Also, data about the weather such as when the sun is up and down, UV index and data about how clear the sky is. Also, data about daily recommended vitamin D intake will be taken from livsmedelsverket.se

Linear regression and optimization algorithms could be used to analyze the data from the user and weather to give a recommendation to when it's best to be outside for sun expsoure. Also a normal distribution could be created from the data from the user when they are outside and another normal distribution from when the uv index. From these distributions a Confidence interval could be calculated from the preference of the user of how much exposure and when they are likely outisde to give a suggestion when they should be outside. 

Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

Every user is unique and some user are more tolerant to sun exposure and needs to be longer outside while others are less tolerant and can easily get sunburnt. Therefore, the AI apps suggestions to the user when they should be outside might not be the best for them and also a lot of users might not be outside when the sun is up due to e.x. working, studying or simply busy. Also, it's impossible for the AI app to know the users vitamin D levels if the user hasn't checked their blood levels. Also, sunlight exposure can be a potential risk to the health and the app might be better served as an useful information app for the consumers


## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
