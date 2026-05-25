---
layout: page
title: "Outbreak location: Baraut"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([29.154148, 77.305954],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Baraut").openTooltip();

var circle_1 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153556, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Jhansi<br>rank: 1<br>hazard index: 0.153557")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_2 = L.circle([29.500882, 77.348383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 89429, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Shamli<br>rank: 2<br>hazard index: 0.089429")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shamli">Shamli</a>')

var circle_3 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28775, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Delhi<br>rank: 3<br>hazard index: 0.028776")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_4 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28762, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Allahabad<br>rank: 4<br>hazard index: 0.028763")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_5 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26490, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Saharanpur<br>rank: 5<br>hazard index: 0.026491")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_6 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9981, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Kanpur<br>rank: 6<br>hazard index: 0.009982")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_7 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5850, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Gwalior<br>rank: 7<br>hazard index: 0.005850")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_8 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5444, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Haridwar<br>rank: 8<br>hazard index: 0.005445")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_9 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2919, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Faridabad<br>rank: 9<br>hazard index: 0.002919")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_10 = L.circle([29.869350, 77.890212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2856, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Roorkee<br>rank: 10<br>hazard index: 0.002857")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a>')

var circle_11 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2720, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Meerut<br>rank: 11<br>hazard index: 0.002721")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_12 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2664, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Bhopal<br>rank: 12<br>hazard index: 0.002665")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_13 = L.circle([24.700385, 78.518668], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2352, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Lalitpur<br>rank: 13<br>hazard index: 0.002353")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lalitpur">Lalitpur</a>')

var circle_14 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2143, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Agra<br>rank: 14<br>hazard index: 0.002144")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_15 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2064, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Lucknow<br>rank: 15<br>hazard index: 0.002064")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_16 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1996, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Chandigarh<br>rank: 16<br>hazard index: 0.001997")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_17 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1850, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Gurgaon<br>rank: 17<br>hazard index: 0.001850")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_18 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1849, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Moradabad<br>rank: 18<br>hazard index: 0.001849")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_19 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1813, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Aligarh<br>rank: 19<br>hazard index: 0.001813")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_20 = L.circle([25.476300, 80.339500], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1665, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Banda<br>rank: 20<br>hazard index: 0.001665")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Banda">Banda</a>')

var circle_21 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1335, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Noida<br>rank: 21<br>hazard index: 0.001335")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_22 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1211, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Loni<br>rank: 22<br>hazard index: 0.001212")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_23 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1202, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Dehradun<br>rank: 23<br>hazard index: 0.001202")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_24 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1199, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Mumbai<br>rank: 24<br>hazard index: 0.001200")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_25 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1020, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Jabalpur<br>rank: 25<br>hazard index: 0.001021")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_26 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1005, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Varanasi<br>rank: 26<br>hazard index: 0.001006")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_27 = L.circle([23.809612, 78.759114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 953, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Sagar<br>rank: 27<br>hazard index: 0.000953")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sagar">Sagar</a>')

var circle_28 = L.circle([30.209087, 76.339872], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 842, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Patiala<br>rank: 28<br>hazard index: 0.000842")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a>')

var circle_29 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 833, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Mathura<br>rank: 29<br>hazard index: 0.000834")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_30 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 815, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Muzaffarnagar<br>rank: 30<br>hazard index: 0.000816")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_31 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 812, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Nagpur<br>rank: 31<br>hazard index: 0.000813")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_32 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 775, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Rohtak<br>rank: 32<br>hazard index: 0.000775")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_33 = L.circle([27.209822, 79.048137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 685, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Mainpuri<br>rank: 33<br>hazard index: 0.000685")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mainpuri">Mainpuri</a>')

var circle_34 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 675, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Rampur<br>rank: 34<br>hazard index: 0.000676")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_35 = L.circle([23.916667, 78.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 665, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Vidisha<br>rank: 35<br>hazard index: 0.000666")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vidisha">Vidisha</a>')

var circle_36 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 660, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Alwar<br>rank: 36<br>hazard index: 0.000660")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_37 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 626, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Hisar<br>rank: 37<br>hazard index: 0.000626")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_38 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 611, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Panipat<br>rank: 38<br>hazard index: 0.000611")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_39 = L.circle([25.375241, 77.828119], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 608, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Shivpuri<br>rank: 39<br>hazard index: 0.000608")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shivpuri">Shivpuri</a>')

var circle_40 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 604, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Firozabad<br>rank: 40<br>hazard index: 0.000604")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_41 = L.circle([29.680327, 76.989625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 596, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Karnal<br>rank: 41<br>hazard index: 0.000596")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karnal">Karnal</a>')

var circle_42 = L.circle([24.500000, 77.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 588, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Guna<br>rank: 42<br>hazard index: 0.000588")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guna">Guna</a>')

var circle_43 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 575, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Sonipat<br>rank: 43<br>hazard index: 0.000576")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_44 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 554, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Ludhiana<br>rank: 44<br>hazard index: 0.000554")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_45 = L.circle([24.935635, 82.647701], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 551, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Mirzapur<br>rank: 45<br>hazard index: 0.000552")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mirzapur">Mirzapur</a>')

var circle_46 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 546, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Hapur<br>rank: 46<br>hazard index: 0.000546")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_47 = L.circle([25.935955, 79.424328], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 521, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Orai<br>rank: 47<br>hazard index: 0.000522")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Orai">Orai</a>')

var circle_48 = L.circle([26.718324, 79.090254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 491, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Etawah<br>rank: 48<br>hazard index: 0.000492")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Etawah">Etawah</a>')

var circle_49 = L.circle([26.166667, 77.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 491, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Morena<br>rank: 49<br>hazard index: 0.000491")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Morena">Morena</a>')

var circle_50 = L.circle([26.500000, 78.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 465, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Bhind<br>rank: 50<br>hazard index: 0.000466")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhind">Bhind</a>')

var circle_51 = L.circle([28.388861, 77.974798], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 463, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Bulandshahr<br>rank: 51<br>hazard index: 0.000463")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bulandshahr">Bulandshahr</a>')

var circle_52 = L.circle([28.618753, 78.550874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 459, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Sambhal<br>rank: 52<br>hazard index: 0.000460")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambhal">Sambhal</a>')

var circle_53 = L.circle([30.129326, 77.245483], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 450, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Jagadhri<br>rank: 53<br>hazard index: 0.000450")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagadhri">Jagadhri</a>')

var circle_54 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 431, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Patna<br>rank: 54<br>hazard index: 0.000431")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_55 = L.circle([25.750000, 78.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 422, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Datia<br>rank: 55<br>hazard index: 0.000423")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Datia">Datia</a>')

var circle_56 = L.circle([28.793170, 76.139128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 410, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Bhiwani<br>rank: 56<br>hazard index: 0.000411")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwani">Bhiwani</a>')

var circle_57 = L.circle([28.923397, 78.488317], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 409, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Amroha<br>rank: 57<br>hazard index: 0.000410")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amroha">Amroha</a>')

var circle_58 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 404, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Pune<br>rank: 58<br>hazard index: 0.000404")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_59 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 393, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Khora<br>rank: 59<br>hazard index: 0.000394")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_60 = L.circle([30.211200, 77.286390], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 391, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Yamunanagar<br>rank: 60<br>hazard index: 0.000391")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a>')

var circle_61 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 384, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Hyderabad<br>rank: 61<br>hazard index: 0.000384")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_62 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 363, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Ambala<br>rank: 62<br>hazard index: 0.000364")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_63 = L.circle([26.638076, 82.059024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 355, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Faizabad<br>rank: 63<br>hazard index: 0.000356")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faizabad">Faizabad</a>')

var circle_64 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 354, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Bahadurgarh<br>rank: 64<br>hazard index: 0.000354")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_65 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 345, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Jind<br>rank: 65<br>hazard index: 0.000345")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_66 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 334, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Chennai<br>rank: 66<br>hazard index: 0.000335")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_67 = L.circle([29.993039, 76.829223], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 322, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Thanesar<br>rank: 67<br>hazard index: 0.000322")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thanesar">Thanesar</a>')

var circle_68 = L.circle([26.653396, 77.624206], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 314, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Dhaulpur<br>rank: 68<br>hazard index: 0.000315")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhaulpur">Dhaulpur</a>')

var circle_69 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 306, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Gorakhpur<br>rank: 69<br>hazard index: 0.000307")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_70 = L.circle([29.822821, 76.378310], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 300, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Kaithal<br>rank: 70<br>hazard index: 0.000301")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kaithal">Kaithal</a>')

var circle_71 = L.circle([28.195647, 76.616518], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 299, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Rewari<br>rank: 71<br>hazard index: 0.000299")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewari">Rewari</a>')

var circle_72 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 295, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Raipur<br>rank: 72<br>hazard index: 0.000295")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_73 = L.circle([25.565691, 80.063489], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 292, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Khanna<br>rank: 73<br>hazard index: 0.000292")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khanna">Khanna</a>')

var circle_74 = L.circle([27.573243, 78.111739], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 285, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Hathras<br>rank: 74<br>hazard index: 0.000286")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hathras">Hathras</a>')

var circle_75 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 284, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Dehri<br>rank: 75<br>hazard index: 0.000285")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')

var circle_76 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 283, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Indore<br>rank: 76<br>hazard index: 0.000284")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_77 = L.circle([25.795593, 82.488341], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 270, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Jaunpur<br>rank: 77<br>hazard index: 0.000271")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaunpur">Jaunpur</a>')

var circle_78 = L.circle([28.826162, 77.541656], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 270, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Modinagar<br>rank: 78<br>hazard index: 0.000271")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Modinagar">Modinagar</a>')

var circle_79 = L.circle([28.176959, 77.373112], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 265, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Palwal<br>rank: 79<br>hazard index: 0.000266")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palwal">Palwal</a>')

var circle_80 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 262, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Bangalore<br>rank: 80<br>hazard index: 0.000263")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_81 = L.circle([29.211757, 78.961731], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 252, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Kashipur<br>rank: 81<br>hazard index: 0.000253")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kashipur">Kashipur</a>')

var circle_82 = L.circle([26.439874, 80.018000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 243, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Akbarpur<br>rank: 82<br>hazard index: 0.000244")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akbarpur">Akbarpur</a>')

var circle_83 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 243, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Satna<br>rank: 83<br>hazard index: 0.000243")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_84 = L.circle([28.488378, 78.735249], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 237, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Chandausi<br>rank: 84<br>hazard index: 0.000237")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandausi">Chandausi</a>')

var circle_85 = L.circle([28.205907, 77.875714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 230, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Khurja<br>rank: 85<br>hazard index: 0.000231")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khurja">Khurja</a>')

var circle_86 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 222, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Jaipur<br>rank: 86<br>hazard index: 0.000222")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_87 = L.circle([26.242511, 82.296169], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 220, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Sultanpur<br>rank: 87<br>hazard index: 0.000221")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sultanpur">Sultanpur</a>')

var circle_88 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 219, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Kolkata<br>rank: 88<br>hazard index: 0.000219")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_89 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 218, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Ahmedabad<br>rank: 89<br>hazard index: 0.000218")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_90 = L.circle([27.036604, 78.651436], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 209, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Shikohabad<br>rank: 90<br>hazard index: 0.000209")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shikohabad">Shikohabad</a>')

var circle_91 = L.circle([27.883846, 78.634890], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 208, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Kasganj<br>rank: 91<br>hazard index: 0.000208")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kasganj">Kasganj</a>')

var circle_92 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 206, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Jalandhar<br>rank: 92<br>hazard index: 0.000207")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_93 = L.circle([27.437194, 79.489129], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 206, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Farrukhabad<br>rank: 93<br>hazard index: 0.000207")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Farrukhabad">Farrukhabad</a>')

var circle_94 = L.circle([23.833962, 80.392456], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 178, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Murwara<br>rank: 94<br>hazard index: 0.000179")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Murwara">Murwara</a>')

var circle_95 = L.circle([25.280733, 83.125128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 172, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Mughal Sarai<br>rank: 95<br>hazard index: 0.000172")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a>')

var circle_96 = L.circle([23.174597, 75.785142], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 168, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Ujjain<br>rank: 96<br>hazard index: 0.000168")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ujjain">Ujjain</a>')

var circle_97 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 147, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Visakhapatnam<br>rank: 97<br>hazard index: 0.000148")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_98 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 139, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Amritsar<br>rank: 98<br>hazard index: 0.000140")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_99 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 136, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Vijayawada<br>rank: 99<br>hazard index: 0.000136")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_100 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 132, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Jalgaon<br>rank: 100<br>hazard index: 0.000133")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Shamli">Shamli</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Baraut. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>