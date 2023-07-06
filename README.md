# Twitch_viewership_rise
Compiled work and analysis of Twitch Global Data set


# Twitch’s Rise: Live Streaming, Community, and  Global Events

## Introduction ##
In April of 2019 there was an immediate and noticeable spike in viewership from the website Twitch, a popular live streaming service. Since the lockdown beginning in the same month, Twitch has continued to see success in retention and addition to their user pool. In partnership with Twitch, Codecademy supplied datasets pertaining to the entire viewership and stream of Twitch clients globally. The goal of our analysis and exploration looked for trends in global current social events, and how they stacked up to average viewership gain on twitch.

### Data Cleaning ###
The analysis was performed within Jupyter Notebook for ease of process explanation. Before exploration could begin data would need to be cleaned and organized for manipulation and visualization. Our initial datasets included string objects in integer columns, which would need to be removed using regex before the data type of columns could be properly transformed. Each object to integer column would be duplicated, have its unnecessary string removed by looping through regex removal, and placed back into the original dataframe, replacing their originals with a new data type.
Repeating the process with our second data frame, I was now able to visualize representation of our data. My first step was to seek correlation between our columns, and to no one’s surprise they were tightly correlated as shown in the heat map. All of our data was directly taken from stream time and channel data, so as more channels appeared more stream time would appear and more viewers would appear and so on. This did however allude to the fact that quantity of channels did contribute to overall popularity of a game’s page. Trends in popularity of channel types created an influx of new streamers, or older streamers changing genres. Before lockdown, twitch numbers rested mainly in games like League of Legends, Grand Theft Auto, and World of Warcraft. The political tension and isolation of individuals incentivised the need of community and an essentially never ending stream of entertainment. Twitch’s platform was the perfect medium to fill this need.
Each game was accompanied by corresponding columns relating to total time streamed, total channels, average viewer count, and hours watched by viewers. Deciding to narrow my search, I ranked the top 15 games for each category and whittled down to the top 3 games overall. League of Legends, Fortnite, and Just Chatting consistently topped the rankings, and all data pertaining to them was split off and graphed separately to visualize the popularity over time of each (viewers, stream time, and channel quantity). The rapid growth of the Just Chatting section of Twitch was astounding to visualize, as it coincided directly with Twitch’s global growth during early phases of lockdown.

### Correlation of Events and Viewership Spikes ###
I wanted to investigate further at this point, and decided to visualize the growth rate of twitch globally through the entirety of the data frame (2016-2022) with month increments for specificity. Within the growth visualization there were six notable spikes and drops in viewership. The initial spike during early lockdown led me to believe that other spikes in twitch viewership may also be connected to major events. A quick google search for the spiked month in question was enough to spark an interesting coincidence between some of the largest social events in recent history and the change in viewership.
The spikes contained a primary category driving viewership to the sight which, through indexing, was found to vary across game types except for our Just Chatting section.  Showing up twice as the most popular category, and still driving a considerable amount of traffic to the site during the time of the spike/incident. 
Now, before we jump to conclusions it is important to note the variety that comes along with the Just Chatting category. Yes, there are those talking on current events, but there is a much larger portion fulfilling certain niches of audiences for entertainment. Unfortunately, with the data I currently have I can’t parse types of Just Chatting streamers, so we can only definitively conclude that traffic rises during these events, particularly in this category. 
With what we have, we can still infer that the viewers are using Twitch as a source for information or for comfort. The events of the past two years have isolated and divided people and there is a clear void for the community that virtual spaces seem to be filling. Whether for distraction or information it serves the same purpose, connection.

## Conclusion ##
Twitch was originally founded for the gaming community, and it still holds that to be true. However,  the natural growth of the platform created by its users allowed a new space to emerge all on its own. If Twitch takes advantage of this new growth correctly, it has a very high potential to transform itself into a multinational hub of live entertainment and a respected source of information. Other companies like Meta and TikTok have already dipped their toe into the live streaming marketplace. Right now Twitch is positioned to become a beast, but they need to keep their momentum and foster the growth in its community for future work.


### Tableau account

https://public.tableau.com/app/profile/anthony.shortt

### LinkedIn

www.linkedin.com/in/anthonyshortt
