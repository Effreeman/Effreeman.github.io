---
layout: post
title:      "CLI Data Gem "
date:       2018-06-11 00:42:32 +0000
permalink:  cli_data_gem
---


My first portfolio project was to create a CLI data gem. When I first started doing this project I was so overwhelmed and lost at what to do. Since this project will be part of my portfolio I wanted to make sure I did a good job on it. I watched the walkthrough videos and after finishing those I had a much better understanding on how to get started.

My first step was deciding what I wanted to scrape. I was debating between two ideas: dog friendly restaurants in Minneapolis MN and gluten free restaurants in Minneapolis MN. I started out with dog friendly restaurants and ended up changing it to gluten free restaurants half way through. The site I was trying to scape kept giving me an error and I ending up having to find a different site. At that point I decided to just switch to my other idea of gluten free restaurants. I have celiac disease and am always looking for gluten free restaurants in my area so I figured I could use this gem to solve this problem. 

After choosing my idea I had to build the CLI interface. Building the CLI came very easy for me and I flew through that part. I established a working CLI that out putted “fake data” in the form of strings to make sure everything was running correctly before I scrapped the real data I needed.  This project ended up taking me way longer then I thought it was going to because of the issue I was having with trying to scrape the first site. I was ready to just give up but then decided to just start on a clean slate. Once I switched my site everything just came together and I finished scraping the info I needed in under an hour. After a tad bit of debugging I had an up and running gem. I couldn’t believe how easy it was the second time around. 

It is a pretty simple scraper that gives you a list of restaurants that are gluten free and prompts you to select the number of the restaurant you want more info on. It then gives you the name, location, cost, features, and rating of the restaurant you choose. You can then type in another number or type exit to quit the app. 

You can check it out at https://github.com/Effreeman/minneapolis_cli_app
