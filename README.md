# Baseball
For my udacity EDV class
##Summary 
The graphic shows the relationship between physical attributes and home runs for a collection of 1157 baseball players.
It highlights that, when they hit homers, the "heftier" guys tended to hit more. The more compact fellows and the tall, lanky fellows hit fewer. The trend holds for left, right, and switch hitters. 


##Design
I had more columns than I could show. I chose the HR column over the avg column based on which would be more interesting. 
Since there are multiple columns, and I did not want a table, I chose the bubble plot. It allows me up to 4 different dimensions
on one chart. I chose to put height and weight on the axis because there are so many values that there was no better way to display them. I chose color for handedness as there are only 3 values and color is good for small numbers of categories. Finally the size is set for the HR value since really it was the "result" and has the most impact.

##Feedback 
* Ed Smith 
 * feedback: The legend for handedness needs to stand out more
 * result: Added title and surounding box
* Isabella Raig
 * feedback: The title gets off center when the browser is resized.
 * result: Moved title into svg 
* Coy Raig
 * feedback: OK so I know that im looking at a chart of baseball stats but I don't know what conclussion im seing.
 * result: Added cutsie blurb "The bigger they are, the farther it falls" to sumarize conclussion
 * feedback: What do the circles represent?
 * result: Added legend for bubles
##Resources 
I consulted D3 and Dimple documentation to create the visualization.
