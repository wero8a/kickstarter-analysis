# **Kickstarting with Excel**

## Overview of Project

Louse needs more information after her play "Fever" nearly reached its goal quickly. 
She wants more information in order to continue having successful campaigns.

### Purpose

This analysis is to demonstrate how campaigns turned out in relation to date launched and funding goals.	

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

First, a "Years" column to the data provided in Kickstart sheet![image](https://user-images.githubusercontent.com/110706169/185146816-fa021de5-6360-48a8-b315-4b77585d9612.png) was added to find the requested analysis.

Then, a pivot table was used to filter by years and theater category. In this case we wanted to count the successful, failed, and cancelled campaigns by Launch Date.

![image](https://user-images.githubusercontent.com/110706169/185149928-18c7f933-db2d-4112-8e4d-4ca0697fbb63.png) &nbsp; &nbsp; ![chart](https://user-images.githubusercontent.com/110706169/185146006-6a4185e6-4cde-4548-a4e6-651a215fdbc8.png)

With the information in the Pivot Table we created a line graph(shown above) to display our final data.

### Analysis of Outcomes Based on Goals

First, we set our dollor-amount ranges  to find how many **plays** are in each category.

![image](https://user-images.githubusercontent.com/110706169/185154735-50ba355b-c229-4c5f-826e-1fe351ec064b.png)

We use the **_COUNTIFS_()** function to filter by goal amount, successful/failed/cancelled, and plays.

![image](https://user-images.githubusercontent.com/110706169/185155582-194912ce-5d8e-4741-be83-088c03a3f209.png)

Once we filtered our data using **_COUNTIFS_()** our table fills with data and we determine the percentages of successful/failed/cancelled campaigns.

![image](https://user-images.githubusercontent.com/110706169/185157668-626408d8-a43b-498e-b12f-925db56035d6.png)

To show a visual representation we created a line graph.

![image](https://user-images.githubusercontent.com/110706169/185159264-fc4cf4e7-9e82-4700-9a95-978285953b96.png)


### Challenges and Difficulties Encountered

While working on the outcomes based on Goals, I had to check multiple times if my data was correct and made sense. I would go back to the Kickstarter sheet and manually filter the data to verify that some fields were correct. The percentage cancelled is a great example, since its all 0's, I had to go back and double check. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  Based on the outcomes from **Launch Date** we concluded that the best date to launch a theater campaign is between May and July; the worst time to start a campaign is most likely December. On October there are  0 cancellations throughout the years, but failed campaigns spiked.

- What can you conclude about the Outcomes based on Goals?

  Based on the outcomes from **Goals** we concluded that campaigns that are $5000 or less are much more likely to be successful. Plays costing between $40,000 and $45,000 are also successful to a certain degree but sample is too small.
  
- What are some limitations of this dataset?

  This study has potential limitations. Some of the estimates in the outcomes based on goals are vey small sample sizes and are subject to biases.

- What are some other possible tables and/or graphs that we could create?

  Outcomes by country may help us determine the best place for a campaign to be successful.
  
![image](https://user-images.githubusercontent.com/110706169/185178600-7bac7983-e571-4744-bd14-6a66ba180158.png)
