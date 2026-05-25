---
layout: page
title: "Outbreak location: Nandurbar"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([21.365999, 74.284004],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Nandurbar").openTooltip();

var circle_1 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 217238, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Akola<br>rank: 1<br>hazard index: 0.217239")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')

var circle_2 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42120, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Surat<br>rank: 2<br>hazard index: 0.042121")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_3 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28549, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Jalgaon<br>rank: 3<br>hazard index: 0.028550")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_4 = L.circle([19.290314, 76.602903], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17921, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Parbhani<br>rank: 4<br>hazard index: 0.017921")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Parbhani">Parbhani</a>')

var circle_5 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12074, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Vadodara<br>rank: 5<br>hazard index: 0.012074")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_6 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11669, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Bhusawal<br>rank: 6<br>hazard index: 0.011669")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_7 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10379, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Nashik<br>rank: 7<br>hazard index: 0.010380")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_8 = L.circle([21.154541, 77.644296], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8374, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Amravati<br>rank: 8<br>hazard index: 0.008375")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amravati">Amravati</a>')

var circle_9 = L.circle([19.877263, 75.339024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8203, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Aurangabad<br>rank: 9<br>hazard index: 0.008203")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aurangabad">Aurangabad</a>')

var circle_10 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5982, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Nanded Waghala<br>rank: 10<br>hazard index: 0.005982")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_11 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3622, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Nagpur<br>rank: 11<br>hazard index: 0.003622")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_12 = L.circle([20.259399, 76.976203], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3535, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Malegaon<br>rank: 12<br>hazard index: 0.003536")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Malegaon">Malegaon</a>')

var circle_13 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2970, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Mumbai<br>rank: 13<br>hazard index: 0.002971")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_14 = L.circle([20.030976, 79.358139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2729, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Chandrapur<br>rank: 14<br>hazard index: 0.002729")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandrapur">Chandrapur</a>')

var circle_15 = L.circle([16.850253, 74.594888], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2541, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Sangli<br>rank: 15<br>hazard index: 0.002542")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sangli">Sangli</a>')

var circle_16 = L.circle([20.825623, 78.613146], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2229, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Wardha<br>rank: 16<br>hazard index: 0.002230")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Wardha">Wardha</a>')

var circle_17 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2026, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Ahmedabad<br>rank: 17<br>hazard index: 0.002027")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_18 = L.circle([21.818774, 75.606458], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1969, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Khargone<br>rank: 18<br>hazard index: 0.001969")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khargone">Khargone</a>')

var circle_19 = L.circle([19.918233, 75.868625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1681, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Jalna<br>rank: 19<br>hazard index: 0.001682")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalna">Jalna</a>')

var circle_20 = L.circle([22.558499, 72.962563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1418, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Anand<br>rank: 20<br>hazard index: 0.001419")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Anand">Anand</a>')

var circle_21 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1217, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Pune<br>rank: 21<br>hazard index: 0.001217")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_22 = L.circle([21.750000, 73.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1204, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Bharuch<br>rank: 22<br>hazard index: 0.001204")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharuch">Bharuch</a>')

var circle_23 = L.circle([20.952407, 72.932383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1120, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Navsari<br>rank: 23<br>hazard index: 0.001121")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Navsari">Navsari</a>')

var circle_24 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1098, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Hyderabad<br>rank: 24<br>hazard index: 0.001098")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_25 = L.circle([22.778500, 73.624516], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 999, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Godhra<br>rank: 25<br>hazard index: 0.000999")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Godhra">Godhra</a>')

var circle_26 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 875, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Jabalpur<br>rank: 26<br>hazard index: 0.000875")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_27 = L.circle([19.794750, 75.077922], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 831, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Gangapur<br>rank: 27<br>hazard index: 0.000831")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gangapur">Gangapur</a>')

var circle_28 = L.circle([20.432402, 73.141172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 819, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Valsad<br>rank: 28<br>hazard index: 0.000820")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Valsad">Valsad</a>')

var circle_29 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 816, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Allahabad<br>rank: 29<br>hazard index: 0.000817")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_30 = L.circle([21.145629, 80.268387], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 810, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Gondiya<br>rank: 30<br>hazard index: 0.000811")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gondiya">Gondiya</a>')

var circle_31 = L.circle([22.610318, 73.461706], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 782, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Kalol<br>rank: 31<br>hazard index: 0.000783")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kalol">Kalol</a>')

var circle_32 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 656, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Varanasi<br>rank: 32<br>hazard index: 0.000657")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_33 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 631, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Kolkata<br>rank: 33<br>hazard index: 0.000632")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_34 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 626, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Indore<br>rank: 34<br>hazard index: 0.000627")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_35 = L.circle([21.977864, 76.568828], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 608, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Khandwa<br>rank: 35<br>hazard index: 0.000608")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khandwa">Khandwa</a>')

var circle_36 = L.circle([18.351469, 76.755121], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 604, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Latur<br>rank: 36<br>hazard index: 0.000605")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Latur">Latur</a>')

var circle_37 = L.circle([19.439885, 72.880383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 562, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Vasai<br>rank: 37<br>hazard index: 0.000562")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a>')

var circle_38 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 513, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Delhi<br>rank: 38<br>hazard index: 0.000513")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_39 = L.circle([19.500000, 78.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 513, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Adilabad<br>rank: 39<br>hazard index: 0.000513")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Adilabad">Adilabad</a>')

var circle_40 = L.circle([20.475195, 78.742396], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 493, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Hinganghat<br>rank: 40<br>hazard index: 0.000494")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hinganghat">Hinganghat</a>')

var circle_41 = L.circle([20.325704, 78.116914], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 462, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Yavatmal<br>rank: 41<br>hazard index: 0.000463")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yavatmal">Yavatmal</a>')

var circle_42 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 389, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Raipur<br>rank: 42<br>hazard index: 0.000389")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_43 = L.circle([21.879616, 77.875681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 374, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Betul<br>rank: 43<br>hazard index: 0.000374")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Betul">Betul</a>')

var circle_44 = L.circle([21.771884, 72.141645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 373, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Bhavnagar<br>rank: 44<br>hazard index: 0.000374")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhavnagar">Bhavnagar</a>')

var circle_45 = L.circle([26.055318, 82.993139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 358, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Nizamabad<br>rank: 45<br>hazard index: 0.000358")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a>')

var circle_46 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 321, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Chennai<br>rank: 46<br>hazard index: 0.000322")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_47 = L.circle([15.857267, 74.506934], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 292, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Belgaum<br>rank: 47<br>hazard index: 0.000293")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Belgaum">Belgaum</a>')

var circle_48 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 232, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Satna<br>rank: 48<br>hazard index: 0.000233")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_49 = L.circle([22.689507, 72.871520], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 230, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Nadiad<br>rank: 49<br>hazard index: 0.000231")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nadiad">Nadiad</a>')

var circle_50 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 211, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Patna<br>rank: 50<br>hazard index: 0.000212")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_51 = L.circle([18.182992, 75.743925], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 187, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Barshi<br>rank: 51<br>hazard index: 0.000187")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barshi">Barshi</a>')

var circle_52 = L.circle([26.269721, 82.994425], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 185, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Burhanpur<br>rank: 52<br>hazard index: 0.000185")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Burhanpur">Burhanpur</a>')

var circle_53 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 184, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Vijayawada<br>rank: 53<br>hazard index: 0.000184")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_54 = L.circle([19.250000, 74.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 177, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Ahmadnagar<br>rank: 54<br>hazard index: 0.000178")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmadnagar">Ahmadnagar</a>')

var circle_55 = L.circle([18.169844, 76.117963], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 177, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Osmanabad<br>rank: 55<br>hazard index: 0.000177")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Osmanabad">Osmanabad</a>')

var circle_56 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 166, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Thane<br>rank: 56<br>hazard index: 0.000166")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_57 = L.circle([16.702841, 74.240533], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 165, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Kolhapur<br>rank: 57<br>hazard index: 0.000166")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolhapur">Kolhapur</a>')

var circle_58 = L.circle([15.351838, 75.137985], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 157, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Hubli<br>rank: 58<br>hazard index: 0.000157")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hubli">Hubli</a>')

var circle_59 = L.circle([21.199035, 81.397955], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 131, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Durg<br>rank: 59<br>hazard index: 0.000132")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durg">Durg</a>')

var circle_60 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Jaipur<br>rank: 60<br>hazard index: 0.000122")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_61 = L.circle([18.761516, 79.478785], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 115, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Ramagundam<br>rank: 61<br>hazard index: 0.000116")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ramagundam">Ramagundam</a>')

var circle_62 = L.circle([17.849907, 75.276320], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 112, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Solapur<br>rank: 62<br>hazard index: 0.000112")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a>')

var circle_63 = L.circle([17.980609, 79.598212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 109, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Warangal<br>rank: 63<br>hazard index: 0.000109")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Warangal">Warangal</a>')

var circle_64 = L.circle([22.305199, 70.802834], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 103, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Rajkot<br>rank: 64<br>hazard index: 0.000104")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a>')

var circle_65 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 100, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Bangalore<br>rank: 65<br>hazard index: 0.000101")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_66 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 98, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Bilaspur<br>rank: 66<br>hazard index: 0.000098")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_67 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 90, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Visakhapatnam<br>rank: 67<br>hazard index: 0.000090")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_68 = L.circle([23.666667, 72.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 89, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Mahesana<br>rank: 68<br>hazard index: 0.000089")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mahesana">Mahesana</a>')

var circle_69 = L.circle([21.200996, 81.335426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 88, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Bhilai Nagar<br>rank: 69<br>hazard index: 0.000089")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhilai_Nagar">Bhilai Nagar</a>')

var circle_70 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 85, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Jamshedpur<br>rank: 70<br>hazard index: 0.000086")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_71 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 85, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Bhubaneswar<br>rank: 71<br>hazard index: 0.000085")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_72 = L.circle([22.168600, 71.668500], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 80, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Botad<br>rank: 72<br>hazard index: 0.000081")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Botad">Botad</a>')

var circle_73 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 79, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Bhopal<br>rank: 73<br>hazard index: 0.000080")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_74 = L.circle([20.972740, 80.691555], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 78, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Rajnandgaon<br>rank: 74<br>hazard index: 0.000079")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajnandgaon">Rajnandgaon</a>')

var circle_75 = L.circle([24.935635, 82.647701], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 77, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Mirzapur<br>rank: 75<br>hazard index: 0.000077")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mirzapur">Mirzapur</a>')

var circle_76 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Chapra<br>rank: 76<br>hazard index: 0.000076")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_77 = L.circle([25.954628, 83.647350], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Maunath Bhanjan<br>rank: 77<br>hazard index: 0.000075")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Maunath_Bhanjan">Maunath Bhanjan</a>')

var circle_78 = L.circle([20.166670, 79.172114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 71, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Bhadravati<br>rank: 78<br>hazard index: 0.000071")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhadravati">Bhadravati</a>')

var circle_79 = L.circle([16.695935, 74.455575], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Ichalkaranji<br>rank: 79<br>hazard index: 0.000070")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ichalkaranji">Ichalkaranji</a>')

var circle_80 = L.circle([22.600150, 77.926645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 67, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Hoshangabad<br>rank: 80<br>hazard index: 0.000068")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshangabad">Hoshangabad</a>')

var circle_81 = L.circle([26.732501, 77.036312], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 64, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Hindaun<br>rank: 81<br>hazard index: 0.000065")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hindaun">Hindaun</a>')

var circle_82 = L.circle([19.295200, 72.854400], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Mira-Bhayandar<br>rank: 82<br>hazard index: 0.000062")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mira-Bhayandar">Mira-Bhayandar</a>')

var circle_83 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 61, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Kota<br>rank: 83<br>hazard index: 0.000062")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_84 = L.circle([22.139831, 78.809645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Chhindwara<br>rank: 84<br>hazard index: 0.000059")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chhindwara">Chhindwara</a>')

var circle_85 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 58, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Jhansi<br>rank: 85<br>hazard index: 0.000059")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_86 = L.circle([27.209822, 79.048137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 56, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Mainpuri<br>rank: 86<br>hazard index: 0.000057")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mainpuri">Mainpuri</a>')

var circle_87 = L.circle([18.627929, 73.800983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 56, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Pimpri Chinchwad<br>rank: 87<br>hazard index: 0.000057")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pimpri_Chinchwad">Pimpri Chinchwad</a>')

var circle_88 = L.circle([19.362531, 73.078475], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 54, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Bhiwandi<br>rank: 88<br>hazard index: 0.000054")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwandi">Bhiwandi</a>')

var circle_89 = L.circle([22.214285, 84.872437], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Raurkela<br>rank: 89<br>hazard index: 0.000052")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raurkela">Raurkela</a>')

var circle_90 = L.circle([19.807608, 85.825254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 46, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Puri<br>rank: 90<br>hazard index: 0.000047")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Puri">Puri</a>')

var circle_91 = L.circle([25.795593, 82.488341], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Jaunpur<br>rank: 91<br>hazard index: 0.000045")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaunpur">Jaunpur</a>')

var circle_92 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Jodhpur<br>rank: 92<br>hazard index: 0.000045")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_93 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Kanpur<br>rank: 93<br>hazard index: 0.000043")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_94 = L.circle([18.112082, 83.405220], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Vizianagaram<br>rank: 94<br>hazard index: 0.000042")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vizianagaram">Vizianagaram</a>')

var circle_95 = L.circle([23.480592, 74.917790], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 41, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Ratlam<br>rank: 95<br>hazard index: 0.000041")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ratlam">Ratlam</a>')

var circle_96 = L.circle([23.223288, 72.649227], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Gandhinagar<br>rank: 96<br>hazard index: 0.000041")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhinagar">Gandhinagar</a>')

var circle_97 = L.circle([17.910400, 77.519900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Bidar<br>rank: 97<br>hazard index: 0.000040")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidar">Bidar</a>')

var circle_98 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 39, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Vasco Da Gama<br>rank: 98<br>hazard index: 0.000040")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_99 = L.circle([25.877933, 84.119959], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 39, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Ballia<br>rank: 99<br>hazard index: 0.000039")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ballia">Ballia</a>')

var circle_100 = L.circle([19.261944, 73.194760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Ulhas Nagar<br>rank: 100<br>hazard index: 0.000038")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ulhas_Nagar">Ulhas Nagar</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Parbhani">Parbhani</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Amravati">Amravati</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Aurangabad">Aurangabad</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Nandurbar. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>