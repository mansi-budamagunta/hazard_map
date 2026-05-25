---
layout: page
title: "Outbreak location: Mahesana"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([23.666667, 72.500000],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Mahesana").openTooltip();

var circle_1 = L.circle([23.774057, 71.683735], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 168781, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Patan<br>rank: 1<br>hazard index: 0.168781")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patan">Patan</a>')

var circle_2 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 89646, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Ahmedabad<br>rank: 2<br>hazard index: 0.089647")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_3 = L.circle([24.170979, 72.436638], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 47136, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Palanpur<br>rank: 3<br>hazard index: 0.047136")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palanpur">Palanpur</a>')

var circle_4 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15096, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Jodhpur<br>rank: 4<br>hazard index: 0.015097")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_5 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10593, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Vadodara<br>rank: 5<br>hazard index: 0.010594")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_6 = L.circle([26.469100, 74.639000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8152, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Ajmer<br>rank: 6<br>hazard index: 0.008152")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a>')

var circle_7 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3699, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Mumbai<br>rank: 7<br>hazard index: 0.003700")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_8 = L.circle([22.305199, 70.802834], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3439, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Rajkot<br>rank: 8<br>hazard index: 0.003439")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a>')

var circle_9 = L.circle([23.071874, 70.131715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2967, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Gandhidham<br>rank: 9<br>hazard index: 0.002967")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhidham">Gandhidham</a>')

var circle_10 = L.circle([24.578721, 73.686257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2837, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Udaipur<br>rank: 10<br>hazard index: 0.002838")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a>')

var circle_11 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2732, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Jaipur<br>rank: 11<br>hazard index: 0.002733")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_12 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2379, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Delhi<br>rank: 12<br>hazard index: 0.002380")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_13 = L.circle([25.604091, 73.415609], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2193, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Pali<br>rank: 13<br>hazard index: 0.002194")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pali">Pali</a>')

var circle_14 = L.circle([26.099214, 74.312704], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2182, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Beawar<br>rank: 14<br>hazard index: 0.002183")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Beawar">Beawar</a>')

var circle_15 = L.circle([24.268349, 72.204387], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2069, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Deesa<br>rank: 15<br>hazard index: 0.002070")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deesa">Deesa</a>')

var circle_16 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1907, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Bikaner<br>rank: 16<br>hazard index: 0.001908")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_17 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1769, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Surat<br>rank: 17<br>hazard index: 0.001769")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_18 = L.circle([22.610318, 73.461706], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1382, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Kalol<br>rank: 18<br>hazard index: 0.001383")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kalol">Kalol</a>')

var circle_19 = L.circle([22.689507, 72.871520], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1380, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Nadiad<br>rank: 19<br>hazard index: 0.001381")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nadiad">Nadiad</a>')

var circle_20 = L.circle([23.223288, 72.649227], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1346, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Gandhinagar<br>rank: 20<br>hazard index: 0.001346")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhinagar">Gandhinagar</a>')

var circle_21 = L.circle([22.558499, 72.962563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1250, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Anand<br>rank: 21<br>hazard index: 0.001251")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Anand">Anand</a>')

var circle_22 = L.circle([21.771884, 72.141645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 954, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Bhavnagar<br>rank: 22<br>hazard index: 0.000955")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhavnagar">Bhavnagar</a>')

var circle_23 = L.circle([22.750000, 71.666667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 914, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Surendranagar<br>rank: 23<br>hazard index: 0.000915")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surendranagar">Surendranagar</a>')

var circle_24 = L.circle([23.247245, 69.668339], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 790, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Bhuj<br>rank: 24<br>hazard index: 0.000790")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhuj">Bhuj</a>')

var circle_25 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 730, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Bangalore<br>rank: 25<br>hazard index: 0.000730")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_26 = L.circle([22.778500, 73.624516], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 563, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Godhra<br>rank: 26<br>hazard index: 0.000564")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Godhra">Godhra</a>')

var circle_27 = L.circle([22.473242, 70.055210], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 481, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Jamnagar<br>rank: 27<br>hazard index: 0.000481")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamnagar">Jamnagar</a>')

var circle_28 = L.circle([23.493079, 74.348402], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 466, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Banswara<br>rank: 28<br>hazard index: 0.000467")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Banswara">Banswara</a>')

var circle_29 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 449, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Pune<br>rank: 29<br>hazard index: 0.000450")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_30 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 418, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Hyderabad<br>rank: 30<br>hazard index: 0.000419")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_31 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 411, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Kolkata<br>rank: 31<br>hazard index: 0.000411")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_32 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 407, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Chennai<br>rank: 32<br>hazard index: 0.000408")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_33 = L.circle([22.168600, 71.668500], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 401, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Botad<br>rank: 33<br>hazard index: 0.000401")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Botad">Botad</a>')

var circle_34 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 366, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Jalandhar<br>rank: 34<br>hazard index: 0.000366")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_35 = L.circle([27.060786, 74.176675], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 283, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Nagaur<br>rank: 35<br>hazard index: 0.000283")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagaur">Nagaur</a>')

var circle_36 = L.circle([21.750000, 73.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 273, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Bharuch<br>rank: 36<br>hazard index: 0.000273")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharuch">Bharuch</a>')

var circle_37 = L.circle([25.488773, 74.699613], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 232, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Bhilwara<br>rank: 37<br>hazard index: 0.000233")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhilwara">Bhilwara</a>')

var circle_38 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 223, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Vasco Da Gama<br>rank: 38<br>hazard index: 0.000223")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_39 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 214, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Jammu<br>rank: 39<br>hazard index: 0.000214")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_40 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 206, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Thane<br>rank: 40<br>hazard index: 0.000207")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_41 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 185, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Lucknow<br>rank: 41<br>hazard index: 0.000186")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_42 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 185, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Agra<br>rank: 42<br>hazard index: 0.000185")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_43 = L.circle([21.517410, 70.464275], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 182, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Junagadh<br>rank: 43<br>hazard index: 0.000182")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Junagadh">Junagadh</a>')

var circle_44 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 154, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Indore<br>rank: 44<br>hazard index: 0.000155")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_45 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 148, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Hisar<br>rank: 45<br>hazard index: 0.000149")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_46 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 143, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Kota<br>rank: 46<br>hazard index: 0.000143")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_47 = L.circle([19.439885, 72.880383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 136, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Vasai<br>rank: 47<br>hazard index: 0.000137")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a>')

var circle_48 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 128, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Kanpur<br>rank: 48<br>hazard index: 0.000129")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_49 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 128, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Nagpur<br>rank: 49<br>hazard index: 0.000128")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_50 = L.circle([24.500000, 74.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 126, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Chittaurgarh<br>rank: 50<br>hazard index: 0.000127")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chittaurgarh">Chittaurgarh</a>')

var circle_51 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 126, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Jhansi<br>rank: 51<br>hazard index: 0.000126")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_52 = L.circle([29.367200, 74.298364], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 117, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Hanumangarh<br>rank: 52<br>hazard index: 0.000118")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hanumangarh">Hanumangarh</a>')

var circle_53 = L.circle([30.179115, 75.047102], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 111, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Bathinda<br>rank: 53<br>hazard index: 0.000112")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a>')

var circle_54 = L.circle([28.206144, 74.691907], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 111, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Churu<br>rank: 54<br>hazard index: 0.000112")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Churu">Churu</a>')

var circle_55 = L.circle([26.588559, 74.861097], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Kishangarh<br>rank: 55<br>hazard index: 0.000111")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kishangarh">Kishangarh</a>')

var circle_56 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 104, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Kochi<br>rank: 56<br>hazard index: 0.000104")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_57 = L.circle([20.905700, 70.378100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 95, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Veraval<br>rank: 57<br>hazard index: 0.000095")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Veraval">Veraval</a>')

var circle_58 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 92, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Varanasi<br>rank: 58<br>hazard index: 0.000093")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_59 = L.circle([27.701115, 74.464936], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 92, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Sujangarh<br>rank: 59<br>hazard index: 0.000092")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sujangarh">Sujangarh</a>')

var circle_60 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 84, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Gurgaon<br>rank: 60<br>hazard index: 0.000085")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_61 = L.circle([21.972182, 70.795524], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 71, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Gondal<br>rank: 61<br>hazard index: 0.000071")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gondal">Gondal</a>')

var circle_62 = L.circle([28.195647, 76.616518], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 70, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Rewari<br>rank: 62<br>hazard index: 0.000071")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewari">Rewari</a>')

var circle_63 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 70, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Bhopal<br>rank: 63<br>hazard index: 0.000070")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_64 = L.circle([23.174597, 75.785142], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Ujjain<br>rank: 64<br>hazard index: 0.000070")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ujjain">Ujjain</a>')

var circle_65 = L.circle([21.764059, 70.616660], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 65, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Jetpur Navagadh<br>rank: 65<br>hazard index: 0.000066")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jetpur_Navagadh">Jetpur Navagadh</a>')

var circle_66 = L.circle([27.662826, 75.027926], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 63, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Sikar<br>rank: 66<br>hazard index: 0.000063")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sikar">Sikar</a>')

var circle_67 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 56, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Chandigarh<br>rank: 67<br>hazard index: 0.000057")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_68 = L.circle([21.640900, 69.611000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 56, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Porbandar<br>rank: 68<br>hazard index: 0.000056")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Porbandar">Porbandar</a>')

var circle_69 = L.circle([23.480592, 74.917790], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 55, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Ratlam<br>rank: 69<br>hazard index: 0.000055")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ratlam">Ratlam</a>')

var circle_70 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Ludhiana<br>rank: 70<br>hazard index: 0.000053")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_71 = L.circle([18.627929, 73.800983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Pimpri Chinchwad<br>rank: 71<br>hazard index: 0.000052")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pimpri_Chinchwad">Pimpri Chinchwad</a>')

var circle_72 = L.circle([24.265131, 75.387182], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Mandsaur<br>rank: 72<br>hazard index: 0.000051")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mandsaur">Mandsaur</a>')

var circle_73 = L.circle([24.462465, 74.850114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Nimach<br>rank: 73<br>hazard index: 0.000051")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nimach">Nimach</a>')

var circle_74 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Nashik<br>rank: 74<br>hazard index: 0.000051")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_75 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Gwalior<br>rank: 75<br>hazard index: 0.000050")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_76 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Jabalpur<br>rank: 76<br>hazard index: 0.000050")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_77 = L.circle([32.301710, 75.658642], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Pathankot<br>rank: 77<br>hazard index: 0.000046")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pathankot">Pathankot</a>')

var circle_78 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Amritsar<br>rank: 78<br>hazard index: 0.000044")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_79 = L.circle([30.885100, 74.660141], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Firozpur<br>rank: 79<br>hazard index: 0.000043")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozpur">Firozpur</a>')

var circle_80 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Raipur<br>rank: 80<br>hazard index: 0.000043")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_81 = L.circle([25.264902, 82.985787], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Morvi<br>rank: 81<br>hazard index: 0.000042")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Morvi">Morvi</a>')

var circle_82 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Alwar<br>rank: 82<br>hazard index: 0.000041")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_83 = L.circle([20.952407, 72.932383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 37, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Navsari<br>rank: 83<br>hazard index: 0.000037")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Navsari">Navsari</a>')

var circle_84 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 37, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Jalgaon<br>rank: 84<br>hazard index: 0.000037")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_85 = L.circle([31.608574, 75.846442], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 35, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Hoshiarpur<br>rank: 85<br>hazard index: 0.000036")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshiarpur">Hoshiarpur</a>')

var circle_86 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 34, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Patna<br>rank: 86<br>hazard index: 0.000035")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_87 = L.circle([27.265212, 77.369126], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 34, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Bharatpur<br>rank: 87<br>hazard index: 0.000034")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharatpur">Bharatpur</a>')

var circle_88 = L.circle([12.305183, 76.655361], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 34, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Mysore<br>rank: 88<br>hazard index: 0.000034")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mysore">Mysore</a>')

var circle_89 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Faridabad<br>rank: 89<br>hazard index: 0.000031")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_90 = L.circle([31.385241, 75.305523], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Kapurthala<br>rank: 90<br>hazard index: 0.000030")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kapurthala">Kapurthala</a>')

var circle_91 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 29, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Akola<br>rank: 91<br>hazard index: 0.000030")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')

var circle_92 = L.circle([20.432402, 73.141172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Valsad<br>rank: 92<br>hazard index: 0.000028")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Valsad">Valsad</a>')

var circle_93 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Rohtak<br>rank: 93<br>hazard index: 0.000024")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_94 = L.circle([30.209087, 76.339872], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Patiala<br>rank: 94<br>hazard index: 0.000024")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a>')

var circle_95 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Allahabad<br>rank: 95<br>hazard index: 0.000024")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_96 = L.circle([15.351838, 75.137985], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Hubli<br>rank: 96<br>hazard index: 0.000023")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hubli">Hubli</a>')

var circle_97 = L.circle([26.122147, 75.663754], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Tonk<br>rank: 97<br>hazard index: 0.000023")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tonk">Tonk</a>')

var circle_98 = L.circle([19.261944, 73.194760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Ulhas Nagar<br>rank: 98<br>hazard index: 0.000023")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ulhas_Nagar">Ulhas Nagar</a>')

var circle_99 = L.circle([19.295200, 72.854400], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Mira-Bhayandar<br>rank: 99<br>hazard index: 0.000022")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mira-Bhayandar">Mira-Bhayandar</a>')

var circle_100 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Meerut<br>rank: 100<br>hazard index: 0.000022")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')
</script>
</div>


<div class="flex-item-right">
<table>
<tr>
<th>Rank</th>
<th>City</th>
</tr>

<tr>
<td>1</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Patan">Patan</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Palanpur">Palanpur</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gandhidham">Gandhidham</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Mahesana. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>