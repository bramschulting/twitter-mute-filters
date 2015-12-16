# Mute filters for Twitter
Some regular expression-based mute filters for Twitter

# Filters
regular expression | description
--- | --- | ---
`^[^\p{Ll}]*$` | Tweets composed solely of all-uppercase words
`^(?i:@[a-z0-9_]+)\s*$` | Empty replies
`(?i:#[a-z0-9]+.*){3,}` | Tweets containing more than three **#hashtags**
`(?i:@[a-z0-9]+.*){3,}` | Tweets containing more than three **@usernames**
`^(?i:I liked a @YouTube video)` | YouTube auto-tweets
`^(?i:I checked in at .*yelp\.com)` | Yelp check-ins
`^(?i:I'm at .*4sq\.com)` | Foursquare check-ins
`(?i:star ?wars)` | ~~Marketing~~ Star Wars tweets

# Clients

## Tweetbot for Mac

1. Click *Mutes* tab or hit ⌘8
2. Scroll down to the *KEYWORDS* section and click *Add Keyword*
3. Copy and paste the regular expression in the *Keyword* field
4. Check *Regular Expression*
5. Click *Save*
