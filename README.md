# Discord-Data-Scraping
Basic examples on how to scrape data, such as member counts and messages from any discord server.

## How to get your authorization key
To scrape data, an access key is required. Anyone with a discord account has a unique key.
To find out your authorization key, follow this simple 5-step tutorial:

1) open and log into your discord account on your web browser
2) activate developer tools on your web browser and navigate to "Network" tab
<img width="1080" alt="tut1" src="https://user-images.githubusercontent.com/90760534/134010659-349beab3-12cc-4d6a-ae4e-a45a2ae07c86.PNG">
3) while making sure the network activity is recorded, open up any random discord channel
<img width="1080" alt="tut2" src="https://user-images.githubusercontent.com/90760534/134010806-44d752db-bc7d-4366-93f8-3862a1bf3bf3.PNG">
4) navigate to "messages?limit=50" which is an api call request. Under the tab "Request Headers" the authorization key is listed as "authorization" 
<img width="1080" alt="tut3" src="https://user-images.githubusercontent.com/90760534/134010810-97e7be70-43c3-41b2-93b5-4e95e420af96.PNG">

## How to get a server_id or channel_id
The easiest way is to activate "Developer Mode" in your advanced discord settings. Once activated a simple right click and "copy ID" will copy any id straight to your clipboard.
<img width="1080" alt="tut4" src="https://user-images.githubusercontent.com/90760534/134010812-597f59e8-5153-42ec-8c31-d36fd3a90c30.PNG">
<img width="673" alt="tut5" src="https://user-images.githubusercontent.com/90760534/134010804-d3dffe6f-a75f-4de3-964c-65432a5aac19.PNG">
