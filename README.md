# Googlemap-polyline
   a simple sample add polyline to googlemap.
# Two Versions
   MapsActivity.java uses FusedLocationProviderApi to getLastLocation and requestLocationUpdates with GoogleApiClient,this makes codes very messy and not readability,and it  was deprecated(but still can use now).
  
   MapActivity2.java uses FusedLocationProviderClient to replace FusedLocationProviderApi,this one is simpler than the old one,because you don't pay attention to connection logic.
