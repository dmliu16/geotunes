This is a project created by Jarret Liang, Melodee Li, Jeremy Zhang, and me at the 2017 TartanHacks at Carnegie Mellon University.


Inspiration

Pop music changes so much throughout the years, and we wanted to create an innovative way to visualize how lyrics around the world have shifted over time. This tool could be used by anyone who could be interested in music trends—music artists and producers could figure out what kinds of lyrics work in the current pop industry; business owners and consultants could capitalize on recurring themes in their products or advertisements; and even historians, journalists, and social scientists could analyze how current global issues have impacted the type of music that people enjoy at the time.


What it does

This webapp examines the lyrics of the top ten charting songs of nine countries (including US, UK, and Korea) from 2010 to 2016. The page first displays a world map, where users update the year they wish to view. Selecting a country will allow users to switch to Word Cloud mode. The word clouds allow users to view particular lyrics that stood out at the selected country and year. This component provides a detailed glance on the specific themes that the songs had. The page also displays a graph displaying the "sentiment values," of the country's songs, which would represent how positive or negative the words used were.


How we built it

The webapp was designed with HTML/CSS and uses Javascript, particularly AngularJS. Python was used to store the name and artists of all of the songs, which were inputted to the LyricsWiki api to extract the raw lyrics. The word clouds were made using Jason Davies' Word Cloud Generator. The sentiment values were calculated with a Microsoft Azure natural language processing program that would analyze the lyrics and determine how positive or negative the words were.


What's next for GeoTunes

In the future, we hope to complete the natural language processing component that was part of our original idea. We also hope to add more lyric data to our project so that our webapp has not only more years but also months. With more data over time, users can get a more detailed and comprehensive visualization. We also hope to make our map more interactive, possibly by adding a window that appears with extra details when the user hovers over a specific country.