---
layout: page
title: "Outbreak location: Hathras"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([27.573243, 78.111739],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Hathras").openTooltip();

var circle_1 = L.circle([27.883846, 78.634890], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 148855, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Kasganj<br>rank: 1<br>hazard index: 0.148855")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kasganj">Kasganj</a>')

var circle_2 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53551, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Delhi<br>rank: 2<br>hazard index: 0.053551")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_3 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43706, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Mathura<br>rank: 3<br>hazard index: 0.043706")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_4 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18861, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Agra<br>rank: 4<br>hazard index: 0.018861")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_5 = L.circle([27.437194, 79.489129], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17882, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Farrukhabad<br>rank: 5<br>hazard index: 0.017882")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Farrukhabad">Farrukhabad</a>')

var circle_6 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8747, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Bareilly<br>rank: 6<br>hazard index: 0.008748")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_7 = L.circle([27.265212, 77.369126], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8727, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Bharatpur<br>rank: 7<br>hazard index: 0.008728")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharatpur">Bharatpur</a>')

var circle_8 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7833, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Aligarh<br>rank: 8<br>hazard index: 0.007833")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_9 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7170, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Meerut<br>rank: 9<br>hazard index: 0.007171")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_10 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7146, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Kanpur<br>rank: 10<br>hazard index: 0.007147")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_11 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5650, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Faridabad<br>rank: 11<br>hazard index: 0.005651")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_12 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4238, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Gwalior<br>rank: 12<br>hazard index: 0.004238")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_13 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3643, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Firozabad<br>rank: 13<br>hazard index: 0.003644")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_14 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3579, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Moradabad<br>rank: 14<br>hazard index: 0.003580")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_15 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3527, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Gurgaon<br>rank: 15<br>hazard index: 0.003527")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_16 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2825, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Lucknow<br>rank: 16<br>hazard index: 0.002826")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_17 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2584, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Noida<br>rank: 17<br>hazard index: 0.002584")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_18 = L.circle([25.954628, 83.647350], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2434, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Maunath Bhanjan<br>rank: 18<br>hazard index: 0.002435")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Maunath_Bhanjan">Maunath Bhanjan</a>')

var circle_19 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2060, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Loni<br>rank: 19<br>hazard index: 0.002061")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_20 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1652, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Alwar<br>rank: 20<br>hazard index: 0.001652")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_21 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1581, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Allahabad<br>rank: 21<br>hazard index: 0.001582")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_22 = L.circle([26.718324, 79.090254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1549, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Etawah<br>rank: 22<br>hazard index: 0.001550")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Etawah">Etawah</a>')

var circle_23 = L.circle([28.068312, 79.046073], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1522, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Budaun<br>rank: 23<br>hazard index: 0.001523")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Budaun">Budaun</a>')

var circle_24 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1451, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Jaipur<br>rank: 24<br>hazard index: 0.001452")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_25 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1439, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Hapur<br>rank: 25<br>hazard index: 0.001440")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_26 = L.circle([27.338577, 80.097526], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1380, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Hardoi<br>rank: 26<br>hazard index: 0.001381")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hardoi">Hardoi</a>')

var circle_27 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1319, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Shahjahanpur<br>rank: 27<br>hazard index: 0.001319")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_28 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1308, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Rampur<br>rank: 28<br>hazard index: 0.001308")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_29 = L.circle([28.388861, 77.974798], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1220, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Bulandshahr<br>rank: 29<br>hazard index: 0.001221")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bulandshahr">Bulandshahr</a>')

var circle_30 = L.circle([27.209822, 79.048137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1168, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Mainpuri<br>rank: 30<br>hazard index: 0.001168")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mainpuri">Mainpuri</a>')

var circle_31 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1167, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Sonipat<br>rank: 31<br>hazard index: 0.001168")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_32 = L.circle([27.036604, 78.651436], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1068, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Shikohabad<br>rank: 32<br>hazard index: 0.001068")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shikohabad">Shikohabad</a>')

var circle_33 = L.circle([26.732501, 77.036312], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 936, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Hindaun<br>rank: 33<br>hazard index: 0.000936")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hindaun">Hindaun</a>')

var circle_34 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 919, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Mumbai<br>rank: 34<br>hazard index: 0.000919")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_35 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 914, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Jhansi<br>rank: 35<br>hazard index: 0.000915")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_36 = L.circle([28.618753, 78.550874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 890, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Sambhal<br>rank: 36<br>hazard index: 0.000890")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambhal">Sambhal</a>')

var circle_37 = L.circle([29.211757, 78.961731], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 888, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Kashipur<br>rank: 37<br>hazard index: 0.000889")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kashipur">Kashipur</a>')

var circle_38 = L.circle([28.488378, 78.735249], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 832, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Chandausi<br>rank: 38<br>hazard index: 0.000832")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandausi">Chandausi</a>')

var circle_39 = L.circle([26.653396, 77.624206], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 828, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Dhaulpur<br>rank: 39<br>hazard index: 0.000829")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhaulpur">Dhaulpur</a>')

var circle_40 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 828, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Khora<br>rank: 40<br>hazard index: 0.000828")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_41 = L.circle([26.166667, 77.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 806, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Morena<br>rank: 41<br>hazard index: 0.000807")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Morena">Morena</a>')

var circle_42 = L.circle([26.500000, 78.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 793, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Bhind<br>rank: 42<br>hazard index: 0.000794")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhind">Bhind</a>')

var circle_43 = L.circle([28.923397, 78.488317], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 793, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Amroha<br>rank: 43<br>hazard index: 0.000793")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amroha">Amroha</a>')

var circle_44 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 685, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Bahadurgarh<br>rank: 44<br>hazard index: 0.000686")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_45 = L.circle([28.205907, 77.875714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 646, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Khurja<br>rank: 45<br>hazard index: 0.000647")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khurja">Khurja</a>')

var circle_46 = L.circle([28.195647, 76.616518], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 575, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Rewari<br>rank: 46<br>hazard index: 0.000575")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewari">Rewari</a>')

var circle_47 = L.circle([28.969640, 79.379747], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 566, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Rudrapur City<br>rank: 47<br>hazard index: 0.000567")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rudrapur_City">Rudrapur City</a>')

var circle_48 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 563, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Dehri<br>rank: 48<br>hazard index: 0.000564")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')

var circle_49 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 551, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Rohtak<br>rank: 49<br>hazard index: 0.000551")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_50 = L.circle([28.176959, 77.373112], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 539, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Palwal<br>rank: 50<br>hazard index: 0.000540")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palwal">Palwal</a>')

var circle_51 = L.circle([28.826162, 77.541656], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 503, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Modinagar<br>rank: 51<br>hazard index: 0.000504")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Modinagar">Modinagar</a>')

var circle_52 = L.circle([27.733696, 81.477321], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 488, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Bahraich<br>rank: 52<br>hazard index: 0.000489")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahraich">Bahraich</a>')

var circle_53 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 483, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Ludhiana<br>rank: 53<br>hazard index: 0.000484")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_54 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 483, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Bangalore<br>rank: 54<br>hazard index: 0.000484")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_55 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 471, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Varanasi<br>rank: 55<br>hazard index: 0.000471")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_56 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 439, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Patna<br>rank: 56<br>hazard index: 0.000439")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_57 = L.circle([26.022697, 83.028873], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 431, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Azamgarh<br>rank: 57<br>hazard index: 0.000431")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Azamgarh">Azamgarh</a>')

var circle_58 = L.circle([29.154148, 77.305954], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 430, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Baraut<br>rank: 58<br>hazard index: 0.000431")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baraut">Baraut</a>')

var circle_59 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 408, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Kolkata<br>rank: 59<br>hazard index: 0.000408")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_60 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 360, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Saharanpur<br>rank: 60<br>hazard index: 0.000360")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_61 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 347, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Ahmedabad<br>rank: 61<br>hazard index: 0.000347")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_62 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 338, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Hyderabad<br>rank: 62<br>hazard index: 0.000339")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_63 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 317, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Kota<br>rank: 63<br>hazard index: 0.000317")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_64 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 296, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Gorakhpur<br>rank: 64<br>hazard index: 0.000297")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_65 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 295, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Chennai<br>rank: 65<br>hazard index: 0.000295")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_66 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 287, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Pune<br>rank: 66<br>hazard index: 0.000288")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_67 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 285, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Chandigarh<br>rank: 67<br>hazard index: 0.000286")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_68 = L.circle([28.793170, 76.139128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 273, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Bhiwani<br>rank: 68<br>hazard index: 0.000274")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwani">Bhiwani</a>')

var circle_69 = L.circle([25.603508, 83.507454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 250, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Ghazipur<br>rank: 69<br>hazard index: 0.000251")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ghazipur">Ghazipur</a>')

var circle_70 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 244, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Amritsar<br>rank: 70<br>hazard index: 0.000244")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_71 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 233, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Muzaffarnagar<br>rank: 71<br>hazard index: 0.000233")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_72 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 227, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Jamshedpur<br>rank: 72<br>hazard index: 0.000227")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_73 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 224, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Panipat<br>rank: 73<br>hazard index: 0.000225")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_74 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 216, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Jalandhar<br>rank: 74<br>hazard index: 0.000217")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_75 = L.circle([26.250000, 81.250000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 215, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Rae Bareli<br>rank: 75<br>hazard index: 0.000215")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rae_Bareli">Rae Bareli</a>')

var circle_76 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 209, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Dehradun<br>rank: 76<br>hazard index: 0.000209")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_77 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 205, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Hisar<br>rank: 77<br>hazard index: 0.000205")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_78 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 205, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Indore<br>rank: 78<br>hazard index: 0.000205")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_79 = L.circle([26.575504, 80.613762], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 195, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Unnao<br>rank: 79<br>hazard index: 0.000195")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Unnao">Unnao</a>')

var circle_80 = L.circle([25.843539, 80.918004], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 186, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Fatehpur<br>rank: 80<br>hazard index: 0.000187")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Fatehpur">Fatehpur</a>')

var circle_81 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 174, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Jind<br>rank: 81<br>hazard index: 0.000175")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_82 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 171, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Vasco Da Gama<br>rank: 82<br>hazard index: 0.000172")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_83 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 168, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Guwahati<br>rank: 83<br>hazard index: 0.000169")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_84 = L.circle([24.578721, 73.686257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 167, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Udaipur<br>rank: 84<br>hazard index: 0.000167")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a>')

var circle_85 = L.circle([24.917151, 76.696403], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 155, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Baran<br>rank: 85<br>hazard index: 0.000156")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baran">Baran</a>')

var circle_86 = L.circle([29.680327, 76.989625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 154, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Karnal<br>rank: 86<br>hazard index: 0.000155")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karnal">Karnal</a>')

var circle_87 = L.circle([34.074744, 74.820444], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 150, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Srinagar<br>rank: 87<br>hazard index: 0.000151")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srinagar">Srinagar</a>')

var circle_88 = L.circle([26.229141, 76.304533], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 149, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Sawai Madhopur<br>rank: 88<br>hazard index: 0.000149")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sawai_Madhopur">Sawai Madhopur</a>')

var circle_89 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 149, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Bhopal<br>rank: 89<br>hazard index: 0.000149")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_90 = L.circle([28.495208, 80.107541], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 146, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Pilibhit<br>rank: 90<br>hazard index: 0.000147")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pilibhit">Pilibhit</a>')

var circle_91 = L.circle([19.794750, 75.077922], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 145, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Gangapur<br>rank: 91<br>hazard index: 0.000146")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gangapur">Gangapur</a>')

var circle_92 = L.circle([29.214460, 79.527918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Haldwani<br>rank: 92<br>hazard index: 0.000142")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haldwani">Haldwani</a>')

var circle_93 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 140, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Nagpur<br>rank: 93<br>hazard index: 0.000140")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_94 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 136, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Bhubaneswar<br>rank: 94<br>hazard index: 0.000136")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_95 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 132, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Jammu<br>rank: 95<br>hazard index: 0.000133")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_96 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 124, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Ranchi<br>rank: 96<br>hazard index: 0.000124")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_97 = L.circle([25.877933, 84.119959], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 122, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Ballia<br>rank: 97<br>hazard index: 0.000123")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ballia">Ballia</a>')

var circle_98 = L.circle([27.504639, 80.829466], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Sitapur<br>rank: 98<br>hazard index: 0.000122")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sitapur">Sitapur</a>')

var circle_99 = L.circle([24.935635, 82.647701], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 119, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Mirzapur<br>rank: 99<br>hazard index: 0.000120")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mirzapur">Mirzapur</a>')

var circle_100 = L.circle([25.512719, 86.090571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 116, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Begusarai<br>rank: 100<br>hazard index: 0.000116")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Begusarai">Begusarai</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Kasganj">Kasganj</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Farrukhabad">Farrukhabad</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bharatpur">Bharatpur</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Hathras. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>