# Collecting Twitter Data

To collect tweets, we will be using [twarc](https://github.com/DocNow/twarc). Twarc is a Python and command-line tool for working with Twitter data, which relies on Twitter’s Application Programming Interface (API). It was developed as part of the [Documenting the Now project](https://www.docnow.io/).

## Glossary

**Command line**

* A text-based interface for interacting with your computer
* Contrast with more familiar Graphical User Interface (GUI)
* Also known as “terminal,”“shell” or “bash” 

**Application Programming Interface (API)**

* An API allows software applications to talk to each other

> “When people speak of ‘an API,’ they sometimes generalize and actually mean ‘a publicly available web-based API that returns data, likely in JSON or XML.’ The API is not the database or even the server, it is the code that governs the access point(s) for the server.”

> -Perry Eising, [“What Exactly IS an API?”](https://medium.com/@perrysetgo/what-exactly-is-an-api-69f36968a41f)

## Collecting Tweets in Realtime or the Recent Past

There are two ways to freely collect tweets with Twitter's public API---either in realtime or up to seven days in the past.

**Filter Realtime**

Read more about the filter realtime details: [https://developer.twitter.com/en/docs/tweets/filter-realtime/overview]()

**Search (7 days in the past)**

Read more about the search details: [https://developer.twitter.com/en/docs/tweets/search/overview/standard-operators](https://developer.twitter.com/en/docs/tweets/search/overview/standard-operators)


## How to Query the Twitter API

![](/images/search-operators.png) 

Read more about the search operators: [https://developer.twitter.com/en/docs/tweets/rules-and-filtering/overview/standard-operators]()

## Twitter Dataset Examples

The datasets in [DocNow's Tweet ID Catalog](https://www.docnow.io/catalog/) provide a helpful model for possible Twitter research areas and effective API queries. We hope to eventually deposit our own datasets to the DocNow Catalog.

![](/images/doc-now-catalog.png)   


## Practice Collecting Tweets with Twarc

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/melaniewalsh/Collecting-Twitter-Data/master)

Ok now we're going to practice collecting and analyzing Twitter data with Twarc! We're going to do so by using an interactive Jupyter notebook. You can access this notebook by clicking the logo above or by going to https://mybinder.org/v2/gh/melaniewalsh/Collecting-Twitter-Data/master

## Questions to Discuss
Which data set did you pick?
What query did they yse?
Why is this interesting to you?
What kind of analysis could you do with this dataset?
