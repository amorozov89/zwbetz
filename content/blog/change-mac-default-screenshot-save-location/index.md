---
title: "Change Mac default screenshot save location"
date: 2019-08-16T15:34:19-05:00
tags: [mac]
toc: false
show_comments: true
---

Check the current screenshot save location. It's usually `~/Desktop`
```
defaults read com.apple.screencapture location
```

Change it to a new location. I save my screenshots to `~/Screenshots`
```
defaults write com.apple.screencapture location ~/Screenshots
```

Enjoy. 
