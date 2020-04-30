Here I provide an exploratory computational analysis of Ajax, and the steps taken for that goal


Key steps:

1. Download corpus found at: http://classics.mit.edu/Sophocles/ajax.pl.txt
2. Preprocess it by making XML/HTML format metadata, making consistent speaker names and line breaks, normalising some content so it will be handled properly by parser. The preprocessed version here took about half an hour, but could easily be expanded to include all kinds of manually added metadata that would later be searchable
3. Parse the corpus using spaCy/buzz
4. Load this corpus into memory
5. Explore it for patterns in language and language frequency
6. Visualise the data in a few novel ways

Note that this is simply demonstrating an example of a computational pipeline for exploring the data. Much is missing from this work as an actual research project (e.g.):

* Using other computational methods (word embeddings, topic modelling) to find new things in data
* Hypothesis driven research, querying the data in order to problematise claims in existing literature
* Comparison with other related texts (also possible with these tools)
* An articulated theoretical grounding in history, literature, linguistics etc. to enrich the computational component, guide the investigation, and enter into the scholarly debate. 
