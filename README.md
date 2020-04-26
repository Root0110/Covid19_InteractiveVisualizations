## Spread of __Covid-19__ around the WHOLE World

<html>
<body>
    <h1>Interactive Covid-19 Statistics of the WHOLE WORLD</h1>
    <p>@Xiaohan Wang</p>
    <p>@IS590 DV 2020Spring</p>
    <h2>Brief Introductions</h2>There is a big event happening, affecting every person in the earth, and it is named
    <p>Covid-19 by WHO. Up to 25th April, the coronavirus pandemic has seen more than 2,850,000 confirmed cases and more
    than 198,000 deaths worldwide. Being a member of the humanity, I feel like everyone is equal struggling with the
    disaster, and the empathy with people in hard time drives me to do something, and the thanksgiving heart of having
        food and a healthy body enables me to devote what I am learning to do some visualizations and analysis.</p>
    <h2>Visualizations</h2>
    <h3>Figure 1. Dashboard to Explore Monthly & Daily Number of Cases in 5 Continents</h3>

    <p>On the left side of this dashboard, the heatmap presents the number of confirmed cases of each continent, during
    each month. The darker color the cell has, the more confirmed cases. And when one cell is selected, the string at
    the top would tell you the precise number, and at the sametime, the bar plot lieing on the right side would present
    the number of confirmed cases of each continent, during each day. In order to group a large number of records into
        groups, I add the continent columns by downloading another dataset.</p>
    <h3>Figure 2. Global Deaths of Countries</h3>
    <iframe src="/InteractiveDV/fig2.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0"></iframe>
    Above interactive data map presents the Covid-19 situation regarding to death quantity in each country, with different
    colors from light to dark. As you can see, the dark blue areas have more deaths while the light yellow areas have less
    deaths. And if you put your click on a certain country, the precise number of deaths(till 04/24/2020) would show up.
    Maybe the colorbar looks werid at first, because it is not linearly scaled. Don't worry, these intervals are power
    results of e(Euler's Number: 2.718).
    <h3>Figure 3. Trendline of Global Cases and Deaths Added Per Day</h3>
    <h3>Figure 4. Bar Plot of Confirmed Cases in Top 50 Countries</h3>
    <h3>Figure 5. Interactive Scatterplots between Varaibles</h3>
    It's easy for readers to choose any two meaningful variables, and have a look at the scatterplot to find potential
    relationship. Also, the colors of data points in the scatterplot would represent another variable, so that more
    complex connections would be explored.
    <h2>Stories Telling</h2>

    <h2>Data Sources</h2>
    1. [Full data of Covid-19] (https://data.world/markmarkoh/coronavirus-data)
    2. [Countries & Continents dataset](https://www.kaggle.com/statchaitya/country-to-continent)
    3. [World Map Data](https://www.naturalearthdata.com/downloads/110m-cultural-vectors/)
    
</body>
</html>
