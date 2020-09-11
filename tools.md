### Data Science & Cloud Computing

The majority of my research centres around large, unstructured data in text (e.g., news articles, tweets, movie scripts), audiovisual (e.g., serial narratives, movies) and brain imaging (fMRI) format. To process, wrangle, and analyze these data structures, I am drawing on a combination of various data scientific techniques.

###### NoSQL

I am maintaining a Eucalyptus cloud-computing cluster that serves as a backend for a distributed Apache Cassandra database. Distributed databases inherit several advantages over traditional, relational database management systems (RDBMS) such as higher spatio-temporal scalability. This database currently stores and preprocesses data from the Global Database of Events, Language, and Tone (GDELT). Furthermore, this database serves as the foundation for the [interface for Communication Research (iCoRe)](http://icore.mnl.ucsb.edu:5000/icore/), an easy-to-use Application Programming Interface (API) that is under active development in the Media Neuroscience Lab. iCoRe's aim is to make GDELT's massive data more accessible to researchers with limited computational and analysis capabilities.

---

### Natural Language Processing

My research draws heavily on various natural language processing (NLP) techniques to automatically content-analyze large quantities of textual data.

###### Python & R

The majority of NLP tasks are executed in Python by utilizing common text-processing libraries such as the Natural Language Toolkit (NLTK), spaCy, and sci-kit learn. Over the course of my research, I have developed numerous text processing and analysis pipelines that span standard protocols such as tokenization, named-entity recognition, part-of-speech tagging, and dependency parsing to more advanced analysis encompassing moral sentiment classification. Statistical analyses are mostly conducted in Python, although R is occasionally consulted for more complex statistical modeling.  

###### The Moral Narrative Analyzer (MoNA)

The [Moral Narrative Analyzer (MoNA)](https://mnl.ucsb.edu/mona/) is a freely available, online crowd-coding and analysis platform that we have developed in the Media Neuroscience Lab. Relying on a django backend, MoNA draws on a hybrid content analytical approach in which NLP and human annotations are combined to extract the latent moral information that permeates textual narratives, such as news articles, movie scripts, and tweets. In a recent study, MoNA was utilized to collect over 25,000 human annotations of news documents to construct an advanced, crowd-sourced Moral Foundations Dictionary (Hopp et al., under review).

---

### High Performance Computing and Neuroimaging

###### Distributed Workflows

In order to process and analyze fMRI datasets, I am maintaining a multi-cluster architecture that spans both physical as well as cloud instances. By relying on SLURM, I harness distributed, concurrent pipelines to organize (see HeuDiConv), pre-process (see fMRIprep), and analyze (see Nipype and BrainIAK) brain imaging data. Researchers interested in harnessing these resources are encouraged to reach out.

---

### Theoretical Knowledge

###### Moral and Social Psychology

The majority of my research is theoretically grounded in moral psychology, spanning social, cognitive, and neuroscientific perspectives. Herein, [Moral Foundations Theory (MFT)](https://moralfoundations.org/) serves as the main theoretical framework that guides my research on moral decision making, moral information processing, and morally-driven behavior. Recently, I have also started to integrate the Morality as Cooperation [(MaC, Curry, 2014)](https://link.springer.com/chapter/10.1007/978-3-319-19671-8_2) framework into my research. 

###### Media Psychology

Several of my published articles utilize theories and models that explicate how humans process psychologically relevant media content. For example, I draw heavily on the Model of Intuitive Morality and Exemplars (MIME; Tamborini, 2011, 2013) to examine how morally-relevant message cues give rise to affective, cognitive, and behavioral media effects, including the sharing of online news articles and narrative enjoyment. 