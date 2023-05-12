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
    font-family:Arial,sans-serif
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
</style>
</head>
<body style="background-color:white;">

<div class="container">
    <h1 style="color:black;text-align:center;"> SAN FRANCISCO </h1>
    <img src="img/SF_background.jpg" alt="SF" style="width:1000px;height:400px;">
    <p>
    Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
    </p>
    <h2> Counts by years in different district </h2>
    <embed type="text/html" src="visualizations/count_plot.html" width="100%" height="550">
    <p>
    In the above map, it can be observed that in areas where the base rate of SUSPICIOUS PERSON incidents is relatively low, such as PARK, RICHMOND, INGLESIDE, TARAVAL, and BAYVIEW, the number of incidents has been decreasing over the years. This is in line with the actual trend, indicating that the security conditions have been improving year by year, possibly due to the continuous development of security technology by the police department and the overall improvement of public awareness.In areas where there are a higher number of incidents, such as the TENDERLOIN and MISSION districts, we also observe a decreasing trend in the number of incidents over the years. However, what's particularly interesting is that in these areas, there was a significant decrease in incidents in 2017, followed by a rebound in 2018. There were several major events that may have influenced the reporting of SUSPICIOUS PERSON incidents in San Francisco in 2017 and 2018. One significant event was the legalization of recreational marijuana in California, which took effect on January 1, 2018. This may have resulted in a decrease in the reporting of SUSPICIOUS PERSON incidents related to drug use or drug dealing, as these activities were no longer illegal in the state. Another major event was the rise of the #MeToo movement in late 2017, which brought attention to sexual harassment and assault. This increased awareness may have led to more people reporting incidents of suspicious behavior, particularly if they felt uncomfortable or threatened. In addition, there were several high-profile incidents of violent crime in San Francisco during this time period, including a shooting in a popular tourist area in late 2017 and a stabbing on a commuter train in 2018. These incidents may have led to increased concern about public safety and a corresponding increase in the reporting of suspicious behavior.
    </p>
    <embed type="text/html" src="visualizations/viz2.html" width="100%" height="445">
    <h2>References</h2>
    <ul>
        <li>Chabria, A. (2022, December 29). Overdose prevention reaches a crossroad in San Francisco - Los Angeles Times. Los Angeles Times. <a href="https://www.latimes.com/california/story/2022-12-28/column-san-francisco-closed-its-safe-drug-consumption-site-pushing-california-toward-more-death">
        https://www.latimes.com/california/story/2022-12-28/column-san-francisco-closed-its-safe-drug-consumption-site-pushing-california-toward-more-death
        </a></li>
        <li>Janert, P. K. (2010). Data Analysis with Open Source Tools.<a href="http://cds.cern.ch/record/1438426/files/9780596802356_TOC.pdf"> 
        http://cds.cern.ch/record/1438426/files/9780596802356_TOC.pdf</a></li> 
    </ul>
    <footer>
        <p style="text-align: center">Person 1, Person 2, Person 3</p>
        <p> <a href="https://github.com/B1nguy1/">Link to explainer notebook </a> </p>
    </footer>
</div>
</body>
</html>
