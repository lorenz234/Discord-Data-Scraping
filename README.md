# Discord-Data-Scraping
Basic examples on how to scrape data such as member counts and messages from any discord server.


## How to get your authorisation key
To scrape data, a access key is required. Anyone with a discord account has a unique key.
To find out your authorisation key follow this simple 5-step tutorial:

1) open and log into your discord account on your web browser
2) activate developer tools on your web browser and navigate to "Network" tab
<img width="1080" alt="tut1" src="https://user-images.githubusercontent.com/90760534/134010659-349beab3-12cc-4d6a-ae4e-a45a2ae07c86.PNG">
4) while making sure the network activity is recorded, open up any random discord channel
5) navigate to "messages?limit=50" which is an api call request
6) under the tab "Request Headers" the authorisation key is listed as "authorization" 

## How to get a server_id or channel_id
The easiest way is to activate "Developer Mode" in your advanced discord settings. Once activated a simple right klick and "copy ID" will copy any id straight to your clipboard.
