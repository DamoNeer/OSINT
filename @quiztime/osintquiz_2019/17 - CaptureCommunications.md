# Challenge

Go to the following coordinates: 34.069958, -118.403740
Zoom in all the way and find the two Samsung series 7 TV's that were captured in April 2019. What is the full MAC address of the TV that starts with "54:bd"?

# Solution

I solved this question using Wigle's API rather than looking at the map.

This is the request parameters I used: https://api.wigle.net/api/v2/bluetooth/search?onlymine=false&latrange1=34.0690&latrange2=34.0700&longrange1=-118.4040&longrange2=-118.4030&lastupdt=20190401&netid=54%3ABD%3A79&showBt=true&showBle=true&resultsPerPage=1000

It's important to note that I googled the MAC prefex of Samsung Electronics and it is 54:BD:79. This will significantly lower the results to just one device from hundreds.

Flag: 54:bd:79:4d:a9:a0
