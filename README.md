# Open Recipe

Users can login and upload recipes and pictures of food or drinks as well as edit and delete their own uploaded recipes. Other users can search for, like, dislike and comment on the recipes

**Link** https://open-recipe-v1.herokuapp.com/

![cocktailscreenshot](https://github.com/TravyTheDev/TravyTheDev/blob/main/recipe-screenshot3a.png?raw=true)

## How it's made:
**Tech used:** React, Node, Express, MongoDB

I wanted personalized accounts, linked recipes, comments, likes and dislikes, as well as being able to edit and delete your own content. Most of my time was definitely spent getting the front end to correctly pass data to the back end.

### Optimizations 
1: The styling isn't the best.

2: I should have added set character limits and fixed heights for the pictures on the front page reel.

3: I probably should have done a loading screen or a spinner.

4: There should be a function to reset passwords.

### Lessons Learned:
You won't have data if you don't actively fetch the data whenever you need it. At first I figured because I was keeping the user state with redux that I'd just have data when I needed it, but nothing loads at first unless you call the API. 

Usually when you pass a body from your API, at least in my case, you only need to pass 1 thing, you don't need to pass an object or it won't be passed correctly. Then in your function to pass data you need to label everything correctly so your route knows what's coming. 

Heroku is very finicky and everything has to be perfect or you will have bugs. 
