## XNXX API Documentation (from GitHub - EchterAlsFake/xnxx_api)

XNXX API is an API for xnxx.com. It allows you to fetch information from videos using regexes and requests.

### Installation

This is a Python API, so it would be installed via pip:

`pip install xnxx-api`

### Usage

```python
from xnxx_api import XNXX

xnxx = XNXX()

# Search for videos
videos = xnxx.search("latin")
for video in videos:
    print(video.title, video.url)

# Get video details by URL
video_details = xnxx.get_video_details("https://www.xnxx.com/video-abcde/example_video")
print(video_details.title, video_details.duration)
```

**Disclaimer:** This API uses regexes and requests to scrape data from xnxx.com. The reliability might vary if the website structure changes.

