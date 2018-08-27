### Dataset of paper "Aggregate Queries on Constrained Probabilistic Similarity Join Pairs"

We construct two files based on the dblp(http://dblp.org/xml/).  

The first file is Publication, of which the schema is Publication(Pid, Name), i.e., paper id and first author name. The second file is denoted as Teacher, of which the schema is Teacher(Tid, Name), i.e., teacher id and teacher name.  

We join Teacher and Publication on their Name attribute to generate PSJ pairs.
