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

<i class="fa fa-border fa-globe-americas tooltip" style="font-size:35px;color:deeppink;position: relative; top: 253px; left:133px;">
<a href="url"><span class="tooltiptext" style="font-size:15px"> Global Analysis of News and Events</span></a>
</i>

<i class="fa fa-balance-scale tooltip" style="font-size:35px;color:deeppink;position: relative; top: 123px; left:102px;">
<a href="url"><span class="tooltiptext" style="font-size:15px"> Media and Morality</span></a>
</i>

<i class="fa fa-film tooltip" style="font-size:37px;color:deeppink;position:relative;top:110px;left:222px;border-radius: 50%;background-size:cover;">
<a href="url"><span class="tooltiptext" style="font-size:15px"> Computational Analysis of Movie Scripts</span></a>

</i>

<i class="fa fa-brain tooltip" style="font-size:37px;color:deeppink;position: relative; top: 292px; left:218px;">
<a href="url"><span class="tooltiptext" style="font-size:15px"> Network Topology of the Moral Brain</span></a>

</i>

</div>


