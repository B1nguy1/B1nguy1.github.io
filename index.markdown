---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
date: 2023-05-11
---

<html>
<head>
<style>
body{
    font-family:Arial,sans-serif,
}
footer{
    background-color: slategrey;
    text-align: center;
    padding: 3px;
    color: white;
}
.container:{
    text-align:center,
    position:relative
}
p{
    line-height:24px;
}
</style>
</head>
<body style="background-color:white;">

<div class="container">
    <h1 style="color:black;text-align:center;margin-top:0px;">A comprehensive analysis of reported cases tagged as "Suspicious Person" in San Francisco</h1>
    <p style="color:grey;text-align:center">May 11, 2023</p>
    <p>
    San Francisco is a highly sought-after destination for both tourists and residents due to its many attractions and diverse culture. However, like other cities in the US, the city is not exempt from undesirable incidents. Because of public awareness, many accidents do not reach a tragic end or are reported to the authorities. The fastest way for the general public to connect with law enforcement units is through the 911 line. 
   </p>
   
   <p>
   In this article, we will analyse the 911 calls originating from residents or visitors in San Francisco. Utilizing the San Francisco open source public safety data we will investigate several variables in the data. The purpose of this article is to demonstrate more details behind the dispatched calls and police response, as well as allow the residents to analyse the situation per location. 
   </p>

   <p>
   We will focus on reported cases that were tagged as “Suspicious person”. Why? Because our team has found the term rather arbitrary. Hopefully, analysis can shed some light on the details of the importance and development of such cases.
  </p>
  <p>
   Among all calls that the dispatch centre has received between the years 2016 and 2022, calls for the SUSPICIOUS PERSON were 4th most common calls: 
  </p>
  <img src="visualizations/911_calls.png" alt="Most common 911 calls" width="100%" height="550">
  <h2> Development of 911 cases for suspicious person </h2>
  <img src="visualizations/combined_graph.jpg" alt="Call types combined" width="100%" height="1250">
  <br><br>
  <p>
    The developments of these calls were also investigated. When the call is received, a dispatcher defines the call type such as “Suspicious person”, however the at the end of the incident a more accurate and final description is prescribed. The graphs above demonstrate the by far most of the call keep their initial description, hower other common categories are “Homeless complaints”, spotting of “Mentally disturbed” or “Trespasser”.
  </p>
    <h2>Case distribution heatmap</h2>
    <embed type="text/html" src="visualizations/my_map.html" width="100%" height="550">
    <br><br>
    <p>
    The heatmap clearly shows that the TENDERLOIN district receives the highest number of reports regarding SUSPICIOUS PERSON incidents.It can be attributed to a variety of factors, including a high population density, a significant number of homeless individuals, and a prevalence of drug use and other criminal activity. These factors contribute to a sense of insecurity and discomfort among residents and visitors to the area, resulting in an increased number of reports of suspicious behavior.At the same time, for other areas, if we zoom in on some of the locations where incidents occur frequently, we can see that the reports are concentrated in certain public places, typically parks.
    The obvious hotspot can be identified next to the United Nations Plaza (the inicidents are assigned to the closest intersection). There were patterns observed of the common drug use in the United Nations Plaza, that might have been reported by other people that are enjoying the perks of the area (Chabria, 2022).
    However, it is also possible that the report originated from the Federall Office staff located in the UN building nearby.
    </p>
    <h2> Counts by years in different district </h2>
    <embed type="text/html" src="visualizations/count_plot.html" width="100%" height="550">
    <br><br>
    <p>
    In the above map, it can be observed that in areas where the base rate of SUSPICIOUS PERSON incidents is relatively low, such as PARK, RICHMOND, INGLESIDE, TARAVAL, and BAYVIEW, the number of incidents has been decreasing over the years. This is in line with the actual trend, indicating that the security conditions have been improving year by year, possibly due to the continuous development of security technology by the police department and the overall improvement of public awareness.In areas where there are a higher number of incidents, such as the TENDERLOIN and MISSION districts, we also observe a decreasing trend in the number of incidents over the years. However, what's particularly interesting is that in these areas, there was a significant decrease in incidents in 2017, followed by a rebound in 2018. There were several major events that may have influenced the reporting of SUSPICIOUS PERSON incidents in San Francisco in 2017 and 2018. One significant event was the legalization of recreational marijuana in California, which took effect on January 1, 2018. This may have resulted in a decrease in the reporting of SUSPICIOUS PERSON incidents related to drug use or drug dealing, as these activities were no longer illegal in the state. Another major event was the rise of the #MeToo movement in late 2017, which brought attention to sexual harassment and assault. This increased awareness may have led to more people reporting incidents of suspicious behavior, particularly if they felt uncomfortable or threatened. In addition, there were several high-profile incidents of violent crime in San Francisco during this time period, including a shooting in a popular tourist area in late 2017 and a stabbing on a commuter train in 2018. These incidents may have led to increased concern about public safety and a corresponding increase in the reporting of suspicious behavior.
    </p>
    <h2>Trends(average processing time) by years in different district</h2>
    <embed type="text/html" src="visualizations/trend_plot.html" width="100%" height="550">
    <br><br>
    <p>
    In the above graph, we can see the changing trends in the processing time for SUSPICIOUS PERSON incidents in different police districts, which provides some insight into the development of different police departments. As we learned earlier, TENDERLOIN and MISSION are the two areas with the highest number of SUSPICIOUS PERSON incidents. From the above graph, we can see that the processing time in these two areas has always been relatively long due to the large number of cases and lack of police resources. However, we can also see that there has been significant improvement in processing times in these two areas before 2019 and 2020. This may be due to the development of police technology and the expansion of police resources, as well as the decrease in the number of incidents over the years.As for the increase in processing time after 2020, all areas have similar situations. This may be due to the fact that the number of cases has decreased significantly, so there is less attention paid to them compared to before. However, overall, the average processing time is still within an acceptable range of 80 minutes or less.For the areas where SUSPICIOUS PERSON incidents occur relatively infrequently, such as PARK, RICHMOND, INGLESIDE, TARAVAL, and BAYVIEW, the processing time has remained fairly stable with small fluctuations each year. These areas have consistently maintained a good level of processing time.In 2019, the NORTHERN district saw a somewhat unusual increase in the number of incidents reported, leading to a noticeable slowdown in the processing of cases compared to other areas. This may have been due to a misjudgment of the situation and a reduction in police presence.Overall, there was a significant improvement in the processing speed of most regions from 2019 to 2020.There are several events that may have led to a faster response time for SUSPICIOUS PERSON reports by the police department in San Francisco between 2019 and 2020. In 2019, the city government launched a program called "Fix-It," aimed at improving public safety and environmental hygiene in the city. The program included increasing police patrols and improving the efficiency of the police department to respond and handle reports of suspicious activity more quickly.Additionally,San Francisco Mayor London Breed announced that $120 million in funding would be redirected from law enforcement agencies to addressing disparities in the Black community. The funds will be used for investments in housing, mental health and wellness, workforce development, economic justice, education, advocacy, and accountability.  These measures may have contributed to faster response times, allowing the police department to better address the growing number of reports of suspicious activity.
    </p>
    <h2>Time trend per district for most urgent cases</h2>
    <img src="visualizations/time_trend.png" alt="Time trend per districts for most urgent cases" width="100%" height="1200">
    <br><br>
    <p>
    The average times between the initial call and police arrival at the location per district were discussed above. In addition, it is interesting to investigate the time that it takes police to arrive at the location from the moment the call has been received at the 911 centre for most urgent cases. The time period of two hours is taken into account, as we consider these reports of a higher urgency. From the histograms below it can be observed that police activity is following the typical shape for the task completion times (Janert, 2010). The histograms showcase how often the case was solved within the specific period of time (in minutes), among all the cases that were solved within two hours. It can be observed that most of the cases are solved within 5 to 15 minutes from the moment the call was received. The value is presented in the percentage of cases that took a specific amount of time to complete. For example, in TRAVAL and RICHMOND regions the peak fluctuates around 3-4%, which shows that out of all the cases that were solved within 120 minutes cases that took one of the times between 5 and 10 minutes constitute to approximately 3% to 4%. The histograms for these regions also have a “tail” that is decreasing significantly. It means that fewer cases have taken more time complete. On the other hand, the histogram for the TENDERLOIN region indicates that the peak values only constitute approximately 2% among all cases that were solved within two hours, and the “tail” is decreasing less evidently. It means that in comparison to the aforementioned regions, the time that past between the 911 call and the end of the case was longer for more cases. 
    </p>
    <h2>Priority for 911 calls about the suspicious person </h2>
    <p>
    When the call is received at the 911 center the dispatcher assigns the priority to the case. Once the situation is solved, the final priority is assigned that represents the urgency of the case more accurately. The most common priorities are A, B and C, the A being the most urgent overall and C the least urgent of the three types. In the graph below you can observe what fraction of all cases are assigned A, B or C priorities per district in San Francisco. It is evident that the most common priority for a SUSPICIOUS PERSON is C, while it is very rare that A priority is given. The difference per district can also be observed, as C priority is given for over 90% of cases in TENDERLOIN, while TRAVAL has a relatively close amount of C (just over 60%) and B (approximately 40%) priorities assigned to the cases. 
    </p>
    <embed type="text/html" src="visualizations/priorities_call.html" width="100%" height="550">
    <br><br>
    <p>
    It is important to mention that when comparing initially assigned and final priorities there is a decrease in C priorities and increas in both A and B priorities in each district. It can be assumed that dispatchers tend to underestimate the severity of the cases in the beginning. 
    </p>
    <h2>Conclusion </h2>
    <p>
    In conclusion, we trust that this article prompts readers to contemplate the handling and progression of 911 calls in San Francisco, as well as in their own region. It is crucial to sustain and enhance transparency regarding these issues, as this can motivate the public to take an active role and avoid being indifferent when encountering suspicious behaviours.
    </p>
    <br>
    <h2>References</h2>
    <ul>
        <li>Chabria, A. (2022, December 29). Overdose prevention reaches a crossroad in San Francisco - Los Angeles Times. Los Angeles Times. <a href="https://www.latimes.com/california/story/2022-12-28/column-san-francisco-closed-its-safe-drug-consumption-site-pushing-california-toward-more-death">
        https://www.latimes.com/california/story/2022-12-28/column-san-francisco-closed-its-safe-drug-consumption-site-pushing-california-toward-more-death
        </a></li>
        <li>
        Corey, D. (2017, December 26).2017 Year in Review: Here are the top 10 biggest news stories.<a href="https://www.nbcnews.com/news/us-news/2017-year-review-here-are-top-10-biggest-news-stories-n828881">https://www.nbcnews.com/news/us-news/2017-year-review-here-are-top-10-biggest-news-stories-n828881</a>
        </li>
        <li>
        Evans, C. (2017, December 27). California ready to go green with legalization of marijuana in 2018 .<a href="https://www.cbsnews.com/news/california-recreational-marijuana-legalization-in-2018/">https://www.cbsnews.com/news/california-recreational-marijuana-legalization-in-2018/</a>
        </li>
        <li>Janert, P. K. (2010). Data Analysis with Open Source Tools.<a href="http://cds.cern.ch/record/1438426/files/9780596802356_TOC.pdf">
        http://cds.cern.ch/record/1438426/files/9780596802356_TOC.pdf</a></li>
        <li>
        Johnson, L. (2017, March 21). SF’s popular fix-it program about to expand around town .<a href="https://www.sfgate.com/bayarea/article/SF-expands-Fix-It-program-from-five-to-20-11017258.php">https://www.sfgate.com/bayarea/article/SF-expands-Fix-It-program-from-five-to-20-11017258.php</a>
        </li>
        <li>
        Martichuox, A and Corell Barnard (2020, August 1) San Francisco Mayor London Breed announces cuts to police in new city budget. <a href="https://abc7news.com/san-francisco-budget-announcement-defund-sfpd-the-police-london-breed-press-conference/6345069/">https://abc7news.com/san-francisco-budget-announcement-defund-sfpd-the-police-london-breed-press-conference/6345069/</a>
        </li>
        <li>
        Serna, J et al. (2017, June 14). Four killed in shooting at San Francisco UPS facility, including gunman.<a href="https://www.latimes.com/local/lanow/la-me-ln-san-francisco-shooting-downtown-20170614-story.html">https://www.latimes.com/local/lanow/la-me-ln-san-francisco-shooting-downtown-20170614-story.html</a>
        </li>
    </ul>
    <div class="footer-container">
    <footer>
        <p style="text-align: center">Person 1, Person 2, Person 3</p>
        <p> <a href="https://github.com/B1nguy1/">Link to explainer notebook </a> </p>
    </footer>
    </div>

</div>
</body>
</html>
