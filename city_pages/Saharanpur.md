---
layout: page
title: "Outbreak location: Saharanpur"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([29.988077, 77.508130],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Saharanpur").openTooltip();

var circle_1 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 84949, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Delhi<br>rank: 1<br>hazard index: 0.084950")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_2 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43357, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Haridwar<br>rank: 2<br>hazard index: 0.043358")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_3 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30453, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Dehradun<br>rank: 3<br>hazard index: 0.030454")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_4 = L.circle([29.869350, 77.890212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22499, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Roorkee<br>rank: 4<br>hazard index: 0.022500")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a>')

var circle_5 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20922, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Ludhiana<br>rank: 5<br>hazard index: 0.020923")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_6 = L.circle([30.211200, 77.286390], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14761, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Yamunanagar<br>rank: 6<br>hazard index: 0.014762")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a>')

var circle_7 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13733, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Ambala<br>rank: 7<br>hazard index: 0.013733")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_8 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13713, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Chandigarh<br>rank: 8<br>hazard index: 0.013713")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_9 = L.circle([30.129326, 77.245483], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13520, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Jagadhri<br>rank: 9<br>hazard index: 0.013520")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagadhri">Jagadhri</a>')

var circle_10 = L.circle([29.500882, 77.348383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11951, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Shamli<br>rank: 10<br>hazard index: 0.011951")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shamli">Shamli</a>')

var circle_11 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9641, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Lucknow<br>rank: 11<br>hazard index: 0.009641")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_12 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8889, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Meerut<br>rank: 12<br>hazard index: 0.008890")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_13 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7809, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Jalandhar<br>rank: 13<br>hazard index: 0.007809")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_14 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7791, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Moradabad<br>rank: 14<br>hazard index: 0.007791")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_15 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5986, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Jhansi<br>rank: 15<br>hazard index: 0.005987")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_16 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5267, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Amritsar<br>rank: 16<br>hazard index: 0.005268")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_17 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3614, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Bareilly<br>rank: 17<br>hazard index: 0.003615")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_18 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3454, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Faridabad<br>rank: 18<br>hazard index: 0.003455")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_19 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3205, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Loni<br>rank: 19<br>hazard index: 0.003205")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_20 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2846, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Gurgaon<br>rank: 20<br>hazard index: 0.002847")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_21 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2741, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Muzaffarnagar<br>rank: 21<br>hazard index: 0.002741")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_22 = L.circle([30.209087, 76.339872], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2184, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Patiala<br>rank: 22<br>hazard index: 0.002185")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a>')

var circle_23 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1884, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Jammu<br>rank: 23<br>hazard index: 0.001885")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_24 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1830, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Noida<br>rank: 24<br>hazard index: 0.001831")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_25 = L.circle([31.104153, 77.170973], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1740, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Shimla<br>rank: 25<br>hazard index: 0.001741")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shimla">Shimla</a>')

var circle_26 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1618, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Kanpur<br>rank: 26<br>hazard index: 0.001619")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_27 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1489, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Allahabad<br>rank: 27<br>hazard index: 0.001490")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_28 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1458, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Mumbai<br>rank: 28<br>hazard index: 0.001459")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_29 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1335, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Rohtak<br>rank: 29<br>hazard index: 0.001335")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_30 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1231, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Shahjahanpur<br>rank: 30<br>hazard index: 0.001231")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_31 = L.circle([30.883006, 75.869732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1227, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("S.A.S. Nagar<br>rank: 31<br>hazard index: 0.001228")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/S.A.S._Nagar">S.A.S. Nagar</a>')

var circle_32 = L.circle([30.370469, 75.504017], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1226, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Barnala<br>rank: 32<br>hazard index: 0.001226")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barnala">Barnala</a>')

var circle_33 = L.circle([30.533129, 75.880760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1058, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Malerkotla<br>rank: 33<br>hazard index: 0.001059")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Malerkotla">Malerkotla</a>')

var circle_34 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1016, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Hapur<br>rank: 34<br>hazard index: 0.001016")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_35 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 980, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Rampur<br>rank: 35<br>hazard index: 0.000980")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_36 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 953, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Panipat<br>rank: 36<br>hazard index: 0.000954")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_37 = L.circle([29.680327, 76.989625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 854, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Karnal<br>rank: 37<br>hazard index: 0.000855")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karnal">Karnal</a>')

var circle_38 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 834, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Gorakhpur<br>rank: 38<br>hazard index: 0.000835")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_39 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 820, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Hisar<br>rank: 39<br>hazard index: 0.000820")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_40 = L.circle([28.923397, 78.488317], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 806, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Amroha<br>rank: 40<br>hazard index: 0.000807")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amroha">Amroha</a>')

var circle_41 = L.circle([30.179115, 75.047102], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 770, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Bathinda<br>rank: 41<br>hazard index: 0.000771")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a>')

var circle_42 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 767, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Bangalore<br>rank: 42<br>hazard index: 0.000767")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_43 = L.circle([31.608574, 75.846442], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 766, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Hoshiarpur<br>rank: 43<br>hazard index: 0.000767")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshiarpur">Hoshiarpur</a>')

var circle_44 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 764, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Sonipat<br>rank: 44<br>hazard index: 0.000765")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_45 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 693, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Khora<br>rank: 45<br>hazard index: 0.000694")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_46 = L.circle([28.793170, 76.139128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 658, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Bhiwani<br>rank: 46<br>hazard index: 0.000658")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwani">Bhiwani</a>')

var circle_47 = L.circle([29.154148, 77.305954], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 650, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Baraut<br>rank: 47<br>hazard index: 0.000650")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baraut">Baraut</a>')

var circle_48 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 647, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Kolkata<br>rank: 48<br>hazard index: 0.000648")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_49 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 620, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Varanasi<br>rank: 49<br>hazard index: 0.000620")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_50 = L.circle([25.565691, 80.063489], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 607, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Khanna<br>rank: 50<br>hazard index: 0.000608")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khanna">Khanna</a>')

var circle_51 = L.circle([28.388861, 77.974798], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 581, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Bulandshahr<br>rank: 51<br>hazard index: 0.000581")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bulandshahr">Bulandshahr</a>')

var circle_52 = L.circle([29.211757, 78.961731], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 560, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Kashipur<br>rank: 52<br>hazard index: 0.000560")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kashipur">Kashipur</a>')

var circle_53 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 551, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Patna<br>rank: 53<br>hazard index: 0.000551")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_54 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 551, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Ahmedabad<br>rank: 54<br>hazard index: 0.000551")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_55 = L.circle([28.618753, 78.550874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 551, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Sambhal<br>rank: 55<br>hazard index: 0.000551")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambhal">Sambhal</a>')

var circle_56 = L.circle([30.783987, 75.160574], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 539, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Moga<br>rank: 56<br>hazard index: 0.000539")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moga">Moga</a>')

var circle_57 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 537, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Agra<br>rank: 57<br>hazard index: 0.000537")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_58 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 537, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Hyderabad<br>rank: 58<br>hazard index: 0.000537")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_59 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 521, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Jaipur<br>rank: 59<br>hazard index: 0.000521")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_60 = L.circle([30.885100, 74.660141], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 513, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Firozpur<br>rank: 60<br>hazard index: 0.000514")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozpur">Firozpur</a>')

var circle_61 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 509, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Bahadurgarh<br>rank: 61<br>hazard index: 0.000510")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_62 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 491, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Aligarh<br>rank: 62<br>hazard index: 0.000492")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_63 = L.circle([28.826162, 77.541656], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 476, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Modinagar<br>rank: 63<br>hazard index: 0.000476")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Modinagar">Modinagar</a>')

var circle_64 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 468, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Chennai<br>rank: 64<br>hazard index: 0.000468")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_65 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 456, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Pune<br>rank: 65<br>hazard index: 0.000457")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_66 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 431, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Jind<br>rank: 66<br>hazard index: 0.000431")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_67 = L.circle([29.993039, 76.829223], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 425, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Thanesar<br>rank: 67<br>hazard index: 0.000425")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thanesar">Thanesar</a>')

var circle_68 = L.circle([29.822821, 76.378310], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 399, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Kaithal<br>rank: 68<br>hazard index: 0.000400")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kaithal">Kaithal</a>')

var circle_69 = L.circle([30.145054, 74.195660], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 391, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Abohar<br>rank: 69<br>hazard index: 0.000392")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Abohar">Abohar</a>')

var circle_70 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 390, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Dehri<br>rank: 70<br>hazard index: 0.000390")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')

var circle_71 = L.circle([27.338577, 80.097526], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 383, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Hardoi<br>rank: 71<br>hazard index: 0.000384")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hardoi">Hardoi</a>')

var circle_72 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 312, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Bikaner<br>rank: 72<br>hazard index: 0.000312")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_73 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 272, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Vasco Da Gama<br>rank: 73<br>hazard index: 0.000272")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_74 = L.circle([26.250000, 81.250000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 269, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Rae Bareli<br>rank: 74<br>hazard index: 0.000269")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rae_Bareli">Rae Bareli</a>')

var circle_75 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 267, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Guwahati<br>rank: 75<br>hazard index: 0.000268")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_76 = L.circle([28.176959, 77.373112], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 265, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Palwal<br>rank: 76<br>hazard index: 0.000266")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palwal">Palwal</a>')

var circle_77 = L.circle([32.301710, 75.658642], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 251, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Pathankot<br>rank: 77<br>hazard index: 0.000252")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pathankot">Pathankot</a>')

var circle_78 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 243, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Muzaffarpur<br>rank: 78<br>hazard index: 0.000244")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_79 = L.circle([34.074744, 74.820444], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 238, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Srinagar<br>rank: 79<br>hazard index: 0.000239")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srinagar">Srinagar</a>')

var circle_80 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 236, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Bhopal<br>rank: 80<br>hazard index: 0.000237")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_81 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 228, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Gwalior<br>rank: 81<br>hazard index: 0.000228")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_82 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 222, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Nagpur<br>rank: 82<br>hazard index: 0.000222")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_83 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 220, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Firozabad<br>rank: 83<br>hazard index: 0.000220")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_84 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 216, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Bhubaneswar<br>rank: 84<br>hazard index: 0.000216")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_85 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 206, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Mathura<br>rank: 85<br>hazard index: 0.000206")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_86 = L.circle([27.504639, 80.829466], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 203, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Sitapur<br>rank: 86<br>hazard index: 0.000204")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sitapur">Sitapur</a>')

var circle_87 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 196, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Ranchi<br>rank: 87<br>hazard index: 0.000197")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_88 = L.circle([28.195647, 76.616518], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 192, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Rewari<br>rank: 88<br>hazard index: 0.000193")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewari">Rewari</a>')

var circle_89 = L.circle([31.385241, 75.305523], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 182, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Kapurthala<br>rank: 89<br>hazard index: 0.000182")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kapurthala">Kapurthala</a>')

var circle_90 = L.circle([25.603508, 83.507454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 177, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Ghazipur<br>rank: 90<br>hazard index: 0.000178")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ghazipur">Ghazipur</a>')

var circle_91 = L.circle([26.698885, 88.320030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 173, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Bagdogra<br>rank: 91<br>hazard index: 0.000174")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagdogra">Bagdogra</a>')

var circle_92 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 164, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Indore<br>rank: 92<br>hazard index: 0.000164")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_93 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 164, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Surat<br>rank: 93<br>hazard index: 0.000164")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_94 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Dhanbad<br>rank: 94<br>hazard index: 0.000153")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_95 = L.circle([26.083143, 86.032571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 146, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Darbhanga<br>rank: 95<br>hazard index: 0.000147")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Darbhanga">Darbhanga</a>')

var circle_96 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 144, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Chapra<br>rank: 96<br>hazard index: 0.000145")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_97 = L.circle([28.488378, 78.735249], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Chandausi<br>rank: 97<br>hazard index: 0.000142")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandausi">Chandausi</a>')

var circle_98 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Kochi<br>rank: 98<br>hazard index: 0.000142")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_99 = L.circle([29.214460, 79.527918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 137, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Haldwani<br>rank: 99<br>hazard index: 0.000138")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haldwani">Haldwani</a>')

var circle_100 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 136, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Alwar<br>rank: 100<br>hazard index: 0.000136")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jagadhri">Jagadhri</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Shamli">Shamli</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Saharanpur. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>