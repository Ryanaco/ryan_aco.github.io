---
layout: default
---

# **Is NYC Safe for Your Trip? Shootings, Weather, and What to Know**

>write an introduction


### **Navigating NYC: Which Boroughs Pose the Biggest Risks?**
<div style="width:800px; margin:auto;">
  {% include shooting_incidents.html %}
</div>



<img src="{{ site.baseurl }}/assets/Radar_plot.jpg" width="670px">

<iframe src="../assets/shootings_map_with_heatmap.html" width="100%" height="700" style="border:none;"></iframe>





### **Weather’s Impact on NYC Shootings—What Tourists Should Know**
Before revealing the direct relationships between rain, temperature, and NYC shootings, let's set the stage with a more in-depth examination of how these trends intersect. Here we compare monthly shooting trends with weather trends such as temperature, rainfall, and cloud cover. These charts reveal seasonal highs and the possible impact of weather, setting the stage for examining more closely how climate can help predict safer periods for your NYC trip.

NYC’s weather can set the tone for your trip, but it might also hint at safety trends. Below, use our interactive histogram to explore how temperature, rainfall, and cloud cover vary across the months. Toggle the dropdown to see how each factor changes and plan your visit accordingly.
{% include Weather_Histogram.html %}

The histogram illustrates the seasonal weather conditions of NYC: temperatures are highest in July and August, at an average of about 25°C, and lowest in January and February, below 5°C. Rainfall, however, is most pronounced in April, at an average of 0.15 mm, and has a secondary peak in July, while in February it is lowest at 0.09 mm. Cloud cover (not illustrated but presumed) would probably have the same trend, higher in wetter months. These trends suggest warmer months could mean more street activity—and possibly tension—although wet periods can influence how often people are outdoors. 

Now that we've viewed how NYC weather varies, let's consider the other side of the equation: shooting incidents. The following boxplot divides per-day shooting incidents by month from 2016 to 2022, showing the city's most dangerous periods. Hover over each month to view the dispersion and plan the safest times for your visit.
{% include shootings_boxplot.html %}
The boxplot reveals a definite pattern in the shooting trends in NYC. The summer months of June, July, and August are the worst. June has a median of 4 shootings per day, which can go up to 22 on its worst day. July and August are close behind with medians between 4 and 5, and some days in excess of 20. In winter months like January and February, though, it's preferable with medians around 3 and fewer really high days. Let's take June to see its figures—25% of days (Q3) experience a minimum of 8 shootings, a definite signal to avoid the busiest summer days. For a safer trip, choose cooler months like February when the chances of a hot day are greatly diminished.

Now that we’ve seen how shootings spike in certain months, let’s explore how weather might play a role. The histograms below compare monthly shooting incidents with average temperature and rainfall
![]({{ site.baseurl }}/assets/Histogram.jpg)
These histograms shows a noticeable relationship between crime and climate in NYC. The histogram on the right shows that incidents peak in July, with shooting incidents exceeding 1200, which is consistent with the average temperature for July, which peaks at about 26°C, and then decreases to an average of about 3°C for January. This suggests that increased street activity—and probably increased tension—when the temperatures are hot leads to a significant rise in shooting incidents. The histogram on the left shows that precipitation differs where July with a little bit of rainfall with about 0.17 mm and October is rated second with closer to 0.16 mm, and with February the lowest at around 0.10 mm. It is interesting that shooting incidents are lower where the temperatures are cooler, and there is somewhat more rainfall. Both warmer temperatures and precipitation have an effect where rain means people might not want to be outside, thus reducing the chances of shooting incidents.

In conclusion, the seasonal patterns observed suggest that weather variables such as temperature and precipitation may be related to the number of shootings in New York City. However, in order to clearly move beyond visual implications and determine the strength of these relationships, we must statistically measure them. In the next section we will look into the actual correlations between weather variables and the shooting incidents to demonstrate just how related climate conditions are between heat and crime.

### **Title for this section**

<img src="{{ site.baseurl }}/assets/Time-serie graph.png" width="500px">

<img src="{{ site.baseurl }}/assets/Correlation.jpg" width="400px">

![]({{ site.baseurl }}/assets/Temperature.jpg)

![]({{ site.baseurl }}/assets/Cloudcover.jpg)

### Conclusion 


### References
