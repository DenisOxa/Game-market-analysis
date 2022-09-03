# Project name: Sales analysis of the global game store

## Description
The online store "A" sells computer games all over the world. Historical data on game sales, user and expert ratings, genres and platforms are available from open sources.

**Data contains**:
- Name - name of the game
- Platform — platform
- Year_of_Release — year of release
- Genre — game's genre
- NA_sales — sales in North America (million copies sold)
- EU_sales — sales in Europe (million copies sold)
- JP_sales — sales in Japan (million copies sold)
- Other_sales — sales in other countries (million copies sold)
- Critic_Score — critics' score (maximum is 100)
- User_Score — user rating (maximum is 10)
- Rating — rating from the ESRB (англ. Entertainment Software Rating Board). This association determines the rating of computer games and assigns them an appropriate age category.

The **goal** of the project:
- Identify patterns that determine the success of the game
- Draw up a portrait of the user from each region (NA, EU, JP)

## Key results:

### The main features of the market

- Half of the games were released between 1980 and 2007 (27 years), the other between 2007 and 2016 (9 years). This indicates an increase in the speed of the release of computer games, an increase in the market as a whole.
- Platforms appear and disappear. At the same time, the average life of the platform is 7 years.
- Leading platforms in general for all data PS2, X360, PS3, Wii, DS
- For the actual researched period, the top platforms are X360, PS3, WiiU, XOne, PS4. Moreover, some of them (X360, PS3) cannot be called a priority for development, unlike PS4, XOne, since they have existed for more than 7 years.
- Based on data from the X360 platform, it was found that the relationship between sales and user scores is higher than between sales and critic scores. However, even a high user scores does not guarantee high sales.
- Most Played - category M Games
- Top three selling genres - Action, Shooter and Sports, unsuccessful genres - Adventure, Strategy and Puzzle

### Portraits of the users
**Average North American user**: 
- Most likely using either PS4 or XOne platform (possibly also X360, 3DS, PS3)
- Plays Action, Shooter, Sports genres (Misc or Role-Playing is also possible) 
- Rated M or E10+

**Average European user**:
- Most likely using PS4 (or XOne, PS3. Also possible PC, 3DS, WiiU)
- Plays Action, Shooter, Sports (or Role-Playing and Racing)
- M-rated (also E and E10+)

**Average user from Japan**:
- Most likely using 3DS, also possibly PS4, PSV (or PS3 and WiiU)
- Plays Role-Playing, Action (or Fighting, Misc and Shooter)
- Rated E, T or M


### For research were used following libraries:
pandas, numpy, seaborn, missingno, statistics, plotly.express, stats from scipy 
