# Crash Landing on Wall Street
## Investigating the Causal Relationship Between Crashes and Market Performance for Boeing 737!
## Authors : Devina Chhajer ( @DevinaChhajer ), Diya Patel ( @Autumn-01 ), Ishika Gupta ( @IshG31 ), Kaitlyn Ho ( @ktho2 ), Tanvi Lamba ( @tanvilamba )
## Authors : <a href="https://github.com/DevinaChhajer"> Devina Chhajer</a>, <a href="https://github.com/Autumn-01"> Diya Patel</a>, <a href="https://github.com/IshG31"> Ishika Gupta</a>, <a href="https://github.com/ktho2 "> Kaitlyn Ho</a>, <a href="https://github.com/tanvilamba"> Tanvi Lamba</a>
  <img href="Github profile image source"> 
</a>  ), Diya Patel ( @Autumn-01 ), Ishika Gupta ( @IshG31 ), Kaitlyn Ho ( @ktho2 ), Tanvi Lamba ( @tanvilamba )

Description: 
Boeing is the leading manufacturer of commercial aircrafts and supplies to majority of the airline companies today. If you are travelling by air, there's a high chance you are travelling in a Boeing aircraft. So, for such a company to have frequent crash incidents, emergency landings and part blowouts is quite concerning. With this project, we are investigating the economic and social impact these kind of incidents have by performing Causal Analysis, Sentiment Analysis and Topic Modelling techniques on the data we collected for 3 specific incidents.

Incidents covered:  
  1. Crash 1: Lion Air Flight 610 on Oct 29, 2018 - no survivors
  2. Crash 2: Ethiopian Airlines Flight 302 on Mar 10, 2019 - no survivors
  3. Incident 3: Alaska Airlines Flight 1282 on Jan 5, 2024 - door blowout
     
Datasets: 
The merged_dataset that can be found in the 'Data' folder is an excel workbook consisting of data scraped from Boeing website, Government(FAA, Federal Aviation Association website), online news publications and social media (Reddit and Quora) articles, Stock data from Yahoo Finance (using yahoo finance library in Python), financial data (Revenue and EBIT, from the Annual Reports of Boeing and Airbus) and orders and cancellations (from the Boeing Website) data. We scraped the social media data using the google chrome extension scraper.io.

Code Files: 
There are 2 code files and 1 html file in the 'Code' folder. 
  1. File "Final_Code (latest)" is a python notebook consisting of all the analysis done so far on the dataset. It is best run on Google Colab.
  2. File "Ethiopian_Airlines_Vader_Score" is a R file consisting of the code for calculating the vader scores for public sentiment analysis on Crash 2. An html file with the same name can also be found.

Blog:
We have posted a blog on Medium, giving an overview of the study and explaining our interpretations for each analysis. Following is the link to the blog.
Link --> https://medium.com/@devinachhajer24/crash-landing-on-wall-street-9e8d11cc8bc5
