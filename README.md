# Crawler

Scrap the content of https://www.ljll.math.upmc.fr/MathModel/jobs/theses.html and send me a mail when we detect a new thesis offers.

## First try
We can start by using scrapy.
Store the mail subscriber, and add more site and format.

## All manual
After that we will try to implement all key feature manually (use request, parse the page content (ElementTree or lxml) compare file, cron job. configure a mail sender on my domain, host the all (flask, heroku)...)

## Step
Lauch the jobs at scheduled time
Scrap
Compare to yesterday
Send mail if need with the new offers

#### Client side
Litle interface to subscribe to a site

## Other site possibilities
- https://jobs.inria.fr/public/classic/fr/offres
- ABG
- ONERA

## Question
---
Some questions that I ask myself and I try to ans
1. How work requirment.txt?
2. What is a callback ?
3. Asybscronous vs syncronous
4. @classmethod
