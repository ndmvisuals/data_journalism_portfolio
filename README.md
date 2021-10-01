# Nick's Data Journalism Work Samples

## Overview

This repository shows examples of the code I have written as a data reporter at the [Howard Center for Investigative Journalism at the University of Maryland](https://merrill.umd.edu/about-merrill/signature-programs/the-howard-center-for-investigative-journalism/).

These code samples have been chosen to show my skills as a data journalist and team leader since starting my graduate education.

## Data Team Leader for OSHA Investigation

I led a data team of 7 journalists for the Howard Center's [“Essential and Exposed,”](https://cnsmaryland.org/essential-and-exposed/) investigation, a deep dive into how the Occupational Safety and Health Administration failed to protect essential workers amid the pandemic.

The story was picked up by the [The Washington Post](https://www.washingtonpost.com/business/walmart-sales-soared-essential-workers-got-scant-protection/2021/05/12/a4fe5d6a-b33f-11eb-bc96-fdf55de43bef_story.html)and others. Read the full version on the Howard Center website [here](https://cnsmaryland.org/2021/05/12/as-walmart-sales-soared-workers-got-scant-covid-19-protection-from-osha/).

I was responsible for compiling the code and results that led to each sentence in the story generated by our team's data analysis, publishing a [factcheck document](https://howard-center-investigations.github.io/essential_and_exposed/osha_walmart/index.html) so our methods were transparent to the public.

Some of the main data findings I was responsible for, using R for my analysis, include:

1. When workers submit COVID-related complaints, only a fraction lead to inspections, and even fewer result in a citation.[My analysis](https://github.com/ndmvisuals/data_journalism_portfolio/blob/main/osha_investigation/osha_complaints_pipeline.Rmd) of osha complaints and enforcement data led to the main data finding that **"As of late March, 3% of closed COVID-19 complaints to federal OSHA offices deemed valid by the agency resulted in an inspection, 12.5% of which led to citations with an average penalty of $13,000. OSHA has reduced over a third of penalties."**
2. I combined Walmart location data with our analysis of worksite outbreak data from health departments to come up with the finding that: **"Across 10 states, one quarter of Walmart-owned facilities had COVID-19 cases"**
3. I coded a [script](https://github.com/ndmvisuals/data_journalism_portfolio/blob/main/osha_investigation/combining_oregon_outbreak_reports.Rmd) that compiled over 30 separate workplace outbreak reports from Oregon Health Authority workplace outbreak data into one dataset. This allowed us to identify the number of Walmarts in the state that had outbreaks.

I also taught the team how to use Git, a form of version control that enables collaborative coding. I created a [template](https://github.com/ndmvisuals/data_analysis_template) for future projects, based on AP data kit best practices, that standardize our team's approach to data analysis.

## Web Scraping

I have written multiple web scrapers in Python to aid in the collection of unique data for analysis in stories.

I have written scrapers using Selenium and Requests, and can automate them to run independently using Github Actions.

### Court Scraper - Object Oriented Programming

As part of a collaboration between the [Howard Center for Investigative Journalism at the University of Maryland](https://merrill.umd.edu/about-merrill/signature-programs/the-howard-center-for-investigative-journalism/) and [Big Local News](https://biglocalnews.org/#/login), I contributed code for a generic court-scraper that supports the most common court record website platforms.

Specifically, I created a [web scraper](https://github.com/ndmvisuals/data_journalism_portfolio/blob/main/web_scraping/Shelby%20Court%20Scraper.ipynb) for Shelby Country Court that download court cases for a specific date range. Since there is no functionality on their website to search cases by date, I wrote an algorithm that will return the latest case through a brute force methodology.

### Scraping police logs

As part of an ongoing project, I am scraping police logs published by universities in the D.C area.

This [web scraper](https://github.com/ndmvisuals/data_journalism_portfolio/blob/main/web_scraping/umd_scraper.ipynb) uses the request library to download data from the University of Maryland since they do not offer a way to bulk download their data.

Using this [workflow](https://github.com/ndmvisuals/data_journalism_portfolio/blob/main/web_scraping/automated_scraper_github_action.txt) that I coded on Github actions, the scraper will run automatically each week and save the data to the repo.

### Organization of Data and Automation

Along with data analysis for journalism stories, I love finding ways to automate tasks in everyday life and efficiently organize information.

- Here is a [tutorial](https://github.com/ndmvisuals/data_driven_resume_lesson) that I put together to teach people how to automate their resume creation.
- Here is a [data project template](https://github.com/ndmvisuals/data_analysis_template) that I standardized for the Howard Center data team

## About Me

Nick McMillan is a data and video journalist, currently based at the Howard Center for Investigative Journalism.

He previously worked for Newsy on their investigative documentary team, where he shot and edited documentaries, as well as visualized unique data analysis in the form of motion graphics.

McMillan is pursuing a master's degree in journalism with an emphasis on investigative and computational journalism at the [Philip Merrill College of Journalism at the University of Maryland](https://merrill.umd.edu/). His undergraduate degree is from [Rice University](https://www.rice.edu/), where he studied statistics.

## Resume

[Nick's Resume](https://github.com/ndmvisuals/data_journalism_portfolio/blob/main/resume/NICKS%20RESUME%202021.pdf)

## Website

www.nickmcmillan.com
