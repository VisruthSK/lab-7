# Lab 7: Visualizing International Space Station Information via APIs

One of the Open-Notify APIs provides predictions of pass times for a given
location when given the corresponding latitude, longitude, and altitude are
given: [Pass Times API](https://g7vrd.co.uk/public-satellite-pass-rest-api)

### Pass Times for U.S. State Captials

You can find the latitudes and longitudes for the U.S. state capitals at [this site](https://people.sc.fsu.edu/~jburkardt/datasets/states/states.html).

1.  Use the API to get the next **three** predicted pass times for all of the 
U.S. state capitals. Organize all of this information into a nice data frame (or
data frame-like object) that will be easy to use for mapping.

### Mapping the Data

2.  Map the U.S. state capitals using `leaflet`.

3.  Find an image of your choosing to use as the marker icon, that's relevant 
for these data. Maybe a spaceship? 🚀 Or an astronaut? Or the moon?

4.  The hover-over information for each marker should include the name of the
state capital and the soonest predicted pass time. The click information should
include the name of the state capital and all three predicted pass times. Make
sure these times are in an easy-to-read format.

### Drawing the Route of the ISS

Check out this video for [adding polylines](https://www.youtube.com/watch?v=iKESL0Iwmmw) to a `leaflet` map.

5.  Overlay lines on your map that connect the U.S. state capitals in order of
pass times (essentially east to west) so that we can see the expected pass
order.

### Submission

Make sure your final file is carefully formatted, so that each analysis is clear
and concise. Be sure your knitted .html file shows all your source code,
including your function definitions.
