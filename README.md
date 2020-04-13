# Project Reproducibility

The goal of this repository is to serve as an example on how to set up any type of data analysis in a reproducible way.

I think this should be considered a best practice in the sciences. Unfortunately, it is not yet a very widespread practice.
Let me tell you why it is at least good for you as a scientist to strive for reproducibility in your projects:

- You keep all the files to run an analysis organized and contained on the same place.
- You save time for yourself when you need to rerun the analysis further down the road: changed a small variable, fix a database, plot figures again, put them on a report, etc.
- It is easier to share code with other people that might need it, saving you time on explanations and increasing your academic presence.
- Saves you time if you stopped working on the project, even if it's only for a short while, you can easily take over were you left off.
- Save time and resources for others that might take over your project later.
- Get proper credit for the work that you have done, even if it is not published on a journal or book. A reproducible project sets a good precedent of work that someone can build upon and not just start over, supporting proper credit to your own work.

So, what are the main parts of a reproducible project?

## the README file

<img align="right" width="150" src="http://experimentalmath.info/blog/wp-content/uploads/2013/01/miracle-264x300.gif">

As you can see, the README file should contain at least a description of your project.
You should also explain the steps to take if you want to run the analysis for the first time on a new computer:
where to start, do you need to contact someone for more information, etc.
Generally explain the how and why of each step of the analysis.

<!-- ![Then a miracle occurs...](http://experimentalmath.info/blog/wp-content/uploads/2013/01/miracle-264x300.gif) -->

## The code folder

This contains all code needed for data retrieveing and cleaning, analysis, figures, and report generation.
Ideally, functions that automatize repetitive tasks, for example:

- code to load the raw data, either from an online database, other repository, or from the `data-raw folder`
- code to clean the raw data and save the clean data in the `data folder`
