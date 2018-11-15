# Purpose

The tracker is a collaborative database of mentions of Decred in "the media". It serves as a building block for futher research that will add to the collective intelligence of the Decred community. The end goal is to make better decisions for the project.

For instance, it can inform us about how Decred comes across in the press and whether we should adjust our outreach/marketing efforts. 

# Overview

The tracker is a list of links with some metadata like date, title, author and language. Since it's a human-built curated dat-set it should have higher data quality than a list of search engine results.

# Applications

The database of links can be used as an input to further research projects. Some examples of what it makes possible:

* statistics
  * how many pieces of content are generated per week/month
  * which domains and authors post more or less about Decred
* deeper analysis from following the links (some can be automated):
  * assess quality of content, including factual errors
  * categorize the subject of the article
  * analyze the keywords/SEO
  * use techniques like sentiment analysis or topic modelling

Researchers can build related datasets with their own metrics that can be merged together to expand the scope for analysis. For example, by assessing the attributes of publications/domains (e.g. reach, reputation) and then using these to better understand and track Decred's performance in the media.

It is likely that people at Ditto could advise us on some aspects of this, in particular when it comes to evaluating the significance of specific publications.

# How it works

Production of the data:

1. participant detects a link that is not in the database, or compiles a set of links
2. submits it a pull request (PR) with the link and some metadata filled: publication date in UTC, title, author and language. Automation is [possible](https://github.com/RichardRed0x/decred-media-tracker/issues/16) here to increase productivity.
3. maintainers review and merge the PR

Participants may also add or correct meta-data for existing entries.

The columns in the file should be considered as an initial set to test with this means of production.

Consumption of the data: researchers can download the database as a CSV file and hack on it.

# Streamlining the process

Initial testing has revealed that the method of adding rows of data via PR is quite clunky, and requires some setting up. It is quite possible that a more convenient way of adding a single row can be found.

We are on the lookout for a better way of collecting data. This would have the following properties:

* supports collaboration of multiple people
* can be fully replicated to all participants
* uses (or can export to) a popular, simple, free format
* allows for easy entry of single additional rows without a steep learning curve
