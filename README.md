## Mass-Spectrometry-Peak-Analysis
Analyzed mass spectrometry peaks in detecting efficacy of tablets from three distinct brands of aspirin with 90% correctness. (Tools used: R)

A chemist is studying the chemical make-up of three tablets from three distinct brands of aspirin using liquid
chromatography-tandem mass spectrometry. In our project, we were provided 7 peaks of mass spectrometry data.
In each peak there are three tablets with 3 different intensities. Our prime goal is to check whether there is any
difference in each peak between the three kinds of tablets.
We have started exploratory data analysis for each pill of each brand under each peak. We used the Time versus
IntesnityPlot, QQPlot, Boxplots, and SmoothScattered plots for our exploratory data analysis. We can see the
distribution of numerical data and skewness by displaying the data quartiles (or percentiles) and averages using
the Intensity vs Time Plot; QQplots shows the type of distribution; and Boxplots shows the distribution of
numerical data and skewness by displaying the data quartiles (or percentiles) and averages. After that, we used
Smoothscatterd plot to create a smoothed color density representation of a scatterplot using a (2D) kernel density
estimate. We then used the mean of the intensity values for a specific aliqout for each tablet of each brand to
compute the area under a peak (AUP). Then we averaged the means of three aliqout intensities for each pill type,
yielding nine total averages of intensities for three pills from each brand. Then, for each peak, we ran a one-way
anova. ANOVA shows us whether there are differences in group means, but it doesn’t tell us what they are. Later,
we used a Tukey’s Honestly Significant Difference (Tukey’s HSD) post-hoc test for pairwise comparisons to see
whether groups were statistically different from one another.
