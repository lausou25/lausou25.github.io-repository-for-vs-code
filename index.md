---
# Do not edit the text between these lines!
layout: default
---

# Summary of Analysis
First, I used read csv rows and columnar to turn the csv data into a table I can visualize with tabulate. I also used head and get_keys to properly set up the column headings. Then I used the select function to just select the own_examples and understanding to analyze. I then used a custom-designed filter function to make two tables, one of students rating own_examples between 1 and 4, and another between 5 and 7. Then I created another custom-designed filter function, but this creates a table where each key is a different category of own_examples rating (1, 2, 3, 4, 5, 6, or 7), and all of the values are each of the understanding survey responses for each student who submitted that comumn's own-example value. I created a scatterplot to show that nearly all of the own_examples values have all of the understanding survey responses, and a line graph and box plot to show the slight positive correlation observed between own_examples and understanding.
# Conclusion

Based on my analysis, the results are somewhat inconclusive, but there appears to be a positive relationshiop between studnets creating theri own examples and their level of understanding. In the box and line plot, higher frequencies of studnets generating their own examples generally correspond to higher reported understanding. Additionally, the box plot shows that students who create their own examples more frequently tend to have higher median understanding levels. Students reporting higher frequences of creating their own examples also tend to report higher levels of understanding. However, the scatter plot indicates the entire range of understanding responses is visible for nearly every response value of own_examples, so it may not be possible to come to a definite conclusion. However, the data does provide some support that students creating their own coding examples may help their understanding, although other factors such as individual learning preferences may contribute to this.  

These findings support my idea that encouraging or requirig students to create their own examples could improve course material understanding. Therefore, I do recommend incorporating regular small assignments (stand-alone problems or ones part of EX assingments) that require students to generate their own coding examples for a given topic. 

However, there are trade-offs that are associated with this recommendation. This strategy could increase studnet workload, and would also likely increase grading workload for TAs, since these assignments may not be feasible to autograde. These assignments may also increase the stress for students already struggling with the material. To address these trade-offs, these assingments could be graded based on completion or for a very low grade percentage. 

To build upon this idea, more survey questions gathering details on how students complete and interact with creating their own examples would be useful. Incorporating low-stakes assingments requring students to create their own code could then be used to generate data that associates the quality of students' coding submissions with their percieved and actual success in COMP 110. Other data gathered could provide insight into if students prefer to craet their own code alone, with a partner, or with tutors/TAs, and if this changes over the duration of the course. 

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
# Visualization

<img src="static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>
<img src="static/imgs/comp110_line_graph.png" alt="Image of line graph. "  width="500"/>
<img src="static/imgs/bar_graph_comp110.png" alt="Image of bar graph. "  width="500"/>
<img src="static/imgs/scatter_comp110.png" alt="Image of scatter plot. "  width="500"/>

