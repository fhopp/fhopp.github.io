The research that I conduct conforms to open-science practises. Data and analysis protocols are therefore made available through the Open Science Framework. By relying on Jupyter Notebooks for most of my research tasks, I aim to keep workflow and analyses protocols transparent and replicable.

----
### Data Science

The majority of my research centres around massive, unstructured data in text (e.g., news articles, tweets, movie scripts), audiovisual (e.g., serial narratives, movies) and brain imaging (fMRI) form. To process, wrangle, and analyze these data structures, I am drawing on a combination of various data scientific techniques:

###### NoSQL

I am maintaining a Eucalyptus cloud-computing cluster that serves as a backend for a distributed Apache Cassandra database. Distributed databases inherit several advantages over traditional, relational database management systems (RDBMS) such as higher spatio-temporal scalability. This database currently stores and preprocesses data from the Global Database of Events, Language, and Tone (GDELT). Furthermore, this database serves as the foundation for the [interface for Communication Research (iCoRe)](https://github.com/medianeuroscience/icore), an easy-to-use Application Programming Interface (API) that is under active development in the Media Neuroscience Lab. iCoRe's aim is to make GDELT's massive data more accessible to researchers with limited computational and analysis capabilities.

###### Apache Spark

I leverage Apache Spark to increase performance (e.g., higher throughput) when querying and analyzing data via iCoRe.

---

### Natural Language Processing

My research draws heavily on various natural language processing (NLP) techniques to automatically content-analyze large quantities of textual data.

###### Python

The majority of NLP tasks are executed in Python by utilizing common text-processing libraries such as the Natural Language Toolkit (NLTK), spaCy, and sci-kit learn. Over the course of my research, I have developed numerous text processing and analysis pipelines that span standard protocols such as tokenization, named-entity recognition, part-of-speech tagging and dependency parsing to more advanced analysis encompassing moral sentiment classification.

###### The Moral Narrative Analyzer (MoNA)

The [Moral Narrative Analyzer (MoNA)](https://mnl.ucsb.edu/mona/) is a freely available, online crowd-coding and analysis platform that we have developed in the Media Neuroscience Lab. Relying on a django backend, MoNA draws on a hybrid content analytical approach in which NLP and human annotations are combined to extract the latent moral information that permeates textual narratives, such as news articles, movie scripts, and tweets. In a recent study, MoNA was utilized to collect over 25,000 human annotations of news documents to construct an advanced, crowd-sourced Moral Foundations Dictionary (Hopp et al., under review).

---

### Scientfic Computing in Neuroimaging

###### Nipype

...

###### fMRIprep

...

---

### Theoretical Foundation

###### Moral Psychology

...

###### Media Neuroscience

...

