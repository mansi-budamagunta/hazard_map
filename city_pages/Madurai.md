---
layout: page
title: "Outbreak location: Madurai"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([9.926115, 78.114098],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Madurai").openTooltip();

var circle_1 = L.circle([8.701220, 77.579269], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 63938, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Tirunelveli<br>rank: 1<br>hazard index: 0.063938")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tirunelveli">Tirunelveli</a>')

var circle_2 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44415, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Coimbatore<br>rank: 2<br>hazard index: 0.044415")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_3 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42195, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Chennai<br>rank: 3<br>hazard index: 0.042196")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_4 = L.circle([10.804973, 78.687030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 37032, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Tiruchirappalli<br>rank: 4<br>hazard index: 0.037033")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruchirappalli">Tiruchirappalli</a>')

var circle_5 = L.circle([9.403158, 77.518264], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 33615, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Rajapalayam<br>rank: 5<br>hazard index: 0.033616")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajapalayam">Rajapalayam</a>')

var circle_6 = L.circle([8.576971, 77.050125], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30724, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Thiruvananthapuram<br>rank: 6<br>hazard index: 0.030725")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thiruvananthapuram">Thiruvananthapuram</a>')

var circle_7 = L.circle([10.330330, 78.067398], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24569, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Dindigul<br>rank: 7<br>hazard index: 0.024569")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dindigul">Dindigul</a>')

var circle_8 = L.circle([8.805260, 78.145274], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18614, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Thoothukudi<br>rank: 8<br>hazard index: 0.018614")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thoothukudi">Thoothukudi</a>')

var circle_9 = L.circle([8.188047, 77.429049], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11545, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Nagercoil<br>rank: 9<br>hazard index: 0.011546")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagercoil">Nagercoil</a>')

var circle_10 = L.circle([8.887951, 76.595501], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6842, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Kollam<br>rank: 10<br>hazard index: 0.006843")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kollam">Kollam</a>')

var circle_11 = L.circle([11.101781, 77.345192], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5334, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Tiruppur<br>rank: 11<br>hazard index: 0.005335")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruppur">Tiruppur</a>')

var circle_12 = L.circle([10.786027, 79.138150], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5240, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Thanjavur<br>rank: 12<br>hazard index: 0.005241")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thanjavur">Thanjavur</a>')

var circle_13 = L.circle([11.369204, 77.676627], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4355, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Erode<br>rank: 13<br>hazard index: 0.004356")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Erode">Erode</a>')

var circle_14 = L.circle([11.664300, 78.146000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3988, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Salem<br>rank: 14<br>hazard index: 0.003988")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Salem">Salem</a>')

var circle_15 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3554, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Bangalore<br>rank: 15<br>hazard index: 0.003555")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_16 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3407, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Delhi<br>rank: 16<br>hazard index: 0.003408")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_17 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3402, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Mumbai<br>rank: 17<br>hazard index: 0.003402")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_18 = L.circle([9.500665, 76.412414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3164, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Alappuzha<br>rank: 18<br>hazard index: 0.003164")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alappuzha">Alappuzha</a>')

var circle_19 = L.circle([10.964555, 79.371730], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3119, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Kumbakonam<br>rank: 19<br>hazard index: 0.003120")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kumbakonam">Kumbakonam</a>')

var circle_20 = L.circle([10.787898, 76.474087], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3083, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Palakkad<br>rank: 20<br>hazard index: 0.003084")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palakkad">Palakkad</a>')

var circle_21 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2874, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Hyderabad<br>rank: 21<br>hazard index: 0.002874")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_22 = L.circle([10.500000, 78.833333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2028, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Pudukkottai<br>rank: 22<br>hazard index: 0.002028")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pudukkottai">Pudukkottai</a>')

var circle_23 = L.circle([10.525626, 76.213254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1874, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Thrissur<br>rank: 23<br>hazard index: 0.001875")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thrissur">Thrissur</a>')

var circle_24 = L.circle([10.044512, 78.743363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1697, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Karaikkudi<br>rank: 24<br>hazard index: 0.001697")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karaikkudi">Karaikkudi</a>')

var circle_25 = L.circle([10.346837, 78.654771], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1460, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Neiveli<br>rank: 25<br>hazard index: 0.001460")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Neiveli">Neiveli</a>')

var circle_26 = L.circle([11.258608, 75.778874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1182, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Kozhikode<br>rank: 26<br>hazard index: 0.001182")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kozhikode">Kozhikode</a>')

var circle_27 = L.circle([10.805628, 79.824660], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1132, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Nagapattinam<br>rank: 27<br>hazard index: 0.001132")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagapattinam">Nagapattinam</a>')

var circle_28 = L.circle([13.631637, 79.423171], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 904, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Tirupati<br>rank: 28<br>hazard index: 0.000904")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tirupati">Tirupati</a>')

var circle_29 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 858, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Jhansi<br>rank: 29<br>hazard index: 0.000859")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_30 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 803, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Kochi<br>rank: 30<br>hazard index: 0.000803")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_31 = L.circle([13.125476, 80.094090], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 602, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Avadi<br>rank: 31<br>hazard index: 0.000603")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Avadi">Avadi</a>')

var circle_32 = L.circle([13.156387, 80.300528], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 574, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Tiruvottiyur<br>rank: 32<br>hazard index: 0.000575")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruvottiyur">Tiruvottiyur</a>')

var circle_33 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 448, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Nagpur<br>rank: 33<br>hazard index: 0.000449")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_34 = L.circle([11.715950, 79.767053], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 429, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Cuddalore Port<br>rank: 34<br>hazard index: 0.000429")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuddalore_Port">Cuddalore Port</a>')

var circle_35 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 416, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Kolkata<br>rank: 35<br>hazard index: 0.000416")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_36 = L.circle([12.869810, 74.843008], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 405, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Mangalore<br>rank: 36<br>hazard index: 0.000405")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mangalore">Mangalore</a>')

var circle_37 = L.circle([12.929903, 80.111823], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 368, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Tambaram<br>rank: 37<br>hazard index: 0.000368")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tambaram">Tambaram</a>')

var circle_38 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 335, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Bhopal<br>rank: 38<br>hazard index: 0.000335")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_39 = L.circle([14.449372, 79.987376], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 327, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Nellore<br>rank: 39<br>hazard index: 0.000327")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nellore">Nellore</a>')

var circle_40 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 307, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Vijayawada<br>rank: 40<br>hazard index: 0.000308")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_41 = L.circle([12.794811, 79.000641], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 304, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Vellore<br>rank: 41<br>hazard index: 0.000305")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vellore">Vellore</a>')

var circle_42 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 303, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Pune<br>rank: 42<br>hazard index: 0.000303")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_43 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 275, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Ahmedabad<br>rank: 43<br>hazard index: 0.000275")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_44 = L.circle([12.989816, 80.100987], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 253, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Pallavaram<br>rank: 44<br>hazard index: 0.000254")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pallavaram">Pallavaram</a>')

var circle_45 = L.circle([12.227213, 79.070156], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 237, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Tiruvannamalai<br>rank: 45<br>hazard index: 0.000237")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruvannamalai">Tiruvannamalai</a>')

var circle_46 = L.circle([10.915649, 79.806949], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 226, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Pondicherry<br>rank: 46<br>hazard index: 0.000226")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pondicherry">Pondicherry</a>')

var circle_47 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 220, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Surat<br>rank: 47<br>hazard index: 0.000221")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_48 = L.circle([11.876225, 75.373804], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 215, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Kannur<br>rank: 48<br>hazard index: 0.000216")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kannur">Kannur</a>')

var circle_49 = L.circle([12.792907, 78.699917], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 195, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Ambur<br>rank: 49<br>hazard index: 0.000195")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambur">Ambur</a>')

var circle_50 = L.circle([12.305183, 76.655361], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 192, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Mysore<br>rank: 50<br>hazard index: 0.000192")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mysore">Mysore</a>')

var circle_51 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 190, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Thane<br>rank: 51<br>hazard index: 0.000190")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_52 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 181, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Visakhapatnam<br>rank: 52<br>hazard index: 0.000182")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_53 = L.circle([11.664535, 92.739045], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 148, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Port Blair<br>rank: 53<br>hazard index: 0.000149")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Port_Blair">Port Blair</a>')

var circle_54 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 139, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Agra<br>rank: 54<br>hazard index: 0.000140")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_55 = L.circle([12.836393, 79.705330], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 134, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Kanchipuram<br>rank: 55<br>hazard index: 0.000134")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanchipuram">Kanchipuram</a>')

var circle_56 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 130, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Jaipur<br>rank: 56<br>hazard index: 0.000131")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_57 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 113, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Meerut<br>rank: 57<br>hazard index: 0.000114")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_58 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Bhubaneswar<br>rank: 58<br>hazard index: 0.000110")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_59 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 91, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Gwalior<br>rank: 59<br>hazard index: 0.000092")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_60 = L.circle([13.340077, 77.100621], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 90, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Tumkur<br>rank: 60<br>hazard index: 0.000091")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tumkur">Tumkur</a>')

var circle_61 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 82, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Vadodara<br>rank: 61<br>hazard index: 0.000082")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_62 = L.circle([13.160105, 79.155551], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 81, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Chittoor<br>rank: 62<br>hazard index: 0.000081")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chittoor">Chittoor</a>')

var circle_63 = L.circle([17.980609, 79.598212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 80, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Warangal<br>rank: 63<br>hazard index: 0.000080")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Warangal">Warangal</a>')

var circle_64 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 78, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Guwahati<br>rank: 64<br>hazard index: 0.000078")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_65 = L.circle([15.830925, 78.042537], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Kurnool<br>rank: 65<br>hazard index: 0.000075")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kurnool">Kurnool</a>')

var circle_66 = L.circle([16.291519, 80.454159], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 73, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Guntur<br>rank: 66<br>hazard index: 0.000073")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guntur">Guntur</a>')

var circle_67 = L.circle([17.849907, 75.276320], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 67, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Solapur<br>rank: 67<br>hazard index: 0.000068")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a>')

var circle_68 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 67, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Vasco Da Gama<br>rank: 68<br>hazard index: 0.000067")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_69 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 64, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Kanpur<br>rank: 69<br>hazard index: 0.000065")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_70 = L.circle([22.305199, 70.802834], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 63, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Rajkot<br>rank: 70<br>hazard index: 0.000064")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a>')

var circle_71 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 61, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Saharanpur<br>rank: 71<br>hazard index: 0.000061")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_72 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Faridabad<br>rank: 72<br>hazard index: 0.000060")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_73 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 58, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Dehradun<br>rank: 73<br>hazard index: 0.000059")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_74 = L.circle([17.005045, 81.780473], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 57, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Rajahmundry<br>rank: 74<br>hazard index: 0.000058")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajahmundry">Rajahmundry</a>')

var circle_75 = L.circle([15.507554, 80.060800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Ongole<br>rank: 75<br>hazard index: 0.000049")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ongole">Ongole</a>')

var circle_76 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 48, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Gurgaon<br>rank: 76<br>hazard index: 0.000048")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_77 = L.circle([26.055318, 82.993139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 48, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Nizamabad<br>rank: 77<br>hazard index: 0.000048")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a>')

var circle_78 = L.circle([18.627929, 73.800983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 47, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Pimpri Chinchwad<br>rank: 78<br>hazard index: 0.000048")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pimpri_Chinchwad">Pimpri Chinchwad</a>')

var circle_79 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 46, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Nashik<br>rank: 79<br>hazard index: 0.000047")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_80 = L.circle([12.955100, 78.269900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Robertson Pet<br>rank: 80<br>hazard index: 0.000045")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Robertson_Pet">Robertson Pet</a>')

var circle_81 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Lucknow<br>rank: 81<br>hazard index: 0.000045")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_82 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Kota<br>rank: 82<br>hazard index: 0.000043")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_83 = L.circle([14.475294, 78.821686], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Kadapa<br>rank: 83<br>hazard index: 0.000042")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kadapa">Kadapa</a>')

var circle_84 = L.circle([19.439885, 72.880383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Vasai<br>rank: 84<br>hazard index: 0.000041")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a>')

var circle_85 = L.circle([16.743454, 77.992319], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Mahbubnagar<br>rank: 85<br>hazard index: 0.000040")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mahbubnagar">Mahbubnagar</a>')

var circle_86 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 35, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Rohtak<br>rank: 86<br>hazard index: 0.000035")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_87 = L.circle([18.761516, 79.478785], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 34, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Ramagundam<br>rank: 87<br>hazard index: 0.000035")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ramagundam">Ramagundam</a>')

var circle_88 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 34, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Muzaffarnagar<br>rank: 88<br>hazard index: 0.000034")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_89 = L.circle([16.237773, 80.646422], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 33, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Tenali<br>rank: 89<br>hazard index: 0.000033")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tenali">Tenali</a>')

var circle_90 = L.circle([12.523889, 76.896196], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 33, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Mandya<br>rank: 90<br>hazard index: 0.000033")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mandya">Mandya</a>')

var circle_91 = L.circle([14.654623, 77.556260], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 32, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Anantapur<br>rank: 91<br>hazard index: 0.000033")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Anantapur">Anantapur</a>')

var circle_92 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 31, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Indore<br>rank: 92<br>hazard index: 0.000031")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_93 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Ludhiana<br>rank: 93<br>hazard index: 0.000031")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_94 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Moradabad<br>rank: 94<br>hazard index: 0.000031")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_95 = L.circle([12.732884, 77.830948], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Hosur<br>rank: 95<br>hazard index: 0.000030")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hosur">Hosur</a>')

var circle_96 = L.circle([17.910400, 77.519900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Bidar<br>rank: 96<br>hazard index: 0.000029")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidar">Bidar</a>')

var circle_97 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Bikaner<br>rank: 97<br>hazard index: 0.000028")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_98 = L.circle([17.166667, 77.083333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Gulbarga<br>rank: 98<br>hazard index: 0.000027")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gulbarga">Gulbarga</a>')

var circle_99 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Nanded Waghala<br>rank: 99<br>hazard index: 0.000027")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_100 = L.circle([22.473242, 70.055210], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Jamnagar<br>rank: 100<br>hazard index: 0.000026")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamnagar">Jamnagar</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Tirunelveli">Tirunelveli</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Tiruchirappalli">Tiruchirappalli</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Rajapalayam">Rajapalayam</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Thiruvananthapuram">Thiruvananthapuram</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Dindigul">Dindigul</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Thoothukudi">Thoothukudi</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Nagercoil">Nagercoil</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kollam">Kollam</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Madurai. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>