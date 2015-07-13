---
layout:     post
title:      Posting here with StackEdit
date:       2015-07-11 12:00:00
author:     Marat Latypov
---

<!-- Start Writing Below in Markdown -->

If you would like to post on these Project Pages but feel uncomfortable with git/GitHub, here is a way of doing that with [StackEdit](https://stackedit.io/), which requires minimum knowledge of git/GitHub. 

1. Make sure you have an access to the blog repository (first time only). 

	1.1. [Sign up](https://github.com/join) for a GitHub account if you do not have one yet

	1.2. Send me your GitHub user name so that I can invite you to [mined-simulations group](https://github.com/mined-simulations) on GitHub

2. Go to StackEdit [Editor](https://stackedit.io/editor) and write contents of your post in markdown.
Markdown syntax is quire straightforward, consult the [example post](https://raw.githubusercontent.com/mined-simulations/group-blog/gh-pages/_posts/2015-07-01-post-example.markdown) showcasing the features supported particularly in [Project Pages](http://matin-hub.github.io/ppguide/). 
The main virtue of StackEdit is that it allows for live preview of the raw markdown file as you write. It is great for getting familiar with the syntax and for preview of the post without having to publish the draft on the actual website.  

	**Important**. Make sure to include the following portion at the beginning of every post with appropriately filled title, date, and author name. 
	
		---
		layout:     post
		title:      Post Headline
		date:       2015-01-01 12:00:00
		author:     Your Name
		---

3. Publish on GitHub from StackEdit.
You can easily publish on GitHub directly from StackEdit. To do so 

	3.1. Open the Editor Menu, go to **Publish**, and choose GitHub. 

	3.2. Fill the form as follows: 	
	
		Repository: https://github.com/mined-simulations/group-blog
		Branch: gh-pages
		File path: _posts/yyyy-mm-dd-file-name
		Format: Markdown
	
	Note that only the file name is variable; other fields will be normally the same. 

Here is how the filled form *Publish on GitHub* looked like for the present post (which was also published through StackEdit). The only variable -- file name -- is highlighted.
![Publish on GitHub Form](https://farm1.staticflickr.com/288/19662822311_93b1535c7b_o_d.png)


These steps should result in a new post in the blog at [http://mined-simulations.github.io/group-blog/](http://mined-simulations.github.io/group-blog/). You can also check if your file appeared in *_posts* folder of the GitHub [repository](https://github.com/mined-simulations/group-blog/tree/gh-pages/_posts) hosting the blog.

For more details on using StackEdit and how to configure it specifically for Project Pages, see the original [tutorial](http://matin-hub.github.io/ppguide/content).

P. S. Images can be uploaded to flickr first and then included here as a hyperlink. For example, the image in the present post was included by 
`![Publish on GitHub Form](https://farm1.staticflickr.com/288/19662822311_93b1535c7b_o_d.png)`.



