---
layout: page
title: "Outbreak location: Moga"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([30.783987, 75.160574],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Moga").openTooltip();

var circle_1 = L.circle([30.885100, 74.660141], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 250636, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Firozpur<br>rank: 1<br>hazard index: 0.250636")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozpur">Firozpur</a>')

var circle_2 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 48117, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Ludhiana<br>rank: 2<br>hazard index: 0.048117")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_3 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 25488, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Jalandhar<br>rank: 3<br>hazard index: 0.025489")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_4 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12290, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Chandigarh<br>rank: 4<br>hazard index: 0.012291")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_5 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12237, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Amritsar<br>rank: 5<br>hazard index: 0.012238")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_6 = L.circle([30.179115, 75.047102], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9930, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Bathinda<br>rank: 6<br>hazard index: 0.009930")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a>')

var circle_7 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9182, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Delhi<br>rank: 7<br>hazard index: 0.009182")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_8 = L.circle([30.209087, 76.339872], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4305, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Patiala<br>rank: 8<br>hazard index: 0.004305")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a>')

var circle_9 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3226, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Hisar<br>rank: 9<br>hazard index: 0.003226")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_10 = L.circle([31.385241, 75.305523], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2987, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Kapurthala<br>rank: 10<br>hazard index: 0.002988")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kapurthala">Kapurthala</a>')

var circle_11 = L.circle([31.608574, 75.846442], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2502, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Hoshiarpur<br>rank: 11<br>hazard index: 0.002503")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshiarpur">Hoshiarpur</a>')

var circle_12 = L.circle([32.301710, 75.658642], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2478, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Pathankot<br>rank: 12<br>hazard index: 0.002479")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pathankot">Pathankot</a>')

var circle_13 = L.circle([30.145054, 74.195660], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2354, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Abohar<br>rank: 13<br>hazard index: 0.002354")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Abohar">Abohar</a>')

var circle_14 = L.circle([29.583333, 75.083333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1962, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Sirsa<br>rank: 14<br>hazard index: 0.001963")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sirsa">Sirsa</a>')

var circle_15 = L.circle([29.367200, 74.298364], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1950, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Hanumangarh<br>rank: 15<br>hazard index: 0.001950")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hanumangarh">Hanumangarh</a>')

var circle_16 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1940, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Mumbai<br>rank: 16<br>hazard index: 0.001940")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_17 = L.circle([31.104153, 77.170973], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1803, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Shimla<br>rank: 17<br>hazard index: 0.001804")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shimla">Shimla</a>')

var circle_18 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1766, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Jind<br>rank: 18<br>hazard index: 0.001766")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_19 = L.circle([31.819302, 75.199994], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1661, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Batala<br>rank: 19<br>hazard index: 0.001662")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Batala">Batala</a>')

var circle_20 = L.circle([29.993039, 76.829223], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1646, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Thanesar<br>rank: 20<br>hazard index: 0.001647")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thanesar">Thanesar</a>')

var circle_21 = L.circle([30.883006, 75.869732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1621, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("S.A.S. Nagar<br>rank: 21<br>hazard index: 0.001622")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/S.A.S._Nagar">S.A.S. Nagar</a>')

var circle_22 = L.circle([30.283140, 74.522997], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1584, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Muktsar<br>rank: 22<br>hazard index: 0.001584")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muktsar">Muktsar</a>')

var circle_23 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1510, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Jammu<br>rank: 23<br>hazard index: 0.001511")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_24 = L.circle([30.533129, 75.880760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1130, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Malerkotla<br>rank: 24<br>hazard index: 0.001131")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Malerkotla">Malerkotla</a>')

var circle_25 = L.circle([30.370469, 75.504017], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 974, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Barnala<br>rank: 25<br>hazard index: 0.000975")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barnala">Barnala</a>')

var circle_26 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 856, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Lucknow<br>rank: 26<br>hazard index: 0.000857")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_27 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 844, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Gurgaon<br>rank: 27<br>hazard index: 0.000845")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_28 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 672, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Ambala<br>rank: 28<br>hazard index: 0.000672")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_29 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 561, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Jhansi<br>rank: 29<br>hazard index: 0.000561")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_30 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 443, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Surat<br>rank: 30<br>hazard index: 0.000444")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_31 = L.circle([29.822821, 76.378310], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 427, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Kaithal<br>rank: 31<br>hazard index: 0.000427")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kaithal">Kaithal</a>')

var circle_32 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 386, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Saharanpur<br>rank: 32<br>hazard index: 0.000386")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_33 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 365, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Varanasi<br>rank: 33<br>hazard index: 0.000366")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_34 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 353, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Dhanbad<br>rank: 34<br>hazard index: 0.000353")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_35 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 297, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Rohtak<br>rank: 35<br>hazard index: 0.000298")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_36 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 273, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Bareilly<br>rank: 36<br>hazard index: 0.000273")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_37 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 270, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Moradabad<br>rank: 37<br>hazard index: 0.000271")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_38 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 256, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Jaipur<br>rank: 38<br>hazard index: 0.000257")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_39 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 218, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Faridabad<br>rank: 39<br>hazard index: 0.000218")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_40 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 174, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Kanpur<br>rank: 40<br>hazard index: 0.000175")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_41 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 165, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Vadodara<br>rank: 41<br>hazard index: 0.000166")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_42 = L.circle([28.793170, 76.139128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 143, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Bhiwani<br>rank: 42<br>hazard index: 0.000143")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwani">Bhiwani</a>')

var circle_43 = L.circle([24.796436, 85.007956], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Gaya<br>rank: 43<br>hazard index: 0.000141")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a>')

var circle_44 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 136, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Dehradun<br>rank: 44<br>hazard index: 0.000136")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_45 = L.circle([23.749721, 91.876635], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 131, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Ganganagar<br>rank: 45<br>hazard index: 0.000132")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ganganagar">Ganganagar</a>')

var circle_46 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 120, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Bahadurgarh<br>rank: 46<br>hazard index: 0.000120")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_47 = L.circle([28.195647, 76.616518], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Rewari<br>rank: 47<br>hazard index: 0.000111")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewari">Rewari</a>')

var circle_48 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 108, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Thane<br>rank: 48<br>hazard index: 0.000108")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_49 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 100, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Bhopal<br>rank: 49<br>hazard index: 0.000101")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_50 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 99, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Shahjahanpur<br>rank: 50<br>hazard index: 0.000100")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_51 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 99, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Kota<br>rank: 51<br>hazard index: 0.000100")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_52 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 98, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Rampur<br>rank: 52<br>hazard index: 0.000099")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_53 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 88, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Agra<br>rank: 53<br>hazard index: 0.000088")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_54 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 86, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Jodhpur<br>rank: 54<br>hazard index: 0.000086")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_55 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 83, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Nashik<br>rank: 55<br>hazard index: 0.000083")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_56 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 82, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Bangalore<br>rank: 56<br>hazard index: 0.000083")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_57 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 80, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Pune<br>rank: 57<br>hazard index: 0.000081")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_58 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 79, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Meerut<br>rank: 58<br>hazard index: 0.000080")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_59 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Haridwar<br>rank: 59<br>hazard index: 0.000076")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_60 = L.circle([30.211200, 77.286390], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 70, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Yamunanagar<br>rank: 60<br>hazard index: 0.000070")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a>')

var circle_61 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Kolkata<br>rank: 61<br>hazard index: 0.000070")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_62 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Patna<br>rank: 62<br>hazard index: 0.000060")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_63 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Ahmedabad<br>rank: 63<br>hazard index: 0.000060")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_64 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Gwalior<br>rank: 64<br>hazard index: 0.000059")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_65 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 58, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Hyderabad<br>rank: 65<br>hazard index: 0.000058")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_66 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 54, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Bikaner<br>rank: 66<br>hazard index: 0.000055")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_67 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 54, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Mathura<br>rank: 67<br>hazard index: 0.000054")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_68 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Aligarh<br>rank: 68<br>hazard index: 0.000053")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_69 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 52, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Sonipat<br>rank: 69<br>hazard index: 0.000053")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_70 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 52, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Loni<br>rank: 70<br>hazard index: 0.000052")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_71 = L.circle([34.074744, 74.820444], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Srinagar<br>rank: 71<br>hazard index: 0.000052")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srinagar">Srinagar</a>')

var circle_72 = L.circle([25.795593, 82.488341], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Jaunpur<br>rank: 72<br>hazard index: 0.000051")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaunpur">Jaunpur</a>')

var circle_73 = L.circle([26.638076, 82.059024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Faizabad<br>rank: 73<br>hazard index: 0.000051")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faizabad">Faizabad</a>')

var circle_74 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Chennai<br>rank: 74<br>hazard index: 0.000051")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_75 = L.circle([28.206144, 74.691907], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Churu<br>rank: 75<br>hazard index: 0.000050")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Churu">Churu</a>')

var circle_76 = L.circle([30.129326, 77.245483], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 47, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Jagadhri<br>rank: 76<br>hazard index: 0.000048")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagadhri">Jagadhri</a>')

var circle_77 = L.circle([26.469100, 74.639000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Ajmer<br>rank: 77<br>hazard index: 0.000045")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a>')

var circle_78 = L.circle([24.900100, 84.018211], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Sasaram<br>rank: 78<br>hazard index: 0.000045")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sasaram">Sasaram</a>')

var circle_79 = L.circle([29.680327, 76.989625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Karnal<br>rank: 79<br>hazard index: 0.000044")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karnal">Karnal</a>')

var circle_80 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Allahabad<br>rank: 80<br>hazard index: 0.000042")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_81 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 41, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Dehri<br>rank: 81<br>hazard index: 0.000042")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')

var circle_82 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 41, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Panipat<br>rank: 82<br>hazard index: 0.000041")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_83 = L.circle([29.869350, 77.890212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 39, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Roorkee<br>rank: 83<br>hazard index: 0.000040")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a>')

var circle_84 = L.circle([25.565691, 80.063489], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Khanna<br>rank: 84<br>hazard index: 0.000039")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khanna">Khanna</a>')

var circle_85 = L.circle([27.338577, 80.097526], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Hardoi<br>rank: 85<br>hazard index: 0.000039")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hardoi">Hardoi</a>')

var circle_86 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Raipur<br>rank: 86<br>hazard index: 0.000038")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_87 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 35, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Khora<br>rank: 87<br>hazard index: 0.000035")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_88 = L.circle([26.439874, 80.018000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 33, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Akbarpur<br>rank: 88<br>hazard index: 0.000034")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akbarpur">Akbarpur</a>')

var circle_89 = L.circle([25.280733, 83.125128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 33, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Mughal Sarai<br>rank: 89<br>hazard index: 0.000034")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a>')

var circle_90 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 33, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Muzaffarnagar<br>rank: 90<br>hazard index: 0.000033")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_91 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 29, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Ranchi<br>rank: 91<br>hazard index: 0.000030")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_92 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 29, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Vasco Da Gama<br>rank: 92<br>hazard index: 0.000029")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_93 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Guwahati<br>rank: 93<br>hazard index: 0.000029")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_94 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Gorakhpur<br>rank: 94<br>hazard index: 0.000028")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_95 = L.circle([18.627929, 73.800983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Pimpri Chinchwad<br>rank: 95<br>hazard index: 0.000027")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pimpri_Chinchwad">Pimpri Chinchwad</a>')

var circle_96 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Hapur<br>rank: 96<br>hazard index: 0.000027")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_97 = L.circle([23.480592, 74.917790], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Ratlam<br>rank: 97<br>hazard index: 0.000026")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ratlam">Ratlam</a>')

var circle_98 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Alwar<br>rank: 98<br>hazard index: 0.000026")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_99 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Noida<br>rank: 99<br>hazard index: 0.000026")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_100 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 25, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Jalgaon<br>rank: 100<br>hazard index: 0.000026")
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
<td><a href="https://buda-magenta.github.io/hazard_map/Firozpur">Firozpur</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kapurthala">Kapurthala</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Moga. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>