# IGR204 MiniProject : Baby Names

## Week 1 - Design Sketches

### Visualization 1

The visualization has to answer the following questions : 
1. How do baby names evolve over time?
2. Are there names that have consistently remained popular or unpopular?
3. Are there some that have were suddenly or briefly popular or unpopular?
4. Are there trends in time?

<ins><b>First design</b></ins>:

To address the given questions, we first chose to use line charts to depict the popularity of specific names over time, with separate charts for feminine and masculine names, with a text field allowing users to select the names they want to plot. It cannot easily be represented on the sketch, but we would also like to integrate a zoom option to focus on specific time periods.

![viz1](https://github.com/GroupeR-DataViz/MiniProject/assets/113033010/883c4af6-ecf7-4530-a212-4635729fa869)

Strengths:

 * Customization: Allowing users to choose the specific names they want to plot provides a high level of customization and personalization. Users can focus on names of interest to them, enabling more meaningful exploration and analysis.
 * Clear Comparison: By separating feminine and masculine names into distinct charts, users can easily compare the popularity trends between the two genders. This design facilitates the identification of any divergences or similarities in naming patterns.
 * Temporal Analysis: Line charts effectively convey the temporal aspect of name popularity, allowing users to observe the evolution of specific names over time. This can reveal trends, spikes, or declines in popularity for the selected names.

Weaknesses:

* Overwhelming Options: Providing the ability to choose specific names to plot can result in a large number of options. If the list of available names is extensive, it may overwhelm users or make it challenging to select names efficiently.
 * Limited Context: The design may lack additional contextual information about the names or the reasons behind their popularity or decline. Users may need to rely on external sources or data to gain a deeper understanding of the naming trends.
 * Data Availability: The availability and completeness of historical name popularity data can vary. In some cases, there may be gaps or missing data for specific names or years, which can affect the accuracy and reliability of the visualization.

To address these weaknesses, we would consider including tooltips or interactive elements that offer additional information about the selected names and their cultural or historical significance, but these information are not present in the available data.

<ins><b>Second design</b></in>:

For the second design, we chose to use spaghetti charts, with each name having its own individual line chart, to depict the popularity of each name over time. It cannot easily be represented on the sketch, but we would also like to integrate a zoom option to focus on specific time periods.

![viz1_design2](https://github.com/GroupeR-DataViz/MiniProject/assets/113033010/7fd7610b-f2b7-49dd-a551-66e3e488d33d)


Strengths:

* Individual Name Analysis: Representing each name with a separate spaghetti chart allows for a detailed examination of its popularity over time. This design enables viewers to focus on specific names of interest and observe their unique trends and patterns.
 * Visualizing Variability: Line charts provide a clear representation of the popularity of each name, as the line's trajectory shows the changing trends over time. Line charts effectively display the variability and fluctuations in name popularity over the years. Viewers can visually identify the rise and fall of specific names, as well as any sudden or gradual changes in popularity.
 * Comparative Analysis: By having multiple line charts, viewers can compare the popularity trends of different names simultaneously. This design enables viewers to easily interpret and compare the relative popularity of different names. This facilitates the identification of commonalities, outliers, or contrasting patterns among the names.

Weaknesses:

 * Limited Space: Allocating sufficient space for each individual line chart can be a challenge, particularly when the number of names is high. Smaller charts may make it harder to discern fine-grained details or interpret the popularity trends accurately.
 * Comparative Analysis: With separate line charts for each name, direct comparison between multiple names can be challenging. Identifying commonalities, differences, or overall trends among the names may require additional effort from viewers.
 * Limited Context: Line charts primarily focus on the popularity of names over time and may lack additional contextual information. Viewers may need to rely on external sources or data to understand the reasons behind the popularity trends.
 * Accuracy issue: Even though we can read quite easily the graph, size is not the first-choice visual variable in terms of accuracy. Several names of close sizes located apart inside the graph can be difficult to compare.

In the same way as for the first design, we would consider including tooltips or interactive elements that offer additional information about the selected names and their cultural or historical significance, but these information are not present in the available data.
 

<ins><b>Third design</b></ins>:

The last design proposition is somehow more original. We chose to represent the names inside the sketch of a baby. The popularity of the names is encoded by the font size and the gender is encoded by the color (blue for boys, pink for girls). A cursor allows to select the years, allowing to see the trends in time.

![viz1_design3](https://github.com/GroupeR-DataViz/MiniProject/assets/113033010/4c140d35-33b1-45db-bf20-b19b56af2cbb)

Strengths:

 * Engaging and Memorable: The use of a visual representation of a baby with names written inside can create an engaging and memorable experience for viewers. It adds a playful and relatable element to the visualization, making it more enjoyable to explore.
 * Gender Differentiation: By color-coding feminine names in pink and masculine names in blue, the design provides a clear visual distinction between the two genders. This helps viewers easily identify and compare naming patterns between boys and girls.
 * Popularity Representation: Varying the size of the written names based on popularity can effectively convey the relative popularity of each name. Viewers can quickly identify the most popular names, allowing for easy visual comparison.

Weaknesses:

 * Limited Name Selection: The design may only accommodate a limited number of popular names within the space available on the baby's figure. This could exclude lesser-known or more niche names, potentially leading to a partial representation of name popularity.
 * Lack of Granularity: Using a single visual element (baby) to represent all names may result in limited granularity for individual names. The size variations may not capture subtle differences in popularity, especially if there are significant gaps in popularity between names.
 * Complexity and Interpretation: Depending on the number of names and their popularity, the visualization may become visually cluttered and challenging to interpret. Overlapping names or small font sizes could make it difficult to read or compare names accurately.

To partially mitigate these weaknesses, we would consider introducing a zoom/focus option to allow the exploration of specific areas of the baby.

                                                              
### Visualization 2

The visualization has to answer the following questions :
1. Is there a regional effect in the data?
2. Are some names more popular in some regions?
3. Are popular names generally popular across the whole country?

To answer to the 3 given questions, we chose to draw 2 maps-based visualization showing the popularity of names in different regions over time (one for masculine names and one for feminine names)

![viz2](https://github.com/GroupeR-DataViz/MiniProject/assets/113033010/03cf8e75-5109-49f0-a9b4-bfb4e1b3d2e2)


Strengths:

* Geographical Context: A map provides a clear geographical context, allowing viewers to quickly understand the regional distribution of name popularity.
* Regional Patterns: This visualization can reveal regional patterns and variations in name preferences, highlighting cultural or regional influences on naming trends.
* Easy Comparison: Comparing popularity across regions becomes intuitive, as viewers can visually compare the intensity of color of markers representing name popularity.

Weaknesses:

 * Data Availability: The availability and granularity of regional data can be a limitation. Obtaining detailed name popularity data for every region can be challenging, and some regions may have limited data, leading to incomplete or biased visualizations.
 * Data Aggregation: Aggregating data at the regional level may smooth out local variations within regions. Viewers may not be able to discern specific nuances or localized popularity within larger regions.
 * Interpretation Challenges: Viewers may interpret the map as suggesting causality between geographical location and name popularity, when in reality, various factors influence naming trends. It is important to clarify that the visualization shows correlations rather than direct causation.

To mitigate these weaknesses, we plan to provide additional information and allow users to explore the data further with a legend and tooltips.
 

### Visualization 3 (bonus)

The visualization has to answer the following questions :
1. Are there gender effects in the data?
2. Does popularity of names given to both sexes evolve consistently?

To answer to the 2 given questions, we chose to draw 2 horizon graphs : one depicting the evolution of the use of a name for boys, the other depicting the evolution of the use of **the same name** for girls.

![viz3](https://github.com/GroupeR-DataViz/MiniProject/assets/113033010/674e0f4c-94ea-4c19-a3f7-6aa09aa5b4fc)


Strengths:

* Efficient use of space: Horizon charts allow for efficient use of space by stacking the data bands vertically, making it easier to compare multiple data sets without requiring excessive horizontal space.
* Clear trend identification: The colouring of the chart makes it easy to identify trends and patterns in the data, such as increases or decreases in values over time.
* Data density: Horizon charts can display a large amount of data in a compact and concise format, enabling users to gain insights from a broad range of data points at a glance.

Weaknesses:

 * Limited precision: Due to the stacking and color-coding of data bands, horizon charts sacrifice precision in representing exact data values. It can be challenging to determine the precise values without referring to numerical scales or labels.
 * Steep learning curve: Horizon charts may not be immediately intuitive to interpret for users who are unfamiliar with this visualization technique. It might require some practice and understanding to effectively read and analyze the charts.

To mitigate these weaknesses, we intend to include numerical scales to mitigate the precision issue. This should allow users to understand the specific values associated with each range and make accurate comparisons. Since horizon charts may not be widely known, it is important to provide clear legends and explanations to help users understand the color-coding and the layout of the chart.

## Week 2 - Initial Implementation

**Install** : The 3 visualisations have been produced using Tableau. To discover them, simply download the 3 workbooks situated in the [Visualizations_week2 folder](https://github.com/GroupeR-DataViz/MiniProject/tree/main/Visualizations_week2) of this repository ... and enjoy :)

### Visualization 1
The visualization 1 helps answer the following questions:

1. How do baby names evolve over time?
The line chart at the bottom of the dashboard provides insights into how baby names evolve over time. By using the filter, we can display all names or only the selected baby names. By examining this chart, we can observe how the number of occurrences of each name varies across the years. This allows us to identify names that have gained or lost popularity over time.

2. Are there names that have consistently remained popular or unpopular?
The horizontal histogram at the top left of the dashboard, sorted in ascending order, displays the most popular baby names. By examining this histogram, we can see the names with the highest number of occurrences, indicating names that have consistently remained popular over an extended period. Similarly, we can identify less frequent names that have consistently remained unpopular over time.

3. Are there some names that have been suddenly or briefly popular or unpopular?
The bubble chart at the top right of the dashboard represents the number of occurrences of each name, with bubble size indicating frequency. By using the filter on the bubbles or the histogram, when we select a specific name, it will be highlighted and selected on all three graphs. This allows us to identify names that have experienced a sudden increase or decrease in popularity, even if it was only for a brief period.

4. Are there trends in baby names over time?
By examining the line chart and observing variations in the number of occurrences of names over the years, we can identify trends in baby names. For example, we may notice periods where certain names become more popular and then decline. Similarly, we may identify periods where certain names regain popularity after being less frequent for a certain time.

Using this visualization, along with the interactive filters and multiple graphs, we can explore and analyze the evolution of baby names over time, identify consistently popular or unpopular names, spot sudden shifts in popularity, and detect trends and changes in naming preferences.


### Visualization 2
From the interactive visualization that we've created using Tableau, we can glean a lot of information about regional variations in name popularity.

Firstly, the map allows us to get a regional perspective. We can click on any department in France and the histogram will immediately update to display the most frequent names in that selected department. This enables us to see which names are particularly popular in certain regions, providing evidence of regional effects in the data.

For example, if we click on the department of 'Hauts-de-Seine', we may see 'Jean' as a frequent name. If we then select 'Loire-Atlantique', and 'Jean' also shows up as a popular name there, we can start to infer that 'Jean' might be a popular name in multiple regions.

Furthermore, by systematically clicking through each department and observing the changes in the histogram, we can identify trends in name popularity across the whole country. If a name frequently appears as one of the top names in the histogram for most departments, it would suggest to us that this name is generally popular across France.

So, the combination of the interactive map and histogram in our visualization is a powerful tool. It allows us to directly observe and analyze regional variations and trends in name popularity across France.

### Visualization 3
The third visualization focuses on trends in gender, and especially tries to answer the following questions : Are there gender effects in the data? Does popularity of names given to both sexes evolve consistently?

The dashboard created is composed of 2 parts : 
* A series of bar charts showing the number of baby given a specific name each year (one chart per name). A color encoding allows to quickly gauge the main gender to which the specific name is attributed (pink for girls, blue for boys). A tooltip gives the exact percent for the year selected, and filters on the right allow to add / remove charts with a text field and reduce / increase the considered year range. Thus, this visualization allows to quickly view if a name if more used for boys or girls, as well as the evolution of the use of the names over time (especially interesting for unisex names such as Camille). The superposition of charts allows the user to compare the names it is more interested in.
* A list of names, sorted according to a "Unisex Delta". The computation of this metric is fairly straightforward : the data contains a field "Sexe" equal to 1 for boys and 2 for girls. Thus, a perfectly interchangeable name for boys and girls would have an mean of 1.5 for this specific field. We computed the absolute difference between the mean "sexe" value for a given name and 1.5 to estimate the spread in use of the name. Therefore, a ratio of 0 characterises a name used as many times for boys as for girls over the years, while a ratio of 0.5 characterises a name mainly used for one specific gender. This metric is not perfect (quite biased when the names are rarely used), but it still provides a quantitative estimation of the unisex characteristic of a name. This view is linked to the bar charts, allowing to add / remove charts for specific names with a simple click.
  
$$ \delta = \mid 1.5 - mean(sexe) \mid $$

## Week 3 - Refined Implementation

### Visualization 1

The calculation of the popularity of names was changed (from count to sum) and the rare names filtered, which should make the bubble chart a bit more informative / interpretable.

### Visualization 2

To take into account the comments made on the forum, a slider allowing to select a year range was added. It is now possible to see the evolution of the popularity of names by region over time.

### Visualization 3

Minor color and wording adjustments were made to try and make the dashboard clearer and more visually appealing. The main modification brougth to this visualization is the addition of a mixed bar / line charts displaying the evolution of the use of unisex names over time. This addition was motivated by comments made by fellow students in the forum. <br>
This new chart show that around 3% of names given to babies are unisex (used both for boys and girls), and the trend is increasing in recent years after a decrease in the 80's. To assess whether a name is unisex or gendered, we reused the Unisex delta previously computed. This metric is equal to 0 if a name if used as many times for boys and girls, and 0.5 if used only for boys or for girls. By setting a threshold at the value 0.35, we defined names as unisex for $\delta <= 0.35$ and gendered for $\delta > 0.35$. This threshold may seem a bit arbitrary, but it is a good compromise to select names used frequently enough for both genders. <br>
The final version of the visualization 3 is the following :

![Viz3](https://github.com/GroupeR-DataViz/MiniProject/assets/113033010/74c21959-676e-45f4-a681-af66636bed48)

### Bonus : Baby Plot (visualization 1)

We would like to present the "baby_plot" as an example of `chartjunk`, which was discussed during class. Despite its playful appearance and interactive functionality, this plot falls short in effectively displaying the change in popularity of baby names over time. Instead, it requires viewers to retain information in their memory to make comparisons across different years.

In the process of creating this visualization, we took a suitable image of a baby and used the `clippingmagic` tool to remove the background. Subsequently, we introduced a word cloud within the body of the baby image. To enhance the interactivity of the plot, we incorporated an `IntSlider` feature, enabling viewers to navigate through different years and observe the frequently given names.

Overall, while the creation of the "baby_plot" was an enjoyable experience, it lacks the clarity and directness necessary to effectively convey the changing popularity of baby names over time to viewers. <br>
In order to admire this masterpice, the following libraries are required (all can be installed via pip):
* matplotlib
* PIL (`pip install Pillow`)
* numpy
* scipy
* pandas
* wordcloud
* ipywidgets

Here is a preview of what to expect when running the notebook :
![baby](https://github.com/GroupeR-DataViz/MiniProject/assets/113033010/46abf5bb-c77d-41d2-82e0-a1fe0297f9b0)
