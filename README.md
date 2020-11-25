# US Election 2020 Shiny App

## A State Level Analysis

### Authors: Kerr McIntosh, David Wright and Conor Power​

For a recent CodeClan showcase event, we came together to work on a group project we felt best demonstrated the skills and techniques we learned on the CodeClan Data Analysis course. 

We decided on a project involving the planning, coding and presentation of a R Shiny app which provided a state level analysis of the 2020 US Presidential Election.

The project took 6 days with all authors working together on it remotely. The app was presented to a diverse audience of potential employers made up of both tech and non-tech backgrounds.


### MVP

It was agreed a simple, tab style app would be developed. It would provide a general state-level overview of the 2020 US Election but also explore some of the typical demographic factors effecting the election and the impact of COVID-19 on the result.


### Data

The data was collated from a number of different sources including the United States Census Bureau and Centers for Disease Control and Prevention. It was pulled and was accurate as of 18/11/2020.


### Tools

We coded in R.

The following libraries were used in creating the app:

`library(tidyverse)`

`library(shiny)`

`library(shinythemes)`

`library(shinyWidgets)`

`library(urbnmapr)`

`library(janitor)`

`library(reshape2)`


### The App (screenshots)

**_Tab 1 - Election Overview_**

![tab1](https://github.com/C-Power1/us_election_shiny_app/blob/master/tab1.png?raw=true)

<br>

**_Tab 2 - State Demographic Factors Overview_**

![tab2](https://github.com/C-Power1/us_election_shiny_app/blob/master/tab2.png?raw=true)

<br>

_**Tab 3 - Influence of COVID-19**_

![tab3](https://github.com/C-Power1/us_election_shiny_app/blob/master/tab3.png?raw=true)

<br>


### Key Findings 

Some interesting findings from the data:

* States who voted for Trump are 50% more likely to have adult residents owning a gun than states who voted for Biden.
* States who voted for Biden are 26% more likely to have residents with a Bachelors level education or higher. 
* States who voted for Biden have a 32% higher unemployment rate than states who voted for Trump.
* Trump won in the majority of states where male population is larger than female population (7 out of 11 states).
* Biden won in all states where there is an above average Hispanic population apart from Texas and Florida.
* States that voted for Biden had nearly double the number of COVID-19 cases than those that voted for Trump.
* States that voted Republican had a higher COVID-19 related death rate than those that voted Democrat - the rate was 1/3 higher.


### Challenges 

In ensuring our delivery of the MVP, we faced a number of challenges relating to time, data and resources. 

**TIME**

Our decision to come together as a group was made on 12/11/2020 and we began work on 13/11/2020 - 6 days prior to the CodeClan data analysis showcase event. All three members of the group had busy schedules and so time working together was scarce and had to planned. 

Our intention was to impress but we also had to keep in mind what would be realistic and achievable in the tight timeframe.

**DATA**

The data had to be cleaned, reformattted and merged in order to carry out meaningful analysis.

When we began our work, the official result of the election was yet to be announced and some states were still being called. This meant we had to ensure our app could be reproducable and take in new data. 


**RESOURCES**

Due to the current global pandemic, we were unable to meet up in person - we would have to work remotely using version control and video conferencing software to support each other effectively.

We wanted to demonstrate the skills and our development since leaving CodeClan so we wanted to do everything from scratch and had limited time.


### With more time...

Due to the constraints of the deadline and scheduling there was a number of things we would like to do have explored/undertaken:

* Investigate social media outlets and their influence within states (text mining).
* Correlation analysis - identifying the particular factors which helped determine how each state voted.
* A deeper exploration of typical demographic factors effecting US elections.








 


