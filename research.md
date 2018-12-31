<style>
.tooltip {
  position: relative;
  display: inline-block;
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: black;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;
  position: absolute;
  z-index: 1;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;

  /* Fade in tooltip - takes 1 second to go from 0% to 100% opac: */
  opacity: 0;
  transition: opacity 1s;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
  opacity: 1;
}
</style>


<div class="brain">

<span class="fa-stack fa-lg">
  <i class="fa fa-circle fa-stack-2x" style="position:relative;top: 253px; left:128px"></i>
  <i class="fa fa-globe-americas fa-stack-1x fa-inverse tooltip" style="font-size:25px;color:deeppink;position:absolute;top: 253px; left:128px">
  <a href="url"><span class="tooltiptext my_text" style="font-size:15px"> Global Analysis of News and Events</span> </a></i>
</span>

<span class="fa-stack fa-lg">
  <i class="fa fa-circle fa-stack-2x" style="position:relative;top: 120px; left:80px"></i>
  <i class="fa fa-balance-scale fa-stack-1x fa-inverse tooltip" style="font-size:25px;color:deeppink;position:absolute;top: 120px; left:80px">
  <a href="url"><span class="tooltiptext" style="font-size:15px"> Media and Morality</span> </a></i>
</span>

<span class="fa-stack fa-lg">
  <i class="fa fa-circle fa-stack-2x" style="position:relative;top:105px;left:185px"></i>
  <i class="fa fa-film fa-stack-1x fa-inverse tooltip" style="font-size:25px;color:deeppink;position:absolute;top:105px;left:185px">
  <a href="url"><span class="tooltiptext" style="font-size:15px"> Computational Analysis of Narratives</span> </a></i>
</span>

<span class="fa-stack fa-lg">
  <i class="fa fa-circle fa-stack-2x" style="position:relative; top: 288px; left:163px;"></i>
  <i class="fa fa-brain fa-stack-1x fa-inverse tooltip" style="font-size:25px;color:deeppink;position:absolute; top: 288px; left:163px;">
  <a href="url"><span class="tooltiptext" style="font-size:15px"> Network Topology of the Moral Brain</span> </a></i>
</span>

</div>


