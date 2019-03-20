---
layout: post
title:      "Not all websites are created the same."
date:       2019-03-20 19:47:55 -0400
permalink:  not_all_websites_are_created_the_same
---


For my first project, we were to create an interactive CLI gem. For most of the project, I was deadset on travel. The wanderlust part of me was craving to find out new places to potentially travel to and all in all, it seemed like a fun project until I got to the scraping. Either the websites had novice HTML that either made it hard to scrape or a robust website like National Geographic that had Javascript running on the main page, and well, Nokogiri and Javascript don't go hand in hand. 

Time was running out as far as the deadline went and every travel website was yielding fruitless results so I turned to the aid of one of the instructors for advice. I wound up revamping the project Saturday and switched gears to focus on Harry Potter. More specifically, Harry Potter illustrated editions from Bloomsbury. 

While most of my time was spent scraping, I learned a lot about how objects interact with each other. It's hard to wrap your mind around how a word can be an object and can refer to its self and to think outside the box. Once you can grasp that and well, I'm still learning, it's much easier to comprehend Ruby's concepts and to code freely. 

Not to say I didn't learn how to scrape, however. Some tips that I learned are:
* Each piece of data needs to massaged and manipulated in Ruby in order for it to display properly to the user. I also learned that using robots.txt after websites helped with understanding permissions. Simply some websites are not allowed to be scraped. 
* You also want to be aware of tables. Tables make selecting the data much more complicated. While it is doable, expect groans. Luckily, most modern websites don't use tables. 
* If you trying to scrape a site that has JS running, Watir is your best bet. I would have used Watir, but again, pressed for time. 
* Look for websites that have easy selectors. 
* If you are in need of finding out if a website is scrapable under a min, I highly recommend https://repl.it/repls/PaleDecimalPublishers. Here, you just input in a few bits of information and you're good to go. 
* Remember, the website itself shouldn't be the most time consuming part. If it's becoming that way, switch! It's much better to have a sophisticated CLI, then a haphazard site just to get similar data. There are literally thousands of websites on topics that your CLI idea could fall under.

Ideally, I would like to make a more robust CLI in the future now that I'm aware of a scraper from one of the professors that makes picking a website much more simple. If you're curious in my latest project, check out my github link at : https://github.com/heather-kirk/harry_potter_cli. 

Will write back again soon!
