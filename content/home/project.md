+++
# Homepage
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 70  # Order that this section will appear in.

title = "Project"
subtitle = "Showcase your inner data scientist"
+++

## TL;DR

Pick a dataset, any dataset...

...and do something with it. That is your final project in a nutshell. More details below.

The final project for this class will consist of analysis on a dataset of your own choosing. The dataset may already exist, or you may collect your own data using a survey or by conducting an experiment. You can choose the data based on your interests or based on work in other courses or research projects. The goal of this project is for you to demonstrate proficiency in the techniques we have covered in this class (and beyond, if you like) and apply them to a novel dataset in a meaningful way.

The goal is not to do an exhaustive data analysis i.e., do not calculate every statistic and procedure you have learned for every variable, but rather let me know that you are proficient at asking meaningful questions and answering them with results of data analysis, that you are proficient in using R, and that you are proficient at interpreting and presenting the results. Focus on methods that help you begin to answer your research questions. You do not have to apply every statistical procedure we learned. Also, critique your own methods and provide suggestions for improving your analysis. Issues pertaining to the reliability and validity of your data, and appropriateness of the statistical analysis should be discussed here.

The project is very open ended. You should create some kind of compelling visualization(s) of this data in R. There is no limit on what tools or packages you may use, but sticking to packages we learned in class (`tidyverse`) is required. You do not need to visualize all of the data at once. A single high quality visualization will receive a much higher grade than a large number of poor quality visualizations. Also pay attention to your presentation. Neatness, coherency, and clarity will count. All analyses must be done in RStudio, using R. 
Here is an example of a past [project write up](https://dcs-210.github.io/project-lizakemuntopatrick/) and [presentation](https://dcs-210.github.io/project-lizakemuntopatrick/presentation/presentation.html#1) on **Lessons to be Learned from Super Bowl Advertisements**. 

### Data

In order for you to have the greatest chance of success with this project it is important that you choose a manageable dataset. This means that the data should be readily accessible and large enough that multiple relationships can be explored. As such, your dataset must have at least 50 observations and between 10 to 20 variables (exceptions can be made but you must speak with me first). The variables in the data should include categorical variables, discrete numerical variables, and continuous numerical variables.

If you are using a dataset that comes in a format that we haven't encountered in class, make sure that you are able to load it into R as this can be tricky depending on the source. If you are having trouble ask for help before it is too late.

**Note on reusing datasets from class:** Do not reuse datasets used in examples, homework assignments, or labs in the class.

Below are a list of data repositories that might be of interest to browse. You're not limited to these resources, and in fact you're encouraged to venture beyond them. But you might find something interesting there:

- [TidyTuesday](https://github.com/rfordatascience/tidytuesday)
- [NHS Scotland Open Data](https://www.opendata.nhs.scot/)
- [Edinburgh Open Data](https://edinburghopendata.info/)
- [Open access to Scotland's official statistics](https://statistics.gov.scot/home)
- [Bikeshare data portal](https://www.bikeshare.com/data/)
- [UK Gov Data](https://data.gov.uk/)
- [Kaggle datasets](https://www.kaggle.com/datasets)
- [OpenIntro datasets](http://openintrostat.github.io/openintro/)
- [Awesome public datasets](https://github.com/awesomedata/awesome-public-datasets)
- [Youth Risk Behavior Surveillance System (YRBSS)](https://chronicdata.cdc.gov/Youth-Risk-Behaviors/DASH-Youth-Risk-Behavior-Surveillance-System-YRBSS/q6p7-56au)
- [PRISM Data Archive Project](https://www.icpsr.umich.edu/icpsrweb/content/ICPSR/fenway.html)
- [Harvard Dataverse](https://dataverse.harvard.edu/)
- [National Archive of Criminal Justice Data](https://www.icpsr.umich.edu/web/pages/NACJD/index.html)
- [TransPop](https://www.icpsr.umich.edu/web/ICPSR/studies/37938) first national probability sample of transgender individuals in the United States.
- [Data is Plural](https://www.data-is-plural.com/archive/)
- [American Community Survey](https://data.census.gov/cedsci/) some Maine data here.
- [IPUMS USA](https://usa.ipums.org/usa/) census microdata
- [The Lawrence Papers](https://scarab.bates.edu/lawrance/) from Bates and [metadata](https://bates-archives.libraryhost.com/repositories/2/resources/185)
- [Health-related datasets](https://libguides.bates.edu/health-economics/resources) compiled by Bates library
- If you know of others, let me know, and we'll add here...

### Deliverables

Together with your team, you will produce a weekly presentation to stakeholders. This is an opportunity to show your progress, ask questions, and get feedback.

You will also work on and submit a final report to the stakeholders.

#### Team Contract

One of the main goals of this course is that you build and develop community leadership skills as a collaborator that shares strengths, builds weaknesses, and contributes to a broader shared understanding. These skills will serve you in this course and beyond in your careers. A crucial part of building strong collaborations is good communication.

Each team will draft a group contract. A group contract is a document to help you formalize the expectations you have for your group members and what they can expect of you. It will help you think about what you need from each other to work effectively as a team! You will create and agree on this contract as a team and refer to it during the project.

At a minimum, your group contract must address these questions:

##### Goals:

- What are our team goals for this project?
- What do we want to accomplish?
- What skills do we want to develop or refine?

##### Expectations:

- What do we expect of one another regarding attendance at meetings, participation, frequency of communication, quality of work, etc.?

##### Policies & Procedures:

- What rules can we agree on to help us meet our goals and expectations?

##### Consequences:

- How will we address non-performance regarding these goals, expectations, policies and procedures?

Each member should "sign" (you can just type out your name) at the bottom of the submission.

Credit for Group Contract: Tiffany Timbers, University of British Columbia

#### Report

The write-up, which you can also think of as an summary of your project, should provide information on the dataset you're using, your research question(s), your methodology, and your findings. 

#### Repo organization

The following folders and files in your project repository:

* `presentation.Rmd` + `presentation.html`: Your presentation slides
* `README.md`: Your write-up
* `/data/*`: Your dataset in csv or RDS format, in the `/data` folder.
* `/report`: Your report write up

Style and format does count for this assignment, so please take the time to make sure everything looks good and your data and code are properly formatted including labelling code chunks. Pay attention to images and plots included in the presentation and make sure to include appropriate alternative text.

## Tips

- You're working in the same repo as your teammates now, so merge conflicts will happen, issues will arise, and that's fine! Pull, commit and push often, and ask questions when stuck.
- Review the marking guidelines below and ask questions if any of the expectations are unclear.
- Make sure each team member is contributing, both in terms of quality and quantity of contribution (we will be reviewing commits from different team members).
- Set aside time to work together.
- When you're done, review the documents on GitHub to make sure you're happy with the final state of your work. Then go get some rest!

- Teamwork: You are to complete the assignment as a team. All team members are expected to contribute equally to the completion of this assignment and team evaluations will be given at its completion - anyone judged to not have sufficient contributed to the final product will have their grade penalized. While different teams members may have different backgrounds and abilities, it is the responsibility of every team member to understand how and why all code and approaches in the assignment works.

## Marking

Total                          | 100 pts
-------------------------------|--------
Proposal                       | 10 pts
Presentation                   | 50 pts
Write-up                       | 15 pts
Reproducibility and organization | 10 pts
Team peer evaluation           | 10 pts
Classmates' evaluation         | 5 pts

### Criteria 

- **Content** - What is the quality of research and/or policy question and relevancy of data to those questions?
- **Correctness** - Are statistical procedures carried out and explained correctly?
- **Writing and Presentation** - What is the quality of the statistical presentation, writing, and explanations?
- **Creativity and Critical Thought** - Is the project carefully thought out? Are the limitations carefully considered? Does it appear that time and effort went into the planning and implementation of the project?
