# RedDown
Client-side Reddit Media Downloader

Check out the website:
## https://red.buzl.uk

If you want to integrate this service in your own subreddit, add the following rule to the automoderator config:
```
---
# Client-side Media Downloader
# Written by @kaangiray26

type: submission
comment_stickied: true
id (regex): '.*'
comment: |
    # [Download](https://red.buzl.uk/?id={{match}})
---
```
