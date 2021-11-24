# song-recommender

# Case Study: The site for recommendations - "Gnod"

### Scenario

You have been hired as a Data Analyst for "Gnod".

"Gnod" is a site that provides recommendations for music, art, literature and products based on collaborative filtering algorithms. Their flagship product is the _music recommender_, which you can try at [www.gnoosic.com](https://www.gnoosic.com). The site asks users to input 3 bands they like, and computes similarity scores with the rest of the users. Then, they recommend to the user bands that users with similar tastes have picked.

"Gnod" is a small company, and its only revenue stream so far are Ads in the site. In the future, they would like to explore partnership options with music apps (such as _Deezer_, _Soundcloud_ or even _Apple Music_ and _Spotify_). However, for that to be possible, they need to expand and improve their recommendations.

That's precisely where you come. They have hired you as a Data Analyst, and they expect you to bring a mix of technical expertise and business mindset to the table.

Jane, CTO of Gnod, has sent you an email assigning you with your first task.

### Task(s)

> This is an e-mail Jane - CTO of Gnod - sent over your inbox in the first weeks working there.

_Dear xxxxxxxx,
We are thrilled to welcome you as a Data Analyst for *Gnoosic*!_

_As you know, we are trying to come up with ways to enhance our music recommendations. One of the new features we'd like to research is to recommend songs (not only bands). We're also aware of the limitations of our collaborative filtering algorithms, and would like to give users two new possibilities when searching for recommendations:_

- _Songs that are actually similar to the ones they picked from an acoustic point of view._
- _Songs that are popular around the world right now, independently from their tastes._

_Coming up with the perfect song recommender will take us months - no need to stress out too much. In this first week, we want you to explore new data sources for songs. The Internet is full of information and our first step is to acquire it do an initial exploration. Feel free to use APIs or directly scrape the web to collect as much information as possible from popular songs. Eventually, we'll need to collect data from millions of songs, but we can start with a few hundreds or thousands from each source and see if the collected features are useful._

_Once the data is collected, we want you to create clusters of songs that are similar to each other. The idea is that if a user inputs a song from one group, we'll prioritize giving them recommendations of songs from that same group._

_On Friday, you will present your work to me and Marek, the CEO and founder. Full disclosure: I need you to be very convincing about this whole song-recommender, as this has been my personal push and the main reason we hired you for!_

_Be open minded about this process: we are agile, and that means that we define our products and features on-the-go, while exploring the tools and the data that's available to us. We'd love you to provide your own vision of the product and the next steps to be taken._

_Lots of luck and strength for this first week with us!_

_-Jane_

## Useful Resources
- https://www.w3schools.com/tags/default.asp
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview
- https://www.guru99.com/difference-get-post-http.html
- https://www.dataquest.io/blog/python-api-tutorial/
- https://www.dataquest.io/blog/last-fm-api-python/
- https://apipheny.io/free-api/
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Status
- https://flukeout.github.io/
- https://www.dataquest.io/blog/web-scraping-python-using-beautiful-soup/
- https://www.dataquest.io/blog/web-scraping-beautifulsoup/
- https://codebeautify.org/htmlviewer?__cf_chl_captcha_tk__=pmd_NIlVq3JKNsYQV7mLl5nR5bsOK7foKgGpUlFvfyc7reI-1631203190-0-gqNtZGzNArujcnBszQrR
- https://www.oreilly.com/library/view/web-scraping-with/9781491910283/
- https://developer.spotify.com/documentation/web-api/reference/#category-search
- https://www.cleo.com/blog/knowledge-base-what-is-an-api
