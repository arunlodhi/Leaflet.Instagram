Leaflet.Instagram
=================

Plugin to show Instagram photos and videos on your Leaflet map. 

Requires
--------
[Leaflet](http://leafletjs.com/)

[jQuery](http://jquery.com/)

[fancyBox](http://fancyapps.com/fancybox/)

Usage
-----

Load data from [Instagram API](http://instagram.com/developer/):
```JavaScript
L.spotTracker('instagram_api_url_with_access_token').addTo(map);
```

Load data from [CartoDB](http://blog.thematicmapping.org/2014/06/syncing-your-instagram-photos-to-cartodb.html):
```JavaScript
L.instagram('cartodb_url_with_sql').addTo(map); 
```
