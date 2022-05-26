# PyPlottingASK
My contribution to the Newcastle University academic skills kit. A repository of jupyter notebook based teachings on producing academic grade plots with various python packages.



## Accessing Python on Campus and on your Personal Computer

Might be easiest to take this from your notes Chris as I'm not that familiar with the Uni virtual machines. However apart from that I'd introduce Jupyter notebook and Spyder here, along with one or two other methods of running python code. Could point out differences between running python code in a terminal vs an IDE. 

Would consist of one maybe two notebooks max, probably mostly markdown. 

## A Crash Introduction to Python

Structure of a python file, data types, importing packages, functions, indexing, slicing arrays/lists. Start to introduce the core packages that you will always use, so numpy and its specific data types. 

Maybe a short piece on how to google something you want to do, finding a relevant python package, installing that package and making sense of a packages wiki page in order to use it. 

One notebook on the intro, one on looking up a package. 

## Importing your data into Python

Pick some most common data formats, .csv's, .xls, plain text, maybe an image as well? Would be a good time to explain good practices with choosing the structure to save your data, assuming you have a choice. 

Examples should come from freely available internet sources that have different data structures to show off problem solving when it comes to parsing data you want from a file.  Maybe some example data structures from lab equipment that chooses its own data structure. 

Is it worth going into detail with different packages for importing data? Or just stick with either numpy, csv or pandas?

One notebook on Best practices in saving your data, another notebook on importing data of various data structures. Possibly a third on alternative packages for importing data. 


## Common Data Processing functions

This section will introduce some basic data processing, so introduce np.arrays, recap on indexing. Basic array functions like ave and std, increasing in complexity to polyfit, then finally lmfit just like your notes Chris. 

If image processing is relevant then possibly some basic image operations as well. 

Maybe some filtering, peak finding, sub-sampling, FFT. But try not to go over the top here, perfect place to leave some external resources for students who want more here. 

One notebook should do, using a data import function made in a previous notebook.


## Best Practices when Plotting with Matplotlib


This section will introduce matplotlib, best practices with producing figures, all the basic operations and figure formatting required for a long text or presentation. 

Mention file formats when saving figures and the best practice of using scalable vector graphics for plots. Though does word still not support .svg's?

Probably two notebooks here, One for a strait forward linear workflow then another using functions/classes, the point of the second is only having to specify your figure formatting once to keep a consistent look to your figures when working on long texts.



## Advanced Plotting, 3d and animations

This section would have short examples on advanced plotting, using imshow, 3d  and animated plots, possibly interactive GUI elements as well. 

One notebook likely, with the data importing now abstracted to a hidden function to concentrate information down for more advanced users. 


## A quick start in the debugging procedure

Not sure about this section but I have a small idea brewing on showing a brief overview on how to get started with debugging.


## Appendix / Optional Extras

Could go into further detail with functions and classes, possibly even on application structure. 

