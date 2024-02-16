---
permalink: /
title: "Publications"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

1.	Zhao, Z., Lin, P., Shen, L., Zhang, M., & Huang, G. Q. (2020). IoT edge computing-enabled collaborative tracking system for manufacturing resources in industrial park. Advanced Engineering Informatics, 43, 101044. 
2.	Zhao, Z., Zhang, M., Chen, J., Qu, T., & Huang, G. Q. (2022). Digital Twin-enabled Dynamic Spatial-temporal Knowledge Graph for Production Logistics Resource Allocation. Computers & Industrial Engineering, 108454.
3.	Wu, W., Shen, L., Zhao, Z.*, Li, M., & Huang, G. Q. (2022). Industrial IoT and Long Short-Term Memory Network Enabled Genetic Indoor Tracking for Factory Logistics. IEEE Transactions on Industrial Informatics.
4.	Zhan, X., Wu, W., Shen, L., Liao, W., Zhao, Z., & Xia, J. (2022). Industrial internet of things and unsupervised deep learning enabled real-time occupational safety monitoring in cold storage warehouse. Safety Science, 152, 105766.
5.	Zhao, Z., Zhang, M., Yang, C., Fang, J. and Huang, G.Q., (2018). Distributed and collaborative proactive tandem location tracking of vehicle products for warehouse operations. Computers & Industrial Engineering, 2018, 125, 
6.	Zhao, Z., Fang, J., Huang, G. Q., & Zhang, M. (2017). Location management of cloud forklifts in finished product warehouse. International Journal of Intelligent Systems, 32(4), 342-370.
7.	Zhao, Z., Fang, J., Huang, G. Q., & Zhang, M. (2016, September). iBeacon enabled indoor positioning for warehouse management. In Computational and Business Intelligence (ISCBI), 2016 4th International Symposium on (pp. 21-26). IEEE. 
8.	Wu, W., Zhao, Z., Shen, L., Kong, X. T., Guo, D., Zhong, R. Y., & Huang, G. Q. (2022). Just Trolley: Implementation of industrial IoT and digital twin-enabled spatial-temporal traceability and visibility for finished goods logistics. Advanced Engineering Informatics, 52, 101571.
9.	Zhao, Z., Zhang, M., Xu, G., Zhang, D., & Huang, G. Q. (2020). Logistics sustainability practices: an IoT-enabled smart indoor parking system for industrial hazardous chemical vehicles. International Journal of Production Research,58(24), 7490-7506. 




A data-driven personal website
======
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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
