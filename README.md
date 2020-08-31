# Udacity-DAND-communicate-data-findings-project

this project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part,I used Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, I produced a short presentation that illustrates interesting properties, trends, and relationships that I discovered in my Newyork go bike 2019 dataset . The primary method of conveying my findings will be through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.

# Newyork go ford bike 2019
## by Eya Sahli


## Dataset

 Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area.Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States.
In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company.he system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.
For my dataset in this project , I choosed to work on New York Ford Go Bike data . Let's see what we'll find !


## Summary of Findings

 * monthly rides decrease from January to February to follow a steady increase reaching nearly 50000 in September , then decreasing again to approximately 20000 rides in december . this evolution is no surprise , given that weather is a determining factor in whether or not to bike ride , that's why winter and fall seasons registred the lowest number of bike rides along the year.
* the distribution per hour shows that most trips occur at 8 am with a total that depasses 40000 trips , followed by 6pm , 5pm and 7am . these results are no surprise , trips at 8am are more likely trips to school or workplace , meanwhile trips at 5 and 6pm are more likely trips from school and workplace . It is worth noting that the least trips occurs at night between midnight and 4am , which is pretty expected , you can't take a bike trip when you're asleep !
* people tend to take shorter rides , with most rides falling under 10 minutes of duration and under 5 minutes even , the number of trips decreases with duration , which is also pretty expected !
* surprisingly , the vast majority of bikers are male , with a dominating percentage of 70.7% , while women make only 22.8% of total bikers , the rest is not known which is due to missing data or maybe people who do not identify as male or female  .
* as we can see in the histogram above , the least number of trips are taken by the under 20 and over mid 60 , while in between , trips increase and decrease inconsistenly ,with people in their thirties taking the most trips.
* in my analysis , I choosed to set the following values with their respective age range :

Teen : 12-17 , Young adult : 18-35 ,Middle adult: 36-55 ,Old adult: 56-65 , Elderly: 66+ .

it is no surprise that Young adults take the most trips since Young adults tend to be the strongest and the healthiest , what is surprising though , is that Teens take the least trips , which tells me that the majority of these trips are taken more to workforce and even colleges , than high schools
* the number of subscribers is nearly 7 times the number of customers ! I think that this may mean that the vast majority of the users are taking bike trips regularly , which also reinforces my theory that most bike rides are taken to work or college , somewhere we go to on a daily basis !
* customers spend more time on trips than subscribers , interesting !
* that
it comes as no surprise that people would often spend more time outside when it's nice and sunny , the average trip duration is increasing steadily in spring season reaching more than 16 minutes average , to decrease a bit in summer to increase again near september than decrease steadily to december where trip duration doesn't exceed 10 minutes for the whole winter. 
* it seems like we have many outlirs that cause the average trip duration to be extremely high in the early hours of the day , perhaps this data belongs to people who take really long trips and have to wake up early , the average duration is higher in the early hours , around 5am , it decreases maintaining values under 20 minute sall day long .
* middle and young adults spend longer time in trips in contrary to elderly and old adults , which is very reasonable as it is always related to health and strength , to endure such long trips . surprisingly , and even though they make a small portion of the dataset , teens are taking relatively longer trips than others !
* judging by the boxplot above , we can see that there is no huge difference in men and women trip durations , even though females tend to take slightly longer rides.
* as we saw in the bivariate section , teens , followed by middle adults and young adults have the longer trips , but it seems that teens tend to have even longer trips in june and in spring/seasons !
* and while teens take the longer trips in spring/summer seasons , middle , followed by young adults take the longer trips in the early hours , while elderly , teens and older adults take shorter trips at these hours , as i mentioned earlier , this can be related to adults going far to work .
* customers do indeed take longer trips , on the contrary , subscribers trips seem to be consistent and short all year round , sounds like it's the regular everyday trip they take !
* a very surprising turn of events ! females take the longer trips in the early hours , with a duration that reaches 4 hours compared to males' trip durations of nearly on hour and a half ! which can explain the subtle difference in duration we saw in the bivarite section !


## Key Insights for Presentation

my 3 key insights for the presentation are going to be about the distribution of gender and its relationship with trip duration in time , the distribution of usertype and its relation with duration in time , as well as the distribution in age group and its relationship with duration in time.
