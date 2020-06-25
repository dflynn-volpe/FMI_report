# FMI Waze Hypothesis Document

Pandemic known patterns: 
	+ Less commuter traffic by at least 50%
	+ Less congestion as a result (90% reduction in jams)
	
## Overarching Questions
<details>
<summary>Was the transportation system more efficient during the pandemic? </summary>

#### Specific Questions:

<details>
	<summary>1. Is home delivery of goods more efficient than store delivery?</summary>
	
##### Summary  
Connect individual pings from trucks to determine routes. Compare volume of waze data to delivery truck routes. Compare delivery frequency during the pandemic to pre-pandemic delivery routes. Correlate waze data volume with truck volume in specific areas.
##### What can we do now?
* Connect pings from trucks to determine routes
* Create metric to determine if trucks are doing home delivery or store delivery
* Correlate delivery truck volume to waze volume
##### What do we need to do?
* Find dataset that shows routes from people’s homes to stores
##### What datasets do we need?
* Personal vehicle travel data to stores
##### What can we learn?
* How delivery of goods changed during the pandemic. 
* Efficiency of home delivery trucks vs personal cars.
</details>

<details>
<summary>2. Has rush hour and congestion changed?</summary>
	
##### Summary
Determine differences in waze volume during rush hour compared to waze data to previous years. Compare this volume to truck volume and truck speed. Calculate truck speeds during congestion. Create metric for congestion.
##### What can we do now?
* Calculate waze volume
* Compare waze data to previous years
* Calculate truck volume and speed
* Create metric for congestion
##### What do we need to do?
##### What datasets do we need?
##### What can we learn?
* How rush hour and congestion have changed due to covid. 
* How rush hour and congestion will change over time as states reopen. 
* If changes in rush hour correlate with continued remote working.
* If changes in rush hour remain over time due to changes in work habits (ie working different times)
</details>

<details>
<summary>3. Have truck speeds increased and delivery routes become more direct?</summary>
	
##### Summary
Connect individual pings from a truck to determine the route and create a metric for directness. Measure the speed of trucks. Compare this data to FAF and FMI data from the previous year as a baseline.
##### What can we do now?
* Measure the speed of trucks
* Determine method of connecting individual pings to a truck route
* Determine metric for directness
* Compare pandemic data to baseline data
##### What do we need to do?
* Get FAF dataset
##### What datasets do we need?
* FAF dataset
##### What can we learn?
* How freight has changed during the pandemic and if it will this pattern will continue once traffic levels reach pre-pandemic levels again.
* If the pandemic has lasting effects on freight.
</details>
</details>

<details>
<summary>Did freight travel patterns change during the pandemic? What structures in the transportation system does the pandemic response reveal?</summary>

#### Specific Questions:  
<details>
<summary>1. Is there evidence of people moving out of cities?</summary>
	
##### Summary
##### What can we do now?
##### What do we need to do?
##### What datasets do we need?
##### What can we learn?
</details>

<details>
<summary>2. Will cars be the main transportation method for personal travel?</summary>

##### Summary
##### What can we do now?
##### What do we need to do?
##### What datasets do we need?
##### What can we learn?
</details>

<details>
<summary>*3. Did long-haul vs short-haul freight exhibit different responses in trip efficiency during the pandemic?*</summary>
	
##### Summary
Connect individual pings from a truck to determine the route. Create a metric for determining short-haul vs. long-haul. Determine volume of trucks on the road. Compare this data to previous FMI data and to FAF as baseline.
##### What can we do now?
* Create metric for short-haul vs. long-haul
	* Depends on speed  and distance traveled between pings
* Calculate volume of trucks
* Calculate if these spatial patterns persist over time. 
##### What do we need to do?
* Get FAF dataset
* Apply metric to FAF dataset
* Compare these datasets
##### What datasets do we need?
* FAF
##### What can we learn?
* How short-haul and long-haul freight differ, if at all, in the way they reacted to the pandemic. Freight activity correlates with the economy. Is this reflected in both short-haul and long-haul freight?
</details>

<details>
<summary>*4. Were there more last mile deliveries and more waze activity in affluent areas? Do last mile deliveries change in different communities (suburbs, cities, rural)?*</summary>
	
##### Summary
Correlate change in last mile deliveries with the change in waze volume and affluence of areas. Create metric for last mile delivery of trucks. Correlate these change with affluence levels in different communities.
##### What can we do now?
* Create last mile delivery metric
* Calculate volume of waze data
* Determine how persistent these last mile changes are.
##### What do we need to do?
* Correlate FEHD and census data to changes in last mile delivery and waze volume data
##### What datasets do we need?
* FEHD dataset on types of work
* Census data on income
##### What can we learn?
* Correlation between last mile delivery changes, waze volume changes, and affluence in different areas. 
* Note that census data won’t reflect employment changes due to covid.
</details>

<details>
<summary>5. Did travel patterns correlate to state-level emergency declarations?</summary>
	
##### Summary
##### What can we do now?
##### What do we need to do?
##### What datasets do we need?
##### What can we learn?
</details>

<details>
<summary>6. Will teleworking continue past reopening of states?</summary>
	
##### Summary
##### What can we do now?
##### What do we need to do?
##### What datasets do we need?
##### What can we learn?
</details>
</details>
