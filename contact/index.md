---
layout: page
title: Contact
tags: [contact Clement Elvira]
modified: 2016-01-15T20:53:07.573882-04:00
comments: true
---

<head>
    <style>
      #map {
        width: 300px;
        height: 200px;
      }
    </style>
	<script src="https://maps.googleapis.com/maps/api/js"></script>
	<script>
	  function initialize() {
		var mapCanvas = document.getElementById('map');
		var mapOptions = {
			center: new google.maps.LatLng(48.116626, -1.639216),
			zoom: 16,
			mapTypeId: google.maps.MapTypeId.ROADMAP
		}
		var map = new google.maps.Map(mapCanvas, mapOptions)
	  }
	  google.maps.event.addDomListener(window, 'load', initialize);
	</script>
</head>

My email is firstname.lastname@inria.fr.

<br/>
My office is at Inria Rennes, office 317. You'll need to ask reception to call me.

<br/>


<article>
	<div style="float:left">
		Snail mail should go to:<br><br>
		Clément Elvira - PANAMA Research Group<br>
		Univ Rennes, Inria, CNRS,  IRISA <br>
		Campus de Beaulieu, 35042 Rennes cedex <br>
		France<br>
	</div>
	<div id="map" style="float:right"></div>
</article>
