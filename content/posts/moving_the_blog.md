---
title: moving the blog
description: A small project to move the blog with the aid of AI or
tags:
  - wordpress
  - Hugo
  - Homebrew
  - Markdown
  - Cloudflare
date: 2026-04-14T23:00:00.000Z
draft: false
categories:
  - small-news
  - technology
  - webstuff
author: admin
lastmod: 2026-04-17T21:02:30.365522Z
showSummary: true
url: /posts/moving_the_blog/
cover:
  image: /images/2026/04/1C291766-9CE7-4FA0-9ADA-F61126692E32-38323-00000657148B6B8B.jpg
  alt:

---


moving the blog!

Over the last couple of weeks, I've completed a small technical project. And it was remarkable so that I will remark on it here. 

The project was to move my blog from WordPress, a dynamic CMS, to a static site. This change will make the blog lighter. I also hope the process of actually putting blog posts up feels lighter. 

The project will see me move blog hosting from my own hosting (the hosting I use for a website) to free providers, using the protection and infrastructure Cloudflare provides for websites. This lets you build a website on their servers for free and pull information directly from GitHub.
[](/images/2026/04/1C291766-9CE7-4FA0-9ADA-F61126692E32-38323-00000657148B6B8B.jpg)

The project took several steps to work through: 
Exporting the WordPress files
Installing Homebrew
Using Homebrew to install Hugo, 
Ensuring the exported files were converted to Markdown,
Uploading the files to GitHub, 
Building the site in Cloudflare Pages from the GitHub resources. 

It was also my first attempt to use the Claude AI engine. I had heard about the Claude AI engine and that it was good for a lot of things, particularly technical software. And I would like to know if it can help me with that. So I used that Claude AI system to help me move around. 

What I used for the project.
To achieve the project, my main tools were the Claude AI LLM web interface, the macOS terminal, a GitHub account, and a Cloudflare account. I already had a GitHub account for work stuff, and I also had a Cloudflare account because I put the front page of my website on the service for faster response times and the added protection it provides. 
 
AI. Ok, but not good.
The process took about a month. It could have been faster if I had paid for Claude. That would have given me more tokens and allowed me to finish the process, but I started and finished it. I used the free account software to get me through the process, so it took longer. Claude also has a significant issue with not giving you the right answer. Most of the time, it was right, and it was Claude. Claude 4.6 I was using most of the time it was right, but by most, I mean 65 to 70%. However, quite often, what it was advising it missed something out, reinforced things, or said, 'do it a different way,' and those were the ones that even worked.
 
The ethics of AI are worth considering because, as a thing, AI promises much but delivers very little. AI promises to take all our jobs and enhance all our lives. (Except the founders and funders of AI keep pausing unnervingly when asked a question about human beings enduring... like Peter Thiel here https://youtube.com/shorts/LXpc1YiXDoQ?si=4wMtX3t5uibwXpbg ). 
The actual delivery of AI resulted in AI giving the wrong answer 30% to 35% of the time. The questions I was asking were about my project, not an obscure project. The answers are clear. The answers are well-documented. The answers are also demonstrable, because if they are wrong, you get an error message. There are correct, well-documented answers that AI, through whatever means, has consulted and knows. It should not have given me wrong answers. However, it did. Ethically, I'm not scared AI is going to take all our jobs and change life, except for the human trait of laziness. It's not going to deliver on the promises it's making. And as investment opportunities go, it's not nearly meeting the possibilities outlined for the new world. This makes me ask: 
Why are they spending money on building massive data centres, when diverting water supplies is causing people living in deserts to go without water? 
Why do they spend money on data centres to enable a process they don't know, one so all-encompassing it requires more data capacity, water, and electricity? All so it can answer small questions with a correct answer, but the AI gives the wrong answer. It doesn't sound like good value for money; it does not feel like AI is currently.
 
There is no value in AI for me based on this experience. It provided a shortcut, so I didn't need to learn to experiment. The whole point of the project was to learn something new and expand my knowledge. Instead, I got better at prompt engineering. I am not sure I want to be good at prompt engineering. Meanwhile, on my project, I learned nothing about the underlying technologies or how to use them.

Based on this project, it's not going to deliver on the promises that it is currently making. The project asked clear questions, and it did help me 60% of the time. It was more convenient. It saved me from having to read a bunch of technical documents on how to do the project steps. However, it was unsatisfying. I am not much further forward.

The project.
The first need was to export the WordPress files from my current blog. Fortunately, WordPress has a very useful tool for exporting files. However, my web hosting provider recently transferred all their data to new hardware, and it didn't go smoothly; my blog stopped working. The self-managed WordPress install I use uses databases and SQL to control it all, and during my web hosting company's move, the databases got corrupted. So much so, I spent 3 months trying to debug why and what rare issue had corrupted the databases. So I decided to move. I was annoyed by WordPress. 

I could have moved to the managed WordPress.com, but its system to add ads to your blog site seemed like too many paper cuts on top of the pain of the blog stopping. So it was best for me to move from a self-hosted solution to a managed one with no ads, which would feel lighter to use. So, I decided to leave WordPress, exported all my data, and thanked them for their service and for the export tool that worked well, even though the blog install itself did not. 

The next move was to install Hugo. I had heard of Hugo as a lightweight, front-end tool that generates a static site; it renders plain-text Markdown files via a CSS file as a website. I installed Hugo with a couple of lines in the terminal. It worked well, guiding me through the process: telling me what to do, and what not to do!

To do this, I installed Homebrew on macOS. Homebrew technically is a package manager. In non-jargon terms, it basically downloads things that your computer (macOS or Linux) didn't come with. Most people will not need Homebrew, but as Hugo is one of the things it operates, I did.

Once Homebrew was installed, I installed Hugo—a very painless experience. 

Next, I added the WordPress to Hugo plugin, which converts your WordPress export into Markdown files that Hugo can read.
This proved troublesome. The AI really struggled with this, suggesting several ways to fix the Markdown files so they were properly rendered in Hugo.

There was also a significant period when the test local site was not working. And in testing, it returned several 404 and 403 errors. That took several hours to try different solutions and eventually get it right. The AI confidently presented its suggested solutions, editing the .yaml file, adding and deleting lines, and adding new ones. But the solution proved to be elusive for several hours. Hmmm. 

Once I had the files in markdown format, I could transfer the content. I uploaded this file to a GitHub repository; this part was painless.
 
I linked the Cloudflare Pages build to the GitHub files. The Cloudflare Pages site could then automatically read the GitHub repository and, using the Hugo install, the CSS file, and the markdown files, build the website. The process was straightforward, and everything worked seamlessly. But it wasn't right; there was an issue with the .yaml file or the CSS, so it was being rendered incorrectly. It took hours to fix. Every issue, AI would confidently assert that this will work. When it didn't work, the AI would tell me I now know what the problem was. This fix will 100% work. etc..... However, it is all fixed now. 

The result is blog.smpaget.com, a site that loads quickly and features a clean and (if I may be so bold) good-looking design.

So I've changed the web address at the top of this, the front page, to open the blog site. I also had to update the CNAME entry in DNS. The CNAME attribute for sm.paget.com points the blog to its domain rather than treating it as a subdomain. To make a blog a subdomain, point it to an exact URL that points to a specific part of the pages. You don't have to know all this. However, I'm more than happy with the results.

My new process is to use the HugoNest app on iOS, a simple Markdown editor, to write these blog posts. I then push the files to GitHub, and they go live on the website.
It's more convenient and easier. It feels lighter than the WordPress process I used before. It looks fresher and has a flatter design. It looks better for it.
 
I'm interested to hear your thoughts on this transition. Bye 
