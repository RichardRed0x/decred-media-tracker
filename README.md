# Purpose

The tracker is a collaborative database of mentions of Decred in "the media". It serves as a building block for futher research that will add to the collective intelligence of the Decred community. The end goal is to make better decisions for the project.

For instance, it can tell us how good or bad Decred looks in the press and whether we should adjust our outreach/marketing efforts. 

# Overview

The tracker is a list of links with some metadata like date, title, author and language. Since it's a human-built curated database it has higher data quality than a list of search engine results.

# Applications

The database of links can be used as an input to further research projects. Some examples of what it makes possible:

* statistics
  * how many pieces of content are generated per week/month
  * which domains and authors post more or less about Decred
* deeper analysis from following the links (some can be automated):
  * assess quality of content, including factual errors
  * analyze if the keywords/SEO are good
  * use advanced algorithms to measure "sentiment" and such

Researchers can build related datasets with their own metrics that can be "joined" together.

# How it works

Production of the data:

1. participant detects a link that is not in the database
2. submits it a pull request (PR) with the link and some metadata filled: publication date in UTC, title, author and language. Automation is [possible](https://github.com/RichardRed0x/decred-media-tracker/issues/16) here to increase productivity.
3. Maintainers review and merge the PR

Consumption of the data: researchers can download the database as a CSV file and hack on it.
