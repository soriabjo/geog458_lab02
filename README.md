# Lab 2: Geo-tagged tweet collection and visualization
## Visualizing tweets related to the NBA in the United States
### Bjorn S. | GEOG 458

With the first round of the 2022 NBA playoffs underway, I wanted to see where NBA fans were located across the United States. In particular, I pulled tweets using Twitter's data API from two time periods from the same day to see if there was any consistency in regards to where tweets popped up in the U.S or if new regions popped up at a later time.

Although early, the NBA playoffs have had a number of exciting games and match ups. Series such as the Boston Celtics versus the Brooklyn Nets, Warriors and Nuggets, and Memphis Grizzlies and Minnesota Timberwolves have offered intense, action-packed moments through 3 games of play.

Pulling geo-tagged data from two different times in a day would allow me check the United States activity before games started and just before tip-off of games. It is likely to assume that higher populated cities would contain more teams. Furthermore, it wouldn't be a bad guess to think that cities that have an NBA team in the playoffs would also have a higher tweet density with respect to geolocation.

### Map 1 - Twitter Activity Well Before NBA Playoff Games

![First Map](img\screenshot_of_map-1.png "Early afternoon Twitter activity")

The first map shows high concentration of tweets in United States coastal cities such as the Pacific Northwest (Seattle Area), California (Los Angeles, Bay Area), Texas, Florida, and numerous East Coast cities. As mentioned before, it's not entirely surprising to see less tweet in the mid-west. However, the Utah Jazz and Dallas Mavericks series as well as the Denver Nuggets and Golden State Warriors seems to have activity around those areas in regards to geo-tagged tweets.


### Map 2 - Twitter Activity Before NBA Playoff Game Tip-Offs

![Second Map](img\screenshot_of_map-2.png "Twitter activity before games start")

The later in the day map shows a similar geospatial pattern. Coastal cities tend to have greater geo-tagged activity with the track tag 'NBA' to it. Mid-west United States has less activity, and the East Coast in general has a more widespread distribution of tweets. My reasoning for the lack of difference is it possible that because the NBA games haven't started, tweets haven't begun to start the discussion over the games. Furthermore, since it's Friday, people have yet to get off traditional work hours for weekdays, and the number of tweets overall are lower than later in the evening when familiy and friends are gathering around to watch the intensity that is NBA Playoff basketball.

### Word Cloud 1 (Early afternoon)

![Cloud 1](img\screenshot_of_wordcloud-1.png "Early afternoon")

Unsurpsingly, it seems that the first word cloud associated with the first map is related to work. Words such as 'work', 'job', and 'out' seems to capture worker sentiment well.

![Cloud 2](img\screenshot_of_wordcloud-2.png "Before tip-off")

It seems that later in the day, the senitment of Twitter users' tweets are happier. With the workweek almost ending, it makes sense that Tweets would begin to be more uplifting. We can see in the cloud with the second map, that 'Thank', 'Love', 'Great', and other words are popping up. With games starting soon, I would guess that the next word cloud when games begin to have more NBA specific tweets, such as player names, basketball vocabulary, and more.