Exploring Titanic Dataset for Udacity Data Analysis Course.
Summary: In the given visualization, I have explored the relationship of Titanic Survivors with their Age and Sex. The graph displays how adult males did not survive the attack compared to females, and young males.
Design: In the given visualization, I chose to display age in ascending order so that one can clearly see how suvival varies with age. I added an animation to explore the survival rates difference in the two genders. Upon feedback, I inverted the colours of the bars - showing blue for survival and red for not survival. I changed this because I got the feedback that red intuitively seemed like "not survived", while in my earlier graph it stood for survival. Upon feedback, I also added clear legend for which sex a viewer is viewing data for. I received feedback that it was not clear in my previous graph.

I used a bar graph because here I am displaying categorical data. The data is for people grouped by age, and these are distinct categories. I did not find it appropriate to use series because we do not have continuous data between the age groups.

Feedback: The main feedback I received was:

Feedback1:
1. The graph displayed the relationship well and what clearly stood out was that more females survived the titanic disaster, while most adult males did not.
2. Age had to be sorted in ascending order
3. The selection of male/female was not clear and the legend had to be highlighted with current selection

Feedback2:
1. Red should display "not survived" instead of "survived".  It is more intuitive to associate red with “not survived”

Feedback3:
1. Initial time lag is too much, and it does not become immediately clear what the graph represents. (Based on this feedback I decreased the time for the highlight to appear)
2. Before one understands what is going on, the graph changes and displays for the other sex. (And that is whenI decreased the speed of animation)

Resources:
1. Stackoverflow for lot of common queries for commands
2. https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.series#addOrderRule to understand the function "OrderRule"
