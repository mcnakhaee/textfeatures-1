# textfeatures 0.3.3

+ Export more functions for use in textrecipes and/or other packages.

# textfeatures 0.3.2

+ A `verbose` options was added to control message logs. Defaults to `TRUE`. 

# textfeatures 0.3.1
+ `textfeatures()` now exports the word vector model by default
+ Added `newdata` argument to allow feature extraction using previously defined
word vector dimensions.

# textfeatures 0.3.0
+ New implementation for estimating word vector dimensions for each string. Now
uses the [text2vec](http://text2vec.org/) package

# textfeatures 0.2.0
+ Various bug fixes and improvements

# textfeatures 0.1.4

* `textfeatures()` now returns word2vec dimension estimates 
* New `sentiment` and `word2vec_dims` arguments allow users to customize (and
speed up) feature extraction process
* Added `normalize` argument, which by default preprocesses feature values
* Various bug fixes and improvements
* `scale_*` functions more robust

# textfeatures 0.1.3

* Functions now return "id" or (the first variable ending with (.|_)id)
* Returns numeric and integer columns to allow scaling flexibility
* Now exports several scale-transformation convenience functions
* Added sentiment and politeness text analysis
* Now allows use of `textfeatures()` method only without the substantive 
analysis (sentiment)

# textfeatures 0.1.2

* Added sentiment and politness variables
* Returns all numeric columns and natural logs all counting variables
* No longer exports redundant grouped_df version
* Various bug fixes and speed improvements

# textfeatures 0.1.1

* Added small executable examples to documentation.

# textfeatures 0.1.0

* Initial package launch.
* Added a `NEWS.md` file to track changes to the package.
