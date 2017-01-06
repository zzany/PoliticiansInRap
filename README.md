Politicians In Rap

Quick Python script to search Genius for a keyword and then scrape the corresponding lyrics, date of release, and genre for the result. I then used TextBlob to determine the polarity of the sentiment of the line that includes the keyword in the lyrics (e.g. whether it is a positive or negative use of the keyword). 


Motivated by https://projects.fivethirtyeight.com/clinton-trump-hip-hop-lyrics/
Implementation borrowed heavily from Jason Q Ng (https://github.com/jasonqng/genius-lyrics-search/blob/master/README.md#genius-lyrics-search) and Big-Ish Data (https://bigishdata.com/2016/09/27/getting-song-lyrics-from-geniuss-api-scraping/) 


Credentials

Before running make sure you get credentials from Genius.com: https://genius.com/api-clients. Add them to credentials.txt and copy it to a credentials.ini.


Limitations
•	Only returns ~1000 results. Limitations of Genius API

•	Can’t filter results by genre. For example, I used this to query use of politicians names in Rap. Unfortunately, mostly news showed up (e.g. transcripts of speeches).

•	TextBlob sentiment analysis doesn’t work particularly well on rap.

