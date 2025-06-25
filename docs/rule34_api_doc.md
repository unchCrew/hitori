## Rule34 API Documentation (from GitHub - ClaustAI/r34-api)

This is a simple API to extract images from rule 34 AKA r34.

**Currently supported sites:**

- https://rule34.us

**Note:** The project is still under development.

### Installation

This is a Python Flask API, so it would need to be run as a service.

### Endpoints (based on typical Flask API structure)

- `/search` (GET/POST): Search for images with tags.
  - Parameters: `tags` (comma-separated string), `limit` (integer), `page` (integer)
  - Example: `/search?tags=cat_ears,1girl&limit=10&page=1`

- `/random` (GET): Get a random image.

**Disclaimer:** This API is still under development and its functionality or reliability might change.

