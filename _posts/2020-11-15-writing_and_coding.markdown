---
layout: post
title:      "Writing and Coding"
date:       2020-11-16 00:41:12 +0000
permalink:  writing_and_coding
---


For my Sinatra project, I made a website that would allow users to track the amount of words that they wrote per day. While this might seem like an odd concept, there's precedent for it: every year during National Novel Writing Month ("NaNoWriMo"), a large group of people will come together to write a book in thirty days during November. If this seems challenging, it is! The target word count is 50,000 words by the end of the month. For reference, by the end of this sentence, we'll have written just shy of 100 words (not including the title!).

So, take the above paragraph and multiply it 500 times (or 505 if we want to be finicky). Per day, to stay on "target" you should be writing about 1,667 words per day (or the above paragraph about 16-17 times). I've actually completed this challenge before a few years back. Last year, I created an Excel spreadsheet to keep track of my progress day by day. It looked a little something like this:


![](https://cdn.discordapp.com/attachments/703484589892698124/777688262843301908/unknown.png)


I didn't want to exactly clone that setup, because I wanted my website to be able to be useful for a wide variety of writing goals. There is a date logger along with wordcount, but rather than having an overall goal built into the instrastructure of the website, it tracks your entries in general. While NaNoWriMo creates a lofty goal, the discipline of it has stuck with me as I went throughout this course: getting something done every day, no matter how much. With that, I wanted users to be able to achieve their own goals rather than feel pressured to reach that 50k wordcount.

In my picture, you can see my wordcount vary wildly per day. That's the way of it: some days you can get more writing done than others, and some days you can get complete more material. Being able to see how your goals develop over time can help motivate you when you're struggling with feeling proud of everything that you've accomplished thus far, despite feeling like it's not been very much at all. 

Working on this project had a lot of ups and downs. I either had extremely productive days or I barely touched it. Despite all the labs leading up to this undertaking, I still found myself learning new things along the way so I could make my program function and be less clunky. There were definitely a fair amount of setbacks due to a variety of reasons. Despite using Corneal to set up the basic infrastructure, I lost several hours on trying to get my Update/Destroy actions working. It ended up being a simple fix (I had to add the `use Rack::MethodOverride` in my `config.ru` file) but after something like that, it's easy to get frustrated and feel like you haven't done much at all.

I wrote notes ahead of time and along the way (not unlike trying to make a story outline), but the best laid plans can still go awry. If you asked me specifically what gave me trouble, I'd be hard-pressed to explain; it felt like a bunch of little things that tripped me up. Things like deleting keys with empty values, using `if` statements in the actual erb file, linking up views and routes properly—there was always something else that needed fixing. 

Persistence is key to writing a novel or coding a program and being able to come out on the other side. I'm hoping it's a lesson that I don't forget to take to heart, even when it's feeling hopeless.
