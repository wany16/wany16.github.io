---
permalink: /
title: "Welcome to Ying Wan's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Ying Wan (万颖) received his Bachelor's degree in Communication Engineering from Northwestern Polytechnical University in 2016 (Advisor: [Ding Wang](https://teacher.nwpu.edu.cn/wangding.html)),
and his PhD degree in Computer Science from Tsinghua University in 2022 (Supervisor: [Bin Liu](https://www.cs.tsinghua.edu.cn/info/1126/3587.htm)).
He conducted a three-month scientific research internship at the University of Victoria (UVic) with the funding of the China Scholarship Council (CSC) in 2015 (Supervisor: [Jianping Pan](https://www.uvic.ca/ecs/computerscience/people/faculty/profiles/pan-jianping.php), [Fei Tong](https://fei-tong.github.io/)). 
He worked as an senior researcher at the Innovation Center, China Mobile (Suzhou) Software Technology from July 2022 to February 2025 (Manager: [Ling Qian](https://www.cnii.com.cn/gxxww/rmydb/202111/t20211110_321826.html), [Yu Jia](https://zhuanlan.zhihu.com/p/406240028)).
Now he is an associate researcher in School of Cyber Science and Engineering, Southeast University.

Research Interests
======
1. Software Defined Networking (SDN)
1. Programmable Dataplane
1. Data Center Network (DCN)
1. In-band Network Telemetry (INT)
1. Hardware AI Acceleration
1. Routing, load balancing, and congestion control  

Teaching
======
1. TBD

Recruitment
======
I am currently looking for motivated students to join my research group. I have several openings for Master's students. If you are interested in pursuing research in the areas of Software Defined Networking, Data Center Networks, or Cyber Security, please contact me at wy25@seu.edu.cn with your CV and a brief statement of your research interests.


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
