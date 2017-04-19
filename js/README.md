Moving some of the documentation from the source code into this readme to make options more transparent.

### Box plot

* @param [options.show=true] Toggle the whole plot on and off
* @param [options.showBox=true] Show the box part of the box plot
* @param [options.showWhiskers=true] Show the whiskers
* @param [options.showMedian=true] Show the median line
* @param [options.showMean=false] Show the mean line
* @param [options.medianCSize=3] The size of the circle on the median
* @param [options.showOutliers=true] Plot outliers
* @param [options.boxwidth=30] The max percent of the group rangeBand that the box can be
* @param [options.lineWidth=boxWidth] The max percent of the group rangeBand that the line can be
* @param [options.outlierScatter=false] Spread out the outliers so they don't all overlap (in development)
* @param [options.outlierCSize=2] Size of the outliers
* @param [options.colors=chart default] The color mapping for the box plot

### Notched box plot

* @param [options.show=true] Toggle the whole plot on and off
* @param [options.showNotchBox=true] Show the notch box
* @param [options.showLines=false] Show lines at the confidence intervals
* @param [options.boxWidth=35] The width of the widest part of the box
* @param [options.medianWidth=20] The width of the narrowist part of the box
* @param [options.lineWidth=50] The width of the confidence interval lines
* @param [options.notchStyle=null] null=traditional style, 'box' cuts out the whole notch in right angles
* @param [options.colors=chart default] The color mapping for the notch boxes

### Violin plot

* @param [options.showViolinPlot=true] True or False, show the violin plot
* @param [options.resolution=100 default]
* @param [options.bandwidth=10 default] May need higher bandwidth for larger data sets
* @param [options.width=50] The max percent of the group rangeBand that the violin can be
* @param [options.interpolation=''] How to render the violin
* @param [options.clamp=0 default]
*   0 = keep data within chart min and max, clamp once data = 0. May extend beyond data set min and max
*   1 = clamp at min and max of data set. Possibly no tails
*  -1 = extend chart axis to make room for data to interpolate to 0. May extend axis and data set min and max

### Swarm/scatter plot

* @param [options.show=true] Toggle the whole plot on and off
* @param [options.showPlot=false] True or false, show points
* @param [options.plotType='none'] Options: no scatter = (false or 'none'); scatter points= (true or [amount=% of width (default=10)]); beeswarm points = ('beeswarm')
* @param [options.pointSize=6] Diameter of the circle in pizels (not the radius)
* @param [options.showLines=['median']] Can equal any of the metrics lines
* @param [options.showbeanLines=false] Options: no lines = false
* @param [options.beanWidth=20] % width
* @param [options.colors=chart default]
