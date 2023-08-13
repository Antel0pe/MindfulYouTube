# APIs to Call

Get channel id of authenticated user - [here](https://developers.google.com/youtube/v3/docs/channels/list?apix_params=%7B%22part%22%3A%5B%22snippet%2CcontentDetails%2Cstatistics%22%5D%2C%22mine%22%3Atrue%7D#usage)

Get channel ids you are subscribed to - [here](https://developers.google.com/youtube/v3/docs/subscriptions/list?apix_params=%7B%22part%22%3A%5B%22snippet%2CcontentDetails%22%5D%2C%22channelId%22%3A%22UCCC6gdKpDDmIDGAcl9LEe0Q%22%7D)

Search for recent uploads - [here](https://developers.google.com/youtube/v3/docs/search/list?apix_params=%7B%22part%22%3A%5B%22snippet%22%5D%2C%22channelId%22%3A%22UCBAu5h7VZBV2HaXBuZcz9aA%22%2C%22order%22%3A%22date%22%2C%22publishedAfter%22%3A%222023-08-13T11%3A30%3A00-04%3A00%22%2C%22type%22%3A%5B%22video%22%5D%7D)

# Tasks
- Provides daily list of subscriptions
  - Email
  - Through extension interface?
  - Embedded video?
    - No other YT elements
    - Does AdBlock work with this?
- Gatekeeps accessing YT site
  - Each access requires text justification
  - Each subsequent 30mins requires new justification
  - Using search requires another justification
- View past justifications
- See daily time spent
