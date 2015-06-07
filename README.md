# Mute filters for Twitter
Some regular expression-based mute filters for Twitter

regular expression | description | Tweetbot
--- | --- | ---
`(#[A-Za-z0-9]+.*){3,}` | Tweets containing more than three **#hashtags** | [Add to Tweetbot](tweetbot:///mute/keyword?regex=1&text=%28%23%5BA-Za-z0-9%5D%2B.%2A%29%7B3%2C%7D)
`(@[A-Za-z0-9]+.*){3,}` | Tweets containing more than three **@usernames** | [Add to Tweetbot](tweetbot:///mute/keyword?regex=1&text=%28%40%5BA-Za-z0-9%5D%2B.%2A%29%7B3%2C%7D)
`^\W*(@[A-Za-z0-9_]+\W*)+$` | Tweets composed entirely of @usernames | [Add to Tweetbot](tweetbot:///mute/keyword?regex=1&text=%5E%5CW%2A%28%40%5BA-Za-z0-9_%5D%2B%5CW%2A%29%2B%24)
