---
layout: page
title: Next Steps
permalink: /next/
---

## Slideshows

There are several tools available for creating slideshows using Markdown syntax. The basic format is to use Markdown syntax as usual for the text (e.g., titles with `##` and bold and italics with asterisks, etc.) and use a special set of symbols to mark the separations between slides  (e.g., `* * *` or `---` ). There are online services for creating and hosting these presentations (such as [Swipe](https://www.swipe.to/markdown/)) or you can use a more DIY approach with [Reveal.js](http://lab.hakim.se/reveal-js/#/) or [Remark.js](http://remarkjs.com/#1). With Reveal.js, you can either convert your Markdown document to HTML (using [Pandoc](http://pandoc.org/README.html#producing-slide-shows-with-pandoc)) or [embed the Markdown into the HTML elements](https://github.com/hakimel/reveal.js#markdown) that make up the slideshow. With Remark.js, you can leave the Markdown document as is, but all the files must be uploaded to a web server (or run as a local web server) to function.

Overall, the benefits here are that you can use an existing outline written in Markdown (say, maybe some lecture notes) and immediately turn it into a slideshow. Or you can convert speaking notes into a slideshow quickly.

Tim Lockridge created [a slideshow using the Swipe service](https://www.swipe.to/6414fs) for a class lecture, and Tim and Derek Van Ittersum used the Remark.js system to make their [CCCC2016 slides](http://processedword.net/cccc16/#1).

## Blogging

As was discussed in the workshop, Markdown can be great for blogging, since it's easy to convert a blog post written in Markdown in a text editor to an HTML snippet that can be pasted into a Wordpress (or similar blogging service) text area. However, several other kinds of blog software allow users to turn a collection of Markdown documents into a blog without converting to HTML or using a web dashboard. These systems are typically called "static site generators" because they take input files (typically Markdown documents) and use them to generate a set of static HTML files that comprise the website. In other words, while Wordpress uses a database to create a blog site, and requires frequent updates and management via the web dashboard, static site generators just create plain old HTML files that can be uploaded to a web server the old-fashioned way.

One of the most popular static site generators is [Jekyll](https://jekyllrb.com/). Jekyll, as with most of these types of software, requires using the command line and can appear a bit intimidating. However, there are many great tutorials ([This one by Tania Rascia](https://www.taniarascia.com/make-a-static-website-with-jekyll/) is great) that walk you through each line of text that needs to be typed into the command line. In fact, if you want to start learning to use the command line for other kinds of projects, setting up a Jekyll site would be a great place to start. Additionally, as with Wordpress, there are [many themes that users have shared](http://jekyllthemes.org/), so you don't have to style the site yourself if you're not comfortable with CSS or graphic design. Even better, you can create a Jekyll site and host it on GitHub for free. Jonathan McGlone has [a great tutorial for using GitHub for Jekyll sites](http://jmcglone.com/guides/github-pages/).

## Markdown Applications

One of the benefits of creating Markdown documents is that they are [plain text files](http://www.macworld.com/article/1161549/forget_fancy_formatting_why_plain_text_is_best.html), meaning that you can open them in nearly any application rather than being limited to proprietary tools and formats. Because Markdown is a relatively simple syntax, application developers can easily support it in their apps. Great apps dedicated to supporting Markdown exist on all platforms (Mac, Windows, Linux) and even as web apps, meaning you can create and open you Markdown files in a variety of apps in order to take advantage of their unique features. It's not necessary to pick one and stick with it forever.

There is a greater diversity of apps in the Apple ecosystem (OS X and iOS), but many great apps exist on Windows and Linux as well. Here are a few examples of some of the interesting features that set different apps apart and can be valuable for different writing tasks and workflows:

* [FoldingText][foldingtext] is a Mac app that allows you to "fold" sections of text based on the Markdown headers. For example, you could hide all the sections of a document except header 3.1, or you could only show the top level headers, or only the fourth level headers, etc. Additionally, FoldingText has a very minimal interface, for those that prefer the "distraction-free" aesthetic
* [MultiMarkdown Composer][multimarkdown], another Mac app, offers a dedicated preview window (which allows you to see the Markdown in one window and the rendered HTML in another) and has some great features for manipulating the document via dragging and dropping headers in the Table of Contents menu. Additionally, MultiMarkdown Composer has unparalleled support for [CriticMarkup](http://criticmarkup.com/), an additional syntax built on top of Markdown that provides features similar to "track changes" in a word processor.
* [Texts][texts] is a Windows app with support for academic citations and support for export templates, meaning you can write your Markdown document in Texts and then export it to PDF or docx or other formats from the app itself. Further, Texts has a "rich text" interface (like FoldingText), which means that you type in the Markdown syntax (e.g., asterisks for bold) but what you see on the screen is bold text.
* [MdCharm][mdcharm] is another Windows app that allows you to open a whole folder of Markdown files at once, showing them in a hierarchical folder view in a small pane on the left side of the app. This lets users quickly and easily select different files to edit.
* [Ulysses][ulyssesapp] and [Byword][bywordapp] and both Mac and iOS apps that sync files seamlessly between your computer and mobile device. In addition, Ulysses offers some interesting features related to file management, allowing users to write in "sheets" that are stored in Ulysses instead of as separate files on the computer. Sheets can be rearranged and combined to export to a single file in a variety of formats (Markdown, HTML, PDF, docx).
* [Scrivener][literatureandlatte] is a Mac or Windows app similar to Ulysses, that stores all the text inside the app, letting users work with an outline of "sheets" that can be manipulated more easily than multiple files.
* [Editorial][omz-software] is an iOS app that includes a text manipulation system built on the Python scripting language. This means users can build "workflows" that can do things to the text in a Markdown file, such as a find and replace (not often possible on mobile apps), manipulating Markdown formatted links, automatically adding links based on open tabs in the web browser, etc. Users without any knowledge of Python can still take advantage of Editorial's power by [downloading workflows shared by other users on the web](http://www.editorial-workflows.com/workflows/staff-picks).
* [Marked][marked2app] is a Mac app that doesn't edit Markdown files (you can't write a Markdown document with it), but instead opens Markdown files and allows users to preview the file and run checks (e.g., Marked will validate all the web links in the document) as well as export using various templates (to HTML and PDF).
* [nvALT][brettterpstra] is a Mac app that can serve as a quick notebook and scratch pad. At the top of the window is a search bar, like a web browser. You can type the name of a file in the bar and it will open immediately, or you can type a new file name and press enter to create the file. Great for small notes to self and reference notes (e.g., keep a Markdown syntax cheat sheet in there).
* Text editors, typically used by programmers to create code, can also be great for Markdown. [Atom][atom] and [SublimeText][sublimetext] (both Mac and Windows) both have many packages dedicated to supporting Markdown. Atom even has a package that will [render a Markdown document like a mindmap][atom 2].


[atom]: https://atom.io/
[atom 2]: https://atom.io/packages/markdown-mindmap
[brettterpstra]: http://brettterpstra.com/projects/nvalt/
[bywordapp]: https://bywordapp.com/
[foldingtext]: http://www.foldingtext.com/
[literatureandlatte]: https://www.literatureandlatte.com/scrivener.php
[markdownpad]: http://markdownpad.com/
[marked2app]: http://marked2app.com/
[mdcharm]: http://www.mdcharm.com/
[multimarkdown]: http://multimarkdown.com/
[omz-software]: http://omz-software.com/editorial/
[sublimetext]: https://www.sublimetext.com/
[texts]: http://www.texts.io/features/
[ulyssesapp]: http://www.ulyssesapp.com/
