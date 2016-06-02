# zoomit
News aggregator with a zoom based filtering system.

## News Aggregator

zoomit is a news aggregator like reddit. You can submit things and vote up and down.

## Filtering

Filtering of news is based on sorting by time and hiding entries. Unlike reddit, where entries are re-arranged by popularity, zoomit entries are always in order. To pare down the number of entries, criteria are added which [fold](https://en.wikipedia.org/wiki/Code_folding) ineligable entries. For example, fold any entries that have < 300 votes. Zooming out to entries >= 1000 votes will show you more entries over a larger time scale, while zooming in to entries >= 5 votes will show you many recent entries.

Top-level comments could also be sorted with the zoomit filter, but after that comments will just be sorted by vote.

## Why

Having entries in order can be useful for certain things where chronology is important. This will also provide better results if you are viewing older submissions, where the "best" ordering is not as useful.

## Outline

The use of a zoom filter is interesting for a news aggregator because it sorts entries by date. This means that there is some potential crossover with a twitter like application. One of the problems with twitter is that your incomming tweets can be overwhelming to sort through. A new twitter feature to help with this is the "while you were away" section, which contains the most retweeted or likes tweets- but this is a clumsy solution. The zoom filter has potential to merge functionality between news aggregators like reddit and live update apps like twitter.

### Site Organization

Using sub-sections to divide the website is something that reddit used to organize content into categories and moderation domains. Another approach would be allow entries to be tagged so they can appear in multiple categories at once, such as hashtags. The problem with this approach is that reduces moderation tools for that tag, as the tags are essentially unowned. A middle approach would be to let entries be reposted (retweeted) to attach additional tags, with each repost subject to that tag's moderation. This would also simplify the duplication of entries and ease navigation into different comment sections.
