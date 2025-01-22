# The New Mainstream Media

This repository contains data collected and labelled by Bloomberg News featured in the story "[The Second Trump Presidency, Brought to You by YouTubers](https://www.bloomberg.com/graphics/2025-youtube-podcast-men-for-trump/)."

Our methodology is detailed at the [bottom of the article](https://www.bloomberg.com/graphics/2025-youtube-podcast-men-for-trump/#methodology).


### data/table_guests_by_channel.csv

A table of guest appearances across channels. Include the total views guests accumulated across channels, how many channels they were booked on, and our categorization of the guest.


### data/videos_by_topic.csv

603 videos with over 1-million views, for which Bloomberg analyzed for six political topics.  Topic columns are denoted with `#`, for example `#vote`. And subtopics feature `##`, for example `##vote_participation`.


Read how we categorized political topics and guests in our methodology.

### data/table_topic_summaries.csv

A table the percentage of videos per channel of each political topic (and sub-topic) we tracked. Aggregated from `data/videos_by_topic.csv`.

### data/guest_timeline.tsv

A record of the guests that appeared on each episode over the past two years. Guests whose videos are not on YouTube are recorded as a guest but contain no data on views.


### data/youtube_metadata.tsv

Metadata pulled from the YouTube Data API for 2,002 videos uploaded by the nine channels in our investigation from Nov. 2022 to Nov. 21, 2024. Importantly, contains views per video.

