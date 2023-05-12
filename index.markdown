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
   In this article, we will analyse the 911 calls originating from residents or visitors in San Franciso. Utilizing the San Francisco open source public safety data we will investigate several variables in the data. The purpose of this article is to demonstrate more details behind the dispatched calls and police response, as well as allow the residents to analyse the situation per location. 
   </p>

   <p>
   We will focus on reported cases that were tagged as “Suspicious person”. Why? Because our team has found the term rather arbitrary. Hopefully, analysis can shed some light on the details of the importance and development of such cases.
  </p>
  <p>
   Among all calls that the dispatch centre has received between the years 2016 and 2022, calls for the SUSPICIOUS PERSON were 4th most common calls: 
  </p>
  <img src="visualizations/911_calls.png" alt="Most common 911 calls" width="100%" height="550">
  <h2> Development of 911 cases for suspicious person </h2>
  <img src="visualizations/combined_graph.jpg" alt="Call types combined" width="100%" height="550">
  <br><br>
  <p>
    The developments of these calls were also investigated. When the call is received, a dispatcher defines the call type such as “Suspicious person”, however the at the end of the incident a more accurate and final description is prescribed. The graphs above demonstrate the by far most of the call keep their initial description, hower other common categories are “Homeless complaints”, spotting of “Mentally disturbed” or “Trespasser”.
  </p>
    <h2>Heatmap?</h2>
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
    <br><br>
    <h2>References</h2>
    <ul>
        <li>Chabria, A. (2022, December 29). Overdose prevention reaches a crossroad in San Francisco - Los Angeles Times. Los Angeles Times. <a href="https://www.latimes.com/california/story/2022-12-28/column-san-francisco-closed-its-safe-drug-consumption-site-pushing-california-toward-more-death">
        https://www.latimes.com/california/story/2022-12-28/column-san-francisco-closed-its-safe-drug-consumption-site-pushing-california-toward-more-death
        </a></li>
        <li>Janert, P. K. (2010). Data Analysis with Open Source Tools.<a href="http://cds.cern.ch/record/1438426/files/9780596802356_TOC.pdf">
        http://cds.cern.ch/record/1438426/files/9780596802356_TOC.pdf</a></li>
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
