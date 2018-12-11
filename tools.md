### Tools and Resources

#### Data Science

The majority of my research centres around massive, unstructured data in text (e.g., news articles, tweets, movie scripts), audiovisual (e.g., serial narratives, movies) and brain imaging (fMRI) form. To process, wrangle, and analyze these data structures, I am drawing on a combination of various data scientific techniques:

###### NoSQL

Currently, I am maintaining a Eucalyptus cloud-computing cluster that serves as a backend for a distributed Apache Cassandra database. Distributed databases inherit several advantages over traditional, relational database management systems (RDBMS) such as higher spatio-temporal scalability. This database currently stores and preprocesses data from the Global Database of Events, Language, and Tone (GDELT). Furthermore, this database serves as the foundation for the interface for Communication Research (iCoRe), an easy-to-use Application Programming Interface (API) that is under active development in the Media Neuroscience Lab. iCoRe's aim is to make GDELT's massive data more accessible to researchers with limited computational and analysis capabilities.

###### Apache Spark

I leverage Apache Spark to increase performance (e.g., higher throughput) when querying and analyzing data via iCoRe.

#### Natural Language Processing

...

###### Python

NLTK, SpaCy, Pandas

###### Crowd-Sourced Annotations

Moral Narrative Analyzer ...

#### Scientfic Computing in Neuroimaging

###### Nipype

...

###### fMRIprep