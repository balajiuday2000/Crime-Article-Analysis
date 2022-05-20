# See Jane - Crime Article Sentiment Analysis

## Contact
* Meredith Conroy
* meredith@seejane.org

## Organization
* See Jane | The Geena Davis Institute on Gender in Media
* https://seejane.org/ 

## Organization Description
Founded in 2004 by Academy Award Winning Actor Geena Davis, the Institute is the only research-based organization working collaboratively within the entertainment industry to create gender balance, foster inclusion and reduce negative stereotyping in family entertainment media.

## Project Type
Data Science

## Project Description
_What is the high level goal or purpose for this project?_

See Jane is working in partnership with a news organization to analyze 7,000 print news articles about crime in order to identify racial bias. The goal of this project is to extract the descriptions of victims, alleged perpetrators, and officers from the articles. 

After extracting the descriptions from the article, perform exploratory analysis on the data to determine the types of victims, perpetrators, officers, and crimes written in the articles. 

## Data Sets & Sources
_Links to data sets e.g. APIs where data will be sourced from, folders/ files in the google drive that we were given, links to sites to be scraped, etc._

The data set consists of 7,000 print news articles which will be provided to the students. The data is reportedly recent (mostly within the past three years) so scraping the articles should hopefully proceed without complications. 

The provided dataset should be more than enough for the scope of the project, as a major focus will be cleaning the provided data for use in extraction and analysis. Our partner wants to identify data of cases and work in three-month chunks from 2019-2021.

## Suggested Steps
_Steps to complete the project including data collection, data cleaning/ processing steps, and analysis_

* Data Cleaning 
  * The collected data sources have a small range of collection (2019-2021)
  * Any website layout changes should not have a significant impact on data cleaning process
* Extract descriptions of victims, alleged perpetrators, officers 
  * Named Entity Recognition 
* Data Analysis
  * Sentiment analysis
  * n-grams
* Report preliminary conclusions 
  * Any patterns, trends, or other insight that can be gleaned from a high-level analysis of the results that the partner can add to their report

## Questions to be answered in Analysis
_Very specific questions that the clients wants answered - maximum of 5_

Who is being mentioned in crime coverage? 
* Identify the types of victims, alleged perpetrators, and law enforcement mentioned in the articles.
  * Can include their identities (gender, race, age, income, education etc.) 

What types of crimes receive the most coverage? 
* Identify the types of crimes mentioned in the articles.

How are specific groups being covered? 
* Tone
* Descriptive adjectives etc. 

If locations are included in the articles, where is crime coverage taking place?
* Mapping/visualization may be interesting since we have data from three stations/locales

Are there any noticeable trends in headlines? Do certain areas of the US have more articles than others? 
* It may be interesting if headlines contain any prominent patterns (e.g., people of color having more sensational headlines, how is race used in headlines, is there more crime in specific states, etc.)

## Ideal Output + Final Deliverable
_What does the client want in-hand at the end of the semester? What format would the client like the final report in (word, ppt)?_

The final deliverable off the project will be a CSV (Excel or Google Sheet) with descriptions of victims, alleged perpetrators, officers, extracted from the print articles, and potential article level data, such as tone, or other text analytics. 

The partner has a deadline to report their analysis of the new data by the end of April, so delivering the new data to them sometime before then (possibly middle of April?) would be preferable.

If time permits, a report on any preliminary conclusions we can draw from the data would be helpful to the partner, but they understand if we cannot provide this.

## Limitations
_Identify / list limitations with data and potential risks of achieving project goal_

Cleaning data may not always be "clean"; depending on the layout of a news article and the quality of its website (assuming all data consists of web articles), it may be difficult to clean the data efficiently. However, we will strive to clean as efficiently as we can for as much data as possible; the sheer number of 7000 articles gives us a lot to work with, and we hope to provide ample data for the client to work with. 

With that said however, because there is so much data to clean and work with, our primary focus will be to clean, extract, and analyze the data and provide this information in an easy to navigate CSV for the partner to use in their own report. Depending on a variety of factors, we may not have time to write a report about what we can draw from the data. If we do have time though, we will try our best to report what we can find in a well-explained and well-organized manner for the client to accompany the CSV.

One more note is that any analysis done on our end may not necessarily be up to the client's standards -- studying racial bias is not our forte, so we can only provide conclusions strictly based on the data and other general trends at most. We will strive to do our best, but our top priority is providing the CSV as described above in the deliverable section.

## Additional Information
_Other relevant information including links to previous work if this is a project continuation_

