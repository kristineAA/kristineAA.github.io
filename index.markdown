---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: "Myths Around Suicide"
---

# Myths Around Suicide

Commonly known suicide myths Suicide is a topic we are all aware of and one surrounded by countless stories—but how many of these are factual, and how many are simply myths? 
Should we trust the belief that most suicides occur during the holidays or that teenagers and college students are at the highest risk? Let's delve into the evidence to separate fact from fiction. 
This analysis will focus on suicide data in San Francisco from 2003 to 2024, derived from a comprehensive dataset that records all reported crimes within the city. The dataset provides detailed information, including the type of crime, enabling us to filter specifically for suicides. Additionally, it contains data points such as the time and date of each incident, the police precinct responsible, and geographical coordinates. These details allow us to create various visualizations that can help uncover trends and provide deeper insights into suicide patterns over the years. 

Analyzing the calendar plot below, one particular day in December 2024 stands out—December 21st. On this day, a dark green color indicates it was among the days with the highest number of suicides recorded over the span of 21 years. This observation might suggest that suicide rates are influenced by the holiday season, as the date falls just a few days before Christmas. Moreover, looking back at December 2023, only one suicide occurred throughout the entire month, but notably, it happened on Christmas Eve. Based solely on these two pieces of data, one could construct a narrative linking Christmas to a negative impact on suicide rates. However, this would present an incomplete picture and overlook the broader trends across the dataset. 

<figure>
  <img src="assets/calendar_plot.png" alt="Calender Plot" />
  <figcaption>**Figure 1:** Calendar heatmap displaying the intensity of daily activity from 2003 to 2024. Each row represents a year, with columns showing months and individual squares representing days of the week. The color gradient from light to dark purple indicates increasing levels of activity on each day. This visualization highlights long-term patterns, seasonal trends, and notable peaks or gaps in activity over the two-decade span.</figcaption>
</figure>

To explore monthly suicide patterns, we can analyze the bokeh plot below. Interestingly, the data reveals that in 2004 and 2010, December had the highest number of suicides compared to other months in those years, potentially lending support to the idea of a holiday-suicide connection. However, a contrasting pattern emerges in 2017 and 2023, where December recorded the lowest number of suicides. These inconsistencies highlight the difficulty in drawing definitive conclusions or identifying a clear trend that links suicides to the holiday season. 

<figure>
    <iframe src="assets/bokeh_plot.html" width="100%" height="600" style="border:none;"></iframe>
    <figcaption>**Figure 2:** Stacked bar chart showing yearly suicide counts from 2003 to 2023, broken down by month. Each bar represents the total annual crime count, with different colors indicating monthly contributions. This visualization highlights overall trends in crime rates over time, seasonal fluctuations, and notable changes in monthly distributions across years.</figcaption>
</figure>

A deeper and more comprehensive analysis of the data is essential to uncover any meaningful insights. Beyond Christmas, other major holidays could also be analyzed for potential links to suicide rates. For example, in the United States, Thanksgiving and the Fourth of July are prominent celebrations worth examining. Thanksgiving, which takes place annually on the fourth Thursday of November, stands out in this analysis due to an unusual spike in suicides near the holiday in 2022. However, as this is a singular occurrence over a span of 21 years, it does not provide substantial evidence to suggest a consistent pattern or trend tied to this holiday. Likewise, an isolated spike in suicides is observed for the Fourth of July in 2007, further emphasizing the lack of recurring trends across these holidays. 

<figure>
    <iframe src="assets/map.html" width="100%" height="600" style="border:none;"></iframe>
    <figcaption>**Figure 3:** Map of San Francisco displaying the geographic distribution of reported suicides. Each red dot marks the location of a recorded suicide case. The map reveals spatial patterns, with higher concentrations in central and eastern neighborhoods.</figcaption>
</figure>

In the Mayo Clinic post titled “8 Common Myths About Suicide,” one myth addresses the belief that teenagers and college students are at the highest risk of suicide. However, when examining the map of suicides above in San Francisco, no suicides have been recorded on university grounds, and only three have occurred in the surrounding area. Notably, one suicide has been recorded just outside the site of UC Law, but none near the Arthur A. Dugoni School of Dentistry. This suggests that college students may not be the group most affected by suicide, challenging the common misconception. 

In conclusion, while isolated data points might appear to reinforce popular beliefs about suicide, a more comprehensive analysis consistently uncovers a nuanced reality that challenges many of these widely held myths. The persistence of such beliefs in media narratives may stem from these isolated instances, which seem to align with common misconceptions. This tendency is reflected in the media-focused paper “Suicide Rate Is Low During the Holidays, but the Holiday-Suicide Myth Persists” from University of Pennsylvania, which highlights how many outlets continue to report the holiday-suicide myth as fact, despite substantial data proving otherwise.

