# Jupyter Notebooks

This repo contains the notebooks used for data capture, along with generating figures used in Colin's
paper in CARDIS2020. You can see an example of the Jupyter notebook here:

![](jupyter.png)

## XY Scanner Results

Using a ChipShover controller, we scan part of the WLCSP package. The area scanned is shown below:

![](probeposition.png)

We can see the number of successes and rests at locations:

![](resetsxy.png)
![](successesxy.png)

We can also see the voltage setting required to get at least one successful glitch:

![](successesxyv_single.png)

Or at least 10 successful glitches:

![](successesxyv_multi.png)

A notebook allows you to recreate these figures, but also contain the raw data captures. You can use this to plot other information.