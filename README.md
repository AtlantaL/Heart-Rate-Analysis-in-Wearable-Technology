# Wearable Data Analysis

**Authors:** Atlanta Liu, Jenny Kim, Lawrence Shao

**Date:** Winter 2020

### What's in this repository?

This project involved conducting an exploratory data analysis on a set of repeated measures data. With only a limited set of features available, we were tasked to find some actionable insights that could be applied to understand how heart rate is impacted (or vice versa) by a small set of variables in a small sample of joggers who wore a fitness tracker.

### Procedures

- K-Means clustering to see if the data revealed any consistent patterns when split into multiple groups
- Associations between amount of sleep and workout intensity
- Intrasubject variability: If there were any visible changes in heart rates as runners went on more jogs

### Findings & Study Limitations

We ran into an issue of having multiple missing timestamps during a participant's run (runners may have turned off their watch when taking a break or perhaps the watch may not have been recording properly). We proposed implementing a cooldown timer that would measure the runner's heart rate recovery over the course of 2 minutes after they have purposefully stopped their records. This allows researchers to locate why missing timestamps occur and provide another feature that could be used to further improve injury prediction results.
