Instructor notes: https://datacarpentry.org/openrefine-socialsci/guide/
Keypoints + Glossary: https://datacarpentry.org/openrefine-socialsci/reference/

download data (zenodo, sufi)


# Highlight
## Creating a new OpenRefine project
* from URL
* file types (data management)
* character encoding
* project name, tags

After import demo rows, records ; stars, flags
* switch between rows, records
* on months_no_water
  * split on semicolon
  * switch between rows, records
  * join on semicolon

*comment on need to be cognizant about separators. in csv file, commas are going to ruin your data

* star / flag village where "Chirdozo"
* facet by star / flag
* select true

Let's look at facets a little more ...

## Using facets
* demo on village
  * do NOT fix the errors
* exercise with interview_date (text facet, transform to date, timeline facet)
* 2 minutes additional playtime with facets

## Using clustering to detect possible typing errors
* example case of clustering 
  * standardized spelling of country (cote d'ivoire)
* machine learning and clustering algorithms
* 2 minutes play time with clustering

## Transforming data
* replace transform
* Custom text facet
* 5 minutes play with transform

## Using undo and redo
* lots of work; what if we want to go back?
* go back, new step, will overwrite

## Trim Leading and Trailing Whitespace
* facet respondent_wall_type
* multiple options of same, see space. edit manually. undo step
* use common transform

## Filtering
### Exclude entries

## Sort
* 7 minutes for exercise, play

## Numbers
* Does OpenRefine know when something can't be asserted (e.g., making text "numeric data")

## Using Scripts
! combine this to the end with export data

## Saving and Exporting a Project
* JSON extract
* export full project
* save data as csv
  * ! data management practices, save your original file as "raw" and your cleaned file as "clean" or some lang to differentiate

**We've seen regular expression throughout, including in the GREL function. let's take an in-depth look at this concept**

# Regular Expressions
* https://librarycarpentry.org/lc-data-intro/04-regular-expressions/index.html
* https://regexr.com
* https://regex101.com

## Advanced OpenRefine functions
* see libcarp lesson https://librarycarpentry.org/lc-open-refine/13-looking-up-data/index.html
 
* look up data from URL
* parse JSON
* reconciliation with wikidata
* look up 10.1186/s13721-016-0042-z (other non-Zenodo dois)


# extra exercises
* transformation arrays: *liv_owned* column https://librarycarpentry.org/lc-open-refine/11-using-arrays-transformations/index.html


# List of Resources
* OpenRefine Faceting https://github.com/OpenRefine/OpenRefine/wiki/Faceting
* OpenRefine Clustering In Depth https://github.com/OpenRefine/OpenRefine/wiki/Clustering-In-Depth
* Refine API: htps://github.com/maxogden/refine-python/wiki/Refine-API
* OpenRefine Python Client Library https://github.com/PaulMakepeace/refine-client-py
