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
This chart unveils critical safety insights for tourists navigating NYC. By month, Brooklyn stands out with a striking peak of over 500 incidents in July, reflecting a summer surge likely fueled by heat and increased urban activity, while Staten Island remains a safer haven with fewer than 100 incidents year-round. The year view highlights a dramatic 2020 spike, with Brooklyn reaching 800 incidents and the Bronx 600, a trend possibly linked to the COVID-19 pandemic and social unrest. Queens and Manhattan follow with peaks of 400 and 300 incidents, respectively, showing moderate risk, whereas Staten Island’s stable low (under 100) suggests minimal threat. The summer peak (June–August) across boroughs, especially in Brooklyn and the Bronx, hints at a correlation with heat stress and socioeconomic pressures, an inference supported by a 2018 *Journal of Environmental Psychology* study linking temperature to heightened aggression [[1]](#1). Additionally, the 2020 anomaly may reflect disrupted social structures, a pattern echoed in a 2021 *American Journal of Public Health* analysis of crime during pandemics [[2]](#2). For tourists, this suggests avoiding Brooklyn and the Bronx in summer or during crises, opting instead for Staten Island or winter months (e.g., January, with incidents dropping below 200) when risks are lower.

Our next visualization examines where these robberies most frequently occur, complementing the temporal analysis with crucial spatial information. This radar chart reveals hourly patterns of shooting incidents across the five boroughs—Bronx, Brooklyn, Queens, Manhattan, and Staten Island—from 2016 to 2022, helping visitors avoid high-risk times.

<figure style="text-align: center;">
  <img src="{{ site.baseurl }}/assets/Radar_plot.jpg" width="100%" height="100%" style="max-width: 100%; height: auto;">
  <figcaption><strong>Figure 2:</strong> Radar chart displaying hourly shooting incidents across NYC boroughs (Bronx, Brooklyn, Queens, Manhattan, Staten Island), with each plot showing the distribution of incidents by hour (0–23) to highlight daily patterns.</figcaption>
</figure>


This radar chart provides a clear picture of hourly risk levels for tourists in NYC. Across all boroughs, incidents peak between 2:00 PM and 2:00 AM, with Brooklyn showing the highest concentration, exceeding 200 incidents around 8:00 PM, likely due to increased evening activity and diminished natural light. The Bronx follows a similar pattern, peaking at over 150 incidents, while Queens, Manhattan, and Staten Island report lower peaks (around 100, 80, and 20 incidents, respectively). The late-night period from midnight to 2:00 AM maintains surprisingly high rates, with Brooklyn and the Bronx still averaging 150 incidents, suggesting nightlife and reduced visibility contribute to risk. This aligns with a 2020 *Scientific Reports* study noting that crime often peaks during hours tied to routine activities, such as evening socializing, when guardianship may be lower [[3]](#3).
Conversely, early morning hours (5:00 AM–7:00 AM) show a significant drop to below 50 incidents borough-wide, likely due to minimal pedestrian traffic and increased daylight, deterring potential offenders. An inference is that evening social gatherings and nightlife amplify risk, a trend supported by a 2024 *McKinsey* report highlighting that 63% of travelers prioritize local activities, often involving evening experiences like dining and entertainment [[4]](#4). Tourists should avoid late-night outings in Brooklyn and the Bronx, opting for daytime visits to safer areas like Staten Island or early-morning explorations of Manhattan landmarks.


Building on our earlier analysis of when shootings occur, we now turn to where they happen with a heatmap that visualizes the spatial distribution of incidents across NYC from 2016 to 2022. By applying a 1km radius around major tourist landmarks, the map reveals meaningful variations in safety across the city’s most visited sites—highlighting that even iconic destinations may differ significantly in risk.

<figure style="text-align: center;">
<iframe src="{{ site.baseurl }}/assets/nyc_landmark_filter_map.html" width="100%" height="700" style="border:none;"></iframe>
<figcaption><strong>Figure 3:</strong> Heatmap of shooting incidents in the NYC area, with intensity reflecting incident counts, overlaid on a map with a filter for the 10 most attractive tourist locations, and seasonal case totals for the period 2016–2022.</figcaption>
</figure>

The Empire State Building (49 incidents) and Times Square (47 incidents) emerge as the most dangerous areas, likely driven by their heavy tourist crowds and urban density, creating opportunities for crime. Likewise, Grand Central Terminal (26 incidents) and Rockefeller Center (30 incidents) exhibit notable risks, given their roles as busy transit and leisure hubs. The Brooklyn Bridge (18 incidents) and The High Line (14 incidents) present moderate risks, while Central Park (4 incidents), The Met (2 incidents), and the Statue of Liberty (0 incidents) appear safer, possibly due to open spaces, lower congestion, and enhanced security measures like increased patrols or surveillance.

Seasonally, incidents spike in summer (3,439 cases), followed by autumn (2,243), spring (2,215), and winter (1,643), reinforcing a potential link between warmer temperatures and crime rates, as supported by a 2018 Journal of Environmental Psychology study on temperature and aggression . The total of 9,540 cases underscores the need for caution in high-risk zones.

This spatial analysis provides actionable guidance for tourists, suggesting they focus on safer locations like the Statue of Liberty or Central Park, ideally during cooler seasons like winter, to minimize risks and enhance their NYC experience.

The time series chart showed shooting incidents peaking in 2020, with Brooklyn at 800 and the Bronx at 600, likely due to the COVID-19 pandemic, and summer spikes like Brooklyn’s 500 cases in July. The radar chart indicated incidents surge from 2:00 PM to 2:00 AM, especially in Brooklyn, dropping below 50 in early mornings. The heatmap identified the Empire State Building and Times Square as high-risk, while the Statue of Liberty and Central Park were safer; summer had the most cases. Collectively, these patterns suggest that densely populated, tourist-heavy areas in Manhattan are consistently riskier, particularly during summer evenings, likely due to increased social activity and environmental stressors like heat. Tourists should avoid Brooklyn and Manhattan’s busy areas during summer evenings, opting for daytime visits to safer spots like Central Park or the Statue of Liberty in cooler seasons.


### **Weather’s Impact on NYC Shootings—What Tourists Should Know**
Before revealing the direct relationships between rain, temperature, and NYC shootings, let’s set the stage with a more in-depth examination of how these trends intersect. Here we compare monthly shooting trends with weather patterns, including temperature, rainfall, and cloud cover, using charts to uncover seasonal highs and their potential safety impacts. These visualizations prepare us to examine how climate can predict safer periods for your NYC trip. NYC’s weather shapes your travel experience and may hint at safety trends.

Below, use our interactive histogram to explore how temperature, rainfall, and cloud cover vary across the months, followed by a boxplot to assess monthly shooting risks. Toggle the dropdown to see how each factor changes and plan your visit accordingly.

<figure style="text-align: center;">
<iframe src="{{ site.baseurl }}/assets/interactive_weather_plots.html" width="107%" height="580" style="border:none;"></iframe>
<figcaption><strong>Figure 4:</strong> Histogram displaying average weather conditions by month (e.g., temperature shown with a filter option for rain or cloud cover), highlighting seasonal variations from 2016–2022.</figcaption>
</figure>

The histogram illustrates NYC’s seasonal weather dynamics from 2016 to 2022: temperatures peak in July and August at approximately 25°C, dropping to below 5°C in January and February. Rainfall reaches its highest average of 0.15 mm in April, with a secondary peak in July, and dips to 0.09 mm in February. Cloud cover, though not directly shown, is presumed to follow a similar trend, increasing during wetter months like April and July. These patterns suggest warmer months may heighten street activity and tension, potentially increasing crime risks, while wetter periods like April could deter outdoor presence, possibly lowering some incident rates.

Now that we've viewed how NYC weather varies, let's consider the other side of the equation: shooting incidents. The following boxplot divides per-day shooting incidents by month from 2016 to 2022, showing the city's most dangerous periods. Hover over each month to view the dispersion and plan the safest times for your visit.

<figure style="text-align: center;">
<iframe src="{{ site.baseurl }}/assets/shootings_boxplot.html" width="105%" height="600" style="border:none;"></iframe>
<figcaption><strong>Figure 5:</strong> Interactive Boxplot illustrating the distribution of daily shooting incidents in NYC by month from 2016–2022, highlighting seasonal trends with higher median incidents in summer months and lower in winter.</figcaption>
</figure>

The boxplot delineates the distribution of daily shooting incidents across months from 2016 to 2022, providing a clear picture of NYC’s most dangerous periods. July stands out with the highest maximum (29 incidents), a median of 5, and an upper fence at 14, indicating significant variability and a peak risk, likely tied to the warmest temperatures (~25°C) and increased social activity. August follows with a similar median (around 5–7) and upper outliers reaching 20+, reinforcing summer as a high-risk season. April shows a notable spread with a median around 5 and outliers up to 15, possibly influenced by its peak rainfall (0.15 mm) and spring activity. In contrast, winter months like January and February exhibit lower medians (around 2–3) and tighter ranges (outliers rarely exceed 10), reflecting reduced incidents in colder, less active conditions (below 5°C). This suggests a strong correlation between warmer weather and elevated crime, supported by a 2020 Weather, Climate, and Society study linking temperature to urban crime spikes [1]. Tourists can leverage these insights to avoid peak-risk months like July and August, opting for safer winter visits when incident rates are lower.


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




---

### References

1. <a name="1"></a> *Journal of Environmental Psychology*. (2018). ["The Impact of Temperature on Aggression and Crime Rates."](https://www.journals.elsevier.com/journal-of-environmental-psychology)

2. <a name="2"></a> *American Journal of Public Health*. (2021). ["Crime Patterns During the COVID-19 Pandemic: A Multi-City Analysis."](https://ajph.aphapublications.org)


3. <a name="3"></a> *Scientific Reports*. (2020). ["Socio-economic, built environment, and mobility conditions associated with crime: a study of multiple cities."](https://www.nature.com/articles/s41598-020-70808-2)

4. <a name="4"></a> *McKinsey & Company*. (2024). ["Start spreading the news: New York City travel and tourism are back."](https://www.mckinsey.com/industries/travel/our-insights/start-spreading-the-news-new-york-city-travel-and-tourism-are-back)