# Progress towards the neurobiological primitives of task behavior
# Talk by Danilo Bzdok

Underlying atoms on the brain that . Three main motivations:

- Problem in psychiatric nosology: the diagnose system relies on manuals created heuristically 
that do not take brain data into account

- Taxonomy of mental operations: towards ontologies that can liberate us from our inaccurate semantic
descriptions of "computation modules" in the brain

- Current descriptions used for psychiatric diagnosis are based on exophenotypes, not endophenotypes
(like in the taxonomy case, we don't have names for the underlying things, but only for the things
we observe). A move towards a latent factor models is necessary.

- Previous approaches like K-Means are inappropriate in that they need a predefined number of clusters,
and these must be non-overlapping

- Use of a semi-supervised dimensionality reduction that explains variance not on the whole data, but between classes
(as seen on his paper on nips 2015).

- Combine with an Indian Buffet Model, allowing for variable number of clusters and multiple labels on data.

- Results: high similarity on some of the latent factors learned between HBP and ARCHI datasets

- Idea for the validation: study the stability of the latent factors
