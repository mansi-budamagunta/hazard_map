---
layout: page
title: "Outbreak location: Hazaribagh"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([23.967515, 85.438846],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Hazaribagh").openTooltip();

var circle_1 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 87723, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Dehri<br>rank: 1<br>hazard index: 0.087724")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')

var circle_2 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 80353, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Patna<br>rank: 2<br>hazard index: 0.080353")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_3 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 60563, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Ranchi<br>rank: 3<br>hazard index: 0.060564")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_4 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23514, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Jamshedpur<br>rank: 4<br>hazard index: 0.023515")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_5 = L.circle([24.796436, 85.007956], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22124, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Gaya<br>rank: 5<br>hazard index: 0.022125")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a>')

var circle_6 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15716, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Dhanbad<br>rank: 6<br>hazard index: 0.015716")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_7 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10465, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Jabalpur<br>rank: 7<br>hazard index: 0.010466")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_8 = L.circle([23.535048, 87.338043], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7670, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Durgapur<br>rank: 8<br>hazard index: 0.007671")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a>')

var circle_9 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7637, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Asansol<br>rank: 9<br>hazard index: 0.007638")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_10 = L.circle([23.699128, 85.991069], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5451, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Bokaro<br>rank: 10<br>hazard index: 0.005451")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bokaro">Bokaro</a>')

var circle_11 = L.circle([25.152471, 85.006878], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5233, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Jehanabad<br>rank: 11<br>hazard index: 0.005234")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jehanabad">Jehanabad</a>')

var circle_12 = L.circle([24.900100, 84.018211], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5143, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Sasaram<br>rank: 12<br>hazard index: 0.005144")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sasaram">Sasaram</a>')

var circle_13 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4376, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Varanasi<br>rank: 13<br>hazard index: 0.004376")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_14 = L.circle([23.730215, 86.839671], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4248, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Kulti<br>rank: 14<br>hazard index: 0.004248")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kulti">Kulti</a>')

var circle_15 = L.circle([25.205305, 85.514612], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3909, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Biharsharif<br>rank: 15<br>hazard index: 0.003910")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Biharsharif">Biharsharif</a>')

var circle_16 = L.circle([25.512719, 86.090571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3307, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Begusarai<br>rank: 16<br>hazard index: 0.003307")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Begusarai">Begusarai</a>')

var circle_17 = L.circle([25.623400, 85.041700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2912, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Dinapur Nizamat<br>rank: 17<br>hazard index: 0.002912")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dinapur_Nizamat">Dinapur Nizamat</a>')

var circle_18 = L.circle([25.220812, 86.517204], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2806, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Munger<br>rank: 18<br>hazard index: 0.002807")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Munger">Munger</a>')

var circle_19 = L.circle([25.133173, 86.525040], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2725, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Kharagpur<br>rank: 19<br>hazard index: 0.002725")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kharagpur">Kharagpur</a>')

var circle_20 = L.circle([24.476642, 86.606732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2675, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Deoghar<br>rank: 20<br>hazard index: 0.002675")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoghar">Deoghar</a>')

var circle_21 = L.circle([22.782355, 86.159003], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2291, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Adityapur<br>rank: 21<br>hazard index: 0.002291")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Adityapur">Adityapur</a>')

var circle_22 = L.circle([25.623457, 84.596839], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2221, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Arrah<br>rank: 22<br>hazard index: 0.002221")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Arrah">Arrah</a>')

var circle_23 = L.circle([24.197443, 82.666145], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2186, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Singrauli<br>rank: 23<br>hazard index: 0.002187")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Singrauli">Singrauli</a>')

var circle_24 = L.circle([25.280733, 83.125128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2071, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Mughal Sarai<br>rank: 24<br>hazard index: 0.002071")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a>')

var circle_25 = L.circle([25.720581, 85.255560], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1937, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Hajipur<br>rank: 25<br>hazard index: 0.001938")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hajipur">Hajipur</a>')

var circle_26 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1897, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Delhi<br>rank: 26<br>hazard index: 0.001898")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_27 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1616, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Kolkata<br>rank: 27<br>hazard index: 0.001617")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_28 = L.circle([25.286698, 87.132254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1484, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Bhagalpur<br>rank: 28<br>hazard index: 0.001485")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a>')

var circle_29 = L.circle([25.329791, 86.456777], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1366, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Jamalpur<br>rank: 29<br>hazard index: 0.001367")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamalpur">Jamalpur</a>')

var circle_30 = L.circle([24.935635, 82.647701], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1110, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Mirzapur<br>rank: 30<br>hazard index: 0.001111")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mirzapur">Mirzapur</a>')

var circle_31 = L.circle([22.214285, 84.872437], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1010, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Raurkela<br>rank: 31<br>hazard index: 0.001011")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raurkela">Raurkela</a>')

var circle_32 = L.circle([26.083143, 86.032571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 956, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Darbhanga<br>rank: 32<br>hazard index: 0.000956")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Darbhanga">Darbhanga</a>')

var circle_33 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 803, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Muzaffarpur<br>rank: 33<br>hazard index: 0.000804")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_34 = L.circle([23.250000, 87.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 778, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Barddhaman<br>rank: 34<br>hazard index: 0.000778")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barddhaman">Barddhaman</a>')

var circle_35 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 696, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Mumbai<br>rank: 35<br>hazard index: 0.000697")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_36 = L.circle([25.560900, 87.647654], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 507, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Katihar<br>rank: 36<br>hazard index: 0.000507")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Katihar">Katihar</a>')

var circle_37 = L.circle([26.716413, 88.430992], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 491, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Siliguri<br>rank: 37<br>hazard index: 0.000492")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siliguri">Siliguri</a>')

var circle_38 = L.circle([25.562071, 84.015672], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 434, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Buxar<br>rank: 38<br>hazard index: 0.000434")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Buxar">Buxar</a>')

var circle_39 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 431, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Bangalore<br>rank: 39<br>hazard index: 0.000432")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_40 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 395, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Satna<br>rank: 40<br>hazard index: 0.000396")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_41 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 340, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Lucknow<br>rank: 41<br>hazard index: 0.000340")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_42 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 330, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Kanpur<br>rank: 42<br>hazard index: 0.000330")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_43 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 323, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Bhopal<br>rank: 43<br>hazard index: 0.000324")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_44 = L.circle([21.400000, 83.883333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 323, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Sambalpur<br>rank: 44<br>hazard index: 0.000324")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambalpur">Sambalpur</a>')

var circle_45 = L.circle([23.332200, 86.361600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 321, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Purulia<br>rank: 45<br>hazard index: 0.000322")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Purulia">Purulia</a>')

var circle_46 = L.circle([25.832642, 86.614893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 319, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Saharsa<br>rank: 46<br>hazard index: 0.000320")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharsa">Saharsa</a>')

var circle_47 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 314, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Guwahati<br>rank: 47<br>hazard index: 0.000314")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_48 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 309, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Allahabad<br>rank: 48<br>hazard index: 0.000309")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_49 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 307, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Bhubaneswar<br>rank: 49<br>hazard index: 0.000308")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_50 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 219, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Nagpur<br>rank: 50<br>hazard index: 0.000220")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_51 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 217, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Hyderabad<br>rank: 51<br>hazard index: 0.000217")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_52 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 207, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Gorakhpur<br>rank: 52<br>hazard index: 0.000208")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_53 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 204, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Agra<br>rank: 53<br>hazard index: 0.000204")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_54 = L.circle([25.680654, 88.124646], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 204, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Raiganj<br>rank: 54<br>hazard index: 0.000204")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raiganj">Raiganj</a>')

var circle_55 = L.circle([20.468600, 85.879200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 185, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Cuttack<br>rank: 55<br>hazard index: 0.000185")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuttack">Cuttack</a>')

var circle_56 = L.circle([23.131954, 87.207397], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 178, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Bankura<br>rank: 56<br>hazard index: 0.000179")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bankura">Bankura</a>')

var circle_57 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 173, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Faridabad<br>rank: 57<br>hazard index: 0.000174")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_58 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 173, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Chapra<br>rank: 58<br>hazard index: 0.000174")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_59 = L.circle([25.572433, 83.609605], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 165, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Medinipur<br>rank: 59<br>hazard index: 0.000166")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Medinipur">Medinipur</a>')

var circle_60 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 161, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Meerut<br>rank: 60<br>hazard index: 0.000162")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_61 = L.circle([23.833962, 80.392456], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 154, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Murwara<br>rank: 61<br>hazard index: 0.000155")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Murwara">Murwara</a>')

var circle_62 = L.circle([24.965712, 88.127778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 139, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("English Bazar<br>rank: 62<br>hazard index: 0.000139")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/English_Bazar">English Bazar</a>')

var circle_63 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 137, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Bilaspur<br>rank: 63<br>hazard index: 0.000138")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_64 = L.circle([26.669512, 84.957411], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 132, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Motihari<br>rank: 64<br>hazard index: 0.000132")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Motihari">Motihari</a>')

var circle_65 = L.circle([26.000000, 87.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 128, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Purnia<br>rank: 65<br>hazard index: 0.000129")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Purnia">Purnia</a>')

var circle_66 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Moradabad<br>rank: 66<br>hazard index: 0.000121")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_67 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 120, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Raipur<br>rank: 67<br>hazard index: 0.000120")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_68 = L.circle([25.954628, 83.647350], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 115, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Maunath Bhanjan<br>rank: 68<br>hazard index: 0.000116")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Maunath_Bhanjan">Maunath Bhanjan</a>')

var circle_69 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 113, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Jhansi<br>rank: 69<br>hazard index: 0.000113")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_70 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Aligarh<br>rank: 70<br>hazard index: 0.000111")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_71 = L.circle([26.131004, 84.391257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Siwan<br>rank: 71<br>hazard index: 0.000110")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siwan">Siwan</a>')

var circle_72 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 108, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Gurgaon<br>rank: 72<br>hazard index: 0.000108")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_73 = L.circle([23.122634, 83.198189], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 108, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Ambikapur<br>rank: 73<br>hazard index: 0.000108")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambikapur">Ambikapur</a>')

var circle_74 = L.circle([26.791073, 84.560107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 104, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Bettiah<br>rank: 74<br>hazard index: 0.000104")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bettiah">Bettiah</a>')

var circle_75 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 99, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Chennai<br>rank: 75<br>hazard index: 0.000100")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_76 = L.circle([27.059011, 84.206464], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 99, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Bagaha<br>rank: 76<br>hazard index: 0.000099")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagaha">Bagaha</a>')

var circle_77 = L.circle([25.795593, 82.488341], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 97, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Jaunpur<br>rank: 77<br>hazard index: 0.000097")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaunpur">Jaunpur</a>')

var circle_78 = L.circle([26.298638, 87.953148], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 96, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Kishanganj<br>rank: 78<br>hazard index: 0.000097")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kishanganj">Kishanganj</a>')

var circle_79 = L.circle([24.759267, 81.655000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 93, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Rewa<br>rank: 79<br>hazard index: 0.000093")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewa">Rewa</a>')

var circle_80 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 91, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Saharanpur<br>rank: 80<br>hazard index: 0.000092")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_81 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 82, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Kota<br>rank: 81<br>hazard index: 0.000083")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_82 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 81, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Jaipur<br>rank: 82<br>hazard index: 0.000082")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_83 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 79, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Noida<br>rank: 83<br>hazard index: 0.000079")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_84 = L.circle([23.750000, 79.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 78, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Damoh<br>rank: 84<br>hazard index: 0.000079")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Damoh">Damoh</a>')

var circle_85 = L.circle([26.423847, 83.762732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 77, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Deoria<br>rank: 85<br>hazard index: 0.000078")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoria">Deoria</a>')

var circle_86 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Firozabad<br>rank: 86<br>hazard index: 0.000076")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_87 = L.circle([21.063329, 86.505373], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 74, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Bhadrak<br>rank: 87<br>hazard index: 0.000074")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhadrak">Bhadrak</a>')

var circle_88 = L.circle([22.472223, 88.093845], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 71, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Uluberia<br>rank: 88<br>hazard index: 0.000072")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Uluberia">Uluberia</a>')

var circle_89 = L.circle([21.500000, 86.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 71, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Baleshwar<br>rank: 89<br>hazard index: 0.000072")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baleshwar">Baleshwar</a>')

var circle_90 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 65, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Thane<br>rank: 90<br>hazard index: 0.000066")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_91 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 63, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Loni<br>rank: 91<br>hazard index: 0.000063")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_92 = L.circle([25.877933, 84.119959], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Ballia<br>rank: 92<br>hazard index: 0.000062")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ballia">Ballia</a>')

var circle_93 = L.circle([23.809612, 78.759114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 61, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Sagar<br>rank: 93<br>hazard index: 0.000062")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sagar">Sagar</a>')

var circle_94 = L.circle([25.603508, 83.507454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 60, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Ghazipur<br>rank: 94<br>hazard index: 0.000061")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ghazipur">Ghazipur</a>')

var circle_95 = L.circle([22.500000, 83.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 56, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Raigarh<br>rank: 95<br>hazard index: 0.000057")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raigarh">Raigarh</a>')

var circle_96 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 55, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Ahmedabad<br>rank: 96<br>hazard index: 0.000055")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_97 = L.circle([19.807608, 85.825254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 54, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Puri<br>rank: 97<br>hazard index: 0.000054")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Puri">Puri</a>')

var circle_98 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Nashik<br>rank: 98<br>hazard index: 0.000053")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_99 = L.circle([21.200996, 81.335426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 52, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Bhilai Nagar<br>rank: 99<br>hazard index: 0.000052")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhilai_Nagar">Bhilai Nagar</a>')

var circle_100 = L.circle([26.626484, 88.734077], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Jalpaiguri<br>rank: 100<br>hazard index: 0.000051")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalpaiguri">Jalpaiguri</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bokaro">Bokaro</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Hazaribagh. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>