---
layout: page
title: Next Steps
permalink: /next/
---
* Next Steps
	* Slideshows
	* Jekyll & GitHub
		* [Chrome extension](https://chrome.google.com/webstore/detail/gabriel/okimajjeocnndpifeelaajdebkkbckff?hl=en-GB) that converts Google doc to Markdown and commits to GitHub repo
	* Pandoc
	* Applications
	* Plain text workflows (pandoc?)


## Slideshows

There are several tools available for creating slideshows using Markdown syntax. The basic format is to use Markdown syntax as usual for the text (e.g., titles with `##` and bold and italics with asterisks, etc.) and use a special set of symbols to mark the separations between slides  (e.g., `* * *` or `---` ). There are online services for creating and hosting these presentations (such as [Swipe](https://www.swipe.to/markdown/)) or you can use a more DIY approach with [Reveal.js](http://lab.hakim.se/reveal-js/#/) or [Remark.js](http://remarkjs.com/#1). With Reveal.js, you can either convert your Markdown document to HTML (using [Pandoc](http://pandoc.org/README.html#producing-slide-shows-with-pandoc)) or [embed the Markdown into the HTML elements](https://github.com/hakimel/reveal.js#markdown) that make up the slideshow. With Remark.js, you can leave the Markdown document as is, but all the files must be uploaded to a web server (or run as a local web server) to function.

Overall, the benefits here are that you can use an existing outline written in Markdown (say, maybe some lecture notes) and immediately turn it into a slideshow. Or you can convert speaking notes into a slideshow quickly.

Tim Lockridge created [a slideshow using the Swipe service](https://www.swipe.to/6414fs) for a class lecture, and Tim and Derek Van Ittersum used the Remark.js system to make their [CCCC2016 slides](http://processedword.net/cccc16/#1).

## Blogging

As was discussed in the workshop, Markdown can be great for blogging, since it's easy to convert a blog post written in Markdown in a text editor to an HTML snippet that can be pasted into a Wordpress (or similar blogging service) text area. However, several other kinds of blog software allow users to turn a collection of Markdown documents into a blog without converting to HTML or using a web dashboard. These systems are typically called "static site generators" because they take input files (typically Markdown documents) and use them to generate a set of static HTML files that comprise the website. In other words, while Wordpress uses a database to create a blog site, and requires frequent updates and management via the web dashboard, static site generators just create plain old HTML files that can be uploaded to a web server the old-fashioned way.

One of the most popular static site generators is [Jekyll](https://jekyllrb.com/). Jekyll, as with most of these types of software, requires using the command line and can appear a bit intimidating. However, there are many great tutorials ([This one by Tania Rascia](https://www.taniarascia.com/make-a-static-website-with-jekyll/) is great) that walk you through each line of text that needs to be typed into the command line. In fact, if you want to start learning to use the command line for other kinds of projects, setting up a Jekyll site would be a great place to start. Additionally, as with Wordpress, there are [many themes that users have shared](http://jekyllthemes.org/), so you don't have to style the site yourself if you're not comfortable with CSS or graphic design. Even better, you can create a Jekyll site and host it on GitHub for free. Jonathan McGlone has [a great tutorial for using GitHub for Jekyll sites](http://jmcglone.com/guides/github-pages/).
