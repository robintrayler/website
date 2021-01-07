+++
author = "Robin B. Trayler"
title = "Website building with Hugo"
date = "2021-01-03"
description = "How I built my website"
draft = true
tags = [
    "hugo",
    "website",
    "markdown",
]
categories = [
    "website",
    "hugo",
]
series = ["Web design"]
+++
# Heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6

This is my personal website. I'm building it using [Hugo](https://gohugo.io), a framework for generating static websites. I previously used [Wordpress](www.wordpress.com) for a now defunct website but I was not happy with it for a variety of reasons, but mostly because it cost $50 a year to host my fairly simple page. 

I'm using this post to track my progress and take notes on the website development and deployment process. I'm not a developer so my hope is this will serve as a reminder when I *inevitably* forget how I did it. 

# Hugo Setup
I followed [This](https://gohugo.io/getting-started/quick-start/) guide to install Hugo and get it running. I already had the [Homebrew](https://brew.sh) package manager installed on my laptop (2020 MacBook Pro running macOS 11.1). I used the following terminal command to install Hugo. 

```
brew install hugo
```

I created a new subfolder in my personal Dropbox and created a new Hugo site there. 

```
cd ~/Dropbox/
mkdir personal_website
```

```
{{< highlight R "linenos=table">}}
library(tidyverse)
data <- read_csv(file = './data/wolves.csv')
data %>% ggplot(mapping = aes(x = d13C_collagen, y = d15N_collagen)) + geom_point()
{{< /highlight >}}
```

![robin](/./images/profile.jpeg)