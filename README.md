# Googlemap-polyline
   A simple sample add polyline to googlemap.
# Two Versions
   MapsActivity.java uses FusedLocationProviderApi to getLastLocation and requestLocationUpdates with GoogleApiClient,this makes codes very messy and not readability,and it  was deprecated(but still can use now).
  
   MapActivity2.java uses FusedLocationProviderClient to replace FusedLocationProviderApi,this one is simpler than the old one,because you don't need to pay attention to connection logic.
# How to use
   Add your google_maps_key in res->values->google_maps_api.xml.
   I use intent-filter to change the start activity in Androidmanifest,just comment out the other.
