# Mute filters for Twitter
Some regular expression-based mute filters for Twitter

# Filters
regular expression | description
--- | --- | ---
`^(?i:@[a-z0-9_]+)\s*$` | Empty replies
`(?i:#[a-z0-9]+.*){3,}` | Tweets containing more than three **#hashtags**
`(?i:@[a-z0-9]+.*){3,}` | Tweets containing more than three **@usernames**
