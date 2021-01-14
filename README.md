# capitol-riot-tweets

A csv file with 80,000+ tweets from January 6th, 2021 -- the day of the capitol hill riots.

Nowhere close to the size of the Parler data dumps, but anyone with NLP experience might be able to find something useful here.

### Comments on data:
  - Each row comes with only a fraction of a tweet's data. You can use the tweet IDs with this tool to get everything: https://github.com/DocNow/hydrator
  - tweets have mentions, hyperlinks, emojis, and punctuation removed. All text is converted to lowercase.
  - Some tweets have coordinates (if users had geotagging enabled).
  - Verified users have their usernames included
  - "user location" is the user's self reported location in their profile. Blank if it doesn't correspond to a US state (or DC)
