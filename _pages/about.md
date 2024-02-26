---
permalink: /
title: "Hi there, I'm Beichuan!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently working as a consultant at the AFRY Södertälje office in the automotive field. I hold a Ph.D. degree from the [Unit of Mechatronics](www.kth.se/mmk/mechatronics), [Department of Engineering Design](www.kth.se/mmk/department-of-machine-design-1.974324) & [Competence Center for Gas Exchange (CCGEx)](www.ccgex.kth.se) at KTH Royal Institute of Technology in Sweden (2023). 

My research interests include the evaluation and optimization of energy and propulsion systems, alongside modeling and control theory for automotive applications. My experience covers combustion engines using renewable fuel, energy optimization for hybrid powertrain systems, discrete-event simulation for transport systems, system identification for mechatronics, and optimal control for autonomous construction vehicles.


Profession & Education
======
My doctoral studies (2018-2023) have focused on thermal analyses and optimization of propulsion systems for marine and vehicle applications, with particular interest in combustion engines using renewable fuels and electrification approaches employing hybrid driveline systems. I possess expertise in modeling, control, and estimation for dynamic systems within the automotive sector. My doctoral work was mainly with [Dr. Andreas Cronhjort](www.kth.se/profile/qwerty), [Professor. Mihai Mihaescu](www.kth.se/profile/mihaescu), and [Professor. Anders Christiansen Erlandsson](scholar.google.se/citations?user=Y5rj2A0AAAAJ&hl=en). My research was conducted in the KTH-CCGEx center and was funded by the Swedish Energy Agency (Energimyndigheten), KTH-CCGEx center and its industrial partners.

<img src="/images/engine_cell.png" width="600">


My work conducted at CCGEx focuses on exergy analysis of combustion systems and the exhaust pulsating flows. The study, carried out from 2018 to 2023, is related to biofuel combustion analysis, exhaust flow field measurement and estimation, as well as emission control strategies. Meanwhile, at the Unit of Mechatronics  (2021-2023), I have also been involved in teaching and research projects concerning embedded systems for motor control, system identification of battery models, and energy optimization of hybrid powertrain systems.

<img src="/images/battery.png" width="600">

From  2016 to 2018, I was a Licentiate student / research engineer at the KTH Transport Planning division within the project of “Optimal Construction Operations”, which was funded by Volvo Construction Equipment (Construction Climate Challenge). My work at the Transport Planning division, Department of Civil and Architectural Engineering involves the optimal control application on construction operations.

<img src="/images/wheel_loader.png" width="600">


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
