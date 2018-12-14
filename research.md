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

<i class="fa fa-globe-americas tooltip" style="font-size:35px;color:deepskyblue;position: relative; top: 253px; left:133px;">
<a href="url"><span class="tooltiptext" style="font-size:15px"> Large-Scale Data Extraction and Analysis</span></a>
</i>

<i class="fa fa-balance-scale tooltip" style="font-size:35px;color:deepskyblue;position: relative; top: 123px; left:102px;">
<span class="tooltiptext" style="font-size:15px" href="url"> Media and Morality</span>
</i>

<i class="fa fa-film tooltip" style="font-size:37px;color:deepskyblue;position: relative; top: 110px; left:222px;">
<span class="tooltiptext" style="font-size:15px" href="url"> Computational Analysis of Movie Scripts</span>

</i>

<i class="fa fa-brain tooltip" style="font-size:37px;color:deepskyblue;position: relative; top: 292px; left:218px;">
<span class="tooltiptext" style="font-size:15px" href="url"> Network Topology of the Moral Brain</span>

</i>

</div>


