# Me and my python machine learning and deep learning code repository projects introduction with internet site link to my kaggle project and dialogflow chatbot. 

Hi, I am Pritam, a data scientist with expertise on NLP and Computer Vision. I was busy working on Artificial intelligence projects in upwork, so I have not uploaded files for long time on github. Recently I have uploaded my machine learning and deep learning projects to this repository that I have done to increase my real experience on artificial intelligence projects. 
In this repository, more of the files are in ipynb format. The projects are on NLP, NLU, computer vision, time series prediction and predictive models in python. 

In the NLU and NLP project, I have done text summarization, entity recognition, intent ranking, topic modeling, used various NLP models like NLTK, devpavlov for NLP and RasaNLU model for NLU. I also trained, saved and loaded models for NLP projects. 

In computer vision projects, I have built a advanced graphics design surveillance system with people recognition and counting,  sophisticated multi layered graphical tracker to track object and people in video and picture file, done a human face emotions recognition project in python and coded a human face generation project using GAN or more specifically DCGAN using Google colaboratory with GPU. 

As a combined project, 
I have coded a speech recognition with NLP and internet data scraping project in pyrhon 3.6. In this project, I have used python to download YouTube video and automatically converted it to audio and the applied speech recognition on the audio file. Then I have summarized the total speech to text data with conditioned mentioned as for the lines in summarized data. Then I have applied some correction and language conversion from English to bengali on the summarised data. At end, I have used two types of sentiment classifier in python to do advanced sentiment and subjectivity on the summarised data in English. 

Also, in this repository, I have added various machine learning models code with variety in each type of model, csv data wrangling project and pyspark big data project for movie ratings prediction and recommendation.  

In this repository, some code instructs that some files needed to be downloaded from internet and how to keep these in required folder to compile the code correctly. 

Also these are assumed that 
- internet connection is on because compile of some of these python code AI projects needs internet connection.   
- python 3.6 and anaconda installed on computer. 
- have the required python libraries installed on computer. 

On kaggle internet site and on github, I have uploaded my python data science project to predict loan data application's 'loan status' for new test data.

kaggle kernel link is- https://www.kaggle.com/pritamcodeai/loan-application-kernel

In this kaggle project, I have done lot of data exploratory analysis and cleaning, missing value processing and data normalization. I have analysed and predicted ptepared data and done a combined sophisticated visualization on the predicted data's 5 metrics and 4 machine learning models. 

the input location of loan application dataset be different in kaggle internet site. the dataset location is- https://www.kaggle.com/pritamcodeai/loan-dataset .

this kaggle project is in python notebook form. please use python jupyter or other python notebook software to open this file.

I have also built an advanced dialogflow chatbot with name-  Company_Receptionist. It is an automated chatbot for booking reservation with sales team of the company data_1. This chatbot works in Facebook messenger, telegram and internet site that works seamlessly in desktop and mobile- internet site and applications. It can also be extended further to work in more platforms. 

Here is the link of the internet sites that you can visit to check my company receptionist chatbot for how it is performing to user input. 

Facebook- 
https://www.facebook.com/Company_Receptionist-183526732531326/?modal=admin_todo_tour 

Telegram- 
https://web.telegram.org/#/im?p=@Company_Receptionistbot 

Internet site- 
https://bot.dialogflow.com/53f15958-8f57-4c94-8b48-117dd7b1c128 


It works as- 


BASIC FEATURE: 

User: Hi 

Chatbot: Hi. 

User: I want to book a reservation with the sales team of data_1 company. Chatbot: For how many clients? 

User: 3 

Chatbot: what is the date of booking reservation? 

User: 5 th december. 

Chatbot: what is the time of booking reservation? 

User: 10 am. 

Chatbot: You have successfully reserved an appointment for 3 clients on Wed Dec 05 2018 10:00.



ADVANCED FEATURE: 

VALIDATION 1:

User: Hello. 

Chatbot: Good day. 

User: How are you? 

Chatbot: Feeling wonderful! 

User: I want to book a reservation with sales team of data_1 company. 

Chatbot: For how many clients? 

User: 3. 

Chatbot: what is date of booking reservation? 

User: 5 th October. 

Chatbot: what is time of booking reservation? 

User: 6 pm. 

Chatbot: You can't make a reservation in the past. Please try again!



ADVANCED FEATURE: 

VALIDATION 2:

User: I want to book a reservation with sales team of data_1 company. 

Chatbot: For how many clients? 

User: - 3. 

Chatbot: What is date of booking reservation? 

User: 5 th December at 6 pm. 

Chatbot: You need to reserve an appointment for at least one person. Please try again!

ADVANCED FEATURE: 

VALIDATION 3:

User: Hello. 

Chatbot: Hi. 

User: I want to book a reservation with sales team of data_1 company. 

Chatbot: For how many clients? 

User: 3. Chatbot: What is the date of booking reservation? 

User: 6th October, at 10 am. 

Chatbot: You can't make a reservation for 2019 yet. Please choose a date in 2018.

This chatbot check for time condition as within the CURRENT YEAR. Although it can be modified, by changing the code in dialogflow code section. 
