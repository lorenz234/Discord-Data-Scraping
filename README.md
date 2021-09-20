# Discord-Data-Scraping
Basic examples on how to scrape data such as member counts and messages from any discord server.


# How to get your authorisation key
To scrape data, a access key is required. Anyone with a discord account has a unique key.
To find out your authorisation key follow this simple 5-step tutorial:

1) open and log into your discord account on your web browser
2) activate developer tools on your web browser and navigate to "Network" tab
3) while making sure the network activity is recorded, open up any random discord channel
4) navigate to "messages?limit=50" which is an api call request
5) under the tab "Request Headers" the authorisation key is listed as "authorization" 

# How to get a server_id or channel_id
The easiest way is to activate "Developer Mode" in your advanced discord settings. Once activated a simple right klick and "copy ID" will copy any id straight to your clipboard.
