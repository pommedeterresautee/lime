# lime 0.3.0.9999

* Added a `NEWS.md` file to track changes to the package.
* Fixed bug when explaining regression models, due to drop=TRUE defaults (#33)
* Integer features are no longer converted to numeric during permutations (#32)
* Fix bug when working with xgboost and tabular predictions (@martinju #1)
* Training data can now contain `NA` values (#8) 
* Keep ordering when plotting with `plot_features()` (#38)
* Fix support for mlr by extracting predictions correctly
* Added support for `h2o` (@mdancho84) (#40)
* Throws meaningful error when all permutations have 0 similarity to original
  observation (#47)
* Explaining data can now contain `NA` values (#45)
