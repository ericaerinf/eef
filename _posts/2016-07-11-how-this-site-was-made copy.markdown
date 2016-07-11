---
layout: post
title:  "How This Site Was Made"
date:   2016-07-11 12:05:58 -0400
categories: jekyll update
---
Jekyll is a super awesome static site generator. Here is how I made my site using it!


------------------------------------------

First thing you want to do is 

# 1. install jekyll...    

 - [NPM](https://www.npmjs.com/)
 - [Node.js](https://nodejs.org/en/)
 - [Ruby](https://www.ruby-lang.org/en/downloads/)
 - [RubyGems](https://rubygems.org/pages/download)
 - [Python](https://www.python.org/downloads/)
 -  [Kramdown](http://kramdown.gettalong.org/)
 - [Jekyll](https://jekyllrb.com/docs/installation/) 

More details to come...

------------------------------------------


# 2. jekyll build 

 - open up terminal window and navigate to the directory where you want your repository to exist locally. 
 
	 *I recommend the home directory!*  
	  ![alt text](https://ericaerinf.github.io/testblog/images/home.png "home directory icon")

 - 	execute `$ jekyll new nameyouwant`      
 it will create a new folder filled with these subfolders:
 
	![alt text](https://ericaerinf.github.io/eef/images/folders.png "folders")
-  then `$ jekyll build` You will notice a new folder appear: _site. Any changes made within this folder are not saved as it is constantly regenerated (I just wouldn't mess with it).
- Go to Github, create a new repository with the same name
-  drag the subfolders (_config.yml - index.html) you just created into the new repository window
-  delete all the folders on your computer that you just made
-  **clone the repository**


to be continued.....
 
--------------------------------------------------------
 

# 3. Deploy site to github pages!


-  On Github, create a new branch called **gh-pages**. Whenever you are pushing, make sure it is to the gh-pages branch and not the master.
- Some changes need to be made in the _config.yml file, open it in your favorite text editor and change the baseurl







