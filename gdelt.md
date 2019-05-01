## Global Analysis of News and Events

The main goal of this line of research is to examine the dynamic relationship between real-world events (e.g., protest movements, terror attacks, elections, etc.) and the news frames that accompany these events. Traditionally, communication research has invested great efforts in understanding how certain types of events are framed and how these frames are processed by audiences. Likewise, data-driven approaches towards event forecasting have aimed to construct stochastic models that predict event likelihoods based on preceding event sequences.

In turn, my research in this area combines both news framing and computational modeling to disentangle the relationship between news frames and events. For example, which news frames are more likely to drive subsequent news frame sequences? Which news frames are more likely to increase the probability of observing certain event types in the future and vice versa, which events precede certain densities of news frames?

Figure 1.
*Time Series of Immigration Protest Events and News Articles Discussing Immigration in the United States*

 <img src="symbols/ts1_gdelt.png" alt="Figure1" style="width: 650px; height:250px">

In order to examine these questions, I harness the Global Database of Events, Language, and Tone (GDELT)[https://www.gdeltproject.org/], a massive, constantly updated database of automatically content-analyzed news stories. For an accessible introduction to GDELT, please see our recent [publication](). Furthermore, to model the dynamic relationships between news frames and event densities, I rely on Hidden Markov Models (HMM). HMMs are a form of stochastic sequence models (comparable to finite-state machines) that allow to classify noisy sequences of observations into discrete states. By learning the stochastic dependency among these observations, HMMs can be harnessed to (a) better understand the co-occurence of news frames and event types and (b) allow to sample observations for news-event forecasting.

### Associated Publications

**Hopp, F. R**., Schaffer, J., Fisher, J. T., Cornell, D., & Weber, R. (in press). iCoRe: The GDELT interface for the advancement of communication research. _Computational Communication Research_.

**Hopp, F.R.**, Fisher, J. T., & Weber, R. (2019, February). The Moral Narrative Analyzer (MoNA): An integrated, spatio-temporal platform for monitoring, predicting, and countering global sociopolitical instability. Paper presented at the Workshop on Naval Applications of Machine Learning (NAML), San Diego, CA.

**Hopp, F.R.**, Fisher, J., & Weber, R. (2019). The dynamic relationship between news frames and real-world events: A hidden markov model approach. Paper submitted to the annual meeting of the International Communication Association (ICA), Washington DC, USA. **Top 5 Paper Award. Computational Methods Divison**.

**Hopp, F. R.**, Fisher, J. T., Mangus, J. M., Huskey, R., Swanson, R., Gordon, A., Khooshabeh, P., Weber, R. (2018). _Mining the Global Database of Events, Language, and Tone: An Introduction for Communication Researchers_. Paper submitted to the annual meeting of the International Communication Association (ICA), Prague, CZ.

Fisher, J., Cornell, D., **Hopp, F. R.**, Weber, R. (2018). _But How are They Talked About?": A Novel Measure of Entity Framing in Online News_. Paper submitted to the annual meeting of the International Communication Association (ICA), Prague, CZ.

**Hopp, F. R.**, Fisher, J. T., Mangus, J. M., Huskey, R., Swanson, R.,Gordon, A., Khooshabeh, P., & Weber, R. (2017). Examining Online News Reporting Using the Global Database of Events, Language, and Tone: Challenges, Opportunities, and Future Directions. 103 rd Annual Convention of the National Communication Association, Dallas, TX, USA.

