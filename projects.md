<style>
.collapsible {
    background-color: #777;
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
}

.active, .collapsible:hover {
    background-color: #555;
}

.collapsible:after {
    content: '\002B';
    color: white;
    font-weight: bold;
    float: right;
    margin-left: 5px;
}

.active:after {
    content: "\2212";
}

.content {
    padding: 0 18px;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.2s ease-out;
    background-color: #f1f1f1;
}
</style>

<body>
<button class="collapsible">Automated Extraction of Latent Moral Information From Textual Corpora</button>
<div class="content" markdown="1">

A majority of our behaviors and decisions, from voting [(Morgan, Skitka, & Wisneski, 2010)](https://spssi.onlinelibrary.wiley.com/doi/full/10.1111/j.1530-2415.2010.01204.x) and protesting [(Mooijman et al., 2018)](https://www.nature.com/articles/s41562-018-0353-0) to message sharing [(Van Bavel et al., 2017)](http://www.pnas.org/content/114/28/7313.short) and persuasion [(Feinberg & Willer, 2013)](http://journals.sagepub.com/doi/abs/10.1177/0956797612449177) are executed in reference to a set of moral values that prescribe what is best for society as a whole.

According to [Moral Foundations Theory](https://www.sciencedirect.com/science/article/pii/B9780124072367000024), these moral values are innate and universal across human beings from different cultures. So far, five moral foundations have been identified: **care/harm** (involving intuitions of sympathy, compassion, and nurturance), **fairness/cheating** (including notions of rights and justice), **loyalty/betrayal** (supporting moral obligations of patriotism and “us vs. them” thinking), **authority/subversion** (including concerns about traditions and maintaining social order), and **sanctity/desecration** (including moral disgust and spiritual concerns about treating the body as a temple).

Recent research has shown that these moral values are also prevalent in a wide variety of media content, ranging from non-fictional media such as news articles [(Clifford & Jerit, 2013)](https://www.journals.uchicago.edu/doi/abs/10.1017/S0022381613000492) and Tweets [(Garten et al., 2018)](https://link.springer.com/article/10.3758/s13428-017-0875-9) to fictional media encompassing television shows [(Weber et al., 2008)](https://www.tandfonline.com/doi/abs/10.1080/15213260802509993), movies [(Lewis et al., 2017)](https://www.tandfonline.com/doi/abs/10.1080/10510974.2017.1340903), and song-lyrics [(Hahn et al., 2018)](https://www.tandfonline.com/doi/abs/10.1080/10510974.2018.1447493). However, given the latent, intuitive nature that underlies human moral judgment [(Haidt, 2001)](), and the increasing amount of freely available text corpora, extracting and classifying these moral values at scale is a challenging task.

In an attempt to increase the reliability, as well as validity of extracting the latent moral information contained in textual narratives, our lab has developed the [(Moral Narrative Analyzer (MoNA)](https://mnl.ucsb.edu/mona/), a freely available online coding and analysis platform. MoNA combines both human-annoated, as well as computational content-analytical methods for moral sentiment classification. In a series of six studies [(Weber et al., 2018)](https://www.tandfonline.com/doi/abs/10.1080/19312458.2018.1447656), we have utilized MoNA and demonstrated that an intuitive highlighting task, executed by a large crowd of human coders achieves highest inter-coder reliabilities.

My recent work in this area has focused on expanding MoNA's capabilities to _automatically_ extract moral information from text narratives that are too large and ephemeral for human annotation. By harnessing the combined power of both human-annotated and algorithmic, machine-learning content classifications, we are currently developing an extension of the [Moral Foundations Dictionary](http://moralfoundations.org/sites/default/files/files/downloads/moral%20foundations%20dictionary.dic) to measure the degree to which text narratives contain moral information.
</div>


<button class="collapsible"><b>Spatiotemporal Event Prediction: Linking News Frame Densities and Real-Wold Event Likelihoods</b></button>
<div class="content" markdown="1">

In progress.
</div>



<button class="collapsible"><b>Moral Content and Media Appeal </b></button>
<div class="content" markdown="1">

In progress.
</div>


<button class="collapsible"><b>Neural Encoding and Decoding of Morally-Laden Media Narratives</b></button>
<div class="content" markdown="1">

Forthcoming.
</div>


<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    } 
  });
}
</script>
</body>