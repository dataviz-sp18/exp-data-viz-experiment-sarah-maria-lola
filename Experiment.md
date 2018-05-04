Data Visualization Experiment
================
Dolores De Iturbe, Maria Diego and Sarah Mixon

Question
--------

Does removing visual cues, such as y-axis labels, affect the accuracy of judgements when comparing values using the three highest ranked perceptual tasks?

Hypothesis
----------

Using Cleveland and McGill’s hierarchical ranking of perceptual tasks - position along a common scale, position along nonaligned scales, and length - which allow more accurate judgements, we wanted to test an idea related to minimalist chart design and the inclusion of visual cues. Our hypothesis is that as the scale cues on the y-axis are reduced, value comparison judgements become less accurate.

Data and methodology
--------------------

To test our hypothesis, we designed a Qualtrics survey that asked respondents to compare values in graphs they were shown. We created four sets of graphs, each set containing a ‘control’ and a ‘treatment’ version. The ‘control’ graphs included small intervals on the y-axis, and the ‘treatment’ graphs only contained the minimum and maximum values on the y-axis. Each set of graphs (shown below) was created to replicate Cleveland and McGill’s hierarchical ranking of perceptual tasks. Respondents only saw one graph, either the control or treatment, from each set, for a total of four graphs seen by each respondent. For each graph, respondents were asked to choose the correct relationship between A, C, and D - either ‘A + C &gt; D’, ‘A + C &lt; D’, or ‘A + C = D’. The Qualtrics survey was published on MTurk, where we had a total of 53 responses. Below is a table to summarize how many respondents saw each type of graph.

| Question                             | Treatment | Control | Total |
|--------------------------------------|-----------|---------|-------|
| Position on Common Scale             | 27        | 24      | 51    |
| Position on Common Scale and Ordered | 28        | 23      | 51    |
| Position Along Nonaligned Scale      | 23        | 28      | 51    |
| Length                               | 21        | 30      | 51    |
| Position on Common Scale and Ordered | 28        | 23      | 51    |

Of those 53 observations, there was one respondent that gave two answers for one graph. We chose not to include this observation. There was also a worker who submitted the survey two times. We paid the worker; however, we chose not to include their responses because they had seen either both the treatment and control graphs for at least one set or had seen the same graphs a second time, which left us with 51 respondents. Bellow are the four sets of graphs used in the MTurk Survey:

***Graph set 1: Position along a common scale - scatter plot*** <img src="graph_set_1.png" width="669" />

*Graph set 1: Position along a common scale - The first set is a dot plot and is meant to replicate the task “position along a common scale”. The control graph, on the left, has a y-axis that ranges from 0 to 12 and increases in increments of 3. The treatment graph, on the right, has a y-axis that ranges from 0-15 with no incremental cues.*

***Graph set 2: Position along a common scale - ordered scatter plot*** <img src="graph_set_2.png" width="654" />

*Graph set 2: Position along a common scale - The second set is a dot plot and is meant to replicate the perceptual task “position along a common scale”. The difference, however, between this set of graphs and the first is that these data points are ordered in descending value. The control graph contains a y-axis with incremental cues and the treatment graph does not.*

***Graph set 3: Position along nonaligned scales- different axis*** <img src="graph_set_3a.png" width="663" />

<img src="graph_set_3b.png" width="677" />

*Graph set 3: Position along non aligned scales - The third set is a bar graph and is meant to replicate the task “position along nonaligned scales”. The control graph on top has a y-axis with incremental cues, and the treatment graph, on the bottom, does not. However, the value comparison forces the respondent to compare values between two graphs (left and right) that have different origin points on the y-axis (0 and 25).*

***Graph set 4: Length - floating axis*** <img src="graph_set_4.png" width="657" />

*Graph set 4: Length - The fourth set is a bar chart and is meant to replicate the perceptual task “length” where none of the bars start at a common origin. The control graph, on the left, has a y-axis that includes increments of 25. The treatment graph, on the right, has a y-axis that does not include any incremental cues.*

Results
-------

In our analysis, we decided to look at two different phenomena. First, for each set of graphs we wanted to compare the accuracy of judgements between graphs with and without incremental cues on the y-axis. To do this, we compared the percent of correct answers for the treatment graph to the control graph within each set of graphs.

***Figure 1***
![](Experiment_files/figure-markdown_github/unnamed-chunk-9-1.png)

For the first set of graphs where we tested position along a common scale using scatter plots, we see the opposite of what we were expecting; that is, a higher percentage of correct answers for the treatment group (67%) than in the control group (58%). Nonetheless, as Figure 1 above shows, both percentages for treatment and control are high and not very different.

***Figure 2***
![](Experiment_files/figure-markdown_github/unnamed-chunk-10-1.png)

The second set of graphs we test position along a common scale again but this time using ordered scatter plots. We find that there is almost no difference in the percentage of correct answers between the two groups. The percentage of correct answers in both groups is around 57% as we can see in Figure 2 .

***Figure 3***
![](Experiment_files/figure-markdown_github/unnamed-chunk-11-1.png)

Next, we test the perceptual task of position along nonaligned scales with different y-axis for the plots. We find that 86% of the control group answered correctly, in comparison to 78% in the treatment group, in line with our hypothesis.

***Figure 4***
![](Experiment_files/figure-markdown_github/unnamed-chunk-12-1.png)

Finally, when testing across treatment and control group, we analyze the length perceptual task using a floating bar chart and we confirm our hypothesis given that we see a greater difference with the percentage of correct answers for the control group (53%) than for the treatment group (38%). These results suggest that including visual cues does not necessarily make these judgements more accurate as we only confirm our hypothesis when using length and position along nonaligned perceptual tasks which are more difficult to judge accurately.

For the second part of our analysis, we wanted to compare the accuracy of judgements across the different perceptual tasks. To do this, we compared the percent of correct answers for each of the four sets of graphs in the control and treatment groups separately.

***Figure 5***
![](Experiment_files/figure-markdown_github/unnamed-chunk-13-1.png)

For the control group, where we included cues, we find that the highest percentage of correct answers corresponds to the different axis bar plot (86%), followed by the scatter plot (58%), the ordered scatter (57%) and, finally, the lowest percentage of correct answers corresponds to the floating bars plot with only 53% of correct answers.

***Figure 6***
![](Experiment_files/figure-markdown_github/unnamed-chunk-14-1.png)

For the treatment group we find, as in the control group, that the different axis graph is the one with the greatest percentage of correct answers (78%) followed by the scatter plot (67%), the ordered scatter plot (56%) and, in line with our findings for the control group, the lowest percentage of correct answers corresponds to the floating bars graph where only 38% of people got to the right answer.

Conclusion
----------

Based on the results from this experiment, we see that visual cues, such as incremental y-axes, are more important for certain types of perceptual tasks than for others. We find that, for those perceptual tasks ranked higher for more accurate judgements, the inclusion or non-inclusion of visual cues did little to increase the percent of correct answers between the treatment and control groups. However, as we move down the ranking of perceptual tasks, we see a higher percent of correct answers for those graphs that do include visual cues. Surprisingly, we find that for the task ‘position on a common scale’, accurate judgements are lower for both treatment and control groups than the lower ranked ‘position on nonaligned scales’. This finding warrants further exploration in future studies. Overall, this experiment was meant to explore the idea of chart minimization and its impact on the accuracy of judgements. We find that, for the purpose of value estimation and comparison, visual cues are necessary for accurate judgements, especially as lower ranked perceptual tasks are used to visual the data.

Appendix
--------

    ## # A tibble: 8 x 4
    ##               graph count correct prop_correct
    ##               <chr> <int>   <int>        <dbl>
    ## 1       DIFFERENT.C    28      24     85.71429
    ## 2       DIFFERENT.T    23      18     78.26087
    ## 3        FLOATING.C    30      16     53.33333
    ## 4        FLOATING.T    21       8     38.09524
    ## 5 ORDERED.SCATTER.C    23      13     56.52174
    ## 6 ORDERED.SCATTER.T    28      16     57.14286
    ## 7         SCATTER.C    24      14     58.33333
    ## 8         SCATTER.T    27      18     66.66667
