---
layout: default
---

# **Is NYC Safe for Your Trip? Shootings, Weather, and What to Know**

>write an introduction


### **Navigating NYC: Which Boroughs Pose the Biggest Risks?**
For tourists planning a trip to New York City, understanding where and when shooting incidents occur can enhance safety. This interactive line chart explores shooting incidents across the five boroughs—Bronx, Brooklyn, Queens, Manhattan, and Staten Island—from 2016 to 2022, offering a toggleable view by month or year. By analyzing temporal patterns, tourists can identify safer times to visit popular destinations.
<figure style="text-align: center;">
  <iframe src="{{ site.baseurl }}/assets/shooting_incidents.html" width="100%" height="600" style="border:none;"></iframe>
  <figcaption><strong>Figure 1:</strong> Interactive line chart showing shooting incidents by year or month (filter), with separate lines for each NYC borough (Bronx, Brooklyn, Queens, Manhattan, Staten Island) from 2016 to 2022.</figcaption>
</figure>
This chart unveils critical safety insights for tourists navigating NYC. By month, Brooklyn stands out with a striking peak of over 500 incidents in July, reflecting a summer surge likely fueled by heat and increased urban activity, while Staten Island remains a safer haven with fewer than 100 incidents year-round. The year view highlights a dramatic 2020 spike, with Brooklyn reaching 800 incidents and the Bronx 600, a trend tied to the COVID-19 pandemic and widespread protests, as documented in the NYC Police Department’s 2020 Annual Report. Queens and Manhattan follow with peaks of 400 and 300 incidents, respectively, showing moderate risk, whereas Staten Island’s stable low (under 100) suggests minimal threat. The summer peak (June–August) across boroughs, especially in Brooklyn and the Bronx, hints at a correlation with heat stress and socioeconomic pressures, an inference supported by a 2018 Journal of Environmental Psychology study linking temperature to heightened aggression. Additionally, the 2020 anomaly may reflect disrupted social structures, a pattern echoed in a 2021 American Journal of Public Health analysis of crime during pandemics. For tourists, this suggests avoiding Brooklyn and the Bronx in summer or during crises, opting instead for Staten Island or winter months (e.g., January, with incidents dropping below 200) when risks are lower. A practical tip: plan visits around major attractions like Central Park during off-peak seasons to minimize exposure.


<figure style="text-align: center;">
  <img src="{{ site.baseurl }}/assets/Radar_plot.jpg" width="100%" height="100%" style="max-width: 100%; height: auto;">
  <figcaption><strong>Figure 2:</strong> Radar chart displaying hourly shooting incidents across NYC boroughs (Bronx, Brooklyn, Queens, Manhattan, Staten Island), with each plot showing the distribution of incidents by hour (0–23) to highlight daily patterns.</figcaption>
</figure>


### 景点的filter显示,1KM以内的incidents
<figure style="text-align: center;">
<iframe src="{{ site.baseurl }}/assets/nyc_landmark_filter_map.html" width="100%" height="700" style="border:none;"></iframe>
<figcaption><strong>Figure 3:</strong> Heatmap of shooting incidents in the NYC area, with intensity reflecting incident counts, overlaid on a map with a filter for the 10 most attractive tourist locations, and seasonal case totals for the period 2016–2022.</figcaption>
</figure>




### **Weather’s Impact on NYC Shootings—What Tourists Should Know**
Before revealing the direct relationships between rain, temperature, and NYC shootings, let's set the stage with a more in-depth examination of how these trends intersect. Here we compare monthly shooting trends with weather trends such as temperature, rainfall, and cloud cover. These charts reveal seasonal highs and the possible impact of weather, setting the stage for examining more closely how climate can help predict safer periods for your NYC trip.

NYC’s weather can set the tone for your trip, but it might also hint at safety trends. Below, use our interactive histogram to explore how temperature, rainfall, and cloud cover vary across the months. Toggle the dropdown to see how each factor changes and plan your visit accordingly.

<figure style="text-align: center;">
<iframe src="{{ site.baseurl }}/assets/interactive_weather_plots.html" width="107%" height="580" style="border:none;"></iframe>
<figcaption><strong>Figure 4:</strong> Histogram displaying average weather conditions by month (e.g., temperature shown with a filter option for rain or cloud cover), highlighting seasonal variations from 2016–2022.</figcaption>
</figure>

The histogram illustrates the seasonal weather conditions of NYC: temperatures are highest in July and August, at an average of about 25°C, and lowest in January and February, below 5°C. Rainfall, however, is most pronounced in April, at an average of 0.15 mm, and has a secondary peak in July, while in February it is lowest at 0.09 mm. Cloud cover (not illustrated but presumed) would probably have the same trend, higher in wetter months. These trends suggest warmer months could mean more street activity—and possibly tension—although wet periods can influence how often people are outdoors. 

Now that we've viewed how NYC weather varies, let's consider the other side of the equation: shooting incidents. The following boxplot divides per-day shooting incidents by month from 2016 to 2022, showing the city's most dangerous periods. Hover over each month to view the dispersion and plan the safest times for your visit.

<figure style="text-align: center;">
<iframe src="{{ site.baseurl }}/assets/shootings_boxplot.html" width="105%" height="600" style="border:none;"></iframe>
<figcaption><strong>Figure 5:</strong> Interactive Boxplot illustrating the distribution of daily shooting incidents in NYC by month from 2016–2022, highlighting seasonal trends with higher median incidents in summer months and lower in winter.</figcaption>
</figure>

The boxplot reveals a definite pattern in the shooting trends in NYC. The summer months of June, July, and August are the worst. June has a median of 4 shootings per day, which can go up to 22 on its worst day. July and August are close behind with medians between 4 and 5, and some days in excess of 20. In winter months like January and February, though, it's preferable with medians around 3 and fewer really high days. Let's take June to see its figures—25% of days (Q3) experience a minimum of 8 shootings, a definite signal to avoid the busiest summer days. For a safer trip, choose cooler months like February when the chances of a hot day are greatly diminished.

Now that we’ve seen how shootings spike in certain months, let’s explore how weather might play a role. The histograms below compare monthly shooting incidents with average temperature and rainfall

<div style="display: flex; gap: 20px; text-align: center;">
  <div>
    <img src="assets/temp.png" width="100%">
    <div><strong>Figure 6:</strong> Dual-axis histogram showing monthly shooting incidents in NYC (bars) alongside average temperature (line) from 2016–2022, revealing patterns like higher incidents in warmer months.</div>
  </div>
  <div>
    <img src="assets/rain.png" width="100%">
    <div><strong>Figure 7:</strong> Dual-axis histogram displaying monthly shooting incidents in NYC (bars) with average rainfall (line) from 2016–2022, highlighting trends such as fewer incidents during high-rainfall months.</div>
  </div>
</div>


These histograms shows a noticeable relationship between crime and climate in NYC. The histogram on the right shows that incidents peak in July, with shooting incidents exceeding 1200, which is consistent with the average temperature for July, which peaks at about 26°C, and then decreases to an average of about 3°C for January. This suggests that increased street activity—and probably increased tension—when the temperatures are hot leads to a significant rise in shooting incidents. The histogram on the left shows that precipitation differs where July with a little bit of rainfall with about 0.17 mm and October is rated second with closer to 0.16 mm, and with February the lowest at around 0.10 mm. It is interesting that shooting incidents are lower where the temperatures are cooler, and there is somewhat more rainfall. Both warmer temperatures and precipitation have an effect where rain means people might not want to be outside, thus reducing the chances of shooting incidents.

In conclusion, the seasonal patterns observed suggest that weather variables such as temperature and precipitation may be related to the number of shootings in New York City. However, in order to clearly move beyond visual implications and determine the strength of these relationships, we must statistically measure them. In the next section we will look into the actual correlations between weather variables and the shooting incidents to demonstrate just how related climate conditions are between heat and crime.

### **Title for this section**

<figure style="text-align: center;">
<img src="{{ site.baseurl }}/assets/Time-serie graph.png" width="100%" height="100%">
  <figcaption><strong>Figure 8:</strong> Standardized time series plot of shooting incidents (purple) and temperature (orange) in NYC from 2016–2022, showing synchronized peaks in summer months (e.g., July) and troughs in winter (e.g., January).</figcaption>
</figure>

<figure style="text-align: center;">
<iframe src="{{ site.baseurl }}/assets/correlation_heatmap.html" width="100%" height="600" style="border:none;"></iframe>
  <figcaption><strong>Figure 9:</strong> Correlation matrix heatmap of NYC shooting incidents with weather variables (temperature, rain, cloud cover) from 2016–2022, showing weak positive correlation between incidents and temperature (0.3) and negligible correlations with rain and cloud cover.</figcaption>
</figure>

<figure style="text-align: center;">
<img src="{{ site.baseurl }}/assets/temperature_rr_plot_with_rr1_line.png" width="100%" height="100%">
  <figcaption><strong>Figure 10:</strong> Grid of histograms showing temperature distributions across NYC boroughs (Bronx, Brooklyn, Manhattan, Staten Island, Queens) from 2016–2022, with relative risk (RR) curves and 95% confidence intervals overlaid to assess the impact of temperature on shooting incidents.</figcaption>
</figure>

<figure style="text-align: center;">
<img src="{{ site.baseurl }}/assets/cloudcover_rr_plot_with_rr1_line.png" width="100%" height="100%">
  <figcaption><strong>Figure 11:</strong> Grid of histograms displaying cloud cover distributions across NYC boroughs (Bronx, Brooklyn, Manhattan, Staten Island, Queens) from 2016–2022, with relative risk (RR) curves and 95% confidence intervals overlaid to evaluate the influence of cloud cover on shooting incidents.</figcaption>
</figure>

### Conclusion 


### References
