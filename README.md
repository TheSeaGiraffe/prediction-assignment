# Prediction Assignment

This repo contains an RMarkdown report and a knitted HTML version for the final assignment
in Course 8 of the Johns Hopkins Data Science Specialization on Coursera. The goal of this
assignment was to train a model to predict the quality of a set of bicep curls. More
information can be found [here][1].

In order to knit the RMarkdown report, make sure you download the [training][2] and
[test][3] data. Additionally, you'll need to go through the report and set the `eval`
option in the `train xgb model` code block to `TRUE` and either set the `eval` option in
the `load saved model` to `FALSE` or remove the block entirely. If you don't intend on
knitting the report yourself, you can simply read the pre-knit HTML file.

[1]: http://groupware.les.inf.puc-rio.br/har
[2]: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv
[3]: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv
