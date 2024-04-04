# Google-Data-Analytics-Capstone-Project

Case study: How does a bike-share navigate speedy success?
Imagining myself as a data analyst working on the marketing analyst team at Cyclistic, a bike-share
company in Chicago. This is an opportunity to analyze historical bicycle trip data in order to identify trends. Understanding how casual riders behave differently from riders with paid memberships is important. This analysis will help executives to make decisions about marketing programs and strategies to convert casual riders to riders with annual memberships. The director of marketing believes the company’s future success
depends on maximizing the number of annual memberships. Therefore, our team wants to
understand how casual riders and annual members use Cyclistic bikes differently. 

1. Business Task: How do annual members and casual
riders use Cyclistic bikes differently?

2. A description of all data sources used:
The datasets have a different name because Cyclistic
is a fictional company. The data has been made available by
Motivate International Inc. under this license https://divvybikes.com/data-license-agreement. Data-privacy issues
prohibit me from using riders’ personally identifiable information. This means that I won’t be
able to connect pass purchases to credit card numbers to determine if casual riders live in the
Cyclistic service area or if they have purchased multiple single passes.

3. Documentation of any cleaning or manipulation of data:
   At first I tried to use excel for the analysis, I was able to download the data to my icloud Drive in the laptop for the first 2 months of Cyclistic data; afterwhich the data became larger and larger and hence resorted to using the BigQuery tool; even then importing was not easy; creating  a bucket in big query which helped me combine data from multiple files into a single file and hence I was able to download large dataset in BigQuery in no time. At first I checked for missing values and duplicates; the data had a lot of missing values with regard to start and stop station id and therefore was left out of my analysis. No personal information was available and hence majorly focussed on timestamps and durations to analyse if casual riders and member riders differed in any way?

4. A summary of my analysis
   The next task was to be super curious with my dataset- ensuring I was at par with the business task at hand. After I checked for duplicates and missing values I was able to select the columns I needed; timestamps helped me arrive at trip durations between the two rider community - average duration for the members was 12.40 minutes whereas for casual riders it was 25.92 minutes. I was curious to explore the usage for weekdays and weekends - it seemed that casual riders used primarily for weekends whereas member rider used it for work; this was also supported when peak times for both the communities were explored. Member riders used the most around 8:00 am and 5:00pm. When exploring during the seasons winter months were low for both the rider communities. 
5. Since data was summarized using averages and sum , 7 million dataset was compressed and excel was used to visualize the dataset.
6. My top three recommendations based on the analysis: Two slots of free minutes upto 30 minutes per ride to casual riders would help us convert to member riders. Secondly joining during winter months - fees could be lower as that would increase the subscription revenue from casual riders. Thirdly member riders get cyclistic merchandise for completing a year  with us.
