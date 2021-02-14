# Opening a Coffee Shop in Northeast Ohio

**1. Introduction**

The suburbs located in Northeast Ohio are a popular Midwest location for people to settle down and raise children.  As these subrubs grow and change, many business owners and entrepreneurs to look towards these locations for new business opportunities in different areas.  For my project, I have determined to focus specifically on the business idea of opening a new coffee shop in a suburb of Northeast Ohio.  This is a business problem that many aspiring entrepreneurs face, and I think entrepreneurs located in the Northeast Ohio area will be interested to see the results.

**2. Data**

I will be collecting data from Foursquare to determine which suburbs from Northeast Ohio have the most coffee shops, as well as the highest rated coffee shops.  I will cluster the suburbs based on this information using K-means.  An entrepreneur interested in opening a coffee shop in the area may then analyze the clusters and determine which cluster they would be interested in opening a shop in- towns with many, high-rated coffee shops, towns with few, low-rated coffee shops, etc.  I think the best business opportunity would be in the suburbs that are found to have a low number of coffee shops without a particularly high rating, so they do not have much competition nearby.

**3. Methodology**
In order to analyze the current distribution of coffee shops within the Cleveland area, I decided to focus on 4 couties in patricular: Geauga, Summit, Portage, and Cuyahoga.  I downloaded a dataset including all of the postal codes for cities in the United States and filtered and cleaned it, so I was working with just the postal codes and latitude/longitude coordinates of the counties I was interested in.

I then used the function created in the New York City clustering activity to get nearby venues to each of the cities I had in the cleaned dataset.  This allowed me to then filter the Venue Category by "Coffee Shop" to determine which cities had popular coffee shops and where they were located.  Using this information, I created a map of coffee shop locations using Folium.

**4. Results**

**5. Discussion**

**6. Conclusions**
