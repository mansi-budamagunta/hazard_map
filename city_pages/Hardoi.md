---
layout: page
title: "Outbreak location: Hardoi"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([27.338577, 80.097526],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Hardoi").openTooltip();

var circle_1 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 101526, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Shahjahanpur<br>rank: 1<br>hazard index: 0.101526")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_2 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 73157, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Lucknow<br>rank: 2<br>hazard index: 0.073157")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_3 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42046, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Bareilly<br>rank: 3<br>hazard index: 0.042046")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_4 = L.circle([27.985060, 80.753845], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40610, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Lakhimpur<br>rank: 4<br>hazard index: 0.040611")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lakhimpur">Lakhimpur</a>')

var circle_5 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28476, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Kanpur<br>rank: 5<br>hazard index: 0.028477")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_6 = L.circle([27.504639, 80.829466], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9352, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Sitapur<br>rank: 6<br>hazard index: 0.009353")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sitapur">Sitapur</a>')

var circle_7 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7534, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Gorakhpur<br>rank: 7<br>hazard index: 0.007534")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_8 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6834, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Rampur<br>rank: 8<br>hazard index: 0.006834")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_9 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6075, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Firozabad<br>rank: 9<br>hazard index: 0.006075")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_10 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5987, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Moradabad<br>rank: 10<br>hazard index: 0.005988")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_11 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3934, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Delhi<br>rank: 11<br>hazard index: 0.003934")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_12 = L.circle([26.250000, 81.250000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3067, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Rae Bareli<br>rank: 12<br>hazard index: 0.003068")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rae_Bareli">Rae Bareli</a>')

var circle_13 = L.circle([27.437194, 79.489129], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2774, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Farrukhabad<br>rank: 13<br>hazard index: 0.002775")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Farrukhabad">Farrukhabad</a>')

var circle_14 = L.circle([26.718324, 79.090254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2583, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Etawah<br>rank: 14<br>hazard index: 0.002584")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Etawah">Etawah</a>')

var circle_15 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2439, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Varanasi<br>rank: 15<br>hazard index: 0.002440")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_16 = L.circle([28.969640, 79.379747], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2258, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Rudrapur City<br>rank: 16<br>hazard index: 0.002259")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rudrapur_City">Rudrapur City</a>')

var circle_17 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2165, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Allahabad<br>rank: 17<br>hazard index: 0.002166")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_18 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2101, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Kolkata<br>rank: 18<br>hazard index: 0.002101")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_19 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2081, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Saharanpur<br>rank: 19<br>hazard index: 0.002081")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_20 = L.circle([28.495208, 80.107541], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2018, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Pilibhit<br>rank: 20<br>hazard index: 0.002019")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pilibhit">Pilibhit</a>')

var circle_21 = L.circle([26.500000, 78.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1985, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Bhind<br>rank: 21<br>hazard index: 0.001986")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhind">Bhind</a>')

var circle_22 = L.circle([25.843539, 80.918004], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1950, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Fatehpur<br>rank: 22<br>hazard index: 0.001950")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Fatehpur">Fatehpur</a>')

var circle_23 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1928, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Ludhiana<br>rank: 23<br>hazard index: 0.001928")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_24 = L.circle([25.935955, 79.424328], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1883, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Orai<br>rank: 24<br>hazard index: 0.001883")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Orai">Orai</a>')

var circle_25 = L.circle([27.733696, 81.477321], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1873, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Bahraich<br>rank: 25<br>hazard index: 0.001874")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahraich">Bahraich</a>')

var circle_26 = L.circle([26.575504, 80.613762], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1838, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Unnao<br>rank: 26<br>hazard index: 0.001839")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Unnao">Unnao</a>')

var circle_27 = L.circle([28.068312, 79.046073], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1602, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Budaun<br>rank: 27<br>hazard index: 0.001602")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Budaun">Budaun</a>')

var circle_28 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1446, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Jhansi<br>rank: 28<br>hazard index: 0.001447")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_29 = L.circle([25.565691, 80.063489], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1400, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Khanna<br>rank: 29<br>hazard index: 0.001401")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khanna">Khanna</a>')

var circle_30 = L.circle([27.109667, 81.918329], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1400, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Gonda<br>rank: 30<br>hazard index: 0.001400")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gonda">Gonda</a>')

var circle_31 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1399, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Dehradun<br>rank: 31<br>hazard index: 0.001399")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_32 = L.circle([27.573243, 78.111739], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1383, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Hathras<br>rank: 32<br>hazard index: 0.001384")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hathras">Hathras</a>')

var circle_33 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1344, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Agra<br>rank: 33<br>hazard index: 0.001344")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_34 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1219, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Chandigarh<br>rank: 34<br>hazard index: 0.001220")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_35 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1015, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Meerut<br>rank: 35<br>hazard index: 0.001016")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_36 = L.circle([29.214460, 79.527918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 931, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Haldwani<br>rank: 36<br>hazard index: 0.000932")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haldwani">Haldwani</a>')

var circle_37 = L.circle([26.638076, 82.059024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 900, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Faizabad<br>rank: 37<br>hazard index: 0.000900")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faizabad">Faizabad</a>')

var circle_38 = L.circle([26.439874, 80.018000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 873, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Akbarpur<br>rank: 38<br>hazard index: 0.000873")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akbarpur">Akbarpur</a>')

var circle_39 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 812, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Aligarh<br>rank: 39<br>hazard index: 0.000812")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_40 = L.circle([28.923397, 78.488317], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 786, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Amroha<br>rank: 40<br>hazard index: 0.000786")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amroha">Amroha</a>')

var circle_41 = L.circle([26.242511, 82.296169], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 709, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Sultanpur<br>rank: 41<br>hazard index: 0.000709")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sultanpur">Sultanpur</a>')

var circle_42 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 708, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Jalandhar<br>rank: 42<br>hazard index: 0.000709")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_43 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 686, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Haridwar<br>rank: 43<br>hazard index: 0.000686")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_44 = L.circle([27.036604, 78.651436], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 661, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Shikohabad<br>rank: 44<br>hazard index: 0.000661")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shikohabad">Shikohabad</a>')

var circle_45 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 598, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Mumbai<br>rank: 45<br>hazard index: 0.000599")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_46 = L.circle([28.488378, 78.735249], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 565, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Chandausi<br>rank: 46<br>hazard index: 0.000566")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandausi">Chandausi</a>')

var circle_47 = L.circle([27.209822, 79.048137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 565, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Mainpuri<br>rank: 47<br>hazard index: 0.000565")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mainpuri">Mainpuri</a>')

var circle_48 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 553, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Amritsar<br>rank: 48<br>hazard index: 0.000553")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_49 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 547, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Chapra<br>rank: 49<br>hazard index: 0.000548")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_50 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 445, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Dhanbad<br>rank: 50<br>hazard index: 0.000445")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_51 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 414, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Patna<br>rank: 51<br>hazard index: 0.000414")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_52 = L.circle([29.211757, 78.961731], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 396, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Kashipur<br>rank: 52<br>hazard index: 0.000396")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kashipur">Kashipur</a>')

var circle_53 = L.circle([27.883846, 78.634890], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 388, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Kasganj<br>rank: 53<br>hazard index: 0.000388")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kasganj">Kasganj</a>')

var circle_54 = L.circle([26.131004, 84.391257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 365, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Siwan<br>rank: 54<br>hazard index: 0.000365")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siwan">Siwan</a>')

var circle_55 = L.circle([26.423847, 83.762732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 351, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Deoria<br>rank: 55<br>hazard index: 0.000352")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoria">Deoria</a>')

var circle_56 = L.circle([30.129326, 77.245483], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 350, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Jagadhri<br>rank: 56<br>hazard index: 0.000350")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagadhri">Jagadhri</a>')

var circle_57 = L.circle([26.724789, 82.793269], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 337, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Basti<br>rank: 57<br>hazard index: 0.000338")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Basti">Basti</a>')

var circle_58 = L.circle([25.476300, 80.339500], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 315, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Banda<br>rank: 58<br>hazard index: 0.000315")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Banda">Banda</a>')

var circle_59 = L.circle([25.795593, 82.488341], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 313, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Jaunpur<br>rank: 59<br>hazard index: 0.000314")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaunpur">Jaunpur</a>')

var circle_60 = L.circle([27.059011, 84.206464], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 306, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Bagaha<br>rank: 60<br>hazard index: 0.000307")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagaha">Bagaha</a>')

var circle_61 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 301, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Muzaffarpur<br>rank: 61<br>hazard index: 0.000302")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_62 = L.circle([29.869350, 77.890212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 298, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Roorkee<br>rank: 62<br>hazard index: 0.000298")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a>')

var circle_63 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 281, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Hapur<br>rank: 63<br>hazard index: 0.000281")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_64 = L.circle([30.211200, 77.286390], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 280, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Yamunanagar<br>rank: 64<br>hazard index: 0.000281")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a>')

var circle_65 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 273, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Bangalore<br>rank: 65<br>hazard index: 0.000273")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_66 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 256, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Ambala<br>rank: 66<br>hazard index: 0.000257")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_67 = L.circle([23.535048, 87.338043], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 241, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Durgapur<br>rank: 67<br>hazard index: 0.000242")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a>')

var circle_68 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 240, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Asansol<br>rank: 68<br>hazard index: 0.000241")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_69 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 240, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Guwahati<br>rank: 69<br>hazard index: 0.000240")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_70 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 212, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Kota<br>rank: 70<br>hazard index: 0.000212")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_71 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 184, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Mathura<br>rank: 71<br>hazard index: 0.000185")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_72 = L.circle([24.796436, 85.007956], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 177, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Gaya<br>rank: 72<br>hazard index: 0.000178")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a>')

var circle_73 = L.circle([25.954628, 83.647350], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 175, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Maunath Bhanjan<br>rank: 73<br>hazard index: 0.000175")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Maunath_Bhanjan">Maunath Bhanjan</a>')

var circle_74 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 168, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Jammu<br>rank: 74<br>hazard index: 0.000168")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_75 = L.circle([25.603508, 83.507454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Ghazipur<br>rank: 75<br>hazard index: 0.000154")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ghazipur">Ghazipur</a>')

var circle_76 = L.circle([24.700385, 78.518668], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Lalitpur<br>rank: 76<br>hazard index: 0.000154")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lalitpur">Lalitpur</a>')

var circle_77 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 152, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Hyderabad<br>rank: 77<br>hazard index: 0.000152")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_78 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 148, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Muzaffarnagar<br>rank: 78<br>hazard index: 0.000148")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_79 = L.circle([23.250000, 87.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 147, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Barddhaman<br>rank: 79<br>hazard index: 0.000147")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barddhaman">Barddhaman</a>')

var circle_80 = L.circle([26.716413, 88.430992], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 127, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Siliguri<br>rank: 80<br>hazard index: 0.000127")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siliguri">Siliguri</a>')

var circle_81 = L.circle([25.720581, 85.255560], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 126, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Hajipur<br>rank: 81<br>hazard index: 0.000127")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hajipur">Hajipur</a>')

var circle_82 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 116, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Noida<br>rank: 82<br>hazard index: 0.000116")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_83 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 115, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Jaipur<br>rank: 83<br>hazard index: 0.000115")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_84 = L.circle([25.895924, 82.437716], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 113, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Badlapur<br>rank: 84<br>hazard index: 0.000113")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Badlapur">Badlapur</a>')

var circle_85 = L.circle([24.935635, 82.647701], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 100, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Mirzapur<br>rank: 85<br>hazard index: 0.000100")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mirzapur">Mirzapur</a>')

var circle_86 = L.circle([25.286698, 87.132254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 95, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Bhagalpur<br>rank: 86<br>hazard index: 0.000096")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a>')

var circle_87 = L.circle([25.512719, 86.090571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 94, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Begusarai<br>rank: 87<br>hazard index: 0.000095")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Begusarai">Begusarai</a>')

var circle_88 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 86, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Ahmedabad<br>rank: 88<br>hazard index: 0.000086")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_89 = L.circle([26.791073, 84.560107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 81, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Bettiah<br>rank: 89<br>hazard index: 0.000082")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bettiah">Bettiah</a>')

var circle_90 = L.circle([26.022697, 83.028873], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 80, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Azamgarh<br>rank: 90<br>hazard index: 0.000081")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Azamgarh">Azamgarh</a>')

var circle_91 = L.circle([25.680654, 88.124646], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 78, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Raiganj<br>rank: 91<br>hazard index: 0.000078")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raiganj">Raiganj</a>')

var circle_92 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 72, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Bhopal<br>rank: 92<br>hazard index: 0.000072")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_93 = L.circle([31.608574, 75.846442], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Hoshiarpur<br>rank: 93<br>hazard index: 0.000070")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshiarpur">Hoshiarpur</a>')

var circle_94 = L.circle([25.280733, 83.125128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Mughal Sarai<br>rank: 94<br>hazard index: 0.000069")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a>')

var circle_95 = L.circle([28.388861, 77.974798], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 64, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Bulandshahr<br>rank: 95<br>hazard index: 0.000065")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bulandshahr">Bulandshahr</a>')

var circle_96 = L.circle([25.623457, 84.596839], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 64, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Arrah<br>rank: 96<br>hazard index: 0.000064")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Arrah">Arrah</a>')

var circle_97 = L.circle([25.560900, 87.647654], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 63, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Katihar<br>rank: 97<br>hazard index: 0.000063")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Katihar">Katihar</a>')

var circle_98 = L.circle([26.083143, 86.032571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Darbhanga<br>rank: 98<br>hazard index: 0.000063")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Darbhanga">Darbhanga</a>')

var circle_99 = L.circle([28.618753, 78.550874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Sambhal<br>rank: 99<br>hazard index: 0.000063")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambhal">Sambhal</a>')

var circle_100 = L.circle([22.591260, 88.390964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 61, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Bidhan Nagar<br>rank: 100<br>hazard index: 0.000062")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidhan_Nagar">Bidhan Nagar</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Lakhimpur">Lakhimpur</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Sitapur">Sitapur</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Hardoi. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>