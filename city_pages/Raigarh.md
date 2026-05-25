---
layout: page
title: "Outbreak location: Raigarh"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([22.500000, 83.500000],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Raigarh").openTooltip();

var circle_1 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69301, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Bilaspur<br>rank: 1<br>hazard index: 0.069301")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_2 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 60362, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Raipur<br>rank: 2<br>hazard index: 0.060362")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_3 = L.circle([21.400000, 83.883333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59014, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Sambalpur<br>rank: 3<br>hazard index: 0.059015")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambalpur">Sambalpur</a>')

var circle_4 = L.circle([22.214285, 84.872437], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22438, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Raurkela<br>rank: 4<br>hazard index: 0.022439")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raurkela">Raurkela</a>')

var circle_5 = L.circle([21.735348, 81.944459], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17685, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Bhatpara<br>rank: 5<br>hazard index: 0.017685")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhatpara">Bhatpara</a>')

var circle_6 = L.circle([22.519770, 82.629515], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16450, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Korba<br>rank: 6<br>hazard index: 0.016451")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Korba">Korba</a>')

var circle_7 = L.circle([21.199035, 81.397955], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16054, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Durg<br>rank: 7<br>hazard index: 0.016054")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durg">Durg</a>')

var circle_8 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14991, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Jamshedpur<br>rank: 8<br>hazard index: 0.014992")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_9 = L.circle([21.200996, 81.335426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11993, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Bhilai Nagar<br>rank: 9<br>hazard index: 0.011993")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhilai_Nagar">Bhilai Nagar</a>')

var circle_10 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11790, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Delhi<br>rank: 10<br>hazard index: 0.011790")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_11 = L.circle([20.972740, 80.691555], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9301, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Rajnandgaon<br>rank: 11<br>hazard index: 0.009302")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajnandgaon">Rajnandgaon</a>')

var circle_12 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8879, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Jalgaon<br>rank: 12<br>hazard index: 0.008879")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_13 = L.circle([21.145629, 80.268387], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7579, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Gondiya<br>rank: 13<br>hazard index: 0.007580")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gondiya">Gondiya</a>')

var circle_14 = L.circle([23.122634, 83.198189], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6609, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Ambikapur<br>rank: 14<br>hazard index: 0.006610")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambikapur">Ambikapur</a>')

var circle_15 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6439, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Kolkata<br>rank: 15<br>hazard index: 0.006439")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_16 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5817, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Jhansi<br>rank: 16<br>hazard index: 0.005818")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_17 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3963, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Nagpur<br>rank: 17<br>hazard index: 0.003963")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_18 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3952, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Bhubaneswar<br>rank: 18<br>hazard index: 0.003952")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_19 = L.circle([22.782355, 86.159003], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3157, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Adityapur<br>rank: 19<br>hazard index: 0.003157")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Adityapur">Adityapur</a>')

var circle_20 = L.circle([22.890183, 88.426939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2456, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Naihati<br>rank: 20<br>hazard index: 0.002457")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Naihati">Naihati</a>')

var circle_21 = L.circle([19.087076, 82.023572], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1898, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Jagdalpur<br>rank: 21<br>hazard index: 0.001898")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagdalpur">Jagdalpur</a>')

var circle_22 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1880, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Bhopal<br>rank: 22<br>hazard index: 0.001880")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_23 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1654, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Ranchi<br>rank: 23<br>hazard index: 0.001654")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_24 = L.circle([21.934900, 86.732400], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1597, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Baripada<br>rank: 24<br>hazard index: 0.001598")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baripada">Baripada</a>')

var circle_25 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1535, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Agra<br>rank: 25<br>hazard index: 0.001536")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_26 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1150, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Patna<br>rank: 26<br>hazard index: 0.001151")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_27 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1071, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Visakhapatnam<br>rank: 27<br>hazard index: 0.001072")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_28 = L.circle([20.468600, 85.879200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1050, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Cuttack<br>rank: 28<br>hazard index: 0.001051")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuttack">Cuttack</a>')

var circle_29 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1027, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Gwalior<br>rank: 29<br>hazard index: 0.001028")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_30 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 910, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Jabalpur<br>rank: 30<br>hazard index: 0.000910")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_31 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 906, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Mumbai<br>rank: 31<br>hazard index: 0.000907")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_32 = L.circle([25.133173, 86.525040], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 847, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Kharagpur<br>rank: 32<br>hazard index: 0.000848")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kharagpur">Kharagpur</a>')

var circle_33 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 693, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Bhusawal<br>rank: 33<br>hazard index: 0.000693")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_34 = L.circle([22.920982, 88.437022], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 654, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Halisahar<br>rank: 34<br>hazard index: 0.000654")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Halisahar">Halisahar</a>')

var circle_35 = L.circle([22.949011, 88.435910], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 629, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Kanchrapara<br>rank: 35<br>hazard index: 0.000630")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanchrapara">Kanchrapara</a>')

var circle_36 = L.circle([24.476642, 86.606732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 593, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Deoghar<br>rank: 36<br>hazard index: 0.000594")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoghar">Deoghar</a>')

var circle_37 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 580, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Satna<br>rank: 37<br>hazard index: 0.000581")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_38 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 516, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Dhanbad<br>rank: 38<br>hazard index: 0.000516")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_39 = L.circle([24.759267, 81.655000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 470, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Rewa<br>rank: 39<br>hazard index: 0.000471")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewa">Rewa</a>')

var circle_40 = L.circle([19.807608, 85.825254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 454, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Puri<br>rank: 40<br>hazard index: 0.000455")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Puri">Puri</a>')

var circle_41 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 413, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Hyderabad<br>rank: 41<br>hazard index: 0.000414")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_42 = L.circle([20.259399, 76.976203], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 404, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Malegaon<br>rank: 42<br>hazard index: 0.000405")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Malegaon">Malegaon</a>')

var circle_43 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 385, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Asansol<br>rank: 43<br>hazard index: 0.000386")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_44 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 378, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Kanpur<br>rank: 44<br>hazard index: 0.000378")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_45 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 347, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Indore<br>rank: 45<br>hazard index: 0.000347")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_46 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 340, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Mathura<br>rank: 46<br>hazard index: 0.000341")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_47 = L.circle([18.112082, 83.405220], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 319, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Vizianagaram<br>rank: 47<br>hazard index: 0.000320")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vizianagaram">Vizianagaram</a>')

var circle_48 = L.circle([19.877263, 75.339024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 318, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Aurangabad<br>rank: 48<br>hazard index: 0.000318")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aurangabad">Aurangabad</a>')

var circle_49 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 265, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Ahmedabad<br>rank: 49<br>hazard index: 0.000265")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_50 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 245, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Jaipur<br>rank: 50<br>hazard index: 0.000245")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_51 = L.circle([23.405848, 88.495893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 198, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Krishnanagar<br>rank: 51<br>hazard index: 0.000199")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Krishnanagar">Krishnanagar</a>')

var circle_52 = L.circle([21.500000, 86.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 196, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Baleshwar<br>rank: 52<br>hazard index: 0.000196")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baleshwar">Baleshwar</a>')

var circle_53 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 194, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Pune<br>rank: 53<br>hazard index: 0.000195")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_54 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 189, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Bangalore<br>rank: 54<br>hazard index: 0.000189")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_55 = L.circle([22.591260, 88.390964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 188, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Bidhan Nagar<br>rank: 55<br>hazard index: 0.000189")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidhan_Nagar">Bidhan Nagar</a>')

var circle_56 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 177, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Varanasi<br>rank: 56<br>hazard index: 0.000178")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_57 = L.circle([18.320022, 83.916077], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 170, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Srikakulam<br>rank: 57<br>hazard index: 0.000171")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srikakulam">Srikakulam</a>')

var circle_58 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 166, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Gurgaon<br>rank: 58<br>hazard index: 0.000167")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_59 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 165, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Akola<br>rank: 59<br>hazard index: 0.000165")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')

var circle_60 = L.circle([23.916667, 78.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 164, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Vidisha<br>rank: 60<br>hazard index: 0.000164")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vidisha">Vidisha</a>')

var circle_61 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 162, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Surat<br>rank: 61<br>hazard index: 0.000163")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_62 = L.circle([19.290314, 76.602903], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 157, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Parbhani<br>rank: 62<br>hazard index: 0.000158")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Parbhani">Parbhani</a>')

var circle_63 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 154, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Lucknow<br>rank: 63<br>hazard index: 0.000154")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_64 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Kota<br>rank: 64<br>hazard index: 0.000154")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_65 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Faridabad<br>rank: 65<br>hazard index: 0.000153")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_66 = L.circle([24.197443, 82.666145], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 147, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Singrauli<br>rank: 66<br>hazard index: 0.000147")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Singrauli">Singrauli</a>')

var circle_67 = L.circle([23.332200, 86.361600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 133, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Purulia<br>rank: 67<br>hazard index: 0.000134")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Purulia">Purulia</a>')

var circle_68 = L.circle([24.700385, 78.518668], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 130, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Lalitpur<br>rank: 68<br>hazard index: 0.000130")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lalitpur">Lalitpur</a>')

var circle_69 = L.circle([23.250000, 87.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 129, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Barddhaman<br>rank: 69<br>hazard index: 0.000130")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barddhaman">Barddhaman</a>')

var circle_70 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 122, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Thane<br>rank: 70<br>hazard index: 0.000123")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_71 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Rohtak<br>rank: 71<br>hazard index: 0.000121")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_72 = L.circle([23.809612, 78.759114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Sagar<br>rank: 72<br>hazard index: 0.000121")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sagar">Sagar</a>')

var circle_73 = L.circle([23.259346, 88.437212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 118, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Santipur<br>rank: 73<br>hazard index: 0.000119")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Santipur">Santipur</a>')

var circle_74 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 118, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Allahabad<br>rank: 74<br>hazard index: 0.000119")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_75 = L.circle([21.154541, 77.644296], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 118, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Amravati<br>rank: 75<br>hazard index: 0.000118")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amravati">Amravati</a>')

var circle_76 = L.circle([23.174597, 75.785142], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 117, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Ujjain<br>rank: 76<br>hazard index: 0.000117")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ujjain">Ujjain</a>')

var circle_77 = L.circle([22.600150, 77.926645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 113, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Hoshangabad<br>rank: 77<br>hazard index: 0.000113")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshangabad">Hoshangabad</a>')

var circle_78 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 106, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Ludhiana<br>rank: 78<br>hazard index: 0.000107")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_79 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 106, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Moradabad<br>rank: 79<br>hazard index: 0.000106")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_80 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 102, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Meerut<br>rank: 80<br>hazard index: 0.000103")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_81 = L.circle([21.879616, 77.875681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 99, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Betul<br>rank: 81<br>hazard index: 0.000100")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Betul">Betul</a>')

var circle_82 = L.circle([23.833962, 80.392456], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 98, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Murwara<br>rank: 82<br>hazard index: 0.000098")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Murwara">Murwara</a>')

var circle_83 = L.circle([22.472223, 88.093845], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 97, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Uluberia<br>rank: 83<br>hazard index: 0.000098")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Uluberia">Uluberia</a>')

var circle_84 = L.circle([23.699128, 85.991069], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 96, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Bokaro<br>rank: 84<br>hazard index: 0.000097")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bokaro">Bokaro</a>')

var circle_85 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 94, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Nashik<br>rank: 85<br>hazard index: 0.000094")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_86 = L.circle([26.716413, 88.430992], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 93, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Siliguri<br>rank: 86<br>hazard index: 0.000093")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siliguri">Siliguri</a>')

var circle_87 = L.circle([20.030976, 79.358139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 93, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Chandrapur<br>rank: 87<br>hazard index: 0.000093")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandrapur">Chandrapur</a>')

var circle_88 = L.circle([21.063329, 86.505373], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 88, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Bhadrak<br>rank: 88<br>hazard index: 0.000088")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhadrak">Bhadrak</a>')

var circle_89 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 85, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Vijayawada<br>rank: 89<br>hazard index: 0.000086")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_90 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 81, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Nanded Waghala<br>rank: 90<br>hazard index: 0.000082")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_91 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 79, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Vadodara<br>rank: 91<br>hazard index: 0.000079")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_92 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 79, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Saharanpur<br>rank: 92<br>hazard index: 0.000079")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_93 = L.circle([19.918233, 75.868625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 79, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Jalna<br>rank: 93<br>hazard index: 0.000079")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalna">Jalna</a>')

var circle_94 = L.circle([18.793568, 80.815939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 77, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Bijapur<br>rank: 94<br>hazard index: 0.000077")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bijapur">Bijapur</a>')

var circle_95 = L.circle([18.351469, 76.755121], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 73, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Latur<br>rank: 95<br>hazard index: 0.000074")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Latur">Latur</a>')

var circle_96 = L.circle([29.154148, 77.305954], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Baraut<br>rank: 96<br>hazard index: 0.000069")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baraut">Baraut</a>')

var circle_97 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 68, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Aligarh<br>rank: 97<br>hazard index: 0.000068")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_98 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 67, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Sonipat<br>rank: 98<br>hazard index: 0.000068")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_99 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 67, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Loni<br>rank: 99<br>hazard index: 0.000067")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_100 = L.circle([23.535048, 87.338043], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 66, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Durgapur<br>rank: 100<br>hazard index: 0.000066")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Sambalpur">Sambalpur</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Raurkela">Raurkela</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhatpara">Bhatpara</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Korba">Korba</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Durg">Durg</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhilai_Nagar">Bhilai Nagar</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Raigarh. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>