# Baseball
For my udacity EDV class
##Summary 
The graphic shows the relationship between physical attributes and home runs for a collection of 1157 baseball players.
It highlights that, when they hit homers, the "heftier" guys tended to hit more. The more compact fellows and the tall, lanky fellows hit fewer. The trend holds for left, right, and switch hitters. 


##Design
I had more columns than I could show. I chose the HR column over the avg column based on which would be more interesting. 
Since there are multiple columns, and I did not want a table, I chose the bubble plot. It allows me up to 4 different dimensions
on one chart.

I chose to put height and weight on the axis because there are so many values that there was no better way to display them. 
Also I wanted the graph's plane to represent the relationship of the body attributes. Its not just weight nor height but the relationship of the two that's important.
I chose color for handedness as there are only 3 values and color is good for small numbers of categories. 

Finally the size is set for the HR value since really it was the "result" and has the most visual impact.


##Feedback 
* Ed Smith 
 * feedback: The legend for handedness needs to stand out more
 * result: Added title and surrounding box
* Isabella Raig
 * feedback: The title gets off center when the browser is resized.
 * result: Moved title into svg 
* Coy Raig
 * feedback: OK so I know that I'm looking at a chart of baseball stats but I don't know what conclusion I'm seeing.
 * result: Added cutesy blurb "The bigger they are, the farther it falls" to summarize conclusion
 * feedback: What do the circles represent?
 * result: Added legend for bubbles
* Udacity Grader
 * feedback: One thing I noticed was that the visualization is over plotted, and the large circles are covering some of the smaller circles.
 * result: Removed mouseover event handler. I have not been able to find a way to rearrange the drawing so smaller circles are above larger ones. So I removed the event handler altogether
 * feedback: the reader should be explicitly told that home runs is encoded to radius.
 * result: added HR legend
 * feedback: the x and y axes should have units like height (inches) and weight (lbs)
 * results: Replaced axis titles
 * feedback: I've seen this data set before, so I know what B L and R stand for. Somebody who hasn't seen it before might or might not especially B. The plot should mention what those letters represent or right them out "right handed", etc.
 * result: added handedness title to legend
 * feedback: I think "the bigger they are, the harder it falls..." is a fun line, but it probably wouldn't give the reader enough information to understand the story. I'd write out a short sentence or two explaining more explicitly what the chart is trying to show.
 * result: Removed cute blurb and added verbage to explain the chart

 
##Resources 
I consulted D3 and Dimple documentation to create the visualization.
cleanAxis function from stackoverflow