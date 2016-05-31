# zoomit
News aggregator with a zoom based filtering system.

## News Aggregator

zoomit is a news aggregator like reddit. You can submit things and vote up and down.

## Filtering

Filtering of news is based on sorting by time and hiding entries. Unlike reddit, where entries are re-arranged by popularity, zoomit entries are always in order. To pare down the number of entries, criteria are added which [fold](https://en.wikipedia.org/wiki/Code_folding) ineligable entries. For example, fold any entries that have < 300 votes. Zooming out to entries >= 1000 votes will show you more entries over a larger time scale, while zooming in to entries >= 5 votes will show you many recent entries.

Top-level comments could also be sorted with the zoomit filter, but after that comments will just be sorted by vote.

## Why

Having entries in order can be useful for certain things where chronology is important. This will also provide better results if you are viewing older submissions, where the "best" ordering is not as useful.
