# Challenge 3: Variable Star Check

Your friend is running a star survey from their backyard telescope, from which they have 
an *i*-band limit of about 17th mag.

They ask you if the star they can sometimes detect at RA, Dec = 62.1187488 -37.0578565 is 
variable in the LSST data set.

Is it? Use the Portal Aspect to find out.

## Resources

Introduction to the Portal Aspect <br>
https://dp0-2.lsst.io/data-access-analysis-tools/portal-intro.html

The schema for the `DiaSource` table <br>
https://dm.lsst.org/sdm_schemas/browser/dp02.html#DiaSource

Portal Tutorial 02: Explore a SNIa Lightcurve <br>
https://dp0-2.lsst.io/tutorials-examples/portal-intermediate.html


## Hints

It requires a table join of `DiaSource` and `CcdVisit` to get both the difference 
image detections and the date. <br>
https://dp0-2.lsst.io/data-access-analysis-tools/adql-recipes.html#table-joins

So long as you use direct-image fluxes (not difference-image), you can convert to magnitudes. <br>
https://dp0-2.lsst.io/data-access-analysis-tools/adql-recipes.html#convert-fluxes-to-magnitudes

