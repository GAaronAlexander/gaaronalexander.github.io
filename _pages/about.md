---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<img src="../images/headerphoto_aboutme.jpg" alt="Image showing a stormy urban landscape with trees and hydrologic extremes occuring in a very heterogenous region." style="float:right;max-width:100%;height:auto;padding:1px;"/>

Welcome! I am a Ph.D. Candidate at the [University of Wisconsin-Madison Water Resources Engineering Department](https://www.engr.wisc.edu/department/civil-environmental-engineering/research-in-cee/water-resources-engineering-science/). I am a member of the [Hydroclimate Extremes Research Group](https://her.cee.wisc.edu/) and [Hydroecology Lab](https://hydroecology.cee.wisc.edu/) at the University of Wisconsin-Madison, and a member of the [Voter Group](https://carolynbvoter.com/) at the University of Delaware. My advisors are Dr. Daniel B. Wright, Dr. Steve Lohiede II, and Dr. Carolyn B. Voter](https://carolynbvoter.com/).

I am an **atmospheric modeler, computational hydrologist, statistical hydrometeorologist, boundary layer meteorologist, accidental engineer, and most importantly a mentor and teacher**. My work is focused on better understanding the links between the atmosphere and the land surface where we live in areas of both extreme heterogeneity and human interactions. I have extensive experience developing a new land surface parametrization suitable to answer questions relating to human responses to climate change in urban spaces within high resolution climate models. I further work with big data in the form of satellites, in-situ, airplane, and imagery data with physically informed methods and statistical/machine learning approaches to quantify the changing extremes in regions around the globe. The overarching goal of my research is to create find intradisciplinary answers to inherently intradisciplinary questions that face society now and in the future. 

**Outside of research**, I am an active volunteer in both the American Meteorological Society and American Geophysical Union. I work to create spaces for those who have been historically excluded in sciences as my own identity of LGBTQIA+ and a first-generation college student gives me a unique context to advocate for others. 

**In the classroom**, I create an active learning environment contextualized by the world around us, drawing examples from current events and using data that students can expect to see in their future careers. Evidence based teaching, projects-based learning, and a philosophy of creating environments where students are ‘safe-to-fail’ characterize my classrooms. 

I received my B.S. in Physics and Atmospheric Sciences from the University of Nevada, Reno. My academic journey continued in the Water Resources Engineering Department at the University of California, Davis where I worked in the realm of land-atmosphere coupling in the Central Valley. In 2020, I joined the Water Resources Engineering Department at the University of Wisconsin-Madison where my dissertation work has been focused on scientifically informed urban climate at the city-scale in partnership with the Milwaukee Metropolitan Sewerage District. As part of this project, I developed a new land surface framework, Noah-MP for Heterogenous Urban Environments, which will soon be in the national release of Noah-MP everywhere. In 2025, I will transition to a NASA funded Land Cover – Land Use Change Postdoc position where we investigate urban greening around the United States, examining co-benefits and tradeoffs in the cities of Chicago, Baltimore, Houston, and Phoenix, as well as create partnerships in each of these communities!

<!-- ======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right.
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header.

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons.

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
