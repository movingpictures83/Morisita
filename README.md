# Morisita
# Language: R
# Input: CSV (abundances)
# Output: CSV (dissimilarity)
# Tested with: PluMA 1.0, R 3.2.5

PluMA plugin that computes dissimilarity between community samples using the Morisita Overlap (Morisita, 1959)
as a metric.  The plugin accepts input as a CSV file with rows representing samples and columns
representing community members, with entry (i, j) indicating the abundance of member j in sample i 
(this does not need to be normalized for this algorithm).

The plugin produces dissimilarities as an output CSV file with both rows and columns representing samples
and entry (i, j) the level of dissimilarity between sample i and sample j.
