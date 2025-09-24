---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

We develop algorithms and statistical models for analyzing large biological datasets. Particularly, we develop scalable algorithms for high-throughput genomic and transcriptomic sequencing data to study problems related to sequence alignment, genome assembly, structural variation detection, and transcriptome analysis. We emphasize applicability of the methods to relevant biological and biomedical questions. 

Principal Investigator Biography
======

I am an Assistant Professor at Stockholm University (the Department of Mathematics) and SciLifeLab Fellow at the national center for molecular biosciences, Science for Life Laboratory. I obtained my PhD in Computer science from KTH Royal institute of Technology and I have worked as a Postdoctoral researcher at Pennsylvania State University and at University of Helsinki. Before that I obtained a bachelor's degree in mathematics and a master's degree in mathematical statistics from Stockholm University, Sweden. See my <a href="http://sahlingroup.github.io/files/ksahlin_CV.pdf">full CV</a>.


<!-- News
======

#### 2022 ####
- ♦️ June:  Awarded with a long term bioinformatic funding grant from NBIS for maintenance and development of [strobealign](https://github.com/ksahlin/StrobeAlign), a fast and accurate short-read aligner based on strobemers seeding technique. (National Bioinformatics Infrastructure of Sweden)
- ♦️ May:  Doctoral network grant LongTREC funded. Funds 11 PhD students. Lead PI Ana Conesa. funded. (Marie Skłodowska-Curie Actions)
- 🌱 April: [Paper](https://www.nature.com/articles/s41596-022-00682-x) out in Nature Protocols on rapid in situ identification of biological specimens via DNA amplicon sequencing, lead by Stefan Prost.

 -->

<!-- #### 2021 ####

- 🌱 December: [Paper](https://ieeexplore.ieee.org/document/9628018) out on transcriptome assembly, lead by [Tomescu Lab](https://www.cs.helsinki.fi/u/tomescu/#)
- ♦️ November:  Awarded with a starting grant from the Swedish Research Council (Vetenskapsrådet)
- 🌱 November: [Paper](https://genome.cshlp.org/content/31/11/2080.short) in Genome Research describing strobemers, a seeding technique for sequence comparison
- 🌱 July: [Paper](https://doi.org/10.1093/bioinformatics/btab540) out in Bioinformatics describing uLTRA, a spliced aligner of long transcriptomic reads together with [Veli Mäkinen](https://www2.helsinki.fi/en/researchgroups/genome-scale-algorithmics/people/veli-makinen)
- 🗣️ July: Presented  ”Strobemers: an alternative to k-mers for sequence comparison” at HitSEQ (ISMB)
- 🗣️ April: Presented  ”Accurate spliced alignment of long RNA sequencing reads.” at RECOMB-Seq
- 🌱 January: [Paper](https://doi.org/10.1002/ece3.7146) out in Ecology and Evolution describing NGSpeciesID, a method for consensus calling of amplicon data together with [Stefan Prost](https://fieldprojects.org/stefan-prost/)
- 🌱 January: [Paper](https://doi.org/10.1038/s41467-020-20340-8) out in Nature communications on error correction of ONT cDNA data together with [Paul Medvedev](https://medvedevgroup.com/)
 -->

<!-- #### 2020 ####

- 🌱 April: Our RECOMB [Paper](https://www.liebertpub.com/doi/abs/10.1089/cmb.2019.0299) out on clustering ONT and PacBio cDNA data in JCB together with [Paul Medvedev](https://medvedevgroup.com/)
- ♦️ January: started as a Scilifelab Fellow and assistant professor in the Department of Mathematics at Stockholm University

 -->


Major Funding
======

<p align="center" width="100%">
    <img width="30%" src="http://sahlingroup.github.io/files/SciLifeLab_Logo.png"> 
    <img width="25%" src="http://sahlingroup.github.io/files/vr_logo.jpeg"> 
    <img width="25%" src="http://sahlingroup.github.io/files/kaw_logotype_large_en.jpg"> 

</p>

<!-- A data-driven personal website
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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
