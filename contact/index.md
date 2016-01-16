---
layout: page
title: Contact
tags: [contact Clement Elvira]
modified: 2016-01-15T20:53:07.573882-04:00
comments: true
image:
  feature: sample-image-5.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
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
			center: new google.maps.LatLng(50.606602, 3.137084),
			zoom: 11,
			mapTypeId: google.maps.MapTypeId.ROADMAP
		}
		var map = new google.maps.Map(mapCanvas, mapOptions)
	  }
	  google.maps.event.addDomListener(window, 'load', initialize);
	</script>
</head>

My email is firstname.lastname@ec-lille.fr.

<br/>
My office is at École Centrale de Lille, office C316. You'll need to ask reception to call me.

<br/>


<article>
	<div style="float:left">
		Snail mail should go to:<br><br>
		&Eacute;cole Centrale de Lille<br>
		Cit&eacute; Scientifique - CS 20048<br>
		59651 Villeneuve d'Ascq Cedex<br>
		France
	</div>
	<div id="map" style="float:right"></div>
</article>
