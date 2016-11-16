---
layout: post
title:  "Reflections on Examination 1"
date:   2016-11-16
categories: jekyll update
---

### Client based web programming, examination 1

The first assignment in this course is this web page, as well as some reflections on the technologies involved. I will address these under separate headlines below.

# Pre-compiling CSS
My first thoughts of pre-compiling CSS was a bit sceptical. While I got the idea behind it,
I never really thought of writing the CSS for a site as a very cumbersome task. For sure it can get a bit repetitious,
 but I wasn't really sure the hassle of CSS was enough to warrant a change into scss. Eternally curious as I am, and considering
 the busy schedule of my work life and studies, I'm always interested in trying out methods that may eventually be beneficial and time-saving.

 My impressions so far are after all mostly positive. I think the main advantage that I see myself in this is
 the ability to use variables, which really helps structuring for instance the colour scheme for a site.

I used variables to start figuring out a colour scheme for my site, and tried out the inheritance functionality,
at the moment for my one and only picture, but the idea is that more will come.

Pros of scss are definitely the added functionality of variables, nested rules, inheritance and others.
It does have the potential of making work easier when building at least somewhat more complex sites.

Disadvantages of pre-compiling css? For starters it's another layer to learn and keep track of. For a simple site it may simply not be worth bothering.
In a way scss adds complexity to your css, which of course can be a huge advantage, and in some ways simplify matter - but it can also result in a code that is
more difficult to maintain and overlook.

# Static site generators
The site that I have the most experience working with is not surprisingly the web site for the school that I'm working at.
Since we were very few people in the beginning me and the principal helped each other take care of the web site for two and a half years
before I got fed up with the way the site is operated and asked to get my admin rights removed. I must say that if I could have worked in this manner with scss and
static site generators I probably wouldn't have minded the task as much, instead of the version of Drupal that is Stockholm City's nightmarish web maintenance tool.

That said...I would have preferred doing the whole thing in notepad rather than the system we are stuck with. Still, I think that for that kind of fairly extensive sites,
where you don't need dynamic content and only a few people need to be doing the updates to the site, this way of working is quite nice. On the other hand, for some of the
projects that we would like to develop in-house at the school, static just won't work for us since we will actually need content to shift depending on the users' needs.

# Robots and humans
Robots.txt is a file that you can put in the root directory of your site for passing robots (for instance search engines that look at your site) to read. here you can
for instance let these robots - the nice ones at least - know what parts of your site you don't want them to look at. this does not, however, protect your site from malevolent robots.
 You can do some things to protect your site from bad robots, at least if you know the id of the bot, but mostly the bad bots will ignore your robots.txt and look around anyway.
 My robots.txt is set to disallow the reading of my blog. If course, that partly defeats the purpose of having a blog, but for now that's the way I want it.

Humans.txt on the other hand, is not similarly a file that tells visiting humans what to do, but rather a file that conveys information about who has done the work with the site.
Of course, in a lot of cases companies or organisations don't advertise openly on the site who has actually done the technical work of building the site.
Humans.txt is then a place where you can let these people get credit for their work without having it on your site, but that people who are in the know can find relatively easily.


# Comments
To get comments implemented in static sites it seems disqus is one of the most common tools, and I figured it was worth trying out. It was also easy and straight forward
to get working, since the code is provided, all I had to do was point to the right place.

# Open Graph
Open graph lets you add tags to your sites that gives you some control over how your site looks when people share it on social media, for instance what picture
shows as thumbnail, what text, and such. I kept the use of it basic to start with, adding just a picture link, name of site, type, description and url.
