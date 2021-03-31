---
layout: default
---

<img src="{{ site.url }}{{ site.baseurl }}/assets/img/eScience.png">


# Professional Websites with GitHub Pages

## Valentina Staneva
### eScience Institute, University of Washington

# Plan for today
* Go over what [GitHub Pages](https://pages.github.com/) are
  * git & Github
    * make sure you have made an account on [Github.com](Github.com) (don't need to install `git` today)
    * [Software Carpentry git-novice lesson](http://swcarpentry.github.io/git-novice/)
  * [Jekyll Templates](https://jekyllrb.com/) (don't need to install it today)
		* [Markdown](https://daringfireball.net/projects/markdown/syntax)]-based (a text marking language designed for the web)
		* Static pages can include web-based visualizations ([d3.js](https://d3js.org/), [vega-lite](https://vega.github.io/vega-lite/))
 
* Build your own webpage from a choice of templates:
  * Personal Website (with a blog)
    * [https://github.com/valentina-s/personal-website-template](https://github.com/valentina-s/personal-website-template)   
  * Project Website (for collaborative projects)
    *[https://github.com/valentina-s/project-website-template](https://github.com/valentina-s/project-website-template)
  * Course Website (if you are teaching a class)
    * [https://github.com/valentina-s/course-website-template](https://github.com/valentina-s/project-website-template)


## Repository Creation

* decide on a name for the repository (it will determine the webpage url, but you can change it later)
* click on `Use this template` & enter your repo name & create repo
* enable publishing through the master branch (Settings -> GitHub-Pages)
* add a link on the right for quick access to the webpage (pay attention to how the url is created)


## Configuring your website
* Modify your project name in the `_config.yml` file
	
## Editing your webpage

* Each page is a markdown document
	* Markdown is a text marking language designed for the web 
		* [Markdown Tutorial](https://daringfireball.net/projects/markdown/syntax)
	
	* You can modify the markdown documents from the website (hit the edit button and commit when finished)
    	* You can also make modifications to the text files locally and upload to the repo
		* [Macdown Editor for Mac](https://macdown.uranusjr.com/)
		* [MarkdownPad for Windows](http://markdownpad.com/news/2013/introducing-markdownpad-2/)
		* [Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown)
		* [Atom editor](https://atom.io/) has a markdown extension


* Images go into [assets/img](https://github.com/valentina-s/project-website-template/tree/master/assets/img)
	* they can be accessed by:
			```
			<img src="{{ site.url }}{{ site.baseurl }}/assets/img/eScience.png">
			```
	
	* feel free to have a different header image relevant to your project

* Blog posts (for the minima theme) go to the [_posts](https://github.com/valentina-s/personal-website-template/tree/master/_posts) folder
  * add a date in the name so they get ordered

* Modifying tabs:
  * sidebar tabs (for project theme):
  	* [https://github.com/uwescience/project-website-template/blob/master/_includes/sidebar.html](https://github.com/valentina-s/project-website-template/blob/master/_includes/sidebar.html) 	
  * header tabs (for personal and course theme) 
  	* in [`_config.yml`](https://github.com/valentina-s/personal-website-template/blob/master/_config.yml) list them under `header_pages` 		
 
