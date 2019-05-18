# Senior Capstone
This was my senior capstone project for Kansas Wesleyan University. 

## Description
This project brings together the power of google maps with weather information provided by [DarkSky](https://darksky.net/) to assist a user in selecting the best travel routes.

## Purpose
The purpose of this project is to create a single user interface that provides routing information along with accurate travel information based upon expected arrival times. While this could be done manually
by using seperate mapping/routing applications a single interface is much simpler to use. Using clickable image markers which are positioned over the various routes users get a quick overview of what the expected 
weather will be as they travel. This application has limited use for most motorists throughout the year but in the winter months or during storm season it would certainly be userful. Motorcyclists would benefit the 
most from this application as weather effects them more then any other type of motorist. During the winter months most motorists could find this useful if they are traveling between different locations that could be 
receiving large amounts of snowfall. 

The best way to demonstrate the purpose however is to use examples, which I've included below.

### Example 1
A motorcyclist has a 2 hour motorcycle ride from his origin to his destination. There are two different ways to get there, one goes south then east. The other goes north then east. By traveling the northern route 
the motorcyclist is going to run into a string of rain storms but if he takes the southern route he won't encounter those same rain storms and instead is looking at a cloudy afternoon. With both routes being approximately 
equal distance and taking around the same time the motorcyclist should opt for the southern route so he can avoid getting rained on. 

### Example 2
You're traveling from central Kansas to Chicago, Illinois in December. The best way to get there is to travel east to Kansas City then to head north on I35 until you reach Cameron, Missouri. From here you have two 
choices. Head east down highway 36, I72, then north up I55. Or continue north on I35 until you reach Des Moines then go east on I80. Both routes are within 4 minutes, and 20miles of each other. Since it's december there 
is currently snow coming down along I35 in Iowa but by the time your expected to be there it should be clear. The stretches along highway 36 and I72 are expected to see heavy snowfall as you arrive. In this scenario, 
neither options is perfect. They both have snow. However, you know by the time you get to Iowa the snow should be cleared and road crews have probably attended to the roads. This will make you select the route using I35 
to I80 because according to the predictions you won't encounter periods of active snow. 

## Notes
This program will not run out of the box. It is missing important API keys from both google maps and darksky.net API's. I removed these for privacy reasons and also to avoid being charged for useage outside of my own.

A Google Maps API Key will be missing on Line 15 in map.html - This key goes at the end of Google URL.

A DarkSky.net API Key will be missing on Line 3 weather.js - This key goes in the API Key variable.