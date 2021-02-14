# Opening a Coffee Shop in Northeast Ohio

**1. Introduction**

The suburbs located in Northeast Ohio are a popular Midwest location for people to settle down and raise children.  As these subrubs grow and change, many business owners and entrepreneurs to look towards these locations for new business opportunities in different areas.  For my project, I have determined to focus specifically on the business idea of opening a new coffee shop in a suburb of Northeast Ohio.  This is a business problem that many aspiring entrepreneurs face, and I think entrepreneurs located in the Northeast Ohio area will be interested to see the results.

**2. Data**

I will be collecting data from Foursquare to determine which suburbs from Northeast Ohio have the most coffee shops, as well as the highest rated coffee shops.  I will cluster the suburbs based on this information using K-means.  An entrepreneur interested in opening a coffee shop in the area may then analyze the clusters and determine which cluster they would be interested in opening a shop in- towns with many, high-rated coffee shops, towns with few, low-rated coffee shops, etc.  I think the best business opportunity would be in the suburbs that are found to have a low number of coffee shops without a particularly high rating, so they do not have much competition nearby.

**3. Methodology**

In order to analyze the current distribution of coffee shops within the Cleveland area, I decided to focus on 4 couties in patricular: Geauga, Summit, Portage, and Cuyahoga.  I downloaded a dataset including all of the postal codes for cities in the United States and filtered and cleaned it, so I was working with just the postal codes and latitude/longitude coordinates of the counties I was interested in.

I then used the function created in the New York City clustering activity to get nearby venues to each of the cities I had in the cleaned dataset.  This allowed me to then filter the Venue Category by "Coffee Shop" to determine which cities had popular coffee shops and where they were located.  Using this information, I created a map of coffee shop locations using Folium.

**4. Results**

I found that using the Foursquare data, there are many cities in Northeast Ohio that would make potentially successful locations for new coffee shops.  I also found that the Foursquare search I conducted did not consist of all of the coffee shops in the area, so this made my analysis more difficult than I initially expected.  An entrepreneur looking to open a new coffee shop in the Northeast Ohio area should take a look at my map of current coffee shop locations and open one in a city in which these data points are sparse.

**5. Discussion**

As I mentioned in the results section, I had trouble with the Foursquare data, as it did not include all of the coffee shops that actually exist in the area.  In order to create a more precise and accurate result in a future project, data scientists should find a different data source to use and perform clustering with.  I think this could lead to more informative results and could lead to a better analysis than I did with this project.

**6. Conclusions**

Overall, the problem of where an entrepreneur should open a new coffee shop in the Northeast Ohio area can be explored by taking a look at the Jupyter notebook I used for this project.  There is still a lot of work to be done and improved on, but my results can allow people who are interested to delve into the current state of coffee shops in the Northeast Ohio area.
