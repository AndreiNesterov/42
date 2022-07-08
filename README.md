# 42
Project of the team 42 ISWS 2022

### Dataset

Data was retrieved through DBpedia [SPARQL Query editor](https://dbpedia.org/sparql) and downloaded in csv format.

Files with SPARQL queries to retrieve data from DBpedia:

[query_1.rq](https://github.com/AndreiNesterov/42/blob/main/query_1.rq): Getting the number of subjects with the same predicate and object for every category

[query_2.rq](https://github.com/AndreiNesterov/42/blob/main/query_2.rq): Getting all triples for every category

[query_3.rq](https://github.com/AndreiNesterov/42/blob/main/query_3.rq): Getting all combinations of subjects and predicate-object-pairs in a category

[query_4.rq](https://github.com/AndreiNesterov/42/blob/main/query_4.rq): Counting the occurrences of the predicate-object pairs for every category in the whole DBpedia for TF-IDF calculation.

The resulting datasets:

1. [Outgoing edges for every category grouped by the number of subjects](https://github.com/AndreiNesterov/42/tree/main/data/outgoing_edges_cleaned)
2. [All triples for every category](https://github.com/AndreiNesterov/42/tree/main/data/triples_in_category)
3. [Combinations for every category](https://github.com/AndreiNesterov/42/tree/main/data/combinations_csv)
4. [Frequency and TF-IDF calculations](https://github.com/AndreiNesterov/42/tree/main/data/tf_idf)

The scripts for datasets generation are in [code](https://github.com/AndreiNesterov/42/tree/main/code)
