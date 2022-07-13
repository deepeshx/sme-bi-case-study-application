# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The goal of exercises in case study is for learners to apply what was learned in the previous courses to new problems or situations. This is best pedagogical practice for retaining and building skills.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/case-study-analyzing-customer-churn-in-tableau/exploratory-analysis-1?ex=4) from the Case Study: Analyzing Customer Churn in Tableau. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners in **case studies**.

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder - Added

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course. - Added `ex-1-intial.pbix`
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix` - Added `ex-1-sol.pbix`

#### Learning Objective

This Exercise is coming from Chapter 2 Lesson 2.3 - Top N Analysis. 

This exercise will emphasize on finding top 5 manufacturers generating most revenue across the regions. This scenario will be explained with a "Top N filter" as well as dynamically with a "Q & A" feature.

#### Context

This analysis is pivotal to answer who are the top manufacturers and how your manufacturer is performing against the other top competitors. 

You will be analysing and comparing the sales of your manufacturer against the other top competitors which are there in the market to understand and see that in which region the other competitors are performing well and in which region you need to take action to increase the sales.

You will be performing this exercise first by creating the visualization and applying a Top N filter. Then, you'll learn how easily same can also be accomplished using Q & A feature where as a business user you'll ask question in plain English and get output in form of visualization.


#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Create a Stacked column chart by taking Revenue in Y axis, Country in X-axis and Manufacturer in Legend section.
- From the Filter Pane, open Manufacturer Filter and write "5" in Show items section and drag Revenue in "By Value" section.
- Under the Visualizations pane, click on "Format visual" section and turn on Data Labels and Zoom Slider ability. This will make it easier for business users to read the data.
- To use Q & A feature, click on "Insert" from the top ribbon and select Q&A. Inside the text box the visual, write "Top 5 manufacturer revenue by country as Table".
- Once you have the desired result from Q&A, click on the icon "Turn this Q&A result into a standard visual", next to the text box of the visual.

#### Exercise question:

What is the total Revenue of the manufacturer "Natura" in Germany?

- a) $ 1,797,817.97
- b) $ 4,245,223.23
- c) $ 6,504,796.70
- d) $ 1,134,042.52

Answer - b)

#### End goal:

![ex-1-sol](https://user-images.githubusercontent.com/22573283/178680920-1afc13c1-3116-4d74-97a6-cef809d4ae5a.jpg)

## Finalized Workbook

#### Files
You can upload your final workbook in the exercises folder as `ex-final-sol.twbx` or `ex-final-sol.pbix`. 
- Uploaded `ex-final-sol.pbix`

#### Explanation & Description
Which answers will the learner be able to solve once building this? How does it fit in the bigger picture?

- Following a real-world business use-case, students will apply the concepts of data warehousing and visualization. 
Through Power BI and Power Query, complete ETL process starting from data integration from multiple sources. Then using Power Query Editor, data transformation, and then data modelling using concepts of DAX and building relationship. 

- Learners will be doing a sales and market share analysis. This type of analysis is very useful for a Chief Marketing Officer (CMO) and is focused not only on the company’s performance internally reflecting on how well do the products sell but also externally analysing how well they are doing against competing manufacturers. 

- After completing this course, the learners will be introduced to a lot of capabilities of Power BI and will also learn and explore many important business scenarios to analyse the sales by doing Competitor Analysis, Top N analysis and Trend analysis.  Thus, enabling the business users to take informed decisions and actions out of the data.


#### End goal:

![Final Report](https://user-images.githubusercontent.com/22573283/178680963-521c7562-1be5-4376-bbad-e579fe4d92f9.jpg)

