---
layout: page
title: "Outbreak location: Amritsar"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([31.634308, 74.873679],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Amritsar").openTooltip();

var circle_1 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 80153, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Ludhiana<br>rank: 1<br>hazard index: 0.080154")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_2 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62934, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Delhi<br>rank: 2<br>hazard index: 0.062934")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_3 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40068, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Jalandhar<br>rank: 3<br>hazard index: 0.040068")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_4 = L.circle([31.819302, 75.199994], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23827, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Batala<br>rank: 4<br>hazard index: 0.023828")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Batala">Batala</a>')

var circle_5 = L.circle([32.301710, 75.658642], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23149, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Pathankot<br>rank: 5<br>hazard index: 0.023150")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pathankot">Pathankot</a>')

var circle_6 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19281, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Jammu<br>rank: 6<br>hazard index: 0.019282")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_7 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10520, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Mumbai<br>rank: 7<br>hazard index: 0.010520")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_8 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6811, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Lucknow<br>rank: 8<br>hazard index: 0.006812")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_9 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6459, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Saharanpur<br>rank: 9<br>hazard index: 0.006460")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_10 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5728, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Jhansi<br>rank: 10<br>hazard index: 0.005729")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_11 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4742, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Kolkata<br>rank: 11<br>hazard index: 0.004743")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_12 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4541, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Chandigarh<br>rank: 12<br>hazard index: 0.004542")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_13 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4149, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Moradabad<br>rank: 13<br>hazard index: 0.004150")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_14 = L.circle([31.608574, 75.846442], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3934, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Hoshiarpur<br>rank: 14<br>hazard index: 0.003935")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshiarpur">Hoshiarpur</a>')

var circle_15 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3535, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Bareilly<br>rank: 15<br>hazard index: 0.003535")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_16 = L.circle([30.179115, 75.047102], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3376, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Bathinda<br>rank: 16<br>hazard index: 0.003376")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a>')

var circle_17 = L.circle([30.145054, 74.195660], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2462, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Abohar<br>rank: 17<br>hazard index: 0.002462")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Abohar">Abohar</a>')

var circle_18 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2319, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Gorakhpur<br>rank: 18<br>hazard index: 0.002319")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_19 = L.circle([30.783987, 75.160574], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2065, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Moga<br>rank: 19<br>hazard index: 0.002066")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moga">Moga</a>')

var circle_20 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2053, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Kanpur<br>rank: 20<br>hazard index: 0.002054")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_21 = L.circle([30.883006, 75.869732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2031, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("S.A.S. Nagar<br>rank: 21<br>hazard index: 0.002031")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/S.A.S._Nagar">S.A.S. Nagar</a>')

var circle_22 = L.circle([30.885100, 74.660141], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1967, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Firozpur<br>rank: 22<br>hazard index: 0.001968")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozpur">Firozpur</a>')

var circle_23 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1828, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Jaipur<br>rank: 23<br>hazard index: 0.001829")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_24 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1657, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Varanasi<br>rank: 24<br>hazard index: 0.001658")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_25 = L.circle([30.283140, 74.522997], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1657, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Muktsar<br>rank: 25<br>hazard index: 0.001657")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muktsar">Muktsar</a>')

var circle_26 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1656, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Agra<br>rank: 26<br>hazard index: 0.001657")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_27 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1641, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Bangalore<br>rank: 27<br>hazard index: 0.001641")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_28 = L.circle([30.533129, 75.880760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1609, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Malerkotla<br>rank: 28<br>hazard index: 0.001610")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Malerkotla">Malerkotla</a>')

var circle_29 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1562, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Patna<br>rank: 29<br>hazard index: 0.001563")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_30 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1509, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Bhopal<br>rank: 30<br>hazard index: 0.001509")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_31 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1407, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Gurgaon<br>rank: 31<br>hazard index: 0.001408")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_32 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1289, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Ambala<br>rank: 32<br>hazard index: 0.001289")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_33 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1286, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Faridabad<br>rank: 33<br>hazard index: 0.001286")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_34 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1272, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Surat<br>rank: 34<br>hazard index: 0.001273")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_35 = L.circle([31.385241, 75.305523], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1272, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Kapurthala<br>rank: 35<br>hazard index: 0.001273")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kapurthala">Kapurthala</a>')

var circle_36 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1130, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Nagpur<br>rank: 36<br>hazard index: 0.001130")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_37 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1108, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Gwalior<br>rank: 37<br>hazard index: 0.001108")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_38 = L.circle([30.211200, 77.286390], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1028, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Yamunanagar<br>rank: 38<br>hazard index: 0.001029")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a>')

var circle_39 = L.circle([30.370469, 75.504017], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1019, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Barnala<br>rank: 39<br>hazard index: 0.001019")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barnala">Barnala</a>')

var circle_40 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 987, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Hisar<br>rank: 40<br>hazard index: 0.000987")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_41 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 966, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Dehradun<br>rank: 41<br>hazard index: 0.000967")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_42 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 966, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Haridwar<br>rank: 42<br>hazard index: 0.000966")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_43 = L.circle([34.074744, 74.820444], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 889, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Srinagar<br>rank: 43<br>hazard index: 0.000889")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srinagar">Srinagar</a>')

var circle_44 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 870, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Meerut<br>rank: 44<br>hazard index: 0.000871")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_45 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 865, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Muzaffarpur<br>rank: 45<br>hazard index: 0.000865")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_46 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 859, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Shahjahanpur<br>rank: 46<br>hazard index: 0.000859")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_47 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 664, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Panipat<br>rank: 47<br>hazard index: 0.000664")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_48 = L.circle([29.869350, 77.890212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 662, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Roorkee<br>rank: 48<br>hazard index: 0.000663")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a>')

var circle_49 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 647, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Rohtak<br>rank: 49<br>hazard index: 0.000648")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_50 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 627, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Jodhpur<br>rank: 50<br>hazard index: 0.000628")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_51 = L.circle([29.680327, 76.989625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 613, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Karnal<br>rank: 51<br>hazard index: 0.000614")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karnal">Karnal</a>')

var circle_52 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 593, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Asansol<br>rank: 52<br>hazard index: 0.000593")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_53 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 588, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Thane<br>rank: 53<br>hazard index: 0.000588")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_54 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 577, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Rampur<br>rank: 54<br>hazard index: 0.000577")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_55 = L.circle([30.129326, 77.245483], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 548, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Jagadhri<br>rank: 55<br>hazard index: 0.000549")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagadhri">Jagadhri</a>')

var circle_56 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 542, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Aligarh<br>rank: 56<br>hazard index: 0.000542")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_57 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 539, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Sonipat<br>rank: 57<br>hazard index: 0.000539")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_58 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 528, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Chapra<br>rank: 58<br>hazard index: 0.000529")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_59 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 527, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Vadodara<br>rank: 59<br>hazard index: 0.000528")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_60 = L.circle([25.565691, 80.063489], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 526, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Khanna<br>rank: 60<br>hazard index: 0.000527")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khanna">Khanna</a>')

var circle_61 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 498, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Nanded Waghala<br>rank: 61<br>hazard index: 0.000499")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_62 = L.circle([23.535048, 87.338043], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 490, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Durgapur<br>rank: 62<br>hazard index: 0.000490")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a>')

var circle_63 = L.circle([27.504639, 80.829466], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 453, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Sitapur<br>rank: 63<br>hazard index: 0.000454")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sitapur">Sitapur</a>')

var circle_64 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 449, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Raipur<br>rank: 64<br>hazard index: 0.000449")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_65 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 440, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Mathura<br>rank: 65<br>hazard index: 0.000440")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_66 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 438, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Pune<br>rank: 66<br>hazard index: 0.000439")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_67 = L.circle([25.512719, 86.090571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 435, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Begusarai<br>rank: 67<br>hazard index: 0.000435")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Begusarai">Begusarai</a>')

var circle_68 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 408, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Guwahati<br>rank: 68<br>hazard index: 0.000409")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_69 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 408, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Ahmedabad<br>rank: 69<br>hazard index: 0.000408")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_70 = L.circle([26.083143, 86.032571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 399, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Darbhanga<br>rank: 70<br>hazard index: 0.000399")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Darbhanga">Darbhanga</a>')

var circle_71 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 397, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Hyderabad<br>rank: 71<br>hazard index: 0.000398")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_72 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 393, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Bikaner<br>rank: 72<br>hazard index: 0.000393")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_73 = L.circle([25.720581, 85.255560], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 385, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Hajipur<br>rank: 73<br>hazard index: 0.000386")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hajipur">Hajipur</a>')

var circle_74 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 375, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Firozabad<br>rank: 74<br>hazard index: 0.000375")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_75 = L.circle([26.724789, 82.793269], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 371, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Basti<br>rank: 75<br>hazard index: 0.000372")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Basti">Basti</a>')

var circle_76 = L.circle([27.109667, 81.918329], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 370, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Gonda<br>rank: 76<br>hazard index: 0.000371")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gonda">Gonda</a>')

var circle_77 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 361, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Jalgaon<br>rank: 77<br>hazard index: 0.000362")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_78 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 359, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Loni<br>rank: 78<br>hazard index: 0.000359")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_79 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 346, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Chennai<br>rank: 79<br>hazard index: 0.000347")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_80 = L.circle([26.469100, 74.639000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 321, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Ajmer<br>rank: 80<br>hazard index: 0.000322")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a>')

var circle_81 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 316, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Kota<br>rank: 81<br>hazard index: 0.000317")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_82 = L.circle([26.131004, 84.391257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 311, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Siwan<br>rank: 82<br>hazard index: 0.000311")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siwan">Siwan</a>')

var circle_83 = L.circle([26.423847, 83.762732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 300, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Deoria<br>rank: 83<br>hazard index: 0.000300")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoria">Deoria</a>')

var circle_84 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 290, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Allahabad<br>rank: 84<br>hazard index: 0.000291")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_85 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 285, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Bahadurgarh<br>rank: 85<br>hazard index: 0.000285")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_86 = L.circle([29.211757, 78.961731], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 274, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Kashipur<br>rank: 86<br>hazard index: 0.000275")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kashipur">Kashipur</a>')

var circle_87 = L.circle([23.250000, 87.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 272, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Barddhaman<br>rank: 87<br>hazard index: 0.000272")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barddhaman">Barddhaman</a>')

var circle_88 = L.circle([29.583333, 75.083333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 261, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Sirsa<br>rank: 88<br>hazard index: 0.000261")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sirsa">Sirsa</a>')

var circle_89 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 261, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Muzaffarnagar<br>rank: 89<br>hazard index: 0.000261")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_90 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 252, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Nashik<br>rank: 90<br>hazard index: 0.000253")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_91 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 248, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Khora<br>rank: 91<br>hazard index: 0.000249")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_92 = L.circle([25.832642, 86.614893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 219, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Saharsa<br>rank: 92<br>hazard index: 0.000219")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharsa">Saharsa</a>')

var circle_93 = L.circle([25.623457, 84.596839], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 218, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Arrah<br>rank: 93<br>hazard index: 0.000218")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Arrah">Arrah</a>')

var circle_94 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 216, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Vasco Da Gama<br>rank: 94<br>hazard index: 0.000217")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_95 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 205, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Jind<br>rank: 95<br>hazard index: 0.000205")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_96 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 204, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Visakhapatnam<br>rank: 96<br>hazard index: 0.000205")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_97 = L.circle([25.560900, 87.647654], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 198, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Katihar<br>rank: 97<br>hazard index: 0.000199")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Katihar">Katihar</a>')

var circle_98 = L.circle([26.250000, 81.250000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 190, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Rae Bareli<br>rank: 98<br>hazard index: 0.000190")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rae_Bareli">Rae Bareli</a>')

var circle_99 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 187, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Alwar<br>rank: 99<br>hazard index: 0.000187")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_100 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 185, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Bilaspur<br>rank: 100<br>hazard index: 0.000186")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Batala">Batala</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Pathankot">Pathankot</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Amritsar. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>