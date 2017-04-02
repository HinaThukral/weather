# weather
In this project,I used one url to convert http to https because when I use only http it did not respond.So I just 
seearched on google why the api doesnot respond they give me this solution.
firstly I make function to get current weather
I get the temperature and description through api.
Then I use if-else statement for icon displaying.
I tried to display fiveday weather too
I used api for getting 16day weather
but I give it count for only five days.
var dt = new Date();
dt = dt.setDate(dt.getDate()+0);
firslt dt gets today's date by Date function
Then I just setDtate by adding number to get nextday date
To display five day I make list in html
Then I use document.getElementById to put in a list date,min_temp,max_temp

Thank You,
