# Link to main page
If you wish to go back to my main page please use the following link:
[Main page](https://oscardavidmi.github.io/Benavides-portfolio/)
# Project Summary
For my project I would like to show information about the evolution of music through the ages. As a musician I have always looked towards music for inspiration and also
when I want to find empathy during a particular time. Personally I have seen how music has changed through the years, given that I am a 1990's person I have seen 
music go from salsa, rock, punk to reggaeton and techno; sometimes I look back and think to myself how did music went from what I knew to this new music and I can see 
people before me thinking the same thing. 
As it turns out the music liked by people is influenced by current events, I will be using information on the billboard top songs by year for the last week of the year 
and crossing that information with events that were taking place in that moment or close to that year (decade for example), I can say that I personally saw the rise
and fall of the "emo" phase; didnt really liked it but I guess it happened because a collective of people felt they didnt fit in with society. I would like to see
the same thing with this information but on a macro level and reducing it to the US so it can be more targeted and easier to identify trends if there are.

# Outline
The following outline displays which are the events that will be taken per decade and some examples of songs that people listened to heavily during that decade.
![Story](https://oscardavidmi.github.io/Benavides-portfolio/Story%20arc.jpeg?raw=true)
We can see some of the most important events in the sad zone given that I am trying to relate some of the events that happen back to the music being listened by people. 
What I hope to achieve is to display how people listening to certain music in a decade use it as a way to deal with the problems they are facing at that time, for 
example if I look back to the pandemic I remember listening to happy music in order to cope with the lockdowns; I want to find similar trends with the US data.

# Sketches
For my project I would like to use a variety of charts that will both show the trend of genres per year for each decade as well as a timeline that will give focus to 
some historical events that may have influenced the trends per decade. Moreover, per each timeline built in each decade I would like to show a example of one of the 
artists and song which was very famous at that time and which I believe is a strong representation of the decade.

- My first visualization will be a bubble chart which shows a rapid change of the genre preferences per year

![First](https://oscardavidmi.github.io/Benavides-portfolio/First_bubble.jpeg?raw=true)


- My second visualization will use a line chart to show how in each decade there are certain events that happen which marked that decade. I will try to tie back these events to one of the most popular genres and the artists that are viewed as the representations of those genres. I will add a picture of the artist next to my visualizations.

![Second](https://oscardavidmi.github.io/Benavides-portfolio/Second_history2.jpeg?raw=true)


- My third visualization is will be a stacked bar to compare all the decades and visualize the proportions of each genre per decade to appreciate how much they have changed.

![Third](https://oscardavidmi.github.io/Benavides-portfolio/Third_different.jpeg?raw=true)


# The data
For this project, I obtained the information needed by constructing it from two datasets. Both datasets were downloaded from the site: 
https://data.world/kcmillersean/billboard-hot-100-1958-2017  shared by @kcmillersean. The datasets contain information on the billboard top 100 up until 2020 which 
includes information such as the week in which a particular song was in the ranking, which position, for how long, etc. Moreover, the is also information on the songs 
like the duration, genres, spotify popularity, etc.
In addition to the link to the datasets, I have created a file which has all the information I plan to use for my project which you can find here by the name 
(Music_Evolution.xlsx):

[Data](https://github.com/oscardavidmi/Benavides-portfolio/blob/main/Music_Evolution.xlsx)

The way I plan to use the information is to cross it using its unique identifier and then extract the relevant information I would need from each of the datasets
One of the data sets has information on the billboard position of songs and the other dataset has information extracted from Spotify and the information is matched 
through a unique key identifier. After crossing the datasets I will be extracting relevant information for example, given that I am interested in getting the genres 
per song and each song can have many genres; what I will be doing is extracting those individual genres and then getting the count those genres appear per year and 
also decade. Furthermore, since I will have the information on the trends per year and decade I will use that information to get the songs and artists relevant to a 
given time. Also, since I have the billboard information for every week of the year I will only be extracting a week of each year.; I have picked the last week as the 
week I will be using for my analysis.

# Method and medium
This project will be completed by using shorthand. Such tool will give me the tools to interactively and creatively present information. Moreover, the charts I have 
sketched will be used as a model for the final visualization which will be done using either Tableau or flourish; those tools will allow me to display all the needed 
information for the public to understand the relation I am trying to build between trends in music per decade and the corresponding events that may have affected such 
trends.


# References
- kcmillersean. (2022, July 18). Billboard Hot Weekly Charts - dataset by kcmillersean. data.world. Retrieved November 20, 2022, from https://data.world/kcmillersean/billboard-hot-100-1958-2017 
