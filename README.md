# Analysis-of-data-on-bioluminescence

This is a quick analysis of data obtained by me by cultivating a strain of bioluminescent bacteria in the laboratory.

The bacteria are Allivibrio Fischeri, the purpose of the measurements was to compare the luminescence obtained after a certain number of hours for different µL of inoculum and by state of origin of the inoculum.

The experiment lasted one month and was performed as follows:

1) The measurements named 1, 2 and 3 were obtained by inoculating a fresh culture of bacteria, subcultivated in the laboratory.
The inoculum volume is 250, 500 and 1000µL respectively.

2) The measurements named 4, 5 and 6 were obtained by inoculating a culture of frozen bacteria, revitalized following the guidelines of the manufacturer.
The inoculum volume is always 250, 500 and 1000µL respectively.

The cultures, both fresh and frozen, were then left in incubator at 22°C for 24 and 48 hours respectively and then measured with a luminometer.

The cultures, both fresh and frozen, were then left in incubator at 22°C for 24 and 48 hours respectively and then measured by a luminometer to assess their viability.

Since there is not much data collected, the cleaning was done with a few lines of code using Python, Pandas and Numpy via Jupyter Notebook; the visualization of the graphs of interest was obtained using the program PowerBI.

Initial measurements initially assumed that there was not much difference in measured luminescence and that even crops obtained from a frozen mother were even more viable than those obtained from subcultivated bacteria.

However, subsequent measurements disproved this observation, resulting in a significantly higher luminescence from cultures descended from a fresh laboratory grown mother.

More specifically, for fresh samples, there was an extremely marginal difference between the 500 and 1000µL inoculum measurements and both were slightly better than the 250µL inoculum.

For frozen mother inoculations, however, a rather curious situation occurred: the higher the inoculated volume, the lower the luminescence observed and therefore, in this situation, the 250µL inocules proved to be the best performing.

