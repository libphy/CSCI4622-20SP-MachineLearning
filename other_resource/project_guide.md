# Project Guide

For the final project, your team are required to:    

1. Identify a machine learning problem.
If you have a relationship with a company or organization who are willing to provide a project task or data, you're welcome to work on their problem. You do not need to share the data, but you should be able to make a public git (that includes your notebook or codes- at least the ML analysis part if sharing all codes are not possible) and video presentation.
If you're going to just use a kaggle competition or similar, you must provide more focus on model building and/or analysis to be a valid project (replicating what's in the kaggle kernel or other notebooks available online is not a valid project. If you add other approaches and compare with those, it's valid). If you find a research paper and want to replicate the experiments or implement an algorithm, that works too. Please consult to the teaching staffs to check if your project idea has a right scope.
2. Gather data, determine the method of data collection and provenance of the data. The data can be web-scraped, or downloaded from any sources as long as it's legal and ethical, and does not violate their policy or intellectual property/copyrights.
3. Clean the data, do EDA (exploratory data analysis- e.g., inspecting and visualization of the data)
4. Perform analysis using machine learning models of your choice.
5. Deliver the results: These deliverables serves two purposes- grade for this course and your project portfolio that you can show when you apply for jobs in the near futures.

**[Deliverable 1]** Jupyter notebook showing a brief problem description, EDA procedure, analysis (model building and training), result and discussion/conclusion. If your work becomes large that it doesn't fit into one notebook (or you think it will be less readable by having one large notebook), you can make several notebooks or scripts in the git (as deliverable 3), and submit a report-style notebook or pdf instead.
In case your project doesn't fit into jupyter notebook format (e.g. you built an app that uses ML), write your approach as a report and submit in a pdf form. Please include all of your team members name in the notebook or report.   

**[Deliverable 2]** Video presentation- record a video of a presentation or demo of your work. The presentation should be a condensed version as if you're doing a short pitch to advertise your work; so please focus on the highlights (1. what problem do you solve, 2. what ML approach you use or what methods your app uses, 3. what the result is or running app demo). Minimum video length 5 min, maximum length 10 min (we will not grade anything after 10 mins) Submit the video in .mp4 format via moodle (only one file per team allowed).

**[Deliverable 3]** Create a public project Git repository with your work (please also include the git repo url in your notebook/report and slides). Data by-product: In case your project creates data and you want to share, please do not upload the data in git, but a good way to share would be through kaggle dataset, or similar. Similarly, please do not upload videos to git- if you want, you can upload to youtube, then you can post those link(s) to your git.

Here is the rough timeline for the next 4 weeks:         

1. **Project week 1** In the earlier phase, you were to make the initial selection of a data source and problem to evaluate and discuss it on Piazza and though OHs. In this stage, you're going to go through the initial data cleaning and EDA, and judge whether you need to collect more data or different data etc.   

2. **Project week 2** Continue more EDA if needed. Start the main analysis (main analysis refers to *machine learning* such as classification or regression, prediction or inference etc OR *other stat analysis*).You are on the right track if you start the main analysis at the latest end of this week or earlier. Depending on your tasks, you may have one model or more. Generally, it is deemed to be a higher quality project if you compare multiple models and show your understanding of why certain model works better than the other or what limitations or cautions certain models may have (and for machine learning models, show enough effort on the hyperparameter optimization).

3. **Project week 3** Continue more main analysis. Hyperparameter optimization. Compare results from your models. Wrap up.

4. **Project week 4** Wrap up and finalize your jupyter notebook write-up. Prepare the presentation. Organize your git repository. Submit the 3 deliverables (finished jupyter notebook write-up, slides, with a link to your project git repository). There will be a submission box in the gradescope. Please upload the jupyter notebook to both gradescope and git repo (the reason why I still need a submission through gradescope is it's easier for me to grade via gradescope). Slides need to be uploaded to gradescope (it only accepts pdf, so you can printout to pdf), and whether you post in git or not is up to you. In the jupyter notebook or slides, please include the url for your git.  
Your github repo must be public and accessible. You do not need to upload data file there (description and some pandas dataframe of data in the write-up is enough). Usually good idea not to upload any large size file in the git.

### EDA procedure example (for the Project Week 1 & 2)
- Describe the data sources, the hypothesis or problem you which to analyze and then describe the factors or components that make up the dataset (The "factors" here is called "features" in the machine learning term. These factors are often columns in the tabulated data). For each factor, use a box-plot, scatter plot, histogram etc to describe the distribution of the data as appropriate.
- Describe correlations between different factors of the dataset and justify your assumption that they are correlated or not correlated. You may use numeric or qualitative / graphical analysis for this step.
- Determine if any data needs to be transformed. For example, if you're planning on using a SVM method for prediction, you may need to normalize or scale the data if there is considerable difference in the range of the data.
- Using your hypothesis, indicate if it's likely that you should transform data, such as using a log transform or other transformation of the dataset.
- You should determine if your data has outliers or needs to be cleaned in any way. Are there missing data values for specific factors? How will you handle the data cleaning? Will you discard, interpolate or otherwise substitute data values?
- If you believe that specific factors will be more important than others in your analysis, you should mention which and why. You will use this to confirm your intuitions in your final writeup.

### How to find data
There are a plethora of data resource these days. Here are a few popular (classic ML data) ones.     
- [UCI ML data repository](https://archive.ics.uci.edu/ml/datasets.php): Their data is from researchers mostly and is relatively clean. Also the task types are mostly for classification or regression, therefore many of them are suitable for the scope of this course's project.     
- [Kaggle](https://www.kaggle.com/): Perhaps one of the most popular data science/ML data repositories today, they have many interesting con-going or past competitions. But most of recent dataset/tasks will be beyond the scope of this course. Should you be still interested, choose problems that have tabulated data and classification or regression type tasks.     
- [Data.gov](https://www.data.gov/) has many government sources of data. You can filter for a specific topic (e.g. Finance) and then restrict your attention to e.g. CSV data, which should be easier to process.
- [Grand Challenge](https://grand-challenge.org/) has various biomed image computer vision competitions.

Some internet blogs about list of dataset:     
- https://medium.com/towards-artificial-intelligence/the-50-best-public-datasets-for-machine-learning-d80e9f030279
- https://towardsdatascience.com/top-sources-for-machine-learning-datasets-bb6d0dc3378b
- https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research
- http://www.statsmodels.org/devel/datasets/index.html
- https://pathmind.com/wiki/open-datasets

### Example Topics
Here is a link to a list of ML projects from the [previous classes](https://docs.google.com/spreadsheets/d/1RG2TrTRbjli5ySZF5E1WRqA0r_o4uETKx_lPhaIN3cU/edit?usp=sharing) I've taught. These are from master-level data science classes- some students there have background on certain fields such as medicine or software engineering but most were first-time learners on ML subjects and many didn't have a CS degree, so the skill-levels widely vary.
