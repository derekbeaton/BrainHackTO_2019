A central home for all the BrainHackTO/Global 2019 on-goings for the outliers project(s) and resources. Details and updates forthcoming!

# Overview

Data are weird and they come in all sorts of types: continuous, categorical, ordinal, and so many more (for an adorable illustration, see Alison Horst's drawings [here](https://twitter.com/allison_horst/status/1185424265287389184)). A common feature across many of the major big neurodata projects (e.g., ONDRI, ADNI, PPMI, UKBioBank): heterogeneous data. 

So, this project takes a different perspective on BrainHackTO's 2019 theme of "Indviduality in the Age of Big NeuroData". This project addresses (1) heterogeneous data and (2) finding outliers. 

This project also has many parts for hackers of all types. This includes (1) resources, materials, and data to learn about (a) heterogeneous data and (b) outlires, (2) contributing new items to existing R packages and a ShinyApp (e.g., documentation, visuals, vignettes), and (3) updating, editing, and generally making existing R packages and a ShinyApp better (e.g., speed ups, memory or computation optimizations). 

Details on the entirety of the project forthcoming. For now here are the resources, links, and packages/apps we'll be working on.

## Packages

* The [Generalized Singular Value Decomposition](https://github.com/derekbeaton/gsvd) package: a core tool for all of our heterogeneous and outlier needs.

* The [Outliers and Robust Structures a.k.a. OuRS](https://github.com/derekbeaton/ours) package: the primary tool for outlier and anomaly detection for heterogeneous data.

* The Ontario Neurodegenerative Disease Research Initiative's [Outliers ShinyApp](https://github.com/derekbeaton/ONDRIApps/tree/master/Outliers). 

## Papers

* The [generalized minimum covariance determinant](https://www.biorxiv.org/content/10.1101/333005v2.abstract) (GMCD)

* High dimensional outlier detection with split-half resampling[see here for a presentation](https://github.com/derekbeaton/OuRS/tree/master/Presentations/JSM2018) and [here for a short publication](https://github.com/derekbeaton/OuRS/tree/master/Publications)

* [Generalized partial least squares](https://www.biorxiv.org/content/10.1101/598888v2)


# Tools and data we'll be using

We'll need R, RStudio, the devtools package, and the roxygen package to help us develop, build, and document. We'll also have a variety of data sets to work with. Some of these data sets will be small toy data sets, small but real data sets, and finally some fairly sizable data sets that are synthesized (via 'synthpop') and imputed (via 'missMDA') from the ADNI project.


# How to make this project work for you!

This pitch has *many* options, and that's the point! We're getting meta with the individuality thing: everyone who wants to take part in this are individuals and so you should be able to get out of this what *you* want. Here are some of the ways:

* Learning about data types and methods to handle them

* Learning how to build, add to, update, and develop R packages

* Learning how to make documention, vignettes, and tutorials

* Anything you want. Do you have an idea or something you want to try out? Pitch it back to this pitch! We'll find a way to suit the individuality of big neurodata for the individuality of you!


