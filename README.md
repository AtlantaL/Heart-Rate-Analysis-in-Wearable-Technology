# Wearable Data Analysis

**Authors:** Atlanta Liu, Jenny Kim, Lawrence Shao

**Date:** Winter 2020

This project involved conducting an exploratory data analysis on a set of repeated measures data. With only a limited set of features available, we were tasked to find some actionable insights that could be applied to understand how heart rate is impacted (or vice versa) by a small set of variables in a small sample of joggers who wore a fitness tracker. We attempted a K-Means cluster to see if the data revealed any consistent patterns across multiple groups, looked at the associations between sleep and workout intensity, as well as if there were any visible changes in heart rate amongst runners who ran the most (intrasubject variability). In doing this we ran into an issue of multiple missing timestamps during their jog (runners may have turned off their records during break or perhaps the watch may not have been recording properly). We proposed implementing a cooldown timer that would measure the runner's heart rate recovery over the course of 2mins after they have purposefully stopped their records, allowing researchers to locate why missing timestamps occur and providing another feature that could be used to improve injury prediction results.
