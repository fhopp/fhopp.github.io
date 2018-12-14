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

<i class="fa fa-globe-americas tooltip" style="font-size:40px;color:deepskyblue;position: relative; top: 360px; left:210px;">
<span class="tooltiptext" style="font-size:20px">Global Database of Events, Language and Tone</span>
</i>

<i class="fa fa-balance-scale"></i>

<i class="fa fa-film"></i>

<i class="fa fa-brain"></i>

</div>


