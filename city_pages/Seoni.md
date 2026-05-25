---
layout: page
title: "Outbreak location: Seoni"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([22.275879, 79.721045],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Seoni").openTooltip();

var circle_1 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 138654, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Nagpur<br>rank: 1<br>hazard index: 0.138655")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_2 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 60774, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Jabalpur<br>rank: 2<br>hazard index: 0.060775")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_3 = L.circle([26.500000, 78.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 58579, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Bhind<br>rank: 3<br>hazard index: 0.058580")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhind">Bhind</a>')

var circle_4 = L.circle([26.718324, 79.090254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24304, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Etawah<br>rank: 4<br>hazard index: 0.024304")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Etawah">Etawah</a>')

var circle_5 = L.circle([23.809612, 78.759114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15756, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Sagar<br>rank: 5<br>hazard index: 0.015757")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sagar">Sagar</a>')

var circle_6 = L.circle([23.833962, 80.392456], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12789, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Murwara<br>rank: 6<br>hazard index: 0.012789")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Murwara">Murwara</a>')

var circle_7 = L.circle([20.972740, 80.691555], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9402, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Rajnandgaon<br>rank: 7<br>hazard index: 0.009403")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajnandgaon">Rajnandgaon</a>')

var circle_8 = L.circle([22.139831, 78.809645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7970, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Chhindwara<br>rank: 8<br>hazard index: 0.007970")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chhindwara">Chhindwara</a>')

var circle_9 = L.circle([21.145629, 80.268387], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7660, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Gondiya<br>rank: 9<br>hazard index: 0.007660")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gondiya">Gondiya</a>')

var circle_10 = L.circle([23.750000, 79.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7204, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Damoh<br>rank: 10<br>hazard index: 0.007204")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Damoh">Damoh</a>')

var circle_11 = L.circle([22.600150, 77.926645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6799, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Hoshangabad<br>rank: 11<br>hazard index: 0.006799")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshangabad">Hoshangabad</a>')

var circle_12 = L.circle([20.825623, 78.613146], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6083, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Wardha<br>rank: 12<br>hazard index: 0.006084")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Wardha">Wardha</a>')

var circle_13 = L.circle([21.879616, 77.875681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5956, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Betul<br>rank: 13<br>hazard index: 0.005957")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Betul">Betul</a>')

var circle_14 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5581, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Jhansi<br>rank: 14<br>hazard index: 0.005582")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_15 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4483, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Raipur<br>rank: 15<br>hazard index: 0.004483")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_16 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4418, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Mumbai<br>rank: 16<br>hazard index: 0.004419")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_17 = L.circle([21.154541, 77.644296], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4130, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Amravati<br>rank: 17<br>hazard index: 0.004130")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amravati">Amravati</a>')

var circle_18 = L.circle([20.030976, 79.358139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3257, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Chandrapur<br>rank: 18<br>hazard index: 0.003258")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandrapur">Chandrapur</a>')

var circle_19 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2522, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Kanpur<br>rank: 19<br>hazard index: 0.002522")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_20 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2298, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Satna<br>rank: 20<br>hazard index: 0.002299")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_21 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2015, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Delhi<br>rank: 21<br>hazard index: 0.002015")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_22 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1881, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Bhopal<br>rank: 22<br>hazard index: 0.001881")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_23 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1796, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Allahabad<br>rank: 23<br>hazard index: 0.001797")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_24 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1751, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Gwalior<br>rank: 24<br>hazard index: 0.001751")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_25 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1725, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Kolkata<br>rank: 25<br>hazard index: 0.001726")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_26 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1681, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Pune<br>rank: 26<br>hazard index: 0.001682")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_27 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1461, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Jalgaon<br>rank: 27<br>hazard index: 0.001461")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_28 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1435, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Agra<br>rank: 28<br>hazard index: 0.001435")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_29 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1423, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Indore<br>rank: 29<br>hazard index: 0.001424")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_30 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1310, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Hyderabad<br>rank: 30<br>hazard index: 0.001311")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_31 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1185, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Bangalore<br>rank: 31<br>hazard index: 0.001185")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_32 = L.circle([21.199035, 81.397955], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1180, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Durg<br>rank: 32<br>hazard index: 0.001181")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durg">Durg</a>')

var circle_33 = L.circle([24.197443, 82.666145], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1160, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Singrauli<br>rank: 33<br>hazard index: 0.001161")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Singrauli">Singrauli</a>')

var circle_34 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1042, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Bilaspur<br>rank: 34<br>hazard index: 0.001043")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_35 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1004, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Chennai<br>rank: 35<br>hazard index: 0.001005")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_36 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 912, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Lucknow<br>rank: 36<br>hazard index: 0.000913")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_37 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 890, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Akola<br>rank: 37<br>hazard index: 0.000890")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')

var circle_38 = L.circle([20.166670, 79.172114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 849, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Bhadravati<br>rank: 38<br>hazard index: 0.000849")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhadravati">Bhadravati</a>')

var circle_39 = L.circle([21.200996, 81.335426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 842, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Bhilai Nagar<br>rank: 39<br>hazard index: 0.000842")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhilai_Nagar">Bhilai Nagar</a>')

var circle_40 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 795, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Aligarh<br>rank: 40<br>hazard index: 0.000795")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_41 = L.circle([23.122634, 83.198189], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 627, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Ambikapur<br>rank: 41<br>hazard index: 0.000628")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambikapur">Ambikapur</a>')

var circle_42 = L.circle([19.500000, 78.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 616, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Adilabad<br>rank: 42<br>hazard index: 0.000617")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Adilabad">Adilabad</a>')

var circle_43 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 550, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Firozabad<br>rank: 43<br>hazard index: 0.000550")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_44 = L.circle([24.759267, 81.655000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 541, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Rewa<br>rank: 44<br>hazard index: 0.000542")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewa">Rewa</a>')

var circle_45 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 533, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Jamshedpur<br>rank: 45<br>hazard index: 0.000534")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_46 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 520, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Varanasi<br>rank: 46<br>hazard index: 0.000520")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_47 = L.circle([20.325704, 78.116914], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 517, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Yavatmal<br>rank: 47<br>hazard index: 0.000518")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yavatmal">Yavatmal</a>')

var circle_48 = L.circle([20.475195, 78.742396], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 512, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Hinganghat<br>rank: 48<br>hazard index: 0.000512")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hinganghat">Hinganghat</a>')

var circle_49 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 481, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Kota<br>rank: 49<br>hazard index: 0.000482")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_50 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 473, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Jaipur<br>rank: 50<br>hazard index: 0.000473")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_51 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 471, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Bhusawal<br>rank: 51<br>hazard index: 0.000472")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_52 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 429, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Vijayawada<br>rank: 52<br>hazard index: 0.000429")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_53 = L.circle([20.259399, 76.976203], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 408, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Malegaon<br>rank: 53<br>hazard index: 0.000409")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Malegaon">Malegaon</a>')

var circle_54 = L.circle([25.375241, 77.828119], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 398, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Shivpuri<br>rank: 54<br>hazard index: 0.000398")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shivpuri">Shivpuri</a>')

var circle_55 = L.circle([23.174597, 75.785142], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 374, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Ujjain<br>rank: 55<br>hazard index: 0.000374")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ujjain">Ujjain</a>')

var circle_56 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 337, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Visakhapatnam<br>rank: 56<br>hazard index: 0.000337")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_57 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 321, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Ahmedabad<br>rank: 57<br>hazard index: 0.000322")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_58 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 318, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Mathura<br>rank: 58<br>hazard index: 0.000318")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_59 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 303, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Surat<br>rank: 59<br>hazard index: 0.000303")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_60 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 298, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Shahjahanpur<br>rank: 60<br>hazard index: 0.000299")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_61 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 285, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Thane<br>rank: 61<br>hazard index: 0.000285")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_62 = L.circle([26.269721, 82.994425], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 278, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Burhanpur<br>rank: 62<br>hazard index: 0.000279")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Burhanpur">Burhanpur</a>')

var circle_63 = L.circle([21.977864, 76.568828], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 278, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Khandwa<br>rank: 63<br>hazard index: 0.000279")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khandwa">Khandwa</a>')

var circle_64 = L.circle([26.575504, 80.613762], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 277, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Unnao<br>rank: 64<br>hazard index: 0.000278")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Unnao">Unnao</a>')

var circle_65 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 275, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Patna<br>rank: 65<br>hazard index: 0.000275")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_66 = L.circle([22.214285, 84.872437], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 258, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Raurkela<br>rank: 66<br>hazard index: 0.000259")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raurkela">Raurkela</a>')

var circle_67 = L.circle([27.437194, 79.489129], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 251, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Farrukhabad<br>rank: 67<br>hazard index: 0.000251")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Farrukhabad">Farrukhabad</a>')

var circle_68 = L.circle([27.265212, 77.369126], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 229, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Bharatpur<br>rank: 68<br>hazard index: 0.000230")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharatpur">Bharatpur</a>')

var circle_69 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 223, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Nashik<br>rank: 69<br>hazard index: 0.000224")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_70 = L.circle([22.519770, 82.629515], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 222, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Korba<br>rank: 70<br>hazard index: 0.000223")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Korba">Korba</a>')

var circle_71 = L.circle([17.980609, 79.598212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 216, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Warangal<br>rank: 71<br>hazard index: 0.000216")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Warangal">Warangal</a>')

var circle_72 = L.circle([23.000000, 76.166667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 210, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Dewas<br>rank: 72<br>hazard index: 0.000210")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dewas">Dewas</a>')

var circle_73 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 203, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Bareilly<br>rank: 73<br>hazard index: 0.000204")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_74 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 199, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Nanded Waghala<br>rank: 74<br>hazard index: 0.000200")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_75 = L.circle([23.480592, 74.917790], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 192, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Ratlam<br>rank: 75<br>hazard index: 0.000192")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ratlam">Ratlam</a>')

var circle_76 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 189, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Bhubaneswar<br>rank: 76<br>hazard index: 0.000189")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_77 = L.circle([26.166667, 77.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 182, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Morena<br>rank: 77<br>hazard index: 0.000183")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Morena">Morena</a>')

var circle_78 = L.circle([27.338577, 80.097526], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 178, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Hardoi<br>rank: 78<br>hazard index: 0.000178")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hardoi">Hardoi</a>')

var circle_79 = L.circle([13.932609, 75.574978], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 175, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Shimoga<br>rank: 79<br>hazard index: 0.000176")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shimoga">Shimoga</a>')

var circle_80 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 171, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Dhanbad<br>rank: 80<br>hazard index: 0.000171")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_81 = L.circle([25.935955, 79.424328], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 157, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Orai<br>rank: 81<br>hazard index: 0.000157")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Orai">Orai</a>')

var circle_82 = L.circle([25.476300, 80.339500], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 157, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Banda<br>rank: 82<br>hazard index: 0.000157")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Banda">Banda</a>')

var circle_83 = L.circle([24.935635, 82.647701], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Mirzapur<br>rank: 83<br>hazard index: 0.000154")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mirzapur">Mirzapur</a>')

var circle_84 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 149, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Coimbatore<br>rank: 84<br>hazard index: 0.000149")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_85 = L.circle([18.761516, 79.478785], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 143, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Ramagundam<br>rank: 85<br>hazard index: 0.000143")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ramagundam">Ramagundam</a>')

var circle_86 = L.circle([24.500000, 77.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 131, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Guna<br>rank: 86<br>hazard index: 0.000131")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guna">Guna</a>')

var circle_87 = L.circle([22.500000, 83.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 129, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Raigarh<br>rank: 87<br>hazard index: 0.000130")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raigarh">Raigarh</a>')

var circle_88 = L.circle([25.565691, 80.063489], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 127, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Khanna<br>rank: 88<br>hazard index: 0.000127")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khanna">Khanna</a>')

var circle_89 = L.circle([11.664300, 78.146000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 124, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Salem<br>rank: 89<br>hazard index: 0.000125")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Salem">Salem</a>')

var circle_90 = L.circle([26.732501, 77.036312], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 120, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Hindaun<br>rank: 90<br>hazard index: 0.000121")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hindaun">Hindaun</a>')

var circle_91 = L.circle([27.209822, 79.048137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 115, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Mainpuri<br>rank: 91<br>hazard index: 0.000116")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mainpuri">Mainpuri</a>')

var circle_92 = L.circle([25.750000, 78.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Datia<br>rank: 92<br>hazard index: 0.000110")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Datia">Datia</a>')

var circle_93 = L.circle([26.653396, 77.624206], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 106, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Dhaulpur<br>rank: 93<br>hazard index: 0.000107")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhaulpur">Dhaulpur</a>')

var circle_94 = L.circle([26.439874, 80.018000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 105, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Akbarpur<br>rank: 94<br>hazard index: 0.000106")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akbarpur">Akbarpur</a>')

var circle_95 = L.circle([27.504639, 80.829466], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 95, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Sitapur<br>rank: 95<br>hazard index: 0.000095")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sitapur">Sitapur</a>')

var circle_96 = L.circle([16.702841, 74.240533], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 94, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Kolhapur<br>rank: 96<br>hazard index: 0.000095")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolhapur">Kolhapur</a>')

var circle_97 = L.circle([19.250000, 74.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 93, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Ahmadnagar<br>rank: 97<br>hazard index: 0.000093")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmadnagar">Ahmadnagar</a>')

var circle_98 = L.circle([27.036604, 78.651436], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 92, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Shikohabad<br>rank: 98<br>hazard index: 0.000092")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shikohabad">Shikohabad</a>')

var circle_99 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 89, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Vadodara<br>rank: 99<br>hazard index: 0.000090")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_100 = L.circle([22.782355, 86.159003], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 87, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Adityapur<br>rank: 100<br>hazard index: 0.000087")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Adityapur">Adityapur</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhind">Bhind</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Etawah">Etawah</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Sagar">Sagar</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Murwara">Murwara</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Rajnandgaon">Rajnandgaon</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Chhindwara">Chhindwara</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gondiya">Gondiya</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Damoh">Damoh</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Seoni. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>