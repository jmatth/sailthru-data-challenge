Sailthru Data Challenge
=======================

<h3>Background</h3>
There are lots of awesome APIs to play with at every hackathon. 
We wanted to give you something different: A huge set of data for you to hack on. The hack can be anything. 

A tool, an algorithm, a visualization, anything that our data can power. Mine it for whatever you’d like. 

<h3>Prize</h3>

<h5><a href="http://ledpixelart.com/pixel/">The Pixel</a> and a guest post on our engineering blog.</h5>  

<img src="assets/pixel.jpg">

<h3>Judging</h3>

Each of the below metrics will be judged on a scale of 1-3.
<ul>
 <li>Easy of use</li>
 <li>Creativity</li>
 <li>Insightfulness</li>
</ul>

<h3>Data</h3>
The data can be located here: 

In a JSON serializable format.

<h3>Schema</h3>

```
‘_id’: Sequential numeric ids

‘browser’: The browsers a user opens email with

‘browser_site’: The browsers a user opens links with

‘click_count’: Total link clicks the user has made

‘click_time’: Time of user’s last click

‘daily_click’: YYMMDD, number of clicks on that day

‘daily_message’: YYMMDD, number of emails the user received that day

‘daily_open’: YYMMDD, the number of email opens the user made that day

‘daily_pv’: YYMMDD, the number of pageviews a user generates that day

‘email_hour’: Number of opens within that GMT hour

‘geo’ : Email location user opened email from’, number of opens from that location

‘geo.count’ : Total number of email opens with geo-data’

‘geo.country’ : Total number of email opens per country

‘geo.state : Total number of email opens per state

‘geo.zipcode’ : Total number of email opens per zipcode

‘horizon’: Number of pageviews on pages with that interest tags. 

‘horizon_count’: Total pageviews

‘horizon_month’ : Total pageviews per month per tag. YYYYMM format for months

‘horizon_time’ : Last pageview date time

‘lifetime_click’ : Total clicks for the user

‘lifetime_message’ : Total email sent to the user

‘mobile_email_hour" : Mobile email opens per GMT hour bucket

‘mobile_site_hour" : Mobile website visits per GMT hour bucket

‘open_count’ : Total open count

‘open_time’ : Last open time

‘signup_time’ : When the user signs up for emails and on-site tracking

‘site_hour’ : Website visits per GMT hour bucket

‘urls_count’ : Total number of dynamic urls
```

<h3> Submitting </h3>

To submit entries make a pull request to:
https://github.com/zencephalon/sailthru-data-challenge
