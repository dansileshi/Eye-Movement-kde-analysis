# Eye analysis using kernel density estimation

Kernel density estimation (KDE) can be used to measure simillarity in eye movements between observers. 
This can be eye movements of two groups (paitents vs contorls) or within one group. 
This example demonstrates gaze data from observers collected while they viwed an image. Before computing the KDE, outliers are discarded the available gaze data of the no VF loss group were excluded 
using isolation forest algorithm. The KDE function was used to compute the probability 
of the average gaze positions of an observer in based on the data from contrls. If the observer viwed in the same locaiton (region)
as the controls the kde probablity will be high and vice versa.

Here's an output from the example:

![alt text](https://github.com/dansileshi/Eye-Movement-kde-analysis/blob/master/output.png)
