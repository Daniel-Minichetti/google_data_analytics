# Course Challenge 1

### 1.

Question 1

Scenario 1, question 1-5

You’ve just started a new job as a data analyst. You’re working for a midsized pharmacy chain with 38 stores in the American Southwest. Your supervisor shares a new data analysis project with you.

She explains that the pharmacy is considering discontinuing a bubble bath product called Splashtastic. Your supervisor wants you to analyze sales data and determine what percentage of each store’s total daily sales come from that product. Then, you’ll present your findings to leadership.

You know that it's important to follow each step of the data analysis process: ask, prepare, process, analyze, share, and act. So, you begin by defining the problem and making sure you fully understand stakeholder expectations.

One of the questions you ask is where to find the dataset you’ll be working with. Your supervisor explains that the company database has all the information you need.

Next, you continue to the prepare step. You access the database and write a query to retrieve data about Splashtastic. You notice that there are only 38 rows of data, representing the company’s 38 stores. In addition, your dataset contains five columns: Store Number, Average Daily Customers, Average Daily Splashtastic Sales (Units), Average Daily Splashtastic Sales (Dollars), and Average Total Daily Sales (All Products).

Considering the size of your dataset, what’s the best way to proceed with the process and analyze steps?

1 / 1 point

**\[ ]Use SQL to process and analyze the data.**

**\[ ]Continue using the company database to process and analyze the data.**

**\[ ]Upload the data, then process and analyze it using Tableau.**

**\[x]Download the data, then use a spreadsheet to process and analyze it.**

Correct


### 2.

Question 2

Scenario 1 continued

You’ve downloaded the data from your company database and imported it into a spreadsheet. IMPORTANT: To answer questions using this dataset for the scenario, click the link below and select the “Use Template” button _before answering the questions._

Link to template: [Course Challenge - Scenario 1](https://docs.google.com/spreadsheets/d/1pIiGuiZ8SZ2xNfXHEIIb5gpX1NNOuKAUbaqtmPh1GUY/template/preview?resourcekey=0-p4GIOWHIaC6wZTvc9HZzyA#gid=0)

OR

If you don’t have a Google account, you can download the template directly from the attachment below.

[Course Challenge Dataset - Scenario 1 - Scenario 1\_ Pharmacy Data - Part 1](https://d3c33hcgiwev3.cloudfront.net/jgOcTMW9S-uDnEzFvfvrYQ_c46ee66727424d2298e2ff73090392f1_Course-Challenge-Dataset---Scenario-1---Scenario-1_-Pharmacy-Data---Part-1.csv?Expires=1698019200\&Signature=iISlGk4oIzYSIt8GblXg1xJQU3flNZC03Fm2T~AFje2LtpLGR2JjAxkBAIm0ckJQuk~Xkc6X~oUI4V1ZIs13xNXtvFSKfVpyCk11W4vSXH~XkuNwjkyDyFGvan3PrAJpBtCeNo8J9xgjkHAo~VpK8rDIJHOW-THs4P8qpyBicqU_\&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

[CSV File](https://d3c33hcgiwev3.cloudfront.net/jgOcTMW9S-uDnEzFvfvrYQ_c46ee66727424d2298e2ff73090392f1_Course-Challenge-Dataset---Scenario-1---Scenario-1_-Pharmacy-Data---Part-1.csv?Expires=1698019200\&Signature=iISlGk4oIzYSIt8GblXg1xJQU3flNZC03Fm2T~AFje2LtpLGR2JjAxkBAIm0ckJQuk~Xkc6X~oUI4V1ZIs13xNXtvFSKfVpyCk11W4vSXH~XkuNwjkyDyFGvan3PrAJpBtCeNo8J9xgjkHAo~VpK8rDIJHOW-THs4P8qpyBicqU_\&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dVuIRwzdTUibiEcM3V1INg_93ac3942fb2e40e9b9fe4fd8b44e22f6_dotted-line-right.png?expiry=1698019200000\&hmac=Nf5uqKVfAs-pRdO8jEex2mwiw1DMEDm9bCuaviJ-yCQ)

Now, it’s time to process the data. As you know, this step involves finding and eliminating errors and inaccuracies that can get in the way of your results. While cleaning the data, you notice that information about Splashtastic is missing for Store Number 15 in Row 16. Which of the following would be an appropriate response?

1 / 1 point

**\[ ]Delete the row with the missing data point.**

**\[ ]Sort the spreadsheet so the row with missing data is at the bottom.**

**\[ ]Replace the row with the average values of the other data points.**

**\[x]Ask a colleague on your team how they've handled similar issues in the past.**

Correct


### 3.

Question 3

Scenario 1 continued

Once you’ve found the missing information, you analyze your dataset. During analysis, you create a new column F. At the top of the column, you add the attribute Average Percentage of Total Sales - Splashtastic.

Fill in the blank: An attribute is a \_\_\_\_\_\_\_ or quality of data used to label a column.

1 / 1 point

**\[x]characteristic**

**\[ ]response**

**\[ ]number**

**\[ ]headline**

Correct


### 4.

Question 4

Scenario 1 continued

Next, you determine the average total daily sales over the past 12 months at all stores. The entire range of cells that contain these sales are E2:E39. Identify the correct way to write your formula.

1 / 1 point

**\[ ]=AVERAGE(E2,E39)**

**\[ ]=AVERAGE(E2-E39)**

**\[ ]=AVERAGE(E2+E39)**

**\[x]=AVERAGE(E2:E39)**

Correct


### 5.

Question 5

Scenario 1 continued

Next, you create a slideshow, which includes a data visualization to highlight the Splashtastic sales insights you've discovered. You’ve reached which phase of the data analysis process?

1 / 1 point

**\[ ]Act**

**\[x]Share**

**\[ ]Analyze**

**\[ ]Manage**

Correct


### 6.

Question 6

Scenario 2, questions 6-10

You’ve been working for the nonprofit National Dental Society (NDS) as a junior data analyst for about two months. The mission of the NDS is to help its members advance the oral health of their patients. NDS members include dentists, hygienists, and dental office support staff.

The NDS is passionate about patient health. Part of this involves automatically scheduling follow-up appointments after crown replacement, emergency dental surgery, and extraction procedures. NDS believes the follow-up is an important step to ensure patient recovery and minimize infection.

Unfortunately, many patients don’t show up for these appointments, so the NDS wants to create a campaign to help its members learn how to encourage their patients to take follow-up appointments seriously. If successful, this will help the NDS achieve its mission of advancing the oral health of all patients.

Your supervisor has just sent you an email saying that you’re doing very well on the team, and he wants to give you some additional responsibility. He describes the issue of many missed follow-up appointments. You are tasked with analyzing data about this problem and presenting your findings using data visualizations.

An NDS member with three dental offices in Colorado offers to share its data on missed appointments. So, your supervisor uses a database query to access the dataset from the dental group. The query instructs the database to retrieve all patient information from the member’s three dental offices, located in zip code 81137.

The table is dental\_data\_table, and the column name is zip\_code. You have written the following query, but received an error when it ran. What is the clause that will correct this query?

`SELECT * FROM dental_data_table WHERE dental_data_table = 81137`

1 / 1 point

**\[x]WHERE zip\_code = 81137**

**\[ ]WHERE\_zip\_code = 81137**

**\[ ]WHERE zip\_code 81137**

**\[ ]WHERE = 81137**

Correct


### 7.

Question 7

Scenario 2 continued

The dataset your supervisor retrieved and imported into a spreadsheet includes a list of patients, their demographic information, dental procedure types, and whether they attended their follow-up appointment. To use the dataset for this scenario, click the link below and select “Use Template.”

Link to template: [Course Challenge - Scenario 2](https://docs.google.com/spreadsheets/d/1tXJvXgUP58iYYSW6tBfiGMD5lJFOgHXvHx2EdDOCxnA/template/preview?resourcekey=0-Ha_b6RzKHJFYElJN20NOyg#gid=0 "Course Challenge - Scenario 2")

OR

If you don’t have a Google account, you can download the template directly from the attachment below.

[Course Challenge Dataset - Scenario 2](https://d3c33hcgiwev3.cloudfront.net/UVdWSYRdQgeXVkmEXaIHXQ_c621f39757c840b6a484589670699cf1_Course-Challenge-Dataset---Scenario-2.csv?Expires=1698019200\&Signature=exfmoyO-Uhc0g4E5ASZinUSUJx7PPAgfz8GUO78v9CHfxFcyWE2tLlChO7k-xrxDKtseukXFTGN7FQ4FsZ76tZgIwAO6BHQu1~7g0u81Z61s7kLQ8L5-Jti9NtyR7b8FmB3YcPtQx6mn5MjG5Bq6AiVAVSDmvU-Wios9fWedVFQ_\&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

[CSV File](https://d3c33hcgiwev3.cloudfront.net/UVdWSYRdQgeXVkmEXaIHXQ_c621f39757c840b6a484589670699cf1_Course-Challenge-Dataset---Scenario-2.csv?Expires=1698019200\&Signature=exfmoyO-Uhc0g4E5ASZinUSUJx7PPAgfz8GUO78v9CHfxFcyWE2tLlChO7k-xrxDKtseukXFTGN7FQ4FsZ76tZgIwAO6BHQu1~7g0u81Z61s7kLQ8L5-Jti9NtyR7b8FmB3YcPtQx6mn5MjG5Bq6AiVAVSDmvU-Wios9fWedVFQ_\&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dVuIRwzdTUibiEcM3V1INg_93ac3942fb2e40e9b9fe4fd8b44e22f6_dotted-line-right.png?expiry=1698019200000\&hmac=Nf5uqKVfAs-pRdO8jEex2mwiw1DMEDm9bCuaviJ-yCQ)

The patient demographic information includes data such as age and gender. As you’re learning, it’s your responsibility as a data analyst to make sure your analysis is fair. Which aspect of patient demographics might get in the way of fairness?

1 / 1 point

**\[ ]The dataset contains patient identification numbers.**

**\[ ]The dataset indicates which dental procedure the patients had performed.**

**\[ ]The dataset represents people who are single.**

**\[x]The dataset includes people who all live in the same zip code.**

Correct


### 8.

Question 8

Scenario 2 continued

As you’re reviewing the dataset, you notice that there are a disproportionate number of senior citizens. So, you investigate further and find out that this zip code represents a rural community in Colorado with about 800 residents. In addition, there’s a large assisted-living facility in the area. Nearly 300 of the residents in the 81137 zip code live in the facility.

You recognize that’s a sizable number, so you want to find out if age has an effect on a patient’s likelihood to attend a follow-up dental appointment. You analyze the data, and your analysis reveals that older people tend to miss follow-ups more than younger people.

So, you do some research online and discover that people over the age 60 are 50% more likely to miss dentist appointments. Sometimes this is because they’re on a fixed income. Also, many senior citizens lack transportation to get to and from appointments.

With this new knowledge, you write an email to your supervisor expressing your concerns about the dataset. He agrees with your concerns, but he’s also impressed with what you’ve learned and thinks your findings could be very important to the project. He asks you to change the business task. Now, the NDS campaign will be about educating dental offices on the challenges faced by senior citizens and finding ways to help them access quality dental care.

Fill in the blank: Changing the business task involves defining a new \_\_\_\_\_.

1 / 1 point

**\[x]question or problem to be solved**

**\[ ]data-cleaning strategy**

**\[ ]gap analysis plan**

**\[ ]graphical representation of the data**

Correct


### 9.

Question 9

Scenario 2 continued

You continue with your analysis. In the end, your findings support what you discovered during your online research: As people get older, they’re less likely to attend follow-up dental visits.

But you’re not done yet. You know that data should be combined with human insights in order to lead to true data-driven decision-making. So, your next step is to share this information with people who are familiar with the problem professionally. They’ll help verify the results of your data analysis.

Fill in the blank: Subject matter experts are people who are familiar with a problem. They can help by identifying inconsistencies in the analysis, offering insights into the business problem, and \_\_\_\_\_.

1 / 1 point

**\[ ]collecting data relevant to the business problem**

**\[ ]redefining the business problem**

**\[ ]creating a presentation with the data**

**\[x]validating the choices being made**

Correct


### 10.

Question 10

Scenario 2 continued

The subject-matter experts are impressed by your analysis. The team agrees to move to the next step: data visualization. You know it’s important that stakeholders at NDS can quickly and easily understand that older people are less likely to attend important follow-up dental appointments than younger people. This will help them create an effective campaign for members.

It’s time to create your presentation to stakeholders. It will include a data visualization that demonstrates the lifetime trend of people being less likely to attend follow-up appointments as they get older.

Which type of chart will be most effective?

1 / 1 point

**\[ ]A pie chart**

**\[x]A line chart**

**\[ ]A doughnut chart**

**\[ ]A table**

Correct
