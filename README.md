# Twitter Trends in Poland in 2022: a dataset

## Overview

This is a dataset of hourly trends from Polish Twitter during 2022, loaded from [getdaytrends.com](https://getdaytrends.com). It consists of 8,760 files, stored in the `files` folder. The filenames have this format:

`YYYY-MM-DD_HH.txt`

(The hour is without the leading zero.)

Example:

`2022-01-09_5.txt`

The dataset also includes a brief summary:

- `trend_counts.csv` is a table of 14,722 unique trending topics sorted by their count of appearances in hourly rankings

- `hashtag_counts.csv` is a subset of `trend_counts.csv` that only includes hashtags; it has 2,368 unique hashtags

The dataset could be used for various purposes, such as NLP, machine learning or Internet archiving.
