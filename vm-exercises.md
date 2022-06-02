# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The goal of exercises in case study is for learners to apply what was learned in the previous courses to new problems or situations. This is best pedagogical practice for retaining and building skills.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/case-study-analyzing-customer-churn-in-tableau/exploratory-analysis-1?ex=4) from the Case Study: Analyzing Customer Churn in Tableau. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners in **case studies**.

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

*Execute creating a calculated column based on provided columns*

#### Context

*Say Hello to your data.  The same way we introduce ourselves when we meet someone for the first time, with questions like how are you and where are you from? Getting to know our data is critical to performing a great analysis everytime.  In this exercise, we will import our data into power BI, examine the tables and extend the columns we have by creating a calculated column.*

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Get the Crypto_Dim_Names.csv and Crypto_FactTable_Purchases.csv files from the datasets folder.
- Inspect both tables in the “data” view to ensure both imported correctly
- Switch to the “model” view to ensure both are connected with the proper relationship
- Rename these two columns to make them easier to understand: “CURRENT_WORTH” to “CURRENT_PRICE” and “DATE” to “PURCHASE_DATE”
- Create a Calculated Column “CURRENT_VALUE” by multiplying “QUANTITY_PURCHASED” and  “CURRENT_PRICE”


#### Exercise question:
*What is the “CURRENT_VALUE” of the coin with symbol LTC and a “PURCHASE_DATE” of 4/15/2018?
- A. 20.7893421199045
- B. 15.1486365045558
- C. 93.4215691451990
- D. 21.9728650982986
*

#### End goal:

![image](https://user-images.githubusercontent.com/19144732/171630541-45341a31-bb57-408c-af3d-c9ce24367a2e.png)

## Finalized Workbook

#### Files
You can upload your final workbook in the exercises folder as `ex-final-sol.twbx` or `ex-final-sol.pbix`.

#### Explanation & Description
Which answers will the learner be able to solve once building this? How does it fit in the bigger picture?

#### End goal:

*Add an image of the final visualization here.*
