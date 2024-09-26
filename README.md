## The Beer Trip Agency (BTA) 🍻

### Abstract:

After a rewarding journey crafting amazing beer-tasting trips, we’re thrilled to share the fruits of our labor! 🥳 Been a tough few weeks correcting endless ADA stories, so how did we celebrate? With a few drinks and unforgettable adventures, of course! Welcome to the Beer Trip Agency (BTA), where we have successfully designed personalized beer-tasting tours across the globe, perfectly tailored to your every beer-loving whim!

Using a treasure trove of data, we curated a variety of trips around the world based on your preferences and some fun factors like beer strength, top-rated brews, and brewery diversity. Our meticulous algorithm has crafted the ideal tours, showcasing the best beer regions just for you. We’ve lined up fantastic brewery visits and connected you with the most passionate local beer aficionados to ensure an expert experience! Ale the best for a trip Lager than life! 🍺

Check out our example website created https://maxcaa.github.io/.

### Key Questions to Answer:

What’s your dream beer trip? If you were planning a beer world tour with your friends, where’s the middle ground? And most importantly, where’s the ultimate beer El Dorado that everyone can agree on?

### Additional Datasets:

- **Location Surface Areas**: Imported from Wikipedia to calculate beer densities.
- **Population per Location**: Also from Wikipedia, helping us gauge beer-lovers per capita.

### Methods: 

#### 1) Data Preprocessing:

- Cleaned and prepared the additional datasets (area, population, etc.).
- Loaded, cleaned, and explored datasets from RateBeer and Beer Advocate.

#### 2) Crafting the Perfect Beer Tour Rankings:

- **Alcohol Percentage Rankings**: We’ve ranked locations for both the strongest and softest beers, ensuring everyone’s taste is satisfied.  
_Status: Complete_

- **Top Beer Ratings**: By grouping beers by location and excluding spots with fewer than five brews, we’ve created rankings for the highest-rated and lowest-rated beers.  
_Status: Complete_

- **Brewery Diversity**: Locations were ranked by brewery density (number of breweries per km²) to maximize brewery visits while minimizing travel time!  
_Status: Complete_

- **The Connoisseur Tour**: Based on reviews from top reviewers, we’ve ensured that only the finest brews made the cut for our ultimate beer tour!  
_Status: Complete_

- **Beer Lovers' Density**: We calculated the number of users from a location relative to the local population, pinpointing the hottest spots for beer enthusiasts.  
_Status: Complete_

- **Emerging Beer Countries**: We identified regions where craft beer is booming, highlighting the best up-and-coming beer destinations!  
_Status: Complete_

- **Feature-Based Rankings**: Rankings based on specific beer characteristics (aroma, palate, flavor, etc.) have been successfully implemented.  
_Status: Complete_

#### 3) The Grand Ranking:

With the rankings all set, we visualized everything on a map. Based on customer preferences, each location was awarded points (10 points for 1st place down to 1 point for 10th), multiplied by their respective preference weights, leading us to discover the El Dorado of beer destinations and plan the ultimate beer world tour!

#### 4) Additional Info for Your Trip:

Now that our tours are wrapped up, we lined up visits to the best breweries in each destination, paired with local guides ready to share their expertise and passion for beer. These guides aren’t just any tour guides—they’re the most dedicated beer enthusiasts from RateBeer and BeerAdvocate, ensuring your beer tour was unforgettable!


### Important Packages to Include:

pandas, numpy, matplotlib.pyplot, seaborn, bs4, requests, statsmodels.stats, scipy, plotly, us, json
