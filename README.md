# bggAnalysis
Playing field with the BoardGameGeek dataset.

This analysis scheleton is bundled in the form of an R Package, so use the following command to install it and check the bundled documentation to start playing.

```R
# install.packages("devtools")
devtools::install_github("9thcirclegames/bgg-analysis")

require("bggAnalysis")

```

The dataset is in the BoardGames object included with the package and its fully documented.
Use the following command to import it:
```R
data(BoardGames)

# Check if data are ok:
head(BoardGames)
```
