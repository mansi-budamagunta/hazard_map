---
layout: page
title: "Outbreak location: Porbandar"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([21.640900, 69.611000],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Porbandar").openTooltip();

var circle_1 = L.circle([22.305199, 70.802834], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 107998, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Rajkot<br>rank: 1<br>hazard index: 0.107998")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a>')

var circle_2 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51390, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Mumbai<br>rank: 2<br>hazard index: 0.051391")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_3 = L.circle([21.517410, 70.464275], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38313, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Junagadh<br>rank: 3<br>hazard index: 0.038314")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Junagadh">Junagadh</a>')

var circle_4 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 31721, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Ahmedabad<br>rank: 4<br>hazard index: 0.031721")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_5 = L.circle([22.473242, 70.055210], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28262, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Jamnagar<br>rank: 5<br>hazard index: 0.028262")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamnagar">Jamnagar</a>')

var circle_6 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21165, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Surat<br>rank: 6<br>hazard index: 0.021165")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_7 = L.circle([20.905700, 70.378100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18387, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Veraval<br>rank: 7<br>hazard index: 0.018388")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Veraval">Veraval</a>')

var circle_8 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11368, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Delhi<br>rank: 8<br>hazard index: 0.011369")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_9 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7905, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Vadodara<br>rank: 9<br>hazard index: 0.007906")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_10 = L.circle([23.071874, 70.131715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5624, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Gandhidham<br>rank: 10<br>hazard index: 0.005624")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhidham">Gandhidham</a>')

var circle_11 = L.circle([21.764059, 70.616660], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5610, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Jetpur Navagadh<br>rank: 11<br>hazard index: 0.005610")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jetpur_Navagadh">Jetpur Navagadh</a>')

var circle_12 = L.circle([21.972182, 70.795524], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5324, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Gondal<br>rank: 12<br>hazard index: 0.005325")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gondal">Gondal</a>')

var circle_13 = L.circle([23.247245, 69.668339], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4235, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Bhuj<br>rank: 13<br>hazard index: 0.004236")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhuj">Bhuj</a>')

var circle_14 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2890, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Jaipur<br>rank: 14<br>hazard index: 0.002891")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_15 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2873, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Thane<br>rank: 15<br>hazard index: 0.002874")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_16 = L.circle([19.439885, 72.880383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2794, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Vasai<br>rank: 16<br>hazard index: 0.002795")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a>')

var circle_17 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2390, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Kolkata<br>rank: 17<br>hazard index: 0.002390")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_18 = L.circle([22.910184, 69.899418], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2199, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Bhadreshwar<br>rank: 18<br>hazard index: 0.002199")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhadreshwar">Bhadreshwar</a>')

var circle_19 = L.circle([20.866667, 70.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2182, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Amreli<br>rank: 19<br>hazard index: 0.002182")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amreli">Amreli</a>')

var circle_20 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2144, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Pune<br>rank: 20<br>hazard index: 0.002144")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_21 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1813, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Nagpur<br>rank: 21<br>hazard index: 0.001813")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_22 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1550, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Hyderabad<br>rank: 22<br>hazard index: 0.001551")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_23 = L.circle([25.264902, 82.985787], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1324, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Morvi<br>rank: 23<br>hazard index: 0.001325")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Morvi">Morvi</a>')

var circle_24 = L.circle([22.750000, 71.666667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1226, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Surendranagar<br>rank: 24<br>hazard index: 0.001226")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surendranagar">Surendranagar</a>')

var circle_25 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1181, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Lucknow<br>rank: 25<br>hazard index: 0.001181")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_26 = L.circle([22.558499, 72.962563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 936, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Anand<br>rank: 26<br>hazard index: 0.000936")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Anand">Anand</a>')

var circle_27 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 824, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Gurgaon<br>rank: 27<br>hazard index: 0.000825")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_28 = L.circle([21.771884, 72.141645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 799, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Bhavnagar<br>rank: 28<br>hazard index: 0.000799")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhavnagar">Bhavnagar</a>')

var circle_29 = L.circle([22.689507, 72.871520], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 775, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Nadiad<br>rank: 29<br>hazard index: 0.000776")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nadiad">Nadiad</a>')

var circle_30 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 761, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Raipur<br>rank: 30<br>hazard index: 0.000761")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_31 = L.circle([18.627929, 73.800983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 720, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Pimpri Chinchwad<br>rank: 31<br>hazard index: 0.000721")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pimpri_Chinchwad">Pimpri Chinchwad</a>')

var circle_32 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 706, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Nashik<br>rank: 32<br>hazard index: 0.000707")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_33 = L.circle([21.750000, 73.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 598, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Bharuch<br>rank: 33<br>hazard index: 0.000599")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharuch">Bharuch</a>')

var circle_34 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 591, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Vasco Da Gama<br>rank: 34<br>hazard index: 0.000591")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_35 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 577, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Bangalore<br>rank: 35<br>hazard index: 0.000578")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_36 = L.circle([20.952407, 72.932383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 532, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Navsari<br>rank: 36<br>hazard index: 0.000533")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Navsari">Navsari</a>')

var circle_37 = L.circle([26.469100, 74.639000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 510, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Ajmer<br>rank: 37<br>hazard index: 0.000510")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a>')

var circle_38 = L.circle([23.666667, 72.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 483, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Mahesana<br>rank: 38<br>hazard index: 0.000483")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mahesana">Mahesana</a>')

var circle_39 = L.circle([20.432402, 73.141172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 408, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Valsad<br>rank: 39<br>hazard index: 0.000409")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Valsad">Valsad</a>')

var circle_40 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 394, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Jodhpur<br>rank: 40<br>hazard index: 0.000394")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_41 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 376, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Bareilly<br>rank: 41<br>hazard index: 0.000377")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_42 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 373, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Moradabad<br>rank: 42<br>hazard index: 0.000373")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_43 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 371, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Chennai<br>rank: 43<br>hazard index: 0.000371")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_44 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 335, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Jamshedpur<br>rank: 44<br>hazard index: 0.000335")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_45 = L.circle([23.223288, 72.649227], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 333, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Gandhinagar<br>rank: 45<br>hazard index: 0.000333")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhinagar">Gandhinagar</a>')

var circle_46 = L.circle([8.576971, 77.050125], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 326, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Thiruvananthapuram<br>rank: 46<br>hazard index: 0.000326")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thiruvananthapuram">Thiruvananthapuram</a>')

var circle_47 = L.circle([19.261944, 73.194760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 324, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Ulhas Nagar<br>rank: 47<br>hazard index: 0.000324")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ulhas_Nagar">Ulhas Nagar</a>')

var circle_48 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 321, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Akola<br>rank: 48<br>hazard index: 0.000322")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')

var circle_49 = L.circle([19.295200, 72.854400], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 311, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Mira-Bhayandar<br>rank: 49<br>hazard index: 0.000311")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mira-Bhayandar">Mira-Bhayandar</a>')

var circle_50 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 296, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Alwar<br>rank: 50<br>hazard index: 0.000297")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_51 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 290, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Jalgaon<br>rank: 51<br>hazard index: 0.000291")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_52 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 281, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Gorakhpur<br>rank: 52<br>hazard index: 0.000282")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_53 = L.circle([17.636129, 74.298278], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 267, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Satara<br>rank: 53<br>hazard index: 0.000267")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satara">Satara</a>')

var circle_54 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 248, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Bilaspur<br>rank: 54<br>hazard index: 0.000249")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_55 = L.circle([19.362531, 73.078475], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 248, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Bhiwandi<br>rank: 55<br>hazard index: 0.000249")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwandi">Bhiwandi</a>')

var circle_56 = L.circle([12.869810, 74.843008], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 246, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Mangalore<br>rank: 56<br>hazard index: 0.000247")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mangalore">Mangalore</a>')

var circle_57 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 220, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Jhansi<br>rank: 57<br>hazard index: 0.000220")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_58 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 216, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Kanpur<br>rank: 58<br>hazard index: 0.000217")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_59 = L.circle([17.849907, 75.276320], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 216, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Solapur<br>rank: 59<br>hazard index: 0.000217")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a>')

var circle_60 = L.circle([22.610318, 73.461706], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 206, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Kalol<br>rank: 60<br>hazard index: 0.000206")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kalol">Kalol</a>')

var circle_61 = L.circle([22.214285, 84.872437], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 205, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Raurkela<br>rank: 61<br>hazard index: 0.000206")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raurkela">Raurkela</a>')

var circle_62 = L.circle([21.199035, 81.397955], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 202, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Durg<br>rank: 62<br>hazard index: 0.000203")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durg">Durg</a>')

var circle_63 = L.circle([23.774057, 71.683735], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 193, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Patan<br>rank: 63<br>hazard index: 0.000194")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patan">Patan</a>')

var circle_64 = L.circle([19.143607, 73.295535], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 188, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Ambarnath<br>rank: 64<br>hazard index: 0.000189")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambarnath">Ambarnath</a>')

var circle_65 = L.circle([24.170979, 72.436638], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 188, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Palanpur<br>rank: 65<br>hazard index: 0.000188")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palanpur">Palanpur</a>')

var circle_66 = L.circle([11.258608, 75.778874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 187, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Kozhikode<br>rank: 66<br>hazard index: 0.000187")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kozhikode">Kozhikode</a>')

var circle_67 = L.circle([22.168600, 71.668500], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 173, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Botad<br>rank: 67<br>hazard index: 0.000173")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Botad">Botad</a>')

var circle_68 = L.circle([24.268349, 72.204387], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 164, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Deesa<br>rank: 68<br>hazard index: 0.000165")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deesa">Deesa</a>')

var circle_69 = L.circle([25.133173, 86.525040], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 155, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Kharagpur<br>rank: 69<br>hazard index: 0.000156")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kharagpur">Kharagpur</a>')

var circle_70 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 154, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Kochi<br>rank: 70<br>hazard index: 0.000154")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_71 = L.circle([8.887951, 76.595501], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 151, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Kollam<br>rank: 71<br>hazard index: 0.000151")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kollam">Kollam</a>')

var circle_72 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 147, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Muzaffarpur<br>rank: 72<br>hazard index: 0.000148")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_73 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 147, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Faridabad<br>rank: 73<br>hazard index: 0.000148")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_74 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Bhusawal<br>rank: 74<br>hazard index: 0.000142")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_75 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 137, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Shahjahanpur<br>rank: 75<br>hazard index: 0.000138")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_76 = L.circle([26.099214, 74.312704], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 137, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Beawar<br>rank: 76<br>hazard index: 0.000137")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Beawar">Beawar</a>')

var circle_77 = L.circle([10.525626, 76.213254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 136, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Thrissur<br>rank: 77<br>hazard index: 0.000137")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thrissur">Thrissur</a>')

var circle_78 = L.circle([28.195647, 76.616518], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 134, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Rewari<br>rank: 78<br>hazard index: 0.000135")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewari">Rewari</a>')

var circle_79 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 129, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Allahabad<br>rank: 79<br>hazard index: 0.000129")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_80 = L.circle([21.365999, 74.284004], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 128, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Nandurbar<br>rank: 80<br>hazard index: 0.000129")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nandurbar">Nandurbar</a>')

var circle_81 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 124, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Bhopal<br>rank: 81<br>hazard index: 0.000124")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_82 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Jabalpur<br>rank: 82<br>hazard index: 0.000122")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_83 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 120, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Varanasi<br>rank: 83<br>hazard index: 0.000121")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_84 = L.circle([22.901200, 88.389900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 120, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Hugli-Chinsurah<br>rank: 84<br>hazard index: 0.000121")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hugli-Chinsurah">Hugli-Chinsurah</a>')

var circle_85 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 118, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Kota<br>rank: 85<br>hazard index: 0.000118")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_86 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 116, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Rohtak<br>rank: 86<br>hazard index: 0.000117")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_87 = L.circle([26.505476, 93.977739], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 113, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Chandan Nagar<br>rank: 87<br>hazard index: 0.000114")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandan_Nagar">Chandan Nagar</a>')

var circle_88 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 106, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Indore<br>rank: 88<br>hazard index: 0.000106")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_89 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 102, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Ludhiana<br>rank: 89<br>hazard index: 0.000103")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_90 = L.circle([21.145629, 80.268387], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 100, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Gondiya<br>rank: 90<br>hazard index: 0.000100")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gondiya">Gondiya</a>')

var circle_91 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 99, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Meerut<br>rank: 91<br>hazard index: 0.000099")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_92 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 97, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Patna<br>rank: 92<br>hazard index: 0.000097")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_93 = L.circle([20.972740, 80.691555], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 86, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Rajnandgaon<br>rank: 93<br>hazard index: 0.000087")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajnandgaon">Rajnandgaon</a>')

var circle_94 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 86, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Coimbatore<br>rank: 94<br>hazard index: 0.000086")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_95 = L.circle([19.250000, 74.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 84, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Ahmadnagar<br>rank: 95<br>hazard index: 0.000085")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmadnagar">Ahmadnagar</a>')

var circle_96 = L.circle([26.588559, 74.861097], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 80, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Kishangarh<br>rank: 96<br>hazard index: 0.000081")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kishangarh">Kishangarh</a>')

var circle_97 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 76, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Saharanpur<br>rank: 97<br>hazard index: 0.000076")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_98 = L.circle([9.500665, 76.412414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Alappuzha<br>rank: 98<br>hazard index: 0.000075")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alappuzha">Alappuzha</a>')

var circle_99 = L.circle([22.500000, 83.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 73, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Raigarh<br>rank: 99<br>hazard index: 0.000073")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raigarh">Raigarh</a>')

var circle_100 = L.circle([24.578721, 73.686257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 72, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Udaipur<br>rank: 100<br>hazard index: 0.000072")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Junagadh">Junagadh</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jamnagar">Jamnagar</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Veraval">Veraval</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gandhidham">Gandhidham</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Porbandar. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>