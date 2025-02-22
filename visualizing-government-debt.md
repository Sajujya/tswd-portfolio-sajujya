| [Home Page](https://sajujya.github.io/tswd-portfolio-sajujya/) | [Visualizing Debt](visualizing-government-debt) | [U.S. Government Budget Analysis](critique_by_design) | [AI: Outgrowing Your Expectations Faster Than a Kardashian Breakup!](final-project-part-one) | [Final Project Part II](final-project-part-two) | [Final Project Part III](final-project-part-three)

<!--| [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) | -->

# OECD Government Debt-to-GDP Ratio
Let's first look at the Government Debt-to-GDP Ratio of some countries for the year 2016. 
<iframe src="https://data.oecd.org/chart/7bbs" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7bbs" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2016</a></iframe>

# Government Debt for Countries between 1995-2021
Now, let's look at the Government Debt-to-GDP Ratio visualized for these countries between the years 1995-2021. 

<div class="flourish-embed flourish-chart" data-src="visualisation/14970508"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Top 10 Countries with the Highest Government Debt-to-GDP Ratio
Now that we have a rough idea of how the Debt-toGDP Ratio of each country has changes from 1995-2021, let's look at the Top 10 countries with the highest government debt-to-GDP ratios for every year. 

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/14973063"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Explanation

1. So, at this point, I know how the debt-toGDP ratio has changed for each country from 1995-2021. However, I wanted to understand what were the worst-performing countries for each year. Since we did not yet do a country-year specific Top-N Analysis, I had the idea of creating a bar chart race graphic!

2. I started with modifying the data in Excel to create a Pivot table, with the columns as the year values and the rows as the country codes. The value in each cell would now correspond to the value of the debt-to-GDP ratio for that country for that year.

3. I imported this data into flourish and started off with a bar-chart race template to create the current visualization.

4. As a sidenote, I would have wanted to color the chart differently. Ideally, I would have wanted a gray-to-red diverging color scale to get the point across that highesr ratios of debt-to-GDP are a sign of failing economies. However, current;y, I do not think that Flourish offers that flexibility in terms of colors.

### Findings 

Among many other things, we find that

1. In the late 1990s, the countries with the highest debt-to-GDP ratio were mostly European countries like Italy and Belgium.
2. However, from early 2000s, with the opening up the Japanese econommy, their debt-to-GD ratio soared high.
3. Additionally, the debt-to-GDP ratio for Greece increased at a tremendous speed from the early 2010s, which finally led to the Greece Debt Crisis!

   
# Comparing and Contrasting the Visualizations

| Bar Chart | Grid of Line Charts | Bar Chart Race |
| ------------- | ------------- |------------- | 
| This chart is simple and easy to understand. However, it does not provide any context as to how the  debt-to-GDP ratio for the different countries has changed over the years. Therefore, at the risk of simplicity, this chart has had to do away with a lot of contextual information. However, if we just want to see the data for a particular year, this is the one that makes the most sense. | This gives us an idea of how the debt-to-GDP ratio has changed for each country between 1995-2021. However, personally, I am not a fan of grid of line charts since often times it feels like information overload.| This graphic shows us what were the top 10 worst performing countries in terms of debt-to-GDP ratio for each year from 1995-2021. Therefore, this answers a different question from the other two, because it compares countries parallelly, over the years, and returns the top 10. Ideally, like how I mentioned, I would like the color scheme to represent the fact that highest debt-to-GDP ratios are a warning signn  | 

