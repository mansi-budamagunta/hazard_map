---
layout: page
title: "Outbreak location: Arrah"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([25.623457, 84.596839],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Arrah").openTooltip();

var circle_1 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 114917, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Patna<br>rank: 1<br>hazard index: 0.114917")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_2 = L.circle([25.623400, 85.041700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 68688, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Dinapur Nizamat<br>rank: 2<br>hazard index: 0.068688")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dinapur_Nizamat">Dinapur Nizamat</a>')

var circle_3 = L.circle([24.900100, 84.018211], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 61124, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Sasaram<br>rank: 3<br>hazard index: 0.061124")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sasaram">Sasaram</a>')

var circle_4 = L.circle([25.562071, 84.015672], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 46090, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Buxar<br>rank: 4<br>hazard index: 0.046091")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Buxar">Buxar</a>')

var circle_5 = L.circle([25.280733, 83.125128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 25011, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Mughal Sarai<br>rank: 5<br>hazard index: 0.025012")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a>')

var circle_6 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13268, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Varanasi<br>rank: 6<br>hazard index: 0.013269")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_7 = L.circle([24.796436, 85.007956], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5859, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Gaya<br>rank: 7<br>hazard index: 0.005860")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a>')

var circle_8 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2793, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Gorakhpur<br>rank: 8<br>hazard index: 0.002793")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_9 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2714, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Delhi<br>rank: 9<br>hazard index: 0.002714")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_10 = L.circle([25.286698, 87.132254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2123, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Bhagalpur<br>rank: 10<br>hazard index: 0.002124")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a>')

var circle_11 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1994, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Kolkata<br>rank: 11<br>hazard index: 0.001994")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_12 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1819, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Dehri<br>rank: 12<br>hazard index: 0.001820")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')

var circle_13 = L.circle([25.512719, 86.090571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1631, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Begusarai<br>rank: 13<br>hazard index: 0.001632")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Begusarai">Begusarai</a>')

var circle_14 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1629, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Ranchi<br>rank: 14<br>hazard index: 0.001629")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_15 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1464, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Muzaffarpur<br>rank: 15<br>hazard index: 0.001465")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_16 = L.circle([26.269721, 82.994425], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1398, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Burhanpur<br>rank: 16<br>hazard index: 0.001398")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Burhanpur">Burhanpur</a>')

var circle_17 = L.circle([25.205305, 85.514612], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1384, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Biharsharif<br>rank: 17<br>hazard index: 0.001385")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Biharsharif">Biharsharif</a>')

var circle_18 = L.circle([26.083143, 86.032571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1367, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Darbhanga<br>rank: 18<br>hazard index: 0.001368")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Darbhanga">Darbhanga</a>')

var circle_19 = L.circle([25.152471, 85.006878], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1325, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Jehanabad<br>rank: 19<br>hazard index: 0.001326")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jehanabad">Jehanabad</a>')

var circle_20 = L.circle([26.055318, 82.993139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1292, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Nizamabad<br>rank: 20<br>hazard index: 0.001292")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a>')

var circle_21 = L.circle([25.264902, 82.985787], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1202, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Morvi<br>rank: 21<br>hazard index: 0.001203")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Morvi">Morvi</a>')

var circle_22 = L.circle([25.954628, 83.647350], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1161, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Maunath Bhanjan<br>rank: 22<br>hazard index: 0.001162")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Maunath_Bhanjan">Maunath Bhanjan</a>')

var circle_23 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 996, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Mumbai<br>rank: 23<br>hazard index: 0.000997")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_24 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 875, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Hyderabad<br>rank: 24<br>hazard index: 0.000876")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_25 = L.circle([26.791073, 84.560107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 871, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Bettiah<br>rank: 25<br>hazard index: 0.000872")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bettiah">Bettiah</a>')

var circle_26 = L.circle([25.220812, 86.517204], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 868, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Munger<br>rank: 26<br>hazard index: 0.000869")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Munger">Munger</a>')

var circle_27 = L.circle([26.669512, 84.957411], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 858, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Motihari<br>rank: 27<br>hazard index: 0.000859")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Motihari">Motihari</a>')

var circle_28 = L.circle([25.720581, 85.255560], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 853, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Hajipur<br>rank: 28<br>hazard index: 0.000853")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hajipur">Hajipur</a>')

var circle_29 = L.circle([27.059011, 84.206464], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 828, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Bagaha<br>rank: 29<br>hazard index: 0.000828")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagaha">Bagaha</a>')

var circle_30 = L.circle([26.716413, 88.430992], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 821, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Siliguri<br>rank: 30<br>hazard index: 0.000822")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siliguri">Siliguri</a>')

var circle_31 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 800, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Chapra<br>rank: 31<br>hazard index: 0.000800")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_32 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 768, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Dhanbad<br>rank: 32<br>hazard index: 0.000769")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_33 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 724, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Allahabad<br>rank: 33<br>hazard index: 0.000724")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_34 = L.circle([25.329791, 86.456777], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 649, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Jamalpur<br>rank: 34<br>hazard index: 0.000650")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamalpur">Jamalpur</a>')

var circle_35 = L.circle([26.022697, 83.028873], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 617, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Azamgarh<br>rank: 35<br>hazard index: 0.000618")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Azamgarh">Azamgarh</a>')

var circle_36 = L.circle([26.423847, 83.762732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 615, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Deoria<br>rank: 36<br>hazard index: 0.000615")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoria">Deoria</a>')

var circle_37 = L.circle([25.572433, 83.609605], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 607, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Medinipur<br>rank: 37<br>hazard index: 0.000608")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Medinipur">Medinipur</a>')

var circle_38 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 583, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Lucknow<br>rank: 38<br>hazard index: 0.000583")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_39 = L.circle([26.131004, 84.391257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 572, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Siwan<br>rank: 39<br>hazard index: 0.000573")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siwan">Siwan</a>')

var circle_40 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 526, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Guwahati<br>rank: 40<br>hazard index: 0.000526")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_41 = L.circle([25.560900, 87.647654], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 500, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Katihar<br>rank: 41<br>hazard index: 0.000500")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Katihar">Katihar</a>')

var circle_42 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 472, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Kanpur<br>rank: 42<br>hazard index: 0.000473")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_43 = L.circle([25.877933, 84.119959], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 452, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Ballia<br>rank: 43<br>hazard index: 0.000453")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ballia">Ballia</a>')

var circle_44 = L.circle([25.832642, 86.614893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 446, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Saharsa<br>rank: 44<br>hazard index: 0.000446")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharsa">Saharsa</a>')

var circle_45 = L.circle([25.603508, 83.507454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 434, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Ghazipur<br>rank: 45<br>hazard index: 0.000435")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ghazipur">Ghazipur</a>')

var circle_46 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 429, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Bangalore<br>rank: 46<br>hazard index: 0.000429")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_47 = L.circle([23.699128, 85.991069], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 424, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Bokaro<br>rank: 47<br>hazard index: 0.000425")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bokaro">Bokaro</a>')

var circle_48 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 398, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Nagpur<br>rank: 48<br>hazard index: 0.000399")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_49 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 396, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Asansol<br>rank: 49<br>hazard index: 0.000397")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_50 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 352, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Pune<br>rank: 50<br>hazard index: 0.000353")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_51 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 342, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Jabalpur<br>rank: 51<br>hazard index: 0.000343")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_52 = L.circle([25.795593, 82.488341], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 294, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Jaunpur<br>rank: 52<br>hazard index: 0.000295")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaunpur">Jaunpur</a>')

var circle_53 = L.circle([24.965712, 88.127778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 261, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("English Bazar<br>rank: 53<br>hazard index: 0.000261")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/English_Bazar">English Bazar</a>')

var circle_54 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 257, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Jamshedpur<br>rank: 54<br>hazard index: 0.000258")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_55 = L.circle([26.000000, 87.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 184, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Purnia<br>rank: 55<br>hazard index: 0.000184")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Purnia">Purnia</a>')

var circle_56 = L.circle([22.305199, 70.802834], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 177, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Rajkot<br>rank: 56<br>hazard index: 0.000178")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a>')

var circle_57 = L.circle([23.967515, 85.438846], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 174, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Hazaribagh<br>rank: 57<br>hazard index: 0.000175")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hazaribagh">Hazaribagh</a>')

var circle_58 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 174, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Chennai<br>rank: 58<br>hazard index: 0.000174")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_59 = L.circle([26.298638, 87.953148], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 164, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Kishanganj<br>rank: 59<br>hazard index: 0.000165")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kishanganj">Kishanganj</a>')

var circle_60 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 164, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Surat<br>rank: 60<br>hazard index: 0.000164")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_61 = L.circle([25.133173, 86.525040], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 145, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Kharagpur<br>rank: 61<br>hazard index: 0.000146")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kharagpur">Kharagpur</a>')

var circle_62 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Moradabad<br>rank: 62<br>hazard index: 0.000141")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_63 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 139, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Bhusawal<br>rank: 63<br>hazard index: 0.000139")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_64 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 136, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Nanded Waghala<br>rank: 64<br>hazard index: 0.000136")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_65 = L.circle([23.535048, 87.338043], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 134, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Durgapur<br>rank: 65<br>hazard index: 0.000135")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a>')

var circle_66 = L.circle([24.476642, 86.606732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 125, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Deoghar<br>rank: 66<br>hazard index: 0.000125")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoghar">Deoghar</a>')

var circle_67 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 124, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Raipur<br>rank: 67<br>hazard index: 0.000124")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_68 = L.circle([23.250000, 87.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 120, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Barddhaman<br>rank: 68<br>hazard index: 0.000120")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barddhaman">Barddhaman</a>')

var circle_69 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 114, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Ludhiana<br>rank: 69<br>hazard index: 0.000114")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_70 = L.circle([24.935635, 82.647701], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 112, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Mirzapur<br>rank: 70<br>hazard index: 0.000112")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mirzapur">Mirzapur</a>')

var circle_71 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 102, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Bareilly<br>rank: 71<br>hazard index: 0.000102")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_72 = L.circle([26.626484, 88.734077], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 97, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Jalpaiguri<br>rank: 72<br>hazard index: 0.000097")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalpaiguri">Jalpaiguri</a>')

var circle_73 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 93, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Thane<br>rank: 73<br>hazard index: 0.000094")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_74 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 91, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Satna<br>rank: 74<br>hazard index: 0.000091")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_75 = L.circle([27.985060, 80.753845], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 81, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Lakhimpur<br>rank: 75<br>hazard index: 0.000081")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lakhimpur">Lakhimpur</a>')

var circle_76 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 79, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Bhubaneswar<br>rank: 76<br>hazard index: 0.000080")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_77 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 78, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Agra<br>rank: 77<br>hazard index: 0.000079")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_78 = L.circle([24.197443, 82.666145], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 78, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Singrauli<br>rank: 78<br>hazard index: 0.000078")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Singrauli">Singrauli</a>')

var circle_79 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 76, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Ahmedabad<br>rank: 79<br>hazard index: 0.000077")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_80 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Nashik<br>rank: 80<br>hazard index: 0.000076")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_81 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Aligarh<br>rank: 81<br>hazard index: 0.000070")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_82 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 68, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Amritsar<br>rank: 82<br>hazard index: 0.000068")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_83 = L.circle([25.895924, 82.437716], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Badlapur<br>rank: 83<br>hazard index: 0.000062")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Badlapur">Badlapur</a>')

var circle_84 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 61, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Jhansi<br>rank: 84<br>hazard index: 0.000061")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_85 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 61, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Jalandhar<br>rank: 85<br>hazard index: 0.000061")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_86 = L.circle([26.242511, 82.296169], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Sultanpur<br>rank: 86<br>hazard index: 0.000060")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sultanpur">Sultanpur</a>')

var circle_87 = L.circle([22.591260, 88.390964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 58, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Bidhan Nagar<br>rank: 87<br>hazard index: 0.000058")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidhan_Nagar">Bidhan Nagar</a>')

var circle_88 = L.circle([20.468600, 85.879200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 57, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Cuttack<br>rank: 88<br>hazard index: 0.000058")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuttack">Cuttack</a>')

var circle_89 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 57, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Saharanpur<br>rank: 89<br>hazard index: 0.000057")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_90 = L.circle([21.977864, 76.568828], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 56, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Khandwa<br>rank: 90<br>hazard index: 0.000056")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khandwa">Khandwa</a>')

var circle_91 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 55, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Mathura<br>rank: 91<br>hazard index: 0.000056")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_92 = L.circle([27.484460, 94.901945], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 54, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Dibrugarh<br>rank: 92<br>hazard index: 0.000054")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dibrugarh">Dibrugarh</a>')

var circle_93 = L.circle([26.638076, 82.059024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Faizabad<br>rank: 93<br>hazard index: 0.000053")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faizabad">Faizabad</a>')

var circle_94 = L.circle([20.030976, 79.358139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Chandrapur<br>rank: 94<br>hazard index: 0.000053")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandrapur">Chandrapur</a>')

var circle_95 = L.circle([26.724789, 82.793269], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 52, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Basti<br>rank: 95<br>hazard index: 0.000052")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Basti">Basti</a>')

var circle_96 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Kota<br>rank: 96<br>hazard index: 0.000051")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_97 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Noida<br>rank: 97<br>hazard index: 0.000051")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_98 = L.circle([23.332200, 86.361600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Purulia<br>rank: 98<br>hazard index: 0.000050")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Purulia">Purulia</a>')

var circle_99 = L.circle([23.131954, 87.207397], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Bankura<br>rank: 99<br>hazard index: 0.000049")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bankura">Bankura</a>')

var circle_100 = L.circle([25.913591, 93.728371], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 48, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Dimapur<br>rank: 100<br>hazard index: 0.000049")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dimapur">Dimapur</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Dinapur_Nizamat">Dinapur Nizamat</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Sasaram">Sasaram</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Buxar">Buxar</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Arrah. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>