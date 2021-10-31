# CLIMATE NEWS API
This is a simple web scraping API that scrapes the major news websites for climate news and returns the response in json format.

## Dependencies Used
-   **[Cheerio](https://cheerio.js.org/)**
-   **[Express](https://expressjs.com/)**
-   **[Axios](https://www.npmjs.com/package/axios)**
-   **[Nodemon](https://www.npmjs.com/package/nodemon)**

### Resources
The API only has two endpoints.These resources are responsible for returning the scraped news articles' response.

#### All News
The endpoint `GET` `/news` returns climate news from the various scraped news sites

#### Single News Publisher
The endpoint `GET` `/news/:newspaperid` returns climate news from a specific news site that satisfies the query string e.g /news/guardian will return the climate news from the guardian news website. 