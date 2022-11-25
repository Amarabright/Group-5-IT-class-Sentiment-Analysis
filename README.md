# Group-5-IT-class-Sentiment-Analysis
This is to show sentiment analytic skills on a .txt file document (Whatsapp)

## *Solving a Problem*:

As a Data Analyst who solves problems with Data, I discovered that there were times people drop questions on Whatsapp group and they were not given immediate response, Other times, the response rate becomes high. As a member of Digital Witch Support Communuity, I had to find a way

In order to know the best time to send messages to the group to receive a response

To know the most active people that are usually online to run to in cases of urgency

To understand the basic tone of the group.

Hence, I thought it wise to carry out a Whatsapp Chat Analysis.

---


WhatsApp data can be used for many data science tasks like sentiment analysis, keyword extraction, name entity recognition, text analysis and several other natural processing languages. But for the sake of this analysis. I will stick with Sentiment Analysis.

For this task, I will be using three main tools: Python, Excel and PowerBI. I will like you to join me on this journey.

---

## *Data Collection*:

Whatsapp data is gotten from the chat. With a smartphone, it is very easy.

Just open the chat on the group,

If you are using an iPhone then tap on the Contact Name or the Group Name. In case you are having an Android smartphone then tap on the 3 dots above.
Then scroll to the bottom and top on Export Chat.
Then select without media for simplicity if it asks you whether you want your chats with or without media.
Then email this chat to yourself and download it to your system.

![EXPORTED CHAT](https://user-images.githubusercontent.com/83390581/203865944-d5b4cb3c-55bd-4540-a40b-fe1965bca24e.png)

---
## Data Preparation and Processing:

The dataset is usually in a .txt document type and will require some processing. This can be done with Excel (Power Query in Excel, or Power Query in PowerBI or some python codes.) I will use Python codes to prepare and import the data.

Now let’s import the data and prepare it in a way that we can use it in a pandas DataFrame:

THE CODES ARE FOUND IN THE JUPYTER NOTEBOOK added in this repository.

![Medium 1](https://user-images.githubusercontent.com/83390581/203865509-9210a685-2082-46d9-b8b7-5de831c8ec70.png)


## Data Exploration:

I explored further into the dataset to get the number of media messages (offer letters in jpg and some voice notes and videos). While downloading the dataset, I downloaded without the media, which is why we have in the dataset a sentence or phrase showing “media omitted”.

To know the number of media files available in the group, we will have to count the number of “media omitted”.



![medium 2](https://user-images.githubusercontent.com/83390581/203865540-a50410ba-cb0d-4831-99f5-b4e968de9877.png)


## Data Visualisation:

With a few lines of code, we got the visualizations below:

![medium 7](https://user-images.githubusercontent.com/83390581/204011319-610a778b-f99b-4f8a-8901-8d41e7c99a2a.png)
![medium 8](https://user-images.githubusercontent.com/83390581/204011424-bcf2aec7-2c9e-41e6-a2e8-d834c0969308.png)

![medium 9](https://user-images.githubusercontent.com/83390581/204011497-1a3aa110-c29d-4f73-be7c-74308cb81969.png)


As a lover of “no-code or low-code”, I decided to use PowerBI and Excel to help those who do not know Python, so they can replicate this project for any Whatsapp chat Analysis.
![Uploading medium 3.png…]()


Next Step: Transform this data into rows and columns. This is done with the python codes above and then converted into an excel file as seen below:

![medium 5](https://user-images.githubusercontent.com/83390581/204013765-b1341828-d154-4a6a-85c1-65588eb82d11.png)

A little transformation was done in Excel to change the Month column to Text and als55555to the Day column to Days of the week. This was done using the TEXT FUNCTION in Excel. We can see below:

![medium 6](https://user-images.githubusercontent.com/83390581/204013790-24783327-f31d-4434-a2ae-99d3f4f592b8.png)


After this, I imported the data into PowerBI and began the analysis. The following were observed:



![GROUP 5 IT SUPPORT REPORT-1](https://user-images.githubusercontent.com/83390581/203865995-5a8da555-8ab3-4967-ad76-d76eaa04d2dd.jpg)
![GROUP 5 IT SUPPORT REPORT-2](https://user-images.githubusercontent.com/83390581/203866000-e82d72fb-f090-45c7-b517-66352ce385d7.jpg)
![GROUP 5 IT SUPPORT REPORT-3](https://user-images.githubusercontent.com/83390581/203866004-075b03f4-0019-4dfe-bb06-78c7fba558e7.jpg)


## Findings:

1. There are a total of 37762 Messages in the group

2. There are 4674 “Number of Media” Shared in the group

3. Number of Links Shared in the group is 2896

4. There were 218 Unique/active persons in the group

5. The Top 10 people in the group are: Ekwutosina, Golden IT class, Nonso IT class, FunmiAde, Lucia Bestlove, Grace Cubana, Goldenjenny, Ama, Blessing Vitalis and Win IT

6. October is the month with the highest Messages (7421 messages), followed by January (5803). While September is the month with the least messages(1278).

7. The general tempo or sentiment in the group is Neutral

8. Congratulations, Upwork and job seem to be some of the most commonly used words. “Media omitted” is also mostly used as it shows the numerous media files that are usually sent to the group.

9. Friday is the day with the highest number of messages(6729 messages), followed by Wednesday (6068 messages).

10. The most active time in the group is 3:10 pm, followed by 9:40 pm. Meaning that the period within this time range promises to be a great window to receive responses when questions are dropped.

Click the link to view the [interactive report](https://app.powerbi.com/view?r=eyJrIjoiMmYxNjhlNDItNGE1Ni00ZDdlLTg4YmUtNWQ0MGNjYTc3NjNjIiwidCI6IjM0ODhhMWU5LTQwNmYtNGMzNS04Yjc0LTkyOGUzNDM5Yzc1MCJ9&pageName=ReportSection) that shows the analysis and findings above.


## Summary:
If you’re still reading to this place, congratulations on being a lover of knowledge.

With the findings from this analysis, I am certain that a lot of people will get value from it and thereafter follow the steps to carry out theirs.

Finally, Thank you for spending time reading this. It means a lot to me.

Take care of yourself, Till my next project.






