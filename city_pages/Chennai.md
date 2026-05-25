---
layout: page
title: "Outbreak location: Chennai"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([13.083694, 80.270186],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Chennai").openTooltip();

var circle_1 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 32453, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Bangalore<br>rank: 1<br>hazard index: 0.032454")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_2 = L.circle([10.804973, 78.687030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24841, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Tiruchirappalli<br>rank: 2<br>hazard index: 0.024841")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruchirappalli">Tiruchirappalli</a>')

var circle_3 = L.circle([13.631637, 79.423171], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21425, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Tirupati<br>rank: 3<br>hazard index: 0.021426")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tirupati">Tirupati</a>')

var circle_4 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18934, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Mumbai<br>rank: 4<br>hazard index: 0.018935")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_5 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18833, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Delhi<br>rank: 5<br>hazard index: 0.018834")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_6 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17886, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Coimbatore<br>rank: 6<br>hazard index: 0.017886")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_7 = L.circle([9.926115, 78.114098], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17859, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Madurai<br>rank: 7<br>hazard index: 0.017860")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Madurai">Madurai</a>')

var circle_8 = L.circle([11.664300, 78.146000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14890, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Salem<br>rank: 8<br>hazard index: 0.014890")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Salem">Salem</a>')

var circle_9 = L.circle([13.125476, 80.094090], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14285, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Avadi<br>rank: 9<br>hazard index: 0.014286")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Avadi">Avadi</a>')

var circle_10 = L.circle([13.156387, 80.300528], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13622, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Tiruvottiyur<br>rank: 10<br>hazard index: 0.013622")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruvottiyur">Tiruvottiyur</a>')

var circle_11 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13178, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Hyderabad<br>rank: 11<br>hazard index: 0.013179")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_12 = L.circle([11.715950, 79.767053], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10174, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Cuddalore Port<br>rank: 12<br>hazard index: 0.010175")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuddalore_Port">Cuddalore Port</a>')

var circle_13 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9868, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Kolkata<br>rank: 13<br>hazard index: 0.009869")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_14 = L.circle([12.929903, 80.111823], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8727, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Tambaram<br>rank: 14<br>hazard index: 0.008728")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tambaram">Tambaram</a>')

var circle_15 = L.circle([14.449372, 79.987376], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7760, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Nellore<br>rank: 15<br>hazard index: 0.007760")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nellore">Nellore</a>')

var circle_16 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7296, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Vijayawada<br>rank: 16<br>hazard index: 0.007296")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_17 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7183, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Pune<br>rank: 17<br>hazard index: 0.007184")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_18 = L.circle([12.989816, 80.100987], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6016, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Pallavaram<br>rank: 18<br>hazard index: 0.006017")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pallavaram">Pallavaram</a>')

var circle_19 = L.circle([8.576971, 77.050125], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4739, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Thiruvananthapuram<br>rank: 19<br>hazard index: 0.004739")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thiruvananthapuram">Thiruvananthapuram</a>')

var circle_20 = L.circle([11.101781, 77.345192], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4690, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Tiruppur<br>rank: 20<br>hazard index: 0.004690")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruppur">Tiruppur</a>')

var circle_21 = L.circle([12.792907, 78.699917], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4630, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Ambur<br>rank: 21<br>hazard index: 0.004630")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambur">Ambur</a>')

var circle_22 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4305, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Visakhapatnam<br>rank: 22<br>hazard index: 0.004306")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_23 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4021, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Ahmedabad<br>rank: 23<br>hazard index: 0.004022")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_24 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3754, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Kochi<br>rank: 24<br>hazard index: 0.003755")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_25 = L.circle([11.664535, 92.739045], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3525, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Port Blair<br>rank: 25<br>hazard index: 0.003526")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Port_Blair">Port Blair</a>')

var circle_26 = L.circle([10.915649, 79.806949], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3519, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Pondicherry<br>rank: 26<br>hazard index: 0.003520")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pondicherry">Pondicherry</a>')

var circle_27 = L.circle([10.786027, 79.138150], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3515, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Thanjavur<br>rank: 27<br>hazard index: 0.003516")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thanjavur">Thanjavur</a>')

var circle_28 = L.circle([12.836393, 79.705330], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3179, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Kanchipuram<br>rank: 28<br>hazard index: 0.003179")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanchipuram">Kanchipuram</a>')

var circle_29 = L.circle([10.330330, 78.067398], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2992, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Dindigul<br>rank: 29<br>hazard index: 0.002993")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dindigul">Dindigul</a>')

var circle_30 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2613, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Bhubaneswar<br>rank: 30<br>hazard index: 0.002614")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_31 = L.circle([8.701220, 77.579269], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2611, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Tirunelveli<br>rank: 31<br>hazard index: 0.002612")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tirunelveli">Tirunelveli</a>')

var circle_32 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2269, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Jhansi<br>rank: 32<br>hazard index: 0.002269")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_33 = L.circle([11.369204, 77.676627], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2191, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Erode<br>rank: 33<br>hazard index: 0.002192")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Erode">Erode</a>')

var circle_34 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1949, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Nagpur<br>rank: 34<br>hazard index: 0.001949")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_35 = L.circle([13.160105, 79.155551], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1930, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Chittoor<br>rank: 35<br>hazard index: 0.001931")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chittoor">Chittoor</a>')

var circle_36 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1852, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Guwahati<br>rank: 36<br>hazard index: 0.001853")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_37 = L.circle([12.869810, 74.843008], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1780, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Mangalore<br>rank: 37<br>hazard index: 0.001780")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mangalore">Mangalore</a>')

var circle_38 = L.circle([16.291519, 80.454159], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1733, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Guntur<br>rank: 38<br>hazard index: 0.001734")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guntur">Guntur</a>')

var circle_39 = L.circle([10.964555, 79.371730], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1721, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Kumbakonam<br>rank: 39<br>hazard index: 0.001721")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kumbakonam">Kumbakonam</a>')

var circle_40 = L.circle([11.258608, 75.778874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1682, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Kozhikode<br>rank: 40<br>hazard index: 0.001682")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kozhikode">Kozhikode</a>')

var circle_41 = L.circle([8.887951, 76.595501], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1610, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Kollam<br>rank: 41<br>hazard index: 0.001611")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kollam">Kollam</a>')

var circle_42 = L.circle([10.525626, 76.213254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1608, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Thrissur<br>rank: 42<br>hazard index: 0.001609")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thrissur">Thrissur</a>')

var circle_43 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1599, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Vasco Da Gama<br>rank: 43<br>hazard index: 0.001600")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_44 = L.circle([12.305183, 76.655361], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1525, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Mysore<br>rank: 44<br>hazard index: 0.001526")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mysore">Mysore</a>')

var circle_45 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1494, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Jaipur<br>rank: 45<br>hazard index: 0.001494")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_46 = L.circle([12.794811, 79.000641], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1451, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Vellore<br>rank: 46<br>hazard index: 0.001451")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vellore">Vellore</a>')

var circle_47 = L.circle([17.005045, 81.780473], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1373, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Rajahmundry<br>rank: 47<br>hazard index: 0.001374")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajahmundry">Rajahmundry</a>')

var circle_48 = L.circle([10.805628, 79.824660], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1259, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Nagapattinam<br>rank: 48<br>hazard index: 0.001259")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagapattinam">Nagapattinam</a>')

var circle_49 = L.circle([15.507554, 80.060800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1171, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Ongole<br>rank: 49<br>hazard index: 0.001171")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ongole">Ongole</a>')

var circle_50 = L.circle([10.787898, 76.474087], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1131, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Palakkad<br>rank: 50<br>hazard index: 0.001131")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palakkad">Palakkad</a>')

var circle_51 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1058, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Thane<br>rank: 51<br>hazard index: 0.001059")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_52 = L.circle([8.805260, 78.145274], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1010, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Thoothukudi<br>rank: 52<br>hazard index: 0.001010")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thoothukudi">Thoothukudi</a>')

var circle_53 = L.circle([12.227213, 79.070156], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 994, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Tiruvannamalai<br>rank: 53<br>hazard index: 0.000995")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruvannamalai">Tiruvannamalai</a>')

var circle_54 = L.circle([10.500000, 78.833333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 947, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Pudukkottai<br>rank: 54<br>hazard index: 0.000948")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pudukkottai">Pudukkottai</a>')

var circle_55 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 935, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Bhopal<br>rank: 55<br>hazard index: 0.000935")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_56 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 922, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Surat<br>rank: 56<br>hazard index: 0.000923")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_57 = L.circle([10.044512, 78.743363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 863, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Karaikkudi<br>rank: 57<br>hazard index: 0.000863")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karaikkudi">Karaikkudi</a>')

var circle_58 = L.circle([8.188047, 77.429049], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 841, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Nagercoil<br>rank: 58<br>hazard index: 0.000842")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagercoil">Nagercoil</a>')

var circle_59 = L.circle([13.340077, 77.100621], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 829, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Tumkur<br>rank: 59<br>hazard index: 0.000829")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tumkur">Tumkur</a>')

var circle_60 = L.circle([16.237773, 80.646422], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 791, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Tenali<br>rank: 60<br>hazard index: 0.000792")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tenali">Tenali</a>')

var circle_61 = L.circle([14.475294, 78.821686], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 718, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Kadapa<br>rank: 61<br>hazard index: 0.000719")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kadapa">Kadapa</a>')

var circle_62 = L.circle([17.980609, 79.598212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 708, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Warangal<br>rank: 62<br>hazard index: 0.000708")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Warangal">Warangal</a>')

var circle_63 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 659, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Indore<br>rank: 63<br>hazard index: 0.000660")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_64 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 647, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Lucknow<br>rank: 64<br>hazard index: 0.000647")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_65 = L.circle([9.403158, 77.518264], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 600, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Rajapalayam<br>rank: 65<br>hazard index: 0.000600")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajapalayam">Rajapalayam</a>')

var circle_66 = L.circle([20.468600, 85.879200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 583, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Cuttack<br>rank: 66<br>hazard index: 0.000584")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuttack">Cuttack</a>')

var circle_67 = L.circle([9.500665, 76.412414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 581, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Alappuzha<br>rank: 67<br>hazard index: 0.000581")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alappuzha">Alappuzha</a>')

var circle_68 = L.circle([16.943738, 82.235061], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 560, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Kakinada<br>rank: 68<br>hazard index: 0.000561")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kakinada">Kakinada</a>')

var circle_69 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 526, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Patna<br>rank: 69<br>hazard index: 0.000526")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_70 = L.circle([17.849907, 75.276320], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 503, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Solapur<br>rank: 70<br>hazard index: 0.000503")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a>')

var circle_71 = L.circle([16.094950, 80.165878], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 472, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Chilakaluripet<br>rank: 71<br>hazard index: 0.000472")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chilakaluripet">Chilakaluripet</a>')

var circle_72 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 466, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Agra<br>rank: 72<br>hazard index: 0.000467")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_73 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 420, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Varanasi<br>rank: 73<br>hazard index: 0.000420")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_74 = L.circle([12.955100, 78.269900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 412, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Robertson Pet<br>rank: 74<br>hazard index: 0.000412")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Robertson_Pet">Robertson Pet</a>')

var circle_75 = L.circle([16.432998, 80.993715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 412, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Gudivada<br>rank: 75<br>hazard index: 0.000412")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gudivada">Gudivada</a>')

var circle_76 = L.circle([23.831238, 91.282382], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 388, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Agartala<br>rank: 76<br>hazard index: 0.000389")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agartala">Agartala</a>')

var circle_77 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 363, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Vadodara<br>rank: 77<br>hazard index: 0.000363")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_78 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 358, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Kanpur<br>rank: 78<br>hazard index: 0.000359")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_79 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 336, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Gwalior<br>rank: 79<br>hazard index: 0.000336")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_80 = L.circle([24.578721, 73.686257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 327, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Udaipur<br>rank: 80<br>hazard index: 0.000327")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a>')

var circle_81 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 326, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Dhanbad<br>rank: 81<br>hazard index: 0.000326")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_82 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 307, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Ranchi<br>rank: 82<br>hazard index: 0.000307")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_83 = L.circle([16.181939, 81.135130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 306, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Machilipatnam<br>rank: 83<br>hazard index: 0.000306")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Machilipatnam">Machilipatnam</a>')

var circle_84 = L.circle([19.807608, 85.825254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 300, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Puri<br>rank: 84<br>hazard index: 0.000301")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Puri">Puri</a>')

var circle_85 = L.circle([16.676135, 81.170868], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 299, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Eluru<br>rank: 85<br>hazard index: 0.000300")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Eluru">Eluru</a>')

var circle_86 = L.circle([15.351838, 75.137985], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 292, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Hubli<br>rank: 86<br>hazard index: 0.000293")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hubli">Hubli</a>')

var circle_87 = L.circle([22.591260, 88.390964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 288, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Bidhan Nagar<br>rank: 87<br>hazard index: 0.000289")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidhan_Nagar">Bidhan Nagar</a>')

var circle_88 = L.circle([18.627929, 73.800983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 284, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Pimpri Chinchwad<br>rank: 88<br>hazard index: 0.000284")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pimpri_Chinchwad">Pimpri Chinchwad</a>')

var circle_89 = L.circle([15.143395, 76.919388], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 277, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Bellary<br>rank: 89<br>hazard index: 0.000277")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bellary">Bellary</a>')

var circle_90 = L.circle([12.732884, 77.830948], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 276, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Hosur<br>rank: 90<br>hazard index: 0.000277")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hosur">Hosur</a>')

var circle_91 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 266, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Gurgaon<br>rank: 91<br>hazard index: 0.000266")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_92 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 262, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Allahabad<br>rank: 92<br>hazard index: 0.000262")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_93 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 260, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Nashik<br>rank: 93<br>hazard index: 0.000260")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_94 = L.circle([16.542769, 81.527344], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 254, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Bhimavaram<br>rank: 94<br>hazard index: 0.000255")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhimavaram">Bhimavaram</a>')

var circle_95 = L.circle([26.698885, 88.320030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 253, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Bagdogra<br>rank: 95<br>hazard index: 0.000253")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagdogra">Bagdogra</a>')

var circle_96 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 247, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Jabalpur<br>rank: 96<br>hazard index: 0.000247")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_97 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 244, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Faridabad<br>rank: 97<br>hazard index: 0.000244")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_98 = L.circle([18.112082, 83.405220], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 239, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Vizianagaram<br>rank: 98<br>hazard index: 0.000239")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vizianagaram">Vizianagaram</a>')

var circle_99 = L.circle([19.439885, 72.880383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 227, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Vasai<br>rank: 99<br>hazard index: 0.000228")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a>')

var circle_100 = L.circle([12.523889, 76.896196], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 226, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Mandya<br>rank: 100<br>hazard index: 0.000227")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mandya">Mandya</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Tiruchirappalli">Tiruchirappalli</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Tirupati">Tirupati</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Madurai">Madurai</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Salem">Salem</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Avadi">Avadi</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Tiruvottiyur">Tiruvottiyur</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Chennai. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>