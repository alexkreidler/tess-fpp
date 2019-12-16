# TESS False Positive Probability Calculations
Alex Kreidler

The scope of this project is to apply Kepler data validation techniques as described in Morton 2012 to TESS Object of Interest Planetary Candidates.

Then the goal is to independently manually verify a few of the top candidates and confirm them.

## Data Check status update
I've successfully reproduced the results from Morton et al. 2016 on the examples KOI. I am now aggregating additional data for the TESS TOIs to pass as the inputs to github.com/timothydmorton/vespa. I will then write a program to automatically do this for all TOIs and then manually verify a few of them.

## Final Data status update

Since the raw data produced by VESPA is in the gigabytes it is infeasible to upload to Canvas, but I've provided a link to the Github of this repository which contains information about the data sources:



## sources

* Timothy D. Morton  (2012) AN EFFICIENT AUTOMATED VALIDATION PROCEDURE FOR EXOPLANET TRANSIT CANDIDATES. _The Astrophysical Journal_, 761(1), 6. [DOI](http://dx.doi.org/10.1088/0004-637X/761/1/6) 
* Sean D. McCauliff, Jon M. Jenkins, Joseph Catanzarite, Christopher J. Burke, Jeffrey L. Coughlin, Joseph D. Twicken, Miles Cote  (2015) AUTOMATIC CLASSIFICATION OFKEPLERPLANETARY TRANSIT CANDIDATES. _The Astrophysical Journal_, 806(1), 6. [DOI](http://dx.doi.org/10.1088/0004-637X/806/1/6) 
* Timothy D. Morton, Stephen T. Bryson, Jeffrey L. Coughlin, Jason F. Rowe, Ganesh Ravichandran, Erik A. Petigura, Natalie M. Batalha  (2016) FALSE POSITIVE PROBABILITIES FOR ALLKEPLEROBJECTS OF INTEREST: 1284 NEWLY VALIDATED PLANETS AND 428 LIKELY FALSE POSITIVES. _The Astrophysical Journal_, 822(2), 86. [DOI](http://dx.doi.org/10.3847/0004-637X/822/2/86) 
* Christopher J. Shallue, Andrew Vanderburg  (2018) Identifying Exoplanets with Deep Learning: A Five-planet Resonant Chain around Kepler-80 and an Eighth Planet around Kepler-90. _The Astronomical Journal_, 155(2), 94. [DOI](http://dx.doi.org/10.3847/1538-3881/aa9e09) 
* Jon M. Jenkins, Douglas A. Caldwell, Hema Chandrasekaran, Joseph D. Twicken, Stephen T. Bryson, Elisa V. Quintana, William J. Borucki  (2010) INITIAL CHARACTERISTICS OFKEPLERLONG CADENCE DATA FOR DETECTING TRANSITING PLANETS. _The Astrophysical Journal_, 713(2), L120–L125. [DOI](http://dx.doi.org/10.1088/2041-8205/713/2/L120) 
* (n.d.) [ _Kepler False Positive Probabilities Table Description_](https://exoplanetarchive.ipac.caltech.edu/docs/fpp_TableDescription.html) 
* Eduardo Nigri, Ognjen Arandjelovic  (n.d.) Machine Learning Based Detection of Kepler Objects of Interest. , 6. 
* Jon M. Jenkins, Douglas A. Caldwell, Hema Chandrasekaran, Joseph D. Twicken, Stephen T. Bryson, Elisa V. Quintana, … William J. Borucki  (2010) OVERVIEW OF THE KEPLER SCIENCE PROCESSING PIPELINE. _The Astrophysical Journal_, 713(2), L87–L91. [DOI](http://dx.doi.org/10.1088/2041-8205/713/2/L87) 
* Stephen T Bryson, Timothy D Morton  (2017) Planet Reliability Metrics: Astrophysical Positional Probabilities for Data Release 25. , 53. 
* Jeffrey L. Coughlin, F. Mullally, Susan E. Thompson, Jason F. Rowe, Christopher J. Burke, David W. Latham, … Khadeejah A. Zamudio  (2016) Planetary Candidates Observed by Kepler VII The First Fully Uniform Catalog Based on The Entire 48 Month Dataset (Q1-Q17 DR24). _The Astrophysical Journal Supplement Series_, 224(1), 12. [DOI](http://dx.doi.org/10.3847/0067-0049/224/1/12) 
* Benjamin T. Montet, Timothy D. Morton, Daniel Foreman-Mackey, John Asher Johnson, David W. Hogg, Brendan P. Bowler, … Andrew W. Mann  (2015) Stellar and Planetary Properties of K2 Campaign 1 Candidates and Validation of 17 Planets, Including a Planet Receiving Earth-like Insolation. _The Astrophysical Journal_, 809(1), 25. [DOI](http://dx.doi.org/10.1088/0004-637X/809/1/25) 
* Timothy D. Morton  (2015) VESPA: False positive probabilities calculator. _Astrophysics Source Code Library_, ascl:1503.011. 
