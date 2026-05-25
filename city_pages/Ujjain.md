---
layout: page
title: "Outbreak location: Ujjain"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([23.174597, 75.785142],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Ujjain").openTooltip();

var circle_1 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 103603, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Indore<br>rank: 1<br>hazard index: 0.103603")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_2 = L.circle([23.587548, 75.675679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 80801, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Nagda<br>rank: 2<br>hazard index: 0.080801")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagda">Nagda</a>')

var circle_3 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 67768, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Bhopal<br>rank: 3<br>hazard index: 0.067769")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_4 = L.circle([23.480592, 74.917790], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18039, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Ratlam<br>rank: 4<br>hazard index: 0.018039")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ratlam">Ratlam</a>')

var circle_5 = L.circle([23.000000, 76.166667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14690, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Dewas<br>rank: 5<br>hazard index: 0.014690")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dewas">Dewas</a>')

var circle_6 = L.circle([25.375241, 77.828119], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8836, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Shivpuri<br>rank: 6<br>hazard index: 0.008836")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shivpuri">Shivpuri</a>')

var circle_7 = L.circle([24.500000, 77.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6808, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Guna<br>rank: 7<br>hazard index: 0.006808")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guna">Guna</a>')

var circle_8 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4656, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Jaipur<br>rank: 8<br>hazard index: 0.004656")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_9 = L.circle([24.462465, 74.850114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4629, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Nimach<br>rank: 9<br>hazard index: 0.004629")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nimach">Nimach</a>')

var circle_10 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4478, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Gwalior<br>rank: 10<br>hazard index: 0.004479")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_11 = L.circle([23.916667, 78.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4346, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Vidisha<br>rank: 11<br>hazard index: 0.004347")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vidisha">Vidisha</a>')

var circle_12 = L.circle([24.500000, 74.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4305, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Chittaurgarh<br>rank: 12<br>hazard index: 0.004306")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chittaurgarh">Chittaurgarh</a>')

var circle_13 = L.circle([23.115688, 77.066239], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4200, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Sehore<br>rank: 13<br>hazard index: 0.004201")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sehore">Sehore</a>')

var circle_14 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4076, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Ahmedabad<br>rank: 14<br>hazard index: 0.004077")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_15 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3650, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Delhi<br>rank: 15<br>hazard index: 0.003651")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_16 = L.circle([24.700385, 78.518668], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3490, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Lalitpur<br>rank: 16<br>hazard index: 0.003490")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lalitpur">Lalitpur</a>')

var circle_17 = L.circle([24.265131, 75.387182], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3455, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Mandsaur<br>rank: 17<br>hazard index: 0.003456")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mandsaur">Mandsaur</a>')

var circle_18 = L.circle([21.977864, 76.568828], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2824, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Khandwa<br>rank: 18<br>hazard index: 0.002824")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khandwa">Khandwa</a>')

var circle_19 = L.circle([21.818774, 75.606458], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2770, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Khargone<br>rank: 19<br>hazard index: 0.002770")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khargone">Khargone</a>')

var circle_20 = L.circle([24.578721, 73.686257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2305, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Udaipur<br>rank: 20<br>hazard index: 0.002305")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a>')

var circle_21 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2225, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Jhansi<br>rank: 21<br>hazard index: 0.002226")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_22 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1803, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Jabalpur<br>rank: 22<br>hazard index: 0.001803")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_23 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1575, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Mumbai<br>rank: 23<br>hazard index: 0.001576")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_24 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1073, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Kota<br>rank: 24<br>hazard index: 0.001073")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_25 = L.circle([23.493079, 74.348402], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 854, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Banswara<br>rank: 25<br>hazard index: 0.000854")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Banswara">Banswara</a>')

var circle_26 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 753, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Nagpur<br>rank: 26<br>hazard index: 0.000754")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_27 = L.circle([23.809612, 78.759114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 683, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Sagar<br>rank: 27<br>hazard index: 0.000683")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sagar">Sagar</a>')

var circle_28 = L.circle([22.600150, 77.926645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 668, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Hoshangabad<br>rank: 28<br>hazard index: 0.000668")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshangabad">Hoshangabad</a>')

var circle_29 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 621, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Bangalore<br>rank: 29<br>hazard index: 0.000622")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_30 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 517, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Surat<br>rank: 30<br>hazard index: 0.000518")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_31 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 488, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Satna<br>rank: 31<br>hazard index: 0.000488")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_32 = L.circle([23.833962, 80.392456], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 438, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Murwara<br>rank: 32<br>hazard index: 0.000439")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Murwara">Murwara</a>')

var circle_33 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 433, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Bhusawal<br>rank: 33<br>hazard index: 0.000433")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_34 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 430, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Hyderabad<br>rank: 34<br>hazard index: 0.000430")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_35 = L.circle([22.139831, 78.809645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 424, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Chhindwara<br>rank: 35<br>hazard index: 0.000425")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chhindwara">Chhindwara</a>')

var circle_36 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 409, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Agra<br>rank: 36<br>hazard index: 0.000409")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_37 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 397, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Jodhpur<br>rank: 37<br>hazard index: 0.000398")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_38 = L.circle([24.759267, 81.655000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 396, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Rewa<br>rank: 38<br>hazard index: 0.000396")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewa">Rewa</a>')

var circle_39 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 375, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Faridabad<br>rank: 39<br>hazard index: 0.000376")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_40 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 359, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Raipur<br>rank: 40<br>hazard index: 0.000359")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_41 = L.circle([21.879616, 77.875681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 353, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Betul<br>rank: 41<br>hazard index: 0.000353")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Betul">Betul</a>')

var circle_42 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 338, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Bilaspur<br>rank: 42<br>hazard index: 0.000338")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_43 = L.circle([26.469100, 74.639000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 331, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Ajmer<br>rank: 43<br>hazard index: 0.000332")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a>')

var circle_44 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 296, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Meerut<br>rank: 44<br>hazard index: 0.000297")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_45 = L.circle([25.488773, 74.699613], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 295, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Bhilwara<br>rank: 45<br>hazard index: 0.000296")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhilwara">Bhilwara</a>')

var circle_46 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 292, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Kolkata<br>rank: 46<br>hazard index: 0.000293")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_47 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 276, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Pune<br>rank: 47<br>hazard index: 0.000277")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_48 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 262, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Vasco Da Gama<br>rank: 48<br>hazard index: 0.000263")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_49 = L.circle([27.437194, 79.489129], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 257, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Farrukhabad<br>rank: 49<br>hazard index: 0.000257")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Farrukhabad">Farrukhabad</a>')

var circle_50 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 247, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Vadodara<br>rank: 50<br>hazard index: 0.000247")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_51 = L.circle([23.750000, 79.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 247, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Damoh<br>rank: 51<br>hazard index: 0.000247")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Damoh">Damoh</a>')

var circle_52 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 241, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Lucknow<br>rank: 52<br>hazard index: 0.000241")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_53 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 237, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Kanpur<br>rank: 53<br>hazard index: 0.000237")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_54 = L.circle([26.500000, 78.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 233, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Bhind<br>rank: 54<br>hazard index: 0.000233")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhind">Bhind</a>')

var circle_55 = L.circle([22.305199, 70.802834], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 226, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Rajkot<br>rank: 55<br>hazard index: 0.000227")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a>')

var circle_56 = L.circle([24.917151, 76.696403], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 223, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Baran<br>rank: 56<br>hazard index: 0.000224")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baran">Baran</a>')

var circle_57 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 171, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Chennai<br>rank: 57<br>hazard index: 0.000171")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_58 = L.circle([26.269721, 82.994425], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 160, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Burhanpur<br>rank: 58<br>hazard index: 0.000160")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Burhanpur">Burhanpur</a>')

var circle_59 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 159, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Saharanpur<br>rank: 59<br>hazard index: 0.000159")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_60 = L.circle([22.689507, 72.871520], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 140, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Nadiad<br>rank: 60<br>hazard index: 0.000140")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nadiad">Nadiad</a>')

var circle_61 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 131, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Dehradun<br>rank: 61<br>hazard index: 0.000131")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_62 = L.circle([22.558499, 72.962563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 128, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Anand<br>rank: 62<br>hazard index: 0.000129")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Anand">Anand</a>')

var circle_63 = L.circle([26.229141, 76.304533], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 124, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Sawai Madhopur<br>rank: 63<br>hazard index: 0.000124")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sawai_Madhopur">Sawai Madhopur</a>')

var circle_64 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 123, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Nanded Waghala<br>rank: 64<br>hazard index: 0.000123")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_65 = L.circle([22.275879, 79.721045], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Seoni<br>rank: 65<br>hazard index: 0.000121")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Seoni">Seoni</a>')

var circle_66 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 117, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Mathura<br>rank: 66<br>hazard index: 0.000118")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_67 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 109, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Varanasi<br>rank: 67<br>hazard index: 0.000109")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_68 = L.circle([22.778500, 73.624516], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 101, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Godhra<br>rank: 68<br>hazard index: 0.000102")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Godhra">Godhra</a>')

var circle_69 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 93, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Jalgaon<br>rank: 69<br>hazard index: 0.000093")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_70 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 91, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Patna<br>rank: 70<br>hazard index: 0.000092")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_71 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 90, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Allahabad<br>rank: 71<br>hazard index: 0.000090")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_72 = L.circle([21.199035, 81.397955], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 89, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Durg<br>rank: 72<br>hazard index: 0.000090")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durg">Durg</a>')

var circle_73 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 88, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Muzaffarnagar<br>rank: 73<br>hazard index: 0.000089")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_74 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 88, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Thane<br>rank: 74<br>hazard index: 0.000088")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_75 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 87, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Bikaner<br>rank: 75<br>hazard index: 0.000087")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_76 = L.circle([26.122147, 75.663754], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 83, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Tonk<br>rank: 76<br>hazard index: 0.000084")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tonk">Tonk</a>')

var circle_77 = L.circle([26.588559, 74.861097], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 78, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Kishangarh<br>rank: 77<br>hazard index: 0.000078")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kishangarh">Kishangarh</a>')

var circle_78 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 70, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Ludhiana<br>rank: 78<br>hazard index: 0.000070")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_79 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Alwar<br>rank: 79<br>hazard index: 0.000070")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_80 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 67, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Akola<br>rank: 80<br>hazard index: 0.000068")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')

var circle_81 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 64, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Vijayawada<br>rank: 81<br>hazard index: 0.000064")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_82 = L.circle([23.666667, 72.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Mahesana<br>rank: 82<br>hazard index: 0.000062")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mahesana">Mahesana</a>')

var circle_83 = L.circle([18.627929, 73.800983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Pimpri Chinchwad<br>rank: 83<br>hazard index: 0.000060")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pimpri_Chinchwad">Pimpri Chinchwad</a>')

var circle_84 = L.circle([25.604091, 73.415609], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 54, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Pali<br>rank: 84<br>hazard index: 0.000054")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pali">Pali</a>')

var circle_85 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Bhubaneswar<br>rank: 85<br>hazard index: 0.000054")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_86 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Gurgaon<br>rank: 86<br>hazard index: 0.000052")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_87 = L.circle([19.439885, 72.880383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Vasai<br>rank: 87<br>hazard index: 0.000051")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a>')

var circle_88 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Haridwar<br>rank: 88<br>hazard index: 0.000051")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_89 = L.circle([27.662826, 75.027926], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Sikar<br>rank: 89<br>hazard index: 0.000050")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sikar">Sikar</a>')

var circle_90 = L.circle([21.517410, 70.464275], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Junagadh<br>rank: 90<br>hazard index: 0.000050")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Junagadh">Junagadh</a>')

var circle_91 = L.circle([26.166667, 77.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Morena<br>rank: 91<br>hazard index: 0.000049")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Morena">Morena</a>')

var circle_92 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 46, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Visakhapatnam<br>rank: 92<br>hazard index: 0.000046")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_93 = L.circle([23.223288, 72.649227], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Gandhinagar<br>rank: 93<br>hazard index: 0.000044")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhinagar">Gandhinagar</a>')

var circle_94 = L.circle([21.771884, 72.141645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Bhavnagar<br>rank: 94<br>hazard index: 0.000043")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhavnagar">Bhavnagar</a>')

var circle_95 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Khora<br>rank: 95<br>hazard index: 0.000043")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_96 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Dhanbad<br>rank: 96<br>hazard index: 0.000041")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_97 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Nashik<br>rank: 97<br>hazard index: 0.000041")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_98 = L.circle([23.071874, 70.131715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 39, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Gandhidham<br>rank: 98<br>hazard index: 0.000039")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhidham">Gandhidham</a>')

var circle_99 = L.circle([22.610318, 73.461706], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Kalol<br>rank: 99<br>hazard index: 0.000039")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kalol">Kalol</a>')

var circle_100 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 37, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Rohtak<br>rank: 100<br>hazard index: 0.000038")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Nagda">Nagda</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ratlam">Ratlam</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Dewas">Dewas</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Shivpuri">Shivpuri</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Guna">Guna</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Nimach">Nimach</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Ujjain. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>