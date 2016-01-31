---
layout: post
title:  Spearman's Rank
date:   2016-01-31 14:24:23 +0000
categories: skills
---
<img src="{{ site.baseurl }}/image/rivers/correlation.svg" style="width:300px; float:right;"> Looking at the relationship between two independant variables, Spearman's will show what type of correlation there is.

<br><br><br>

#### **How to plan and draw a Spearman's Rank**

* Ensure there's a title of what the rank shows


1. Formulate a hypothesis or a predition - i.e: *as you move away from the centre of London, the number of pedestrians will decrease*
2. Carry out the investigation at a reasonable interval (such as every 10 minutes) and collect at least 10 samples - i.e: *10 sites in London, counting every 10 munutes at each*
3. Put results into a table with appropriate headings - i.e: *Distance and no. people*
4. Plot a scatter graph with the information from the table with a summary comment - *the graph shows as distance from the centre of london increases, the number of people decrease*.
5. Complete the Spearman's rank table.
6. Conclude from data in Spearman's table about correlation shown

#### **Example: *Spearman's rank for Hydraulic Radius*:**
*The closer to 1 the hydraulic radius is, means the river is flowing more efficiently*

1.***Hypothesis:***

<img src="{{ site.baseurl }}/image/rivers/hydraulic-radius.svg" style="width:400px; float:right;">
As distance downstream increases, hydraulic radius (channel efficiency) will increase.

Hydraulic radius is calculated by "cross-sectional area/wetted perimiter"

So for above, Hydraulic Radius = 28/15 = 1.87

<br>
3. ***Data from investigation:***

| Site location | Hydraulic Radius (efficiency) |
| --- | --- |
| A| 0.02 |
| B| 0.02|
| C| 0.07|
| D| 0.05|
| E| 0.08|
| F| 0.081|
| G| 0.33|
| H| 0.297|
| I | 0.46|
| J | 0.323|

<br>

4.***Graph:***


<img src="{{ site.baseurl }}/image/rivers/hydraulic-radius-graph.png" style="width:600px;">

5.***Table of Results:***

| Site Location | Rank from source <br> near to far | Hydraulic Radius | Rank <br>(large to small) | Rank Difference <br> (D) |&nbsp; D² &nbsp; |
| --- | --- | --- | --- | --- | --- |
| A | 10 | 0.02 | 9 | 1 | 1 |
| B| 9| 0.02| 9 | 1| 1|
| C| 8| 0.07| 7| 1| 1|
| D| 7| 0.05| 8| -1| 1|
| E| 6| 0.08| 6 | 0| 0|
| F| 5| 0.081| 5| 0| 0|
| G| 4| 0.33|2 |2 |4 |
| H| 3| 0.297|4|1 |1 |
| I| 2| 0.46|1 |1 |1 |
| J| 1| 0.321| 3 |-2|4 |
|  |  |  | | | **Σ = 13** |

<img src="{{ site.baseurl }}/image/rivers/spearman2.png" style="width:200px;">

n = 10 as 10 sites

<img src="{{ site.baseurl }}/image/rivers/spearman1.png" style="width:200px;">

*Rs = 1 - 0.078878*

*Rs = 0.9212122*

***Rs = 0.92***

<br>

6.**Concluding**

* The value of 0.92 is between +1 and -1 so is ok
* The critical value for 10 results is -0.8 - +0.8 so the result is within the range of a significant positive result

<img src="{{ site.baseurl }}/image/rivers/spearman-relationship.png" style="width:400px;">

The 0.92 value mans there is a significant correlation between the distance from source and the river's efficiency, this is reflected in my scatter graph.
This means that my hypotheisis was correct, as further downstream the riveris more efficient.


The reason a river with a greater hydraulic radius has a greater velocity is as it has:

* A wider channel so can transport more discharge
* A lighter bedload made of smaller objects such as smoother worn down rock and sand-like particles instead of heavy large boulders
* Smoother channel so less erosion and drag which slows the velocity of the water.