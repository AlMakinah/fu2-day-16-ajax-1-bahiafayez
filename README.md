# AJAX

1. Using <a href="http://jsonplaceholder.typicode.com">JSONPlaceholder Fake API</a>, you're required to do the following:
	
	* Make an ajax request using the URL format: <em>http://jsonplaceholder.typicode.com/users/:id</em> to get and display some basic info (name, email & website) about User 1 on your html page
	* Make another ajax request to get all the posts made by User 1 and append them to your html page
  
2. Let's play around with some APIs. Using <a href="https://openweathermap.org/forecast5">Open Weather Map Forecast API</a>, make an ajax request to get and display the weather forecast in Cairo for the next couple of hours.
    Hint: Cairo's id is 360630
    
3. We'll be using the <a href="http://www.last.fm/api">LastFM api</a>. Go to that link, you'll find all the possible api requests you can make. Feel free to play around as you wish.

Note: We're providing you with the api key you'll be using in this exercise. If you want to create a new one at any point, you can do so by creating a new account, verify your email. Then you'll be able to create an application. You don't need to fill in the callback url or anything. When you submit you'll be given the api key.

You're required to do the following:

* We want to be able to search for an artist by his/her name. So create an html page with an input field for the user to enter the name and upon submitting, use the api to search for the artist.
* For every artist in the search results received, display their name, a thumbnail image and a link to their LastFM page.
* Make sure that for every new search, only the new search results are shown.
* Add a 'Show Top Tracks' button for every artist. When clicked, it displays this artist's top 3 songs/tracks. (Extra: Make this button hide the top tracks if they are shown, and shows them if they're hidden).
* Extra: Only display 10 artists at first and add a load more button that keeps on getting the next 10 artists. Hint: check the limit and page query parameters.
    
