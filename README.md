# UFO
Module 11

## Overview of the Analysis

Purpose of this project was to use UFO sighting provided and create a static web page that allows you to filter sighting results by specific parameters.  The page was built using javascript enhanced with D3, and html enhanced with bootstrap.

## Results

Construction of the table required reading the data.js file and loading it to a table via html.  This is done as a first step when the page is opened and this function is called:

![](https://github.com/lavec0324/UFO/blob/main/static/images/buildtable.PNG)

The functions code:

![](https://github.com/lavec0324/UFO/blob/main/static/images/buildtable_funct.PNG)

As users select options on the filter list they update the filter boxes and the listener waits for a change in any of the elements:

![](https://github.com/lavec0324/UFO/blob/main/static/images/apply_change_listener.PNG)

That listener invokes another function that stores the updated filters and aggregates to existing filters if they are present:

![](https://github.com/lavec0324/UFO/blob/main/static/images/update_filter.PNG)

Finally, the above will call a filtered table function to present the filtered results:

![](https://https://github.com/lavec0324/UFO/blob/main/static/images/filter_updates.PNG)

## Summary

One drawback of this webpage:

* 

Two additional recommendations:

* 
