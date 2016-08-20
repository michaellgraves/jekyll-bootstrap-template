## Overview
The purpose of this project is to create a Jekyll theme for science fair projects. With this theme students can document online a record of their lab notes throughout the duration of their project as well as use the outline for their science fair presentation.

I have blended the work from several sources including:

1. [pool/hyde jekyll templates](https://github.com/poole/hyde)

2. [Carl Boettiger's open lab-notebook design] (http://www.carlboettiger.info/2015/lab-notebook)

3. [Science Buddies Science Fair Content] (http://www.sciencebuddies.org)

4. [Pavel Dmytrenko Stochastic Stuff blog for Jekyll tagging] (http://pavdmyt.com/how-to-implement-tags-at-jekyll-website/)

5. [Kate L. Turabian 8th Edition for Bibliography and Footnote guide] (http://www.press.uchicago.edu/books/turabian/turabian_citationguide.html)

The lab notes (a.k.a post) markdown files are located under the _posts folder and should be titled YYYY-MM-DD-PageName.md.  Sample posts can be found in the samplePosts folder.

The science fair project presentation outline is located under the pages folder. Students can edit these pages directly for their project presentation.

The site configuration is located in the config.yaml file 

## Steps to run local version of projects pages

### Pre-requsite
1. Create [Github account](http://github.com/)
2. Install [Github desktop] (https://desktop.github.com/)
3. Install a code editor such as [editPlus](https://www.editplus.com/download.html)
4. Follow the [Jekyll install steps] (https://jekyllrb.com/docs/installation/)

### Steps to create project site
1. Create new Github project
2. Create gh-pages branch within Github <project>
3. Switch to desktop and clone project
4. Switch branch to gh-pages
5. Download and copy project into local project folder
6. In _config.yaml, update:
	* url and baseurl
	* title
	* tagline
	* description
	* analytics
7. Commit to <project> gh-pages branch and synch
