# What is this repo?
NASA's Kepler Space Telescope has collected high-precision, high-cadence time series photometry on 781,590 unique postage-stamp targets across 21 different fields of view. These observations have already yielded 2,496 scientific publications by authors from 63 countries. The full data set is now public and available from NASA's data archives, enabling continued investigations and discoveries of exoplanets, oscillating stars, eclipsing binaries, stellar variability, star clusters, supernovae, galaxies, asteroids, and much more.

In this repo, we document 20 important data analysis projects which are enabled by the archive data. You can read the accompanying white paper [here](whitepaperlink). The aim of this paper is to help new users understand where there may be important scientific gains left to be made in analyzing Kepler data, and to encourage the continued use of the archives. 
With the TESS mission about to start releasing data, the studies will inform new experiments, new surveys, and new analysis techniques. The Kepler mission has provided an unprecedented data set with a precision and duration that will not be rivaled for decades. The studies discussed in this paper show that many of Kepler's contributions still lie ahead of us, owing to the emergence of complementary new data sets like Gaia, novel data analysis methods, and advances in computing power. Kepler's unique data archive will provide new discoveries for years to come, touching upon key aspects of each of NASA's three big astrophysics questions; How does the universe work? How did we get here? Are we alone? 

# Why are these projects still available?
Kepler's community has been vibrant, innovative, and has produced science at a spectacular pace. 
All the projects listed in this paper have already been explored by talented teams. Certain aspects of these projects have remained unsolved -- not because of a lack of drive or expertise, but primarily for the following reasons:


* K2's open data policy and its fast-paced delivery schedule (new data was released approximately every 3 months) have encouraged users to pursue quick, high-impact discoveries first. Projects which are more time-consuming have been lower priority, potentially meaning several more difficult discoveries and analyses are awaiting attention from the community.
* Some projects could not be completed until the final data products had been released. For example, occurrence rate studies require complete, uniform, and carefully-characterized planet catalogs. Other studies are waiting for the K2 uniform global re-processing effort to complete.
* Some projects were not computationally tractable in the early days of Kepler. New data analysis techniques (such as easily accessible machine learning tools) and more computational power allows them to be executed now.
* Some data products can be challenging to work with. Challenges include large file sizes and complicated data formats. The Kepler Guest Observer (GO) Office have recently begun releasing new High Level Science Products and new tools and tutorials (see the [lightkurve](https://docs.lightkurve.org) Python package) to enable the community to better access Kepler data and expertise, including the more unusual data products. 

Below we summarize 20 science opportunities (10 exoplanet, 6 galactic, 2 extragalactic, and 2 solar system science projects). They have been inspired by a multitude of existing recent literature publications and conference presentations. While we have made every effort to cite these works, we remind the reader that this paper does not intend to be a comprehensive literature review.

# How to use this repo

The issues on this github repo are all projects that could be done with Kepler data. At the time of writing these are all projects where new publications could be made. If you are interested in completing one of these projects, please go ahead! If you have valuable insights to contribute, or directions to add to the projects, please do comment on the issues. Particularly if you feel there is helpful literature that hasn't been mentioned, do add it to the issue. 

If you feel there are projects that are missing from the list, you can open a new issue and add a label (Exoplanet Science, Stellar Astrophysics, Extragalactic Astrophysics or Solar System Science) to help direct peoples attention. 
