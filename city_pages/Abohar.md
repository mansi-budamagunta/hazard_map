---
layout: page
title: "Outbreak location: Abohar"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([30.145054, 74.195660],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Abohar").openTooltip();

var circle_1 = L.circle([30.179115, 75.047102], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 96483, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Bathinda<br>rank: 1<br>hazard index: 0.096484")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a>')

var circle_2 = L.circle([23.749721, 91.876635], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 34300, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Ganganagar<br>rank: 2<br>hazard index: 0.034301")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ganganagar">Ganganagar</a>')

var circle_3 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 32457, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Delhi<br>rank: 3<br>hazard index: 0.032458")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_4 = L.circle([29.367200, 74.298364], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27557, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Hanumangarh<br>rank: 4<br>hazard index: 0.027557")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hanumangarh">Hanumangarh</a>')

var circle_5 = L.circle([30.209087, 76.339872], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19854, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Patiala<br>rank: 5<br>hazard index: 0.019855")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a>')

var circle_6 = L.circle([30.885100, 74.660141], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17345, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Firozpur<br>rank: 6<br>hazard index: 0.017345")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozpur">Firozpur</a>')

var circle_7 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14984, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Ludhiana<br>rank: 7<br>hazard index: 0.014985")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_8 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13570, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Jodhpur<br>rank: 8<br>hazard index: 0.013570")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_9 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12058, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Bikaner<br>rank: 9<br>hazard index: 0.012059")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_10 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10338, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Hisar<br>rank: 10<br>hazard index: 0.010339")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_11 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9177, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Amritsar<br>rank: 11<br>hazard index: 0.009177")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_12 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8907, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Saharanpur<br>rank: 12<br>hazard index: 0.008907")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_13 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8005, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Jalandhar<br>rank: 13<br>hazard index: 0.008005")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_14 = L.circle([30.370469, 75.504017], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6359, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Barnala<br>rank: 14<br>hazard index: 0.006359")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barnala">Barnala</a>')

var circle_15 = L.circle([29.583333, 75.083333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6290, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Sirsa<br>rank: 15<br>hazard index: 0.006290")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sirsa">Sirsa</a>')

var circle_16 = L.circle([30.283140, 74.522997], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5898, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Muktsar<br>rank: 16<br>hazard index: 0.005898")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muktsar">Muktsar</a>')

var circle_17 = L.circle([28.793170, 76.139128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5182, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Bhiwani<br>rank: 17<br>hazard index: 0.005182")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwani">Bhiwani</a>')

var circle_18 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5109, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Ambala<br>rank: 18<br>hazard index: 0.005110")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_19 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4316, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Kolkata<br>rank: 19<br>hazard index: 0.004317")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_20 = L.circle([28.195647, 76.616518], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3749, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Rewari<br>rank: 20<br>hazard index: 0.003750")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewari">Rewari</a>')

var circle_21 = L.circle([23.831238, 91.282382], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2943, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Agartala<br>rank: 21<br>hazard index: 0.002943")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agartala">Agartala</a>')

var circle_22 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2852, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Haridwar<br>rank: 22<br>hazard index: 0.002852")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_23 = L.circle([30.129326, 77.245483], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2743, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Jagadhri<br>rank: 23<br>hazard index: 0.002743")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagadhri">Jagadhri</a>')

var circle_24 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2662, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Kanpur<br>rank: 24<br>hazard index: 0.002662")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_25 = L.circle([23.743524, 92.738291], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2148, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Aizawl<br>rank: 25<br>hazard index: 0.002149")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aizawl">Aizawl</a>')

var circle_26 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1865, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Agra<br>rank: 26<br>hazard index: 0.001865")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_27 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1619, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Patna<br>rank: 27<br>hazard index: 0.001619")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_28 = L.circle([30.211200, 77.286390], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1581, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Yamunanagar<br>rank: 28<br>hazard index: 0.001582")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a>')

var circle_29 = L.circle([29.869350, 77.890212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1496, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Roorkee<br>rank: 29<br>hazard index: 0.001497")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a>')

var circle_30 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1351, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Faridabad<br>rank: 30<br>hazard index: 0.001351")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_31 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1326, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Jhansi<br>rank: 31<br>hazard index: 0.001327")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_32 = L.circle([27.060786, 74.176675], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1320, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Nagaur<br>rank: 32<br>hazard index: 0.001321")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagaur">Nagaur</a>')

var circle_33 = L.circle([30.783987, 75.160574], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1218, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Moga<br>rank: 33<br>hazard index: 0.001219")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moga">Moga</a>')

var circle_34 = L.circle([30.883006, 75.869732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1183, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("S.A.S. Nagar<br>rank: 34<br>hazard index: 0.001184")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/S.A.S._Nagar">S.A.S. Nagar</a>')

var circle_35 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1110, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Jind<br>rank: 35<br>hazard index: 0.001111")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_36 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1074, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Allahabad<br>rank: 36<br>hazard index: 0.001075")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_37 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1001, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Rohtak<br>rank: 37<br>hazard index: 0.001002")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_38 = L.circle([31.608574, 75.846442], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 786, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Hoshiarpur<br>rank: 38<br>hazard index: 0.000786")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshiarpur">Hoshiarpur</a>')

var circle_39 = L.circle([30.533129, 75.880760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 725, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Malerkotla<br>rank: 39<br>hazard index: 0.000725")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Malerkotla">Malerkotla</a>')

var circle_40 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 595, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Jammu<br>rank: 40<br>hazard index: 0.000596")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_41 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 580, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Firozabad<br>rank: 41<br>hazard index: 0.000581")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_42 = L.circle([31.385241, 75.305523], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 578, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Kapurthala<br>rank: 42<br>hazard index: 0.000579")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kapurthala">Kapurthala</a>')

var circle_43 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 557, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Mumbai<br>rank: 43<br>hazard index: 0.000557")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_44 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 554, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Chandigarh<br>rank: 44<br>hazard index: 0.000554")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_45 = L.circle([23.535048, 87.338043], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 545, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Durgapur<br>rank: 45<br>hazard index: 0.000545")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a>')

var circle_46 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 543, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Asansol<br>rank: 46<br>hazard index: 0.000543")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_47 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 458, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Gurgaon<br>rank: 47<br>hazard index: 0.000459")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_48 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 445, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Jaipur<br>rank: 48<br>hazard index: 0.000445")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_49 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 424, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Lucknow<br>rank: 49<br>hazard index: 0.000425")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_50 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 416, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Bahadurgarh<br>rank: 50<br>hazard index: 0.000417")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_51 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 413, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Mathura<br>rank: 51<br>hazard index: 0.000414")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_52 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 399, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Bhopal<br>rank: 52<br>hazard index: 0.000399")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_53 = L.circle([24.800609, 93.937000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 377, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Imphal<br>rank: 53<br>hazard index: 0.000378")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Imphal">Imphal</a>')

var circle_54 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 352, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Ahmedabad<br>rank: 54<br>hazard index: 0.000352")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_55 = L.circle([24.817861, 92.756221], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 312, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Silchar<br>rank: 55<br>hazard index: 0.000313")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Silchar">Silchar</a>')

var circle_56 = L.circle([23.250000, 87.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 302, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Barddhaman<br>rank: 56<br>hazard index: 0.000303")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barddhaman">Barddhaman</a>')

var circle_57 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 293, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Bangalore<br>rank: 57<br>hazard index: 0.000293")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_58 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 292, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Moradabad<br>rank: 58<br>hazard index: 0.000293")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_59 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 282, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Meerut<br>rank: 59<br>hazard index: 0.000283")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_60 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 271, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Dehradun<br>rank: 60<br>hazard index: 0.000271")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_61 = L.circle([32.301710, 75.658642], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 257, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Pathankot<br>rank: 61<br>hazard index: 0.000258")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pathankot">Pathankot</a>')

var circle_62 = L.circle([25.623457, 84.596839], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 251, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Arrah<br>rank: 62<br>hazard index: 0.000251")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Arrah">Arrah</a>')

var circle_63 = L.circle([26.718324, 79.090254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 247, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Etawah<br>rank: 63<br>hazard index: 0.000247")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Etawah">Etawah</a>')

var circle_64 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 234, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Gwalior<br>rank: 64<br>hazard index: 0.000234")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_65 = L.circle([24.935635, 82.647701], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 224, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Mirzapur<br>rank: 65<br>hazard index: 0.000225")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mirzapur">Mirzapur</a>')

var circle_66 = L.circle([31.819302, 75.199994], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 218, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Batala<br>rank: 66<br>hazard index: 0.000219")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Batala">Batala</a>')

var circle_67 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 205, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Hyderabad<br>rank: 67<br>hazard index: 0.000205")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_68 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 187, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Aligarh<br>rank: 68<br>hazard index: 0.000188")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_69 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 186, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Sonipat<br>rank: 69<br>hazard index: 0.000186")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_70 = L.circle([25.843539, 80.918004], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 186, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Fatehpur<br>rank: 70<br>hazard index: 0.000186")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Fatehpur">Fatehpur</a>')

var circle_71 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 185, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Loni<br>rank: 71<br>hazard index: 0.000185")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_72 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 178, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Chennai<br>rank: 72<br>hazard index: 0.000179")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_73 = L.circle([25.680654, 88.124646], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 176, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Raiganj<br>rank: 73<br>hazard index: 0.000177")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raiganj">Raiganj</a>')

var circle_74 = L.circle([25.623400, 85.041700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 175, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Dinapur Nizamat<br>rank: 74<br>hazard index: 0.000175")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dinapur_Nizamat">Dinapur Nizamat</a>')

var circle_75 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 174, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Pune<br>rank: 75<br>hazard index: 0.000175")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_76 = L.circle([28.206144, 74.691907], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 159, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Churu<br>rank: 76<br>hazard index: 0.000159")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Churu">Churu</a>')

var circle_77 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 143, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Surat<br>rank: 77<br>hazard index: 0.000144")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_78 = L.circle([25.604091, 73.415609], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 143, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Pali<br>rank: 78<br>hazard index: 0.000143")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pali">Pali</a>')

var circle_79 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 136, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Panipat<br>rank: 79<br>hazard index: 0.000136")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_80 = L.circle([26.469100, 74.639000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 135, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Ajmer<br>rank: 80<br>hazard index: 0.000135")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a>')

var circle_81 = L.circle([22.591260, 88.390964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 126, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Bidhan Nagar<br>rank: 81<br>hazard index: 0.000126")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidhan_Nagar">Bidhan Nagar</a>')

var circle_82 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 124, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Khora<br>rank: 82<br>hazard index: 0.000125")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_83 = L.circle([28.176959, 77.373112], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 123, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Palwal<br>rank: 83<br>hazard index: 0.000123")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palwal">Palwal</a>')

var circle_84 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 122, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Nanded Waghala<br>rank: 84<br>hazard index: 0.000122")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_85 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 115, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Kota<br>rank: 85<br>hazard index: 0.000115")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_86 = L.circle([24.170979, 72.436638], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Palanpur<br>rank: 86<br>hazard index: 0.000110")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palanpur">Palanpur</a>')

var circle_87 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 108, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Varanasi<br>rank: 87<br>hazard index: 0.000109")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_88 = L.circle([29.500882, 77.348383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 106, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Shamli<br>rank: 88<br>hazard index: 0.000106")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shamli">Shamli</a>')

var circle_89 = L.circle([25.280733, 83.125128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 105, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Mughal Sarai<br>rank: 89<br>hazard index: 0.000106")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a>')

var circle_90 = L.circle([23.071874, 70.131715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 105, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Gandhidham<br>rank: 90<br>hazard index: 0.000105")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhidham">Gandhidham</a>')

var circle_91 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 104, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Bareilly<br>rank: 91<br>hazard index: 0.000105")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_92 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 104, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Indore<br>rank: 92<br>hazard index: 0.000105")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_93 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 104, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Vasco Da Gama<br>rank: 93<br>hazard index: 0.000104")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_94 = L.circle([27.036604, 78.651436], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 103, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Shikohabad<br>rank: 94<br>hazard index: 0.000103")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shikohabad">Shikohabad</a>')

var circle_95 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 102, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Guwahati<br>rank: 95<br>hazard index: 0.000102")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_96 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 100, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Muzaffarnagar<br>rank: 96<br>hazard index: 0.000101")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_97 = L.circle([25.562071, 84.015672], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 98, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Buxar<br>rank: 97<br>hazard index: 0.000099")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Buxar">Buxar</a>')

var circle_98 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 95, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Hapur<br>rank: 98<br>hazard index: 0.000095")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_99 = L.circle([27.662826, 75.027926], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 95, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Sikar<br>rank: 99<br>hazard index: 0.000095")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sikar">Sikar</a>')

var circle_100 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 95, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Akola<br>rank: 100<br>hazard index: 0.000095")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ganganagar">Ganganagar</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Hanumangarh">Hanumangarh</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Firozpur">Firozpur</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Abohar. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>