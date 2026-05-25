---
layout: page
title: "Outbreak location: Delhi"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([28.651718, 77.221939],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Delhi").openTooltip();

var circle_1 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19053, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Kanpur<br>rank: 1<br>hazard index: 0.019053")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_2 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17168, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Mumbai<br>rank: 2<br>hazard index: 0.017169")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_3 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14136, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Gurgaon<br>rank: 3<br>hazard index: 0.014136")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_4 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13087, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Lucknow<br>rank: 4<br>hazard index: 0.013088")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_5 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12976, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Faridabad<br>rank: 5<br>hazard index: 0.012977")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_6 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10684, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Jhansi<br>rank: 6<br>hazard index: 0.010684")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_7 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10289, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Rohtak<br>rank: 7<br>hazard index: 0.010290")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_8 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9037, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Ludhiana<br>rank: 8<br>hazard index: 0.009038")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_9 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9034, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Bangalore<br>rank: 9<br>hazard index: 0.009035")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_10 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9017, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Moradabad<br>rank: 10<br>hazard index: 0.009017")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_11 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8708, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Meerut<br>rank: 11<br>hazard index: 0.008709")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_12 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7623, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Kolkata<br>rank: 12<br>hazard index: 0.007623")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_13 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6725, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Saharanpur<br>rank: 13<br>hazard index: 0.006725")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_14 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6489, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Patna<br>rank: 14<br>hazard index: 0.006490")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_15 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6488, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Ahmedabad<br>rank: 15<br>hazard index: 0.006488")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_16 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6325, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Agra<br>rank: 16<br>hazard index: 0.006325")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_17 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6321, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Hyderabad<br>rank: 17<br>hazard index: 0.006322")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_18 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6137, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Jaipur<br>rank: 18<br>hazard index: 0.006137")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_19 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5788, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Aligarh<br>rank: 19<br>hazard index: 0.005788")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_20 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5745, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Sonipat<br>rank: 20<br>hazard index: 0.005745")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_21 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5709, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Loni<br>rank: 21<br>hazard index: 0.005709")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_22 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5509, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Chennai<br>rank: 22<br>hazard index: 0.005510")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_23 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5376, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Pune<br>rank: 23<br>hazard index: 0.005377")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_24 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5331, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Chandigarh<br>rank: 24<br>hazard index: 0.005332")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_25 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4616, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Allahabad<br>rank: 25<br>hazard index: 0.004617")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_26 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4564, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Amritsar<br>rank: 26<br>hazard index: 0.004564")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_27 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4535, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Bahadurgarh<br>rank: 27<br>hazard index: 0.004535")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_28 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4201, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Panipat<br>rank: 28<br>hazard index: 0.004201")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_29 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4048, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Jalandhar<br>rank: 29<br>hazard index: 0.004049")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_30 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3840, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Khora<br>rank: 30<br>hazard index: 0.003841")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_31 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3346, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Varanasi<br>rank: 31<br>hazard index: 0.003346")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_32 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3259, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Jind<br>rank: 32<br>hazard index: 0.003259")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_33 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3228, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Bareilly<br>rank: 33<br>hazard index: 0.003229")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_34 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3207, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Vasco Da Gama<br>rank: 34<br>hazard index: 0.003208")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_35 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3149, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Guwahati<br>rank: 35<br>hazard index: 0.003150")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_36 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3109, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Muzaffarnagar<br>rank: 36<br>hazard index: 0.003110")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_37 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2938, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Hapur<br>rank: 37<br>hazard index: 0.002939")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_38 = L.circle([29.680327, 76.989625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2889, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Karnal<br>rank: 38<br>hazard index: 0.002890")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karnal">Karnal</a>')

var circle_39 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2846, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Noida<br>rank: 39<br>hazard index: 0.002846")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_40 = L.circle([34.074744, 74.820444], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2810, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Srinagar<br>rank: 40<br>hazard index: 0.002811")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srinagar">Srinagar</a>')

var circle_41 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2788, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Bhopal<br>rank: 41<br>hazard index: 0.002788")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_42 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2645, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Rampur<br>rank: 42<br>hazard index: 0.002646")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_43 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2616, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Nagpur<br>rank: 43<br>hazard index: 0.002616")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_44 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2592, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Firozabad<br>rank: 44<br>hazard index: 0.002592")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_45 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2546, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Bhubaneswar<br>rank: 45<br>hazard index: 0.002546")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_46 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2522, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Dehradun<br>rank: 46<br>hazard index: 0.002523")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_47 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2479, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Jammu<br>rank: 47<br>hazard index: 0.002480")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_48 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2426, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Mathura<br>rank: 48<br>hazard index: 0.002427")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_49 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2316, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Ranchi<br>rank: 49<br>hazard index: 0.002317")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_50 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2144, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Haridwar<br>rank: 50<br>hazard index: 0.002144")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_51 = L.circle([30.179115, 75.047102], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2050, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Bathinda<br>rank: 51<br>hazard index: 0.002051")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a>')

var circle_52 = L.circle([26.698885, 88.320030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2042, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Bagdogra<br>rank: 52<br>hazard index: 0.002043")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagdogra">Bagdogra</a>')

var circle_53 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1931, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Indore<br>rank: 53<br>hazard index: 0.001931")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_54 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1931, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Surat<br>rank: 54<br>hazard index: 0.001931")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_55 = L.circle([28.195647, 76.616518], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1924, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Rewari<br>rank: 55<br>hazard index: 0.001924")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewari">Rewari</a>')

var circle_56 = L.circle([28.793170, 76.139128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1900, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Bhiwani<br>rank: 56<br>hazard index: 0.001901")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwani">Bhiwani</a>')

var circle_57 = L.circle([30.209087, 76.339872], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1853, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Patiala<br>rank: 57<br>hazard index: 0.001853")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a>')

var circle_58 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1799, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Hisar<br>rank: 58<br>hazard index: 0.001800")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_59 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1719, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Gwalior<br>rank: 59<br>hazard index: 0.001720")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_60 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1669, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Kochi<br>rank: 60<br>hazard index: 0.001669")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_61 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1649, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Ambala<br>rank: 61<br>hazard index: 0.001649")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_62 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1603, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Alwar<br>rank: 62<br>hazard index: 0.001603")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_63 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1537, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Kota<br>rank: 63<br>hazard index: 0.001538")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_64 = L.circle([28.923397, 78.488317], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1517, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Amroha<br>rank: 64<br>hazard index: 0.001517")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amroha">Amroha</a>')

var circle_65 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1490, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Jodhpur<br>rank: 65<br>hazard index: 0.001491")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_66 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1455, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Raipur<br>rank: 66<br>hazard index: 0.001456")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_67 = L.circle([29.500882, 77.348383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1352, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Shamli<br>rank: 67<br>hazard index: 0.001352")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shamli">Shamli</a>')

var circle_68 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1330, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Vadodara<br>rank: 68<br>hazard index: 0.001331")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_69 = L.circle([27.265212, 77.369126], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1300, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Bharatpur<br>rank: 69<br>hazard index: 0.001300")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharatpur">Bharatpur</a>')

var circle_70 = L.circle([29.154148, 77.305954], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1286, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Baraut<br>rank: 70<br>hazard index: 0.001286")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baraut">Baraut</a>')

var circle_71 = L.circle([30.129326, 77.245483], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1205, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Jagadhri<br>rank: 71<br>hazard index: 0.001206")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagadhri">Jagadhri</a>')

var circle_72 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1147, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Gorakhpur<br>rank: 72<br>hazard index: 0.001148")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_73 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1141, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Bikaner<br>rank: 73<br>hazard index: 0.001141")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_74 = L.circle([24.578721, 73.686257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1113, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Udaipur<br>rank: 74<br>hazard index: 0.001113")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a>')

var circle_75 = L.circle([28.176959, 77.373112], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1057, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Palwal<br>rank: 75<br>hazard index: 0.001058")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palwal">Palwal</a>')

var circle_76 = L.circle([29.869350, 77.890212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1030, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Roorkee<br>rank: 76<br>hazard index: 0.001030")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a>')

var circle_77 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 960, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Thane<br>rank: 77<br>hazard index: 0.000960")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_78 = L.circle([28.826162, 77.541656], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 930, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Modinagar<br>rank: 78<br>hazard index: 0.000930")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Modinagar">Modinagar</a>')

var circle_79 = L.circle([8.576971, 77.050125], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 870, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Thiruvananthapuram<br>rank: 79<br>hazard index: 0.000871")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thiruvananthapuram">Thiruvananthapuram</a>')

var circle_80 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 858, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Visakhapatnam<br>rank: 80<br>hazard index: 0.000858")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_81 = L.circle([28.388861, 77.974798], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 828, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Bulandshahr<br>rank: 81<br>hazard index: 0.000829")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bulandshahr">Bulandshahr</a>')

var circle_82 = L.circle([26.469100, 74.639000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 814, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Ajmer<br>rank: 82<br>hazard index: 0.000815")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a>')

var circle_83 = L.circle([28.618753, 78.550874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 804, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Sambhal<br>rank: 83<br>hazard index: 0.000804")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambhal">Sambhal</a>')

var circle_84 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 772, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Coimbatore<br>rank: 84<br>hazard index: 0.000773")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_85 = L.circle([30.211200, 77.286390], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 753, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Yamunanagar<br>rank: 85<br>hazard index: 0.000754")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a>')

var circle_86 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 722, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Shahjahanpur<br>rank: 86<br>hazard index: 0.000723")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_87 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 666, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Vijayawada<br>rank: 87<br>hazard index: 0.000666")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_88 = L.circle([24.796436, 85.007956], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 665, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Gaya<br>rank: 88<br>hazard index: 0.000665")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a>')

var circle_89 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 648, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Dehri<br>rank: 89<br>hazard index: 0.000649")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')

var circle_90 = L.circle([28.068312, 79.046073], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 645, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Budaun<br>rank: 90<br>hazard index: 0.000645")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Budaun">Budaun</a>')

var circle_91 = L.circle([28.079690, 75.541768], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 628, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Jhunjhunun<br>rank: 91<br>hazard index: 0.000629")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhunjhunun">Jhunjhunun</a>')

var circle_92 = L.circle([27.573243, 78.111739], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 624, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Hathras<br>rank: 92<br>hazard index: 0.000625")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hathras">Hathras</a>')

var circle_93 = L.circle([29.993039, 76.829223], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 620, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Thanesar<br>rank: 93<br>hazard index: 0.000621")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thanesar">Thanesar</a>')

var circle_94 = L.circle([29.211757, 78.961731], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 596, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Kashipur<br>rank: 94<br>hazard index: 0.000597")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kashipur">Kashipur</a>')

var circle_95 = L.circle([29.822821, 76.378310], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 583, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Kaithal<br>rank: 95<br>hazard index: 0.000584")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kaithal">Kaithal</a>')

var circle_96 = L.circle([28.205907, 77.875714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 559, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Khurja<br>rank: 96<br>hazard index: 0.000560")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khurja">Khurja</a>')

var circle_97 = L.circle([28.488378, 78.735249], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 548, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Chandausi<br>rank: 97<br>hazard index: 0.000548")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandausi">Chandausi</a>')

var circle_98 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 527, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Jabalpur<br>rank: 98<br>hazard index: 0.000527")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_99 = L.circle([26.716413, 88.430992], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 485, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Siliguri<br>rank: 99<br>hazard index: 0.000486")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siliguri">Siliguri</a>')

var circle_100 = L.circle([24.800609, 93.937000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 441, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Imphal<br>rank: 100<br>hazard index: 0.000441")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Imphal">Imphal</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Delhi. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>