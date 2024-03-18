# BBC Film Project – Film Critics' Favorites

## Main Findings:
- American critics tend to vote for US films
- War movies are more popular among critics, while Sci-Fi movies are more popular among the general public

## Data Collection and Analysis ##
- **Setting the scope:** There are millions of films existing out there, so I based this analysis on the BBC 100 Greatest Films in the 21st Century list. Being aware of its potential biases (as being American or Western-centric), I looked at how different critics from different countries voted; the list collected the films that are well-known, so the analysis is more relatable but aimed less to be representative as the whole world of films.
- **OMDb API:** The OMDb API gives a pretty accurate search for the 101 movies on the list. I fetched the data turned them into a data frame, and normalized the data on the 2nd layer.
- **Genre Analysis:** Genres were a part of the OMDb data, while the categorization is rather rough. 
## Growth ##
- I felt like an idiot dealing with all sorts of APIs, but in the end I could actually get the items I wanted!
## Things I wish I could do ##
- **Genre Analysis:** A better approach might be scraping the keyword/label data from the IMDb website (which does not offer free API) through the IMDB ID available in the OMDb data.
- **Critic Votes Analysis:** I would love to break it down further to countries/regions and test if critics are just prone to vote for movies from their own countries/regions
- **Genre List**: I probably didn't need to list out up to 10 genres, or I should've highlighted the difference. That graphic right now is just not informative. Definitely coming back to fix it.
