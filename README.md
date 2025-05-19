# HR Survey Analysis

## The Situation
You've just been hired as a Human Resources (HR) Associate for the Seattle Department of Public Works.

## The Assignment
The city recently surveyed ~1,500 public works employees to measure job satisfaction and identify opportunities to keep staff motivated and engaged.
You've been asked to analyze the survey response data, and prepare a visual summary for the HR leadership team.

## The Objectives
1. Explore and profile the data to correct any quality issues
2. Prepare and reformat the data for visualization
3. Visualize the data and identify key insights and recommendations

## The Data Set

#### Employee Survey Responses
Actual responses from an employee engagement survey conducted by Pierce County WA and completed voluntarily by government employees.

#### Recommended Analysis
1. Which survey questions did respondents agree with or disagree with most?
2. Do you see any patterns or trends by department or role?
3. As an employer, what steps might you take to improve employee satisfaction based on the survey results?

#### Objective 1: Profile & QA the data
Your first objective is to explore and QA the data by calculating basic profiling metrics, removing blank and duplicate records, and standardizing inconsistent text fields.

* Calculate the minimum, maximum, count, and number of blanks for each numerical field.
* Remove any records with blank responses.
* Remove any records containing duplicate values across all fields.
* Calculate the count or frequency of each value in the Department and Question fields, and standardize any inconsistencies you find.

#### Objective 2: Prepare the data for visualization
Your second objective is to produce clean source data for visualization by calculating response frequencies and proportions for each of the 10 survey questions.

* Create a new tab named Chart Source, and generate a unique list of survey questions.
* For each question, calculate the count of records associated with each response type (1-4) and the average response, excluding zeros.
* Add new columns to convert the counts into percentages, based on the total responses for 1, 2, 3 or 4.
* Copy and paste the data as values, then sort the questions descending by average response.

#### Objective 3: Visualize the data and summarize findings
Your final objective is to visualize the data using stacked bar charts and Likert scales, and derive insights and recommendations to share with the HR leadership team based on your findings.

* Visualize the percentages as a 100% stacked bar chart, showing the question with the highest average response at the top.
* Update colors to shades of orange or red for negative responses (1,2), and shades of blue for positive responses (3,4).
* Add data labels and remove the x-axis, title and vertical gridlines, then format individual chart elements to improve readability.
* Based on your findings, what insights or recommendations might you bring to the HR leadership team?
* BONUS: Modify the chart to vertically align the bars so that positive responses skew to the right and negative responses skew to the left (you’ll need calculated columns).

#### [Project Link]()