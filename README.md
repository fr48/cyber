# Phishing Attacks are Still the Biggest Threats

This project digs into the latest _Internet & Technology_ research from the **Pew Research Center**. The idea was to look at American perceptions of cybersecurity and privacy and compare the results of what users said about passwords and security with what industry reports say about what user security.

Privacy-related statistics are pulled from the _Americans and Privacy: Concerned, Confused and Feeling Lack of Control over Their Personal Information_ report.

I looked at how Americans handle their own data protection by analyzing the dataset that was published by Pew Research on how well people know about online security and whether or not they actually do those things. The analysis compares different groups and what their security habits were.

## Data sources: 

* Privacy viewpoints (https://www.pewresearch.org/internet/2019/11/15/americans-and-privacy-concerned-confused-and-feeling-lack-of-control-over-their-personal-information/) 

* personal security habits (https://www.pewresearch.org/internet/dataset/march-may-2016-cybersecurity/)

* cybersecurity knowledge (https://www.pewresearch.org/internet/dataset/june-2016-cybersecurity-knowledge/)

* Phishing related statistics from Webroot's _Hook Line and Sinker_ report (https://mypage.webroot.com/rs/557-FSI-195/images/Hook-Line-and-Sinker-Final.pdf)

## Contents 

The code notebook (Jupyter) is annotated to walk through the different analysis that was done, and decisions that were made during the course of the analysis about how to use the data are documented through code comments. The clean data used for the visualizations are provided as .csv files.

Codebook (topline.pdf) is available in the analysis\data\ directory. (topline)

## Visualizations

The project is available at (https://fr48.github.io/cyber)

* Password security (security measures they should be using, what's up with passwords)

* Do consumers punish companies after a breach (as measured by stock price)?

Wireframes are available at https://fr48.github.io/cyber/wireframe.html

## Interactive:

* How well do you know security: a text-based game that tests you on the security questions, as well as shows stats on how others did. (TBD)

* Calvin is having a bad day: What different scams look like and why people for them, with statistics for different scenarios.

* Do data breaches impact stock prices?: Chart looking at different stock prices for different companies.

## Tools Used:

* For analysis: python, regex, pandas

* For visualizations: DataWrapper, Illustrator, ai2html, matplotlib/seaborn
