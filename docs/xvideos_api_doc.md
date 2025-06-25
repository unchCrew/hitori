## Xvideos Scraper Bulk Scraper Pro API (from Apify)

This is a paid API service that allows you to extract video data from Xvideos using keywords. It provides titles, URLs, durations, thumbnails, uploaders, and views in JSON.

### Usage

To use this API, you need an Apify account and your API token. You can start the Actor by sending an HTTP POST request to the Run Actor endpoint. The Actor’s input and its content type can be passed as a payload of the POST request, and additional options can be specified using URL query parameters.

**Example (HTTP POST Request):**

```
POST https://api.apify.com/v2/acts/hello~xvideos-scraper/run-sync?token=<YOUR_API_TOKEN>
Content-Type: application/json

{
  "keywords": "latina",
  "proxyConfiguration": {
    "useApifyProxy": true
  }
}
```

After the run finishes, you can list the data from its default dataset via the API.

**Disclaimer:** This is a paid service. Integration will require an Apify account and API token.

