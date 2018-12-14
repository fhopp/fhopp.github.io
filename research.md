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
<span class="tooltiptext" style="font-size:20px">Global Database of Events, Language and Tone</span>
</i>

<i class="fa fa-balance-scale tooltip" style="font-size:35px;color:deepskyblue;position: relative; top: 123px; left:102px;">
<span class="tooltiptext" style="font-size:20px">Moral Judgment and Decision Making</span>
</i>

<i class="fa fa-film tooltip" style="font-size:35px;color:deepskyblue;position: relative; top: 180px; left:335px;">
<span class="tooltiptext" style="font-size:20px">Automated Analysis and Cognitive Processing of Movie Scripts</span>

</i>

<i class="fa fa-brain tooltip" style="font-size:35px;color:deepskyblue;position: relative; top: 450px; left:450px;">
<span class="tooltiptext" style="font-size:20px">Moral Brain Network Toplogy</span>

</i>

</div>


