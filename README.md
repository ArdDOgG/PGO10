# PGO10

## Stream API exercise. Eleven methods on a small order dataset, each one implemented with a Stream pipeline. The methods cover the usual suspects: filter, map, flatMap, sorted, collect with groupingBy and partitioningBy, and summaryStatistics.
One constraint worth noting: no mutating an external list inside forEach. Everything goes through the pipeline and comes out the other end.