# lsst-dsfp-2023

Challenges and solutions for the LSST DSFP 2023.

These will only work in the Rubin Science Platform (RSP) deployed at the
Interim Data Facility (IDF) for Data Preview 0 (DP0), at data.lsst.cloud.
These will only work with the <a href="https://dp0-2.lsst.io/index.html">DP0.2 data release</a>.


## Resources

Particular resources are given in each challenge, but generally all of them are
in the <a href="https://dp0-2.lsst.io/">DP0.2 documentation</a>, including
<a href="https://dp0-2.lsst.io/data-access-analysis-tools/index.html#rubin-science-platform-rsp">instructions for the Rubin Science Platform</a>, the contents
of the <a href="https://dp0-2.lsst.io/data-products-dp0-2/index.html#dp0-2-data-products-definition-document-dpdd">DP0.2 data release</a> (and the <a href="https://dm.lsst.org/sdm_schemas/browser/dp02.html">DP0.2 catalog schema browser</a>), and various <a href="https://dp0-2.lsst.io/tutorials-examples/index.html">DP0.2 tutorials</a>.


## Instructions

### Get set up.

Work in pairs, with one of you as the driver and the other as the navigator.

**Driver:** Has Rubin data rights and is logged in to their account in the 
Rubin Science Platform at data.lsst.cloud.
See the "<a href="https://dp0-2.lsst.io/dp0-delegate-resources/index.html#delegate-homepage-getting-started-checklist">Getting started with DP0 checklist</a>" for how to get an RSP account.

**Navigator:** Accesses the DP0.2 documentation, data product schemas, 
does the Google searches, etc. Data rights and an RSP account are not needed.

### Pick a challenge.

Pick any that interest you. They are not sequential.

Challenges come with limited instructions so you have to figure things out for yourself.

Peaking at the solutions is totally fine! Have fun.

They are designed to help learn about the Rubin Science Platform
and the Data Preview 0 format and contents, not necessarily to learn
about data science.

#### Or choose an alternative activity.

If for any reason the challenges aren't working for you, feel free to try these alternatives.
If you're completely new to Jupyter Notebooks, consider running through 
the first tutorial in the `notebooks/tutorial-notebooks/` folder first.

Work through this set of <a href="https://github.com/rubin-dp0/little-demos">little RSP demos</a> (~10 min each).

Work through a <a href="https://dp0-2.lsst.io/tutorials-examples/index.html">full DP0 tutorial</a> (30-60 min each).


### Give feedback.

These challenges are brand new for the DSFP 2023.
At the end of the session, discuss how well they functioned as learning tools.

Consider emailing <a href="https://astro.washington.edu/people/melissa-l-graham">Melissa Graham</a> with your thoughts.


## Portal Challenges

Last verified to run: Sun Jul 11 2023

### Challenge 1: Where's Waldo?

Knowing only the approximate coordinates of a particularly bright galaxy (Waldo),
find it in the `Object` catalog.

### Challenge 2: Galaxy Cluster Color-Magnitude Diagram

Given the central coordinates of a rich galaxy cluster, make a
color-magnitude diagram.

### Challenge 3: Variable Star Check

Be a good friend and check if LSST knows whether a star is variable.



## Notebook Challenges

Last verified to run: Sun Jul 11 2023 <br>
Recommended RSP image: Weekly 2023_21 <br>
Container size: large

### Challenge 4: Datashader

Use the plotting package `datashader` to make an interactive plot of a million or more data points.


