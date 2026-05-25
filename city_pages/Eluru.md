---
layout: page
title: "Outbreak location: Eluru"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([16.676135, 81.170868],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Eluru").openTooltip();

var circle_1 = L.circle([17.980609, 79.598212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 77010, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Warangal<br>rank: 1<br>hazard index: 0.077011")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Warangal">Warangal</a>')

var circle_2 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 60726, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Vijayawada<br>rank: 2<br>hazard index: 0.060726")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_3 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43422, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Hyderabad<br>rank: 3<br>hazard index: 0.043423")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_4 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 41259, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Visakhapatnam<br>rank: 4<br>hazard index: 0.041259")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_5 = L.circle([17.005045, 81.780473], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30922, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Rajahmundry<br>rank: 5<br>hazard index: 0.030922")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajahmundry">Rajahmundry</a>')

var circle_6 = L.circle([16.291519, 80.454159], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22223, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Guntur<br>rank: 6<br>hazard index: 0.022224")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guntur">Guntur</a>')

var circle_7 = L.circle([16.943738, 82.235061], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21031, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Kakinada<br>rank: 7<br>hazard index: 0.021031")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kakinada">Kakinada</a>')

var circle_8 = L.circle([18.761516, 79.478785], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10834, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Ramagundam<br>rank: 8<br>hazard index: 0.010835")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ramagundam">Ramagundam</a>')

var circle_9 = L.circle([16.876586, 81.545145], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8773, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Tadepalligudem<br>rank: 9<br>hazard index: 0.008774")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tadepalligudem">Tadepalligudem</a>')

var circle_10 = L.circle([15.507554, 80.060800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5539, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Ongole<br>rank: 10<br>hazard index: 0.005540")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ongole">Ongole</a>')

var circle_11 = L.circle([16.237773, 80.646422], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4717, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Tenali<br>rank: 11<br>hazard index: 0.004717")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tenali">Tenali</a>')

var circle_12 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4091, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Chennai<br>rank: 12<br>hazard index: 0.004092")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_13 = L.circle([16.181939, 81.135130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3957, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Machilipatnam<br>rank: 13<br>hazard index: 0.003957")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Machilipatnam">Machilipatnam</a>')

var circle_14 = L.circle([18.793568, 80.815939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3617, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Bijapur<br>rank: 14<br>hazard index: 0.003617")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bijapur">Bijapur</a>')

var circle_15 = L.circle([16.432998, 80.993715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3431, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Gudivada<br>rank: 15<br>hazard index: 0.003432")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gudivada">Gudivada</a>')

var circle_16 = L.circle([14.449372, 79.987376], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3365, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Nellore<br>rank: 16<br>hazard index: 0.003365")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nellore">Nellore</a>')

var circle_17 = L.circle([16.542769, 81.527344], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3314, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Bhimavaram<br>rank: 17<br>hazard index: 0.003314")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhimavaram">Bhimavaram</a>')

var circle_18 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3161, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Kolkata<br>rank: 18<br>hazard index: 0.003161")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_19 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2788, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Bhubaneswar<br>rank: 19<br>hazard index: 0.002788")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_20 = L.circle([16.094950, 80.165878], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2548, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Chilakaluripet<br>rank: 20<br>hazard index: 0.002549")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chilakaluripet">Chilakaluripet</a>')

var circle_21 = L.circle([18.112082, 83.405220], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2249, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Vizianagaram<br>rank: 21<br>hazard index: 0.002249")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vizianagaram">Vizianagaram</a>')

var circle_22 = L.circle([16.238924, 80.047288], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2196, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Narasaraopet<br>rank: 22<br>hazard index: 0.002197")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Narasaraopet">Narasaraopet</a>')

var circle_23 = L.circle([17.500000, 80.333333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1579, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Khammam<br>rank: 23<br>hazard index: 0.001580")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khammam">Khammam</a>')

var circle_24 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1186, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Bangalore<br>rank: 24<br>hazard index: 0.001186")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_25 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 871, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Mumbai<br>rank: 25<br>hazard index: 0.000872")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_26 = L.circle([16.870988, 79.561398], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 783, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Miryalaguda<br>rank: 26<br>hazard index: 0.000784")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Miryalaguda">Miryalaguda</a>')

var circle_27 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 770, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Raipur<br>rank: 27<br>hazard index: 0.000770")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_28 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 751, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Delhi<br>rank: 28<br>hazard index: 0.000751")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_29 = L.circle([26.055318, 82.993139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 727, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Nizamabad<br>rank: 29<br>hazard index: 0.000727")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a>')

var circle_30 = L.circle([18.320022, 83.916077], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 671, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Srikakulam<br>rank: 30<br>hazard index: 0.000672")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srikakulam">Srikakulam</a>')

var circle_31 = L.circle([13.631637, 79.423171], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 641, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Tirupati<br>rank: 31<br>hazard index: 0.000641")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tirupati">Tirupati</a>')

var circle_32 = L.circle([19.087076, 82.023572], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 625, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Jagdalpur<br>rank: 32<br>hazard index: 0.000625")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagdalpur">Jagdalpur</a>')

var circle_33 = L.circle([20.468600, 85.879200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 610, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Cuttack<br>rank: 33<br>hazard index: 0.000611")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuttack">Cuttack</a>')

var circle_34 = L.circle([16.743454, 77.992319], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 609, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Mahbubnagar<br>rank: 34<br>hazard index: 0.000609")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mahbubnagar">Mahbubnagar</a>')

var circle_35 = L.circle([18.434644, 79.132265], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 606, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Karimnagar<br>rank: 35<br>hazard index: 0.000607")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karimnagar">Karimnagar</a>')

var circle_36 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 600, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Dhanbad<br>rank: 36<br>hazard index: 0.000600")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_37 = L.circle([15.830925, 78.042537], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 578, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Kurnool<br>rank: 37<br>hazard index: 0.000579")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kurnool">Kurnool</a>')

var circle_38 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 554, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Ranchi<br>rank: 38<br>hazard index: 0.000555")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_39 = L.circle([17.910400, 77.519900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 432, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Bidar<br>rank: 39<br>hazard index: 0.000433")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidar">Bidar</a>')

var circle_40 = L.circle([17.166667, 77.083333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 405, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Gulbarga<br>rank: 40<br>hazard index: 0.000405")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gulbarga">Gulbarga</a>')

var circle_41 = L.circle([14.475294, 78.821686], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 386, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Kadapa<br>rank: 41<br>hazard index: 0.000387")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kadapa">Kadapa</a>')

var circle_42 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 368, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Nanded Waghala<br>rank: 42<br>hazard index: 0.000369")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_43 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 365, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Coimbatore<br>rank: 43<br>hazard index: 0.000366")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_44 = L.circle([19.807608, 85.825254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 320, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Puri<br>rank: 44<br>hazard index: 0.000321")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Puri">Puri</a>')

var circle_45 = L.circle([20.030976, 79.358139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 307, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Chandrapur<br>rank: 45<br>hazard index: 0.000307")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandrapur">Chandrapur</a>')

var circle_46 = L.circle([17.849907, 75.276320], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 307, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Solapur<br>rank: 46<br>hazard index: 0.000307")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a>')

var circle_47 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 303, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Pune<br>rank: 47<br>hazard index: 0.000304")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_48 = L.circle([11.664300, 78.146000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 286, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Salem<br>rank: 48<br>hazard index: 0.000286")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Salem">Salem</a>')

var circle_49 = L.circle([15.351838, 75.137985], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 278, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Hubli<br>rank: 49<br>hazard index: 0.000278")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hubli">Hubli</a>')

var circle_50 = L.circle([14.422347, 77.720069], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 273, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Dharmavaram<br>rank: 50<br>hazard index: 0.000273")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dharmavaram">Dharmavaram</a>')

var circle_51 = L.circle([16.083333, 77.166667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 265, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Raichur<br>rank: 51<br>hazard index: 0.000266")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raichur">Raichur</a>')

var circle_52 = L.circle([16.857964, 79.217494], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 235, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Nalgonda<br>rank: 52<br>hazard index: 0.000236")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nalgonda">Nalgonda</a>')

var circle_53 = L.circle([22.214285, 84.872437], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 222, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Raurkela<br>rank: 53<br>hazard index: 0.000223")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raurkela">Raurkela</a>')

var circle_54 = L.circle([25.133173, 86.525040], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 217, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Kharagpur<br>rank: 54<br>hazard index: 0.000218")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kharagpur">Kharagpur</a>')

var circle_55 = L.circle([21.400000, 83.883333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 216, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Sambalpur<br>rank: 55<br>hazard index: 0.000216")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambalpur">Sambalpur</a>')

var circle_56 = L.circle([23.699128, 85.991069], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 213, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Bokaro<br>rank: 56<br>hazard index: 0.000214")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bokaro">Bokaro</a>')

var circle_57 = L.circle([19.290314, 76.602903], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 202, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Parbhani<br>rank: 57<br>hazard index: 0.000202")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Parbhani">Parbhani</a>')

var circle_58 = L.circle([21.200996, 81.335426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 183, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Bhilai Nagar<br>rank: 58<br>hazard index: 0.000183")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhilai_Nagar">Bhilai Nagar</a>')

var circle_59 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 175, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Ahmedabad<br>rank: 59<br>hazard index: 0.000175")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_60 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 172, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Nagpur<br>rank: 60<br>hazard index: 0.000172")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_61 = L.circle([15.475377, 78.478558], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 167, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Nandyal<br>rank: 61<br>hazard index: 0.000168")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nandyal">Nandyal</a>')

var circle_62 = L.circle([16.185317, 75.696792], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 151, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Bagalkot<br>rank: 62<br>hazard index: 0.000152")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagalkot">Bagalkot</a>')

var circle_63 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 149, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Jhansi<br>rank: 63<br>hazard index: 0.000150")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_64 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 139, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Vasco Da Gama<br>rank: 64<br>hazard index: 0.000140")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_65 = L.circle([15.143395, 76.919388], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 133, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Bellary<br>rank: 65<br>hazard index: 0.000133")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bellary">Bellary</a>')

var circle_66 = L.circle([12.794811, 79.000641], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 132, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Vellore<br>rank: 66<br>hazard index: 0.000133")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vellore">Vellore</a>')

var circle_67 = L.circle([19.918233, 75.868625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 128, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Jalna<br>rank: 67<br>hazard index: 0.000129")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalna">Jalna</a>')

var circle_68 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 127, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Jaipur<br>rank: 68<br>hazard index: 0.000128")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_69 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 123, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Kochi<br>rank: 69<br>hazard index: 0.000124")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_70 = L.circle([18.437436, 77.110521], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 122, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Udgir<br>rank: 70<br>hazard index: 0.000122")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udgir">Udgir</a>')

var circle_71 = L.circle([11.101781, 77.345192], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 122, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Tiruppur<br>rank: 71<br>hazard index: 0.000122")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruppur">Tiruppur</a>')

var circle_72 = L.circle([15.426365, 75.630079], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Gadag<br>rank: 72<br>hazard index: 0.000121")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gadag">Gadag</a>')

var circle_73 = L.circle([21.500000, 86.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 120, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Baleshwar<br>rank: 73<br>hazard index: 0.000121")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baleshwar">Baleshwar</a>')

var circle_74 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 117, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Jalgaon<br>rank: 74<br>hazard index: 0.000117")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_75 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 105, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Asansol<br>rank: 75<br>hazard index: 0.000105")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_76 = L.circle([19.309813, 84.797156], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 105, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Brahmapur<br>rank: 76<br>hazard index: 0.000105")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Brahmapur">Brahmapur</a>')

var circle_77 = L.circle([12.227213, 79.070156], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 103, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Tiruvannamalai<br>rank: 77<br>hazard index: 0.000103")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruvannamalai">Tiruvannamalai</a>')

var circle_78 = L.circle([21.934900, 86.732400], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 101, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Baripada<br>rank: 78<br>hazard index: 0.000102")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baripada">Baripada</a>')

var circle_79 = L.circle([10.804973, 78.687030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 101, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Tiruchirappalli<br>rank: 79<br>hazard index: 0.000102")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruchirappalli">Tiruchirappalli</a>')

var circle_80 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 99, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Varanasi<br>rank: 80<br>hazard index: 0.000099")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_81 = L.circle([22.591260, 88.390964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 92, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Bidhan Nagar<br>rank: 81<br>hazard index: 0.000093")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidhan_Nagar">Bidhan Nagar</a>')

var circle_82 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 88, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Jamshedpur<br>rank: 82<br>hazard index: 0.000089")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_83 = L.circle([20.825623, 78.613146], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 87, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Wardha<br>rank: 83<br>hazard index: 0.000088")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Wardha">Wardha</a>')

var circle_84 = L.circle([12.869810, 74.843008], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 86, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Mangalore<br>rank: 84<br>hazard index: 0.000086")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mangalore">Mangalore</a>')

var circle_85 = L.circle([10.525626, 76.213254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 85, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Thrissur<br>rank: 85<br>hazard index: 0.000085")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thrissur">Thrissur</a>')

var circle_86 = L.circle([20.475195, 78.742396], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 83, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Hinganghat<br>rank: 86<br>hazard index: 0.000084")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hinganghat">Hinganghat</a>')

var circle_87 = L.circle([21.063329, 86.505373], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 82, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Bhadrak<br>rank: 87<br>hazard index: 0.000082")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhadrak">Bhadrak</a>')

var circle_88 = L.circle([21.199035, 81.397955], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 82, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Durg<br>rank: 88<br>hazard index: 0.000082")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durg">Durg</a>')

var circle_89 = L.circle([16.702841, 74.240533], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 77, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Kolhapur<br>rank: 89<br>hazard index: 0.000078")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolhapur">Kolhapur</a>')

var circle_90 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 77, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Lucknow<br>rank: 90<br>hazard index: 0.000078")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_91 = L.circle([9.926115, 78.114098], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 73, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Madurai<br>rank: 91<br>hazard index: 0.000073")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Madurai">Madurai</a>')

var circle_92 = L.circle([16.850253, 74.594888], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 71, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Sangli<br>rank: 92<br>hazard index: 0.000071")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sangli">Sangli</a>')

var circle_93 = L.circle([15.857267, 74.506934], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 69, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Belgaum<br>rank: 93<br>hazard index: 0.000069")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Belgaum">Belgaum</a>')

var circle_94 = L.circle([15.266493, 76.387230], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 66, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Hospet<br>rank: 94<br>hazard index: 0.000067")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hospet">Hospet</a>')

var circle_95 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 66, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Bilaspur<br>rank: 95<br>hazard index: 0.000067")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_96 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 64, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Indore<br>rank: 96<br>hazard index: 0.000064")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_97 = L.circle([23.250000, 87.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 63, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Barddhaman<br>rank: 97<br>hazard index: 0.000064")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barddhaman">Barddhaman</a>')

var circle_98 = L.circle([14.654623, 77.556260], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Anantapur<br>rank: 98<br>hazard index: 0.000060")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Anantapur">Anantapur</a>')

var circle_99 = L.circle([22.519770, 82.629515], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 58, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Korba<br>rank: 99<br>hazard index: 0.000059")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Korba">Korba</a>')

var circle_100 = L.circle([13.125476, 80.094090], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 58, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Avadi<br>rank: 100<br>hazard index: 0.000058")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Avadi">Avadi</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Warangal">Warangal</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Rajahmundry">Rajahmundry</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Guntur">Guntur</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kakinada">Kakinada</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ramagundam">Ramagundam</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Tadepalligudem">Tadepalligudem</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ongole">Ongole</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Eluru. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>