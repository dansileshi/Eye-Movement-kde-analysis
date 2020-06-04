# Eye analysis using kernel density estimation

Kernel density estimation (KDE) can be used to measure similarity in eye movements between observers. This can be eye movements of two groups (patients vs controls) or within one group. This example demonstrates gaze data from observers collected while they viewed an image. Before computing the KDE, outliers from the normal group (red data point shown in the figure) are discarded using isolation forest algorithm. The KDE computes the probability of the average gaze positions of an observer (blue data point) using the data from controls. If the observer view in the same location (region) as the controls the kde probability will be high and vice versa.
Here's an output from the example:

![alt text](https://github.com/dansileshi/Eye-Movement-kde-analysis/blob/master/output.png)

The kde analysis 

[Here is an example of analysing a real eye movement data using kde.](https://www.youtube.com/watch?v=PyDDjMhkq5M) The visualization shows similarity in fixations among participants who watched the video with no (green), moderate (yellow), and advanced (red) simulated vision loss. 
