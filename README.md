# Cinepath

Links to see the visualizations:

- [Cinepath: Paris, Texas](https://lilanyang.studio/cinepath-paris-texas)

- [Cinepath: Paris, Texas V2 with Customized Markers](https://lilanyang.studio/v2-cinepath-paris-texas)

- [Cinepath: Frances Ha](https://lilanyang.studio/cinepath-frances-ha)

## Project Overview
Started with rigorous research on where each scene of a movie was shot, Cinepath projects fictional spatial movement on real-life Google Maps as a personal voyage of cinema using data visualization to investigate how cinema creates new landmarks and reshapes the cultural landscape.

## Ideation
As a cinephile and an avid traveler, the way I learn about unfamiliar places and people and ultimately attempt to understand the world, is through the lens of cinematography. Both academically and personally, these interests have led me to ponder: how do filmmakers choose the locations to shoot? Where are those film locations in real life? And how would the visualization of the patterns be like through mapping between fiction and reality?

I was inspired by a video which mapped the opening scene of Baby Driver. However, instead of making a video with tools much as Adobe After Effects to animate all the routes, I had this visualization automaton in mind which uses webpages as the medium and allows user interactions to explore the map online.

## Data Collection
The most time-consuming process while developing Cinepath was to go through each film, breaking down a movie frame by frame to get actual timestamps, then researching the real filming locations. I used a multitude of resources: original scripts, director’s commentary, Internet Movie Database, other cinephile’s film location blogs, and even Google Maps Street Views as a cross-referencing tool.

However, as I dive deep into research, I found out that directors would intentionally choose their film locations that may not add up to the plots but serve either personal or atmospheric purposes. For instance, the director Wenders revealed in his commentary for Paris, Texas that he chose to film in a byway town just because of its same name with his grandfather.

## Implementation
Now we have coordinates, but how can we show the movement from point A to point B? Online Google Maps API Documentation has been extremely helpful resources to request a route with specific transportation methods varied from walking to public transportation. I wrote codes in JavaScript using Google Maps API as the generic method of visualization. Finally, I designed map layouts and customized colors based on the theme of and my emotional response to the film itself.

