---
title: 'FMI-Waze Cross-Project Hypotheses'
output:
  html_document:
    df_print: paged
    toc: yes
    toc_depth: 3
    toc_float:
      collapsed: yes
      smooth_scroll: yes
---

<!-- saved from url=(0014)about:internet -->
<!-- This needs to be manually added to the second line of the html -->
 
Pandemic known patterns: 

+ Less commuter traffic by at least 50%
+ Less congestion as a result (90% reduction in jams)
	
## Broad Questions
### 1. Was the transportation system more efficient during the pandemic?
1. Has volume, speed, and congestion changed during the pandemic?
1. Have truck delivery routes become more direct?
	
### 2. Did freight travel patterns change during the pandemic? What structures in the transportation system does the pandemic response reveal?
1. Did long-haul vs last-mile freight exhibit different responses in trip efficiency during the pandemic?
1. Were there socioeconomic drivers that led to a change in waze activity or last-mile delivery during the pandemic?

## Research Question Details

### 1-1. Has volume, speed, and congestion changed during the pandemic?
##### Summary
Determine differences in waze volume compared to previous years. Compare waze volume to truck volume and truck speed. Calculate truck speeds during congestion.

##### Action Items:

* Create metric for congestion
	* Waze volume
* Compare waze data volume to previous years
* Calculate truck volume and speed
* Correlate truck data with congestion
* Compare this congestion to the previous data
* Compare how data changes over time

##### Learning Outcomes:

* How truck volume and speeds correlate to congestion and how this correlation has changed due to covid
* How truck volume, speed and congestion will change over time as states reopen
* How changes in congestion correlate with continued remote working
* If changes in congestion remain over time due to changes in work habits (ie working different times)

### 1-2. Have truck delivery routes become more direct?	

##### Summary

Connect individual pings from a truck to determine the route and create a metric for directness. Measure the speed of trucks. Compare this data to FAF and FMI data from the previous year as a baseline.

##### Data sets Needed:

* FAF data set

##### Action Items:

* Measure the speed of trucks
* Determine method of connecting individual pings to a truck route
* Determine metric for directness
	* map matching
* Compare pandemic data baseline data

##### Next Steps:

* Obtain FAF data set

##### Learning Outcomes:

* How freight routes have changed during the pandemic 
* How freight speeds have changed during the pandemic
* If these pattern will continue once traffic levels reach pre-pandemic levels
* If the pandemic has lasting effects on freight

### 2-1. Did long-haul vs. last-mile freight exhibit different responses in trip efficiency during the pandemic?	

##### Summary

Connect individual pings from a truck to determine the route. Create a metric for determining short-haul vs. long-haul. Determine volume of trucks on the road. Compare this data to previous FMI data and to FAF as baseline.

##### Data sets Needed:

* FAF

##### Action Items:

* Create metric for short-haul vs. long-haul
	* Depends on speed and distance traveled between pings
* Calculate volume of trucks
* Calculate if these spatial patterns persist over time

##### Next Steps:

* Get FAF data set
* Apply metric to FAF data set
* Compare data sets

##### Learning Outcomes:

* Changes in freight response to the pandemic
* How short-haul and long-haul freight differ, if at all, in the way they reacted to the pandemic
* Strength/weaknesses of freight infrastructure

### 2-2. Were there socioeconomic drivers that led to a change in waze activity or last-mile delivery during the pandemic?
##### Summary
Correlate change in last mile deliveries with the change in waze volume and affluence of areas. Create metric for last mile delivery of trucks. Correlate these change with affluence levels in different communities.

##### Data sets Needed:

* LEHD data set

##### Action Items:

* Create last mile delivery metric
* Calculate volume of waze data
* Determine how persistent these last mile changes are
* Determine other variables to be correlated

##### Next Steps:

* Correlate LEHD and census data to changes in last mile delivery and waze volume data

##### Learning Outcomes:

* Correlation between last mile delivery changes, waze volume changes, and affluence in different areas. 
* Note that census data won’t reflect employment changes due to covid.

### Others Questions

* Is there evidence of people moving out of cities?
* Will cars be the main transportation method for personal travel?
* Did travel patterns correlate to state-level emergency declarations
* Will teleworking continue past reopening of states?
* Is last mile delivery more efficient than individual store trips?
