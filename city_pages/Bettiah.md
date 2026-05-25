---
layout: page
title: "Outbreak location: Bettiah"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([26.791073, 84.560107],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Bettiah").openTooltip();

var circle_1 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 87917, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Muzaffarpur<br>rank: 1<br>hazard index: 0.087917")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_2 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 74764, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Gorakhpur<br>rank: 2<br>hazard index: 0.074765")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_3 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 52186, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Delhi<br>rank: 3<br>hazard index: 0.052186")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_4 = L.circle([26.669512, 84.957411], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40619, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Motihari<br>rank: 4<br>hazard index: 0.040619")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Motihari">Motihari</a>')

var circle_5 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26032, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Patna<br>rank: 5<br>hazard index: 0.026032")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_6 = L.circle([27.059011, 84.206464], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12789, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Bagaha<br>rank: 6<br>hazard index: 0.012790")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagaha">Bagaha</a>')

var circle_7 = L.circle([26.083143, 86.032571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10721, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Darbhanga<br>rank: 7<br>hazard index: 0.010721")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Darbhanga">Darbhanga</a>')

var circle_8 = L.circle([26.055318, 82.993139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4801, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Nizamabad<br>rank: 8<br>hazard index: 0.004802")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a>')

var circle_9 = L.circle([25.205305, 85.514612], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4591, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Biharsharif<br>rank: 9<br>hazard index: 0.004592")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Biharsharif">Biharsharif</a>')

var circle_10 = L.circle([25.954628, 83.647350], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4438, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Maunath Bhanjan<br>rank: 10<br>hazard index: 0.004438")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Maunath_Bhanjan">Maunath Bhanjan</a>')

var circle_11 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4054, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Bareilly<br>rank: 11<br>hazard index: 0.004054")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_12 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4051, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Moradabad<br>rank: 12<br>hazard index: 0.004052")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_13 = L.circle([25.623457, 84.596839], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4038, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Arrah<br>rank: 13<br>hazard index: 0.004038")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Arrah">Arrah</a>')

var circle_14 = L.circle([26.269721, 82.994425], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3261, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Burhanpur<br>rank: 14<br>hazard index: 0.003262")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Burhanpur">Burhanpur</a>')

var circle_15 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3117, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Chapra<br>rank: 15<br>hazard index: 0.003118")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_16 = L.circle([25.623400, 85.041700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2818, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Dinapur Nizamat<br>rank: 16<br>hazard index: 0.002819")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dinapur_Nizamat">Dinapur Nizamat</a>')

var circle_17 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2774, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Varanasi<br>rank: 17<br>hazard index: 0.002775")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_18 = L.circle([25.286698, 87.132254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2707, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Bhagalpur<br>rank: 18<br>hazard index: 0.002707")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a>')

var circle_19 = L.circle([25.572433, 83.609605], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2615, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Medinipur<br>rank: 19<br>hazard index: 0.002616")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Medinipur">Medinipur</a>')

var circle_20 = L.circle([25.720581, 85.255560], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2275, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Hajipur<br>rank: 20<br>hazard index: 0.002275")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hajipur">Hajipur</a>')

var circle_21 = L.circle([27.985060, 80.753845], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2178, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Lakhimpur<br>rank: 21<br>hazard index: 0.002179")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lakhimpur">Lakhimpur</a>')

var circle_22 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2120, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Lucknow<br>rank: 22<br>hazard index: 0.002120")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_23 = L.circle([26.131004, 84.391257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2079, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Siwan<br>rank: 23<br>hazard index: 0.002080")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siwan">Siwan</a>')

var circle_24 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1817, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Mumbai<br>rank: 24<br>hazard index: 0.001817")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_25 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1745, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Kolkata<br>rank: 25<br>hazard index: 0.001746")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_26 = L.circle([26.724789, 82.793269], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1639, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Basti<br>rank: 26<br>hazard index: 0.001640")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Basti">Basti</a>')

var circle_27 = L.circle([26.423847, 83.762732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1507, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Deoria<br>rank: 27<br>hazard index: 0.001507")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoria">Deoria</a>')

var circle_28 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1462, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Shahjahanpur<br>rank: 28<br>hazard index: 0.001463")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_29 = L.circle([26.022697, 83.028873], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1456, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Azamgarh<br>rank: 29<br>hazard index: 0.001456")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Azamgarh">Azamgarh</a>')

var circle_30 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1396, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Rampur<br>rank: 30<br>hazard index: 0.001396")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_31 = L.circle([25.152471, 85.006878], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1336, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Jehanabad<br>rank: 31<br>hazard index: 0.001336")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jehanabad">Jehanabad</a>')

var circle_32 = L.circle([24.796436, 85.007956], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1327, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Gaya<br>rank: 32<br>hazard index: 0.001327")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a>')

var circle_33 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1143, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Kanpur<br>rank: 33<br>hazard index: 0.001143")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_34 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1126, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Hapur<br>rank: 34<br>hazard index: 0.001126")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_35 = L.circle([25.562071, 84.015672], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1086, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Buxar<br>rank: 35<br>hazard index: 0.001087")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Buxar">Buxar</a>')

var circle_36 = L.circle([25.877933, 84.119959], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1068, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Ballia<br>rank: 36<br>hazard index: 0.001068")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ballia">Ballia</a>')

var circle_37 = L.circle([25.603508, 83.507454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1025, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Ghazipur<br>rank: 37<br>hazard index: 0.001026")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ghazipur">Ghazipur</a>')

var circle_38 = L.circle([25.512719, 86.090571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 948, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Begusarai<br>rank: 38<br>hazard index: 0.000948")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Begusarai">Begusarai</a>')

var circle_39 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 864, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Jhansi<br>rank: 39<br>hazard index: 0.000864")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_40 = L.circle([28.923397, 78.488317], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 841, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Amroha<br>rank: 40<br>hazard index: 0.000841")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amroha">Amroha</a>')

var circle_41 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 811, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Khora<br>rank: 41<br>hazard index: 0.000812")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_42 = L.circle([27.504639, 80.829466], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 795, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Sitapur<br>rank: 42<br>hazard index: 0.000796")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sitapur">Sitapur</a>')

var circle_43 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 737, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Gurgaon<br>rank: 43<br>hazard index: 0.000738")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_44 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 677, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Faridabad<br>rank: 44<br>hazard index: 0.000677")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_45 = L.circle([27.109667, 81.918329], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 615, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Gonda<br>rank: 45<br>hazard index: 0.000615")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gonda">Gonda</a>')

var circle_46 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 536, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Rohtak<br>rank: 46<br>hazard index: 0.000537")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_47 = L.circle([25.560900, 87.647654], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 513, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Katihar<br>rank: 47<br>hazard index: 0.000513")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Katihar">Katihar</a>')

var circle_48 = L.circle([25.832642, 86.614893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 512, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Saharsa<br>rank: 48<br>hazard index: 0.000512")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharsa">Saharsa</a>')

var circle_49 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 505, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Nanded Waghala<br>rank: 49<br>hazard index: 0.000506")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_50 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 491, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Allahabad<br>rank: 50<br>hazard index: 0.000492")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_51 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 471, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Ludhiana<br>rank: 51<br>hazard index: 0.000472")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_52 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 471, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Bangalore<br>rank: 52<br>hazard index: 0.000471")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_53 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 454, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Meerut<br>rank: 53<br>hazard index: 0.000454")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_54 = L.circle([26.716413, 88.430992], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 420, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Siliguri<br>rank: 54<br>hazard index: 0.000420")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siliguri">Siliguri</a>')

var circle_55 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 383, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Hyderabad<br>rank: 55<br>hazard index: 0.000384")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_56 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 350, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Saharanpur<br>rank: 56<br>hazard index: 0.000351")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_57 = L.circle([26.000000, 87.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 342, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Purnia<br>rank: 57<br>hazard index: 0.000343")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Purnia">Purnia</a>')

var circle_58 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 338, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Ahmedabad<br>rank: 58<br>hazard index: 0.000339")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_59 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 330, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Agra<br>rank: 59<br>hazard index: 0.000330")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_60 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 324, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Bhusawal<br>rank: 60<br>hazard index: 0.000324")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_61 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 321, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Asansol<br>rank: 61<br>hazard index: 0.000321")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_62 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 320, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Jaipur<br>rank: 62<br>hazard index: 0.000320")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_63 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 302, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Aligarh<br>rank: 63<br>hazard index: 0.000302")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_64 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 299, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Sonipat<br>rank: 64<br>hazard index: 0.000300")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_65 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 297, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Loni<br>rank: 65<br>hazard index: 0.000298")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_66 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 287, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Chennai<br>rank: 66<br>hazard index: 0.000288")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_67 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 280, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Pune<br>rank: 67<br>hazard index: 0.000281")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_68 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 278, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Chandigarh<br>rank: 68<br>hazard index: 0.000278")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_69 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 276, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Surat<br>rank: 69<br>hazard index: 0.000276")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_70 = L.circle([25.329791, 86.456777], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 274, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Jamalpur<br>rank: 70<br>hazard index: 0.000275")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamalpur">Jamalpur</a>')

var circle_71 = L.circle([29.211757, 78.961731], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 268, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Kashipur<br>rank: 71<br>hazard index: 0.000268")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kashipur">Kashipur</a>')

var circle_72 = L.circle([24.900100, 84.018211], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 246, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Sasaram<br>rank: 72<br>hazard index: 0.000247")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sasaram">Sasaram</a>')

var circle_73 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 238, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Amritsar<br>rank: 73<br>hazard index: 0.000238")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_74 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 236, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Bahadurgarh<br>rank: 74<br>hazard index: 0.000237")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_75 = L.circle([23.535048, 87.338043], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 220, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Durgapur<br>rank: 75<br>hazard index: 0.000221")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a>')

var circle_76 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 219, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Panipat<br>rank: 76<br>hazard index: 0.000219")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_77 = L.circle([23.131954, 87.207397], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 212, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Bankura<br>rank: 77<br>hazard index: 0.000213")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bankura">Bankura</a>')

var circle_78 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 211, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Jalandhar<br>rank: 78<br>hazard index: 0.000211")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_79 = L.circle([25.133173, 86.525040], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 200, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Kharagpur<br>rank: 79<br>hazard index: 0.000201")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kharagpur">Kharagpur</a>')

var circle_80 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 197, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Ranchi<br>rank: 80<br>hazard index: 0.000198")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_81 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 190, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Thane<br>rank: 81<br>hazard index: 0.000191")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_82 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 189, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Guwahati<br>rank: 82<br>hazard index: 0.000189")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_83 = L.circle([25.280733, 83.125128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 184, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Mughal Sarai<br>rank: 83<br>hazard index: 0.000184")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a>')

var circle_84 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 178, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Jabalpur<br>rank: 84<br>hazard index: 0.000178")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_85 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 176, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Bhopal<br>rank: 85<br>hazard index: 0.000176")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_86 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 174, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Raipur<br>rank: 86<br>hazard index: 0.000175")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_87 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 174, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Dhanbad<br>rank: 87<br>hazard index: 0.000174")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_88 = L.circle([18.434644, 79.132265], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 173, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Karimnagar<br>rank: 88<br>hazard index: 0.000174")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karimnagar">Karimnagar</a>')

var circle_89 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 170, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Jind<br>rank: 89<br>hazard index: 0.000170")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_90 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 167, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Vasco Da Gama<br>rank: 90<br>hazard index: 0.000167")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_91 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 162, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Muzaffarnagar<br>rank: 91<br>hazard index: 0.000162")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_92 = L.circle([29.680327, 76.989625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 150, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Karnal<br>rank: 92<br>hazard index: 0.000151")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karnal">Karnal</a>')

var circle_93 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 149, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Nashik<br>rank: 93<br>hazard index: 0.000150")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_94 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 148, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Noida<br>rank: 94<br>hazard index: 0.000149")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_95 = L.circle([34.074744, 74.820444], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 146, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Srinagar<br>rank: 95<br>hazard index: 0.000147")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srinagar">Srinagar</a>')

var circle_96 = L.circle([27.733696, 81.477321], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Bahraich<br>rank: 96<br>hazard index: 0.000142")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahraich">Bahraich</a>')

var circle_97 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 136, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Nagpur<br>rank: 97<br>hazard index: 0.000137")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_98 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 135, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Firozabad<br>rank: 98<br>hazard index: 0.000135")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_99 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 132, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Bhubaneswar<br>rank: 99<br>hazard index: 0.000133")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_100 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 131, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Dehradun<br>rank: 100<br>hazard index: 0.000132")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Motihari">Motihari</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bagaha">Bagaha</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Darbhanga">Darbhanga</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Biharsharif">Biharsharif</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Maunath_Bhanjan">Maunath Bhanjan</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Bettiah. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>