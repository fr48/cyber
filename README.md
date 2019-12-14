# Americans' View of Cybersecurity

This project digs into the latest _Internet & Technology_ research from the **Pew Research Center**. The idea was to look at American perceptions of cybersecurity and privacy. 

American consumers don't trust the organizations--government or companies--to keep information about them safe, and they also think that data collection is inevitable. However, there is some contradiction. Not only do Americans not trust government and companies to protect their data online from thieves, but they don't do a very good job with protecting their data, either. 

Privacy-related statistics are pulled from the _Americans and Privacy: Concerned, Confused and Feeling Lack of Control over Their Personal Information_ report.

I looked at how Americans handle their own data protection by analyzing the dataset that was published by Pew Research on how well people know about online security and whether or not they actually do those things. The analysis compares different groups and what their security habits were.

## Data sources: 

* Privacy viewpoints (https://www.pewresearch.org/internet/2019/11/15/americans-and-privacy-concerned-confused-and-feeling-lack-of-control-over-their-personal-information/) 

* personal security habits (https://www.pewresearch.org/internet/dataset/march-may-2016-cybersecurity/)

* cybersecurity knowledge (https://www.pewresearch.org/internet/dataset/june-2016-cybersecurity-knowledge/)

* Phishing related statistics from Webroot's _Hook Line and Sinker_ report (https://mypage.webroot.com/rs/557-FSI-195/images/Hook-Line-and-Sinker-Final.pdf)

## Contents 

The code notebook (Jupyter) is annotated to walk through the different analysis that was done, and decisions that were made during the course of the analysis about how to use the data are documented through code comments. The clean data used for the visualizations are provided as .csv files.

Codebook is available in the directory.

## Visualizations

The visualizations will eventually be visible at the project website (https://fr48.github.io/cybersecurity):

Images (still under consideration. rough sketches are in the directory):

* Most Americans have been affected by a data breach, and the type of incidents they have been affected by.

* Perception of what they trust, or don't trust.

* Common security measures they should be using/not using (passwords, device lock, etc)

* Do consumers punish companies after a breach (measured by stock price). Could be small multiples?

Interactive:

* _Time permitting:_ using a game to walk through security decisions

* Scrollytelling to talk about perceptions of privacy and data collection

Tools used for analysis: python, regex, pandas

Tools used for visualizations:
