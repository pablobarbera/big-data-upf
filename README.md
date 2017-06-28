# Summer School: Social Media and Big Data Research

## Sponsored by 
* [Barcelona Summer School in Survey Methodology](https://eventum.upf.edu/event_detail/7273/detail/barcelona-summer-school-in-survey-methodology-2017.html)

## June 26 - June 29, 2017
 
## Instructor

* [Pablo Barber&aacute;](http://pablobarbera.com/)

(with some content based on materials prepared by [Dan Cervone](http://dcervone.com/), [Alex Hanna](http://alex-hanna.com), [Ken Benoit](http://www.kenbenoit.net/), [Paul Nulty](https://github.com/pnulty), [Kevin Munger](https://github.com/kmunger), and [Justin Grimmer](http://www.justingrimmer.org/).)

## Description

Citizens across the globe spend an increasing proportion of their daily lives online. Their activities leave behind granular, time-stamped footprints of human behavior and personal interactions that represent a new and exciting source of data to study standing questions about political and social behavior. At the same time, the volume and heterogeneity of web data present unprecedented methodological challenges. The goal of this course is to introduce participants to new computational methods and tools required to explore and analyze Big Data from online sources using the R programming language. We will focus in particular on data collected from social networking sites, such as Facebook and Twitter, whose use is becoming widespread in the social sciences.

Each session will provide an overview of the literature and research methods on one of three main themes of the course -- big data, network data, and text data -- to then dive into a specific application, documenting each step from data collection to the analysis required to test hypotheses related to core social science questions. Code and data for all the applications will be provided, and students are encouraged to bring their own laptops to follow along.

After the course, students will have an advanced understanding of the opportunities of big data and social media mining for social science studies, and will be equipped with the technical skills necessary to conduct their own research.

## Setup and Preparation

There are two ways you can follow the course and run the code contained in this GitHub repository. The recommended method is to connect to the provided RStudio server where all the R packages have already been installed, and all the R code is available. To access the server, visit bigdata.pablobarbera.com and log in with the information provided during class.

Alternatively, you can run the code in your own laptop. You will need [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/) installed. Given the number of attendants, I will not be able to provide support during the course, but feel free to email me later if you have any issue.

If you're using your own laptop, you can either download the course materials clicking on each link in this repository, download it as a zip file, or you can "clone" it, using the buttons found to the right side of your browser window as you view this repository.  If you do not have a git client installed on your system, you will need to [get one here](https://git-scm.com/download/gui) and also to make sure that [git is installed](https://git-scm.com/downloads). 

You can also subscribe to the repository if you have [a GitHub account](https://github.com), which will send you updates each time new changes are pushed to the repository.

## Day 1

The first session will begin with a discussion of the definition of "Big Data" and the research opportunities and challenges of the use of massive-scale datasets in the social sciences. We will then focus on how social media sites represent a new source of data to study human behavior, and also how its use raises a whole new series of questions that are relevant to social scientists. The applied part of this session will demonstrate different methods to "scrape" data from the web, with sentiment analysis of newspaper stories as a running example.

[Slides: Big Data and Social Media Research(.pdf)](slides/01-big-data.pdf)

[Slides: Scraping the web (.pdf)](slides/02-scraping.pdf)

[Code: Introduction to RMarkdown and setup (.html)](code/00-setup.html)

[Code: Scraping tables (.html)](code/01a-scraping-tables.html)

[Code: Scraping unstructured data (.html)](code/01b-scraping-unstructured-data.html)

[Code: Web APIs (.html)](code/01c-apis.html)

## Day 2

Social network analysis applied to social media data will be the main theme of the second session. After a short introduction to the main concepts and methods in network analysis, we will go over two applications: the online diffusion of information in the context of a social protest, and the debate on whether social media represents an "echo chamber" where individuals are only exposed to information that aligns with their previous political beliefs. Both examples rely on Twitter data -- this session will also explain the different types of data available and how they can be collected.

[Slides: Social network analysis (.pdf)](slides/03-networks.pdf)

[Slides: Collecting Twitter data (.pdf)](slides/04-twitter.pdf)

[Code: Introduction to network analysis and visualization (.html)](02a-networks-intro-visualization.html)

[Code: Descriptive analysis of networks (.html)](02b-networks-descriptive-analysis.html)

[Exercise: Analysis of a protest network (.html)](02c-analysis-protest-network.html)

[Solutions: Analysis of a protest network (.html)](02c-analysis-protest-network-solutions.html)

[Code: Collecting Twitter data from the Streaming API (.html)](02d-twitter-streaming-data-collection.html)

[Code: Collecting Twitter data from the REST API (.html)](02e-twitter-REST-data-collection.html)

[Code: Analyzing polarization in Twitter networks (.html)](02f-polarization-networks.html)

## Day 3

The last session of the course will focus on automated text analysis. I will introduce the two main techniques currently used by social scientists: large-scale classification of documents into categories (supervised learning) and discovery of "topics" or classes of documents in a corpus (unsupervised learning). These methods will be demonstrated in the context of two applications -- one related to the automated detection of hate speech in tweets, and another showing how Facebook posts by politicians can be classified into relevant political issues. As with the previous sessions, here we will cover the entire research process, from the collection of data through the Facebook API to the estimation of machine learning methods and the interpretation of the output.

[Slides: Introduction to text analysis (.pdf)](slides/05-text.pdf)

[Slides: Facebook data and topic models (.pdf)](slides/06-facebook-topic-models.pdf)

[Code: Introduction to text analysis (.html)](03a-text-intro.html)

[Code: Dictionary methods (.html)](03b-dictionary-methods.html)

[Code: Supervised learning (.html)](03c-supervised-learning.html)

[Exercise: Supervised learning (.html)](03d-supervised-learning-exercise.html)

[Solutions: Supervised learning (.html)](03d-supervised-learning-exercise-solutions.html)

[Code: Collecting Facebook data (.html)](03e-facebook-data-collection.html)

[Code: Unsupervised learning, topic models (.html)](03f-unsupervised-learning.html)

[Code: Measuring issue ownership in Facebook posts using topic models (.html)](03g-issue-ownership.html)




