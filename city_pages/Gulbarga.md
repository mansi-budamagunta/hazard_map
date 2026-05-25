---
layout: page
title: "Outbreak location: Gulbarga"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([17.166667, 77.083333],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Gulbarga").openTooltip();

var circle_1 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 123779, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Hyderabad<br>rank: 1<br>hazard index: 0.123780")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_2 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 97167, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Bangalore<br>rank: 2<br>hazard index: 0.097167")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_3 = L.circle([14.466127, 75.920636], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62306, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Davanagere<br>rank: 3<br>hazard index: 0.062306")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Davanagere">Davanagere</a>')

var circle_4 = L.circle([18.351469, 76.755121], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27775, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Latur<br>rank: 4<br>hazard index: 0.027776")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Latur">Latur</a>')

var circle_5 = L.circle([14.625888, 75.635724], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15230, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Ranibennur<br>rank: 5<br>hazard index: 0.015230")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranibennur">Ranibennur</a>')

var circle_6 = L.circle([15.631900, 77.275900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8844, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Adoni<br>rank: 6<br>hazard index: 0.008844")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Adoni">Adoni</a>')

var circle_7 = L.circle([18.169844, 76.117963], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5694, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Osmanabad<br>rank: 7<br>hazard index: 0.005694")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Osmanabad">Osmanabad</a>')

var circle_8 = L.circle([15.351838, 75.137985], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4621, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Hubli<br>rank: 8<br>hazard index: 0.004622")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hubli">Hubli</a>')

var circle_9 = L.circle([12.305183, 76.655361], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4567, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Mysore<br>rank: 9<br>hazard index: 0.004568")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mysore">Mysore</a>')

var circle_10 = L.circle([17.910400, 77.519900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4183, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Bidar<br>rank: 10<br>hazard index: 0.004184")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidar">Bidar</a>')

var circle_11 = L.circle([18.182992, 75.743925], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3927, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Barshi<br>rank: 11<br>hazard index: 0.003927")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barshi">Barshi</a>')

var circle_12 = L.circle([13.340077, 77.100621], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3526, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Tumkur<br>rank: 12<br>hazard index: 0.003527")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tumkur">Tumkur</a>')

var circle_13 = L.circle([16.083333, 77.166667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3499, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Raichur<br>rank: 13<br>hazard index: 0.003500")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raichur">Raichur</a>')

var circle_14 = L.circle([16.185317, 75.696792], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3423, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Bagalkot<br>rank: 14<br>hazard index: 0.003423")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagalkot">Bagalkot</a>')

var circle_15 = L.circle([16.743454, 77.992319], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3300, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Mahbubnagar<br>rank: 15<br>hazard index: 0.003300")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mahbubnagar">Mahbubnagar</a>')

var circle_16 = L.circle([15.830925, 78.042537], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3061, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Kurnool<br>rank: 16<br>hazard index: 0.003061")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kurnool">Kurnool</a>')

var circle_17 = L.circle([17.980609, 79.598212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2702, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Warangal<br>rank: 17<br>hazard index: 0.002703")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Warangal">Warangal</a>')

var circle_18 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2484, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Mumbai<br>rank: 18<br>hazard index: 0.002485")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_19 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2198, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Vijayawada<br>rank: 19<br>hazard index: 0.002198")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_20 = L.circle([18.437436, 77.110521], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2158, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Udgir<br>rank: 20<br>hazard index: 0.002159")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udgir">Udgir</a>')

var circle_21 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2141, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Delhi<br>rank: 21<br>hazard index: 0.002142")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_22 = L.circle([26.055318, 82.993139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2072, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Nizamabad<br>rank: 22<br>hazard index: 0.002073")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a>')

var circle_23 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2038, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Chennai<br>rank: 23<br>hazard index: 0.002038")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_24 = L.circle([17.849907, 75.276320], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1996, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Solapur<br>rank: 24<br>hazard index: 0.001997")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a>')

var circle_25 = L.circle([14.226644, 76.400512], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1839, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Chitradurga<br>rank: 25<br>hazard index: 0.001840")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chitradurga">Chitradurga</a>')

var circle_26 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1693, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Visakhapatnam<br>rank: 26<br>hazard index: 0.001693")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_27 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1551, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Nanded Waghala<br>rank: 27<br>hazard index: 0.001551")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_28 = L.circle([11.664300, 78.146000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1532, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Salem<br>rank: 28<br>hazard index: 0.001532")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Salem">Salem</a>')

var circle_29 = L.circle([18.761516, 79.478785], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1502, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Ramagundam<br>rank: 29<br>hazard index: 0.001503")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ramagundam">Ramagundam</a>')

var circle_30 = L.circle([16.291519, 80.454159], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1418, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Guntur<br>rank: 30<br>hazard index: 0.001419")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guntur">Guntur</a>')

var circle_31 = L.circle([12.955100, 78.269900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1234, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Robertson Pet<br>rank: 31<br>hazard index: 0.001235")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Robertson_Pet">Robertson Pet</a>')

var circle_32 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1012, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Kolkata<br>rank: 32<br>hazard index: 0.001012")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_33 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 865, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Pune<br>rank: 33<br>hazard index: 0.000866")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_34 = L.circle([12.732884, 77.830948], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 829, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Hosur<br>rank: 34<br>hazard index: 0.000829")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hosur">Hosur</a>')

var circle_35 = L.circle([15.143395, 76.919388], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 788, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Bellary<br>rank: 35<br>hazard index: 0.000788")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bellary">Bellary</a>')

var circle_36 = L.circle([18.434644, 79.132265], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 783, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Karimnagar<br>rank: 36<br>hazard index: 0.000784")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karimnagar">Karimnagar</a>')

var circle_37 = L.circle([14.422347, 77.720069], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 778, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Dharmavaram<br>rank: 37<br>hazard index: 0.000778")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dharmavaram">Dharmavaram</a>')

var circle_38 = L.circle([13.932609, 75.574978], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 770, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Shimoga<br>rank: 38<br>hazard index: 0.000771")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shimoga">Shimoga</a>')

var circle_39 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 743, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Jalgaon<br>rank: 39<br>hazard index: 0.000744")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_40 = L.circle([12.523889, 76.896196], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 679, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Mandya<br>rank: 40<br>hazard index: 0.000679")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mandya">Mandya</a>')

var circle_41 = L.circle([16.857964, 79.217494], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 671, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Nalgonda<br>rank: 41<br>hazard index: 0.000672")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nalgonda">Nalgonda</a>')

var circle_42 = L.circle([13.631637, 79.423171], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 661, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Tirupati<br>rank: 42<br>hazard index: 0.000662")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tirupati">Tirupati</a>')

var circle_43 = L.circle([19.290314, 76.602903], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 656, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Parbhani<br>rank: 43<br>hazard index: 0.000656")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Parbhani">Parbhani</a>')

var circle_44 = L.circle([13.137000, 78.133961], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 636, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Kolar<br>rank: 44<br>hazard index: 0.000637")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolar">Kolar</a>')

var circle_45 = L.circle([12.869810, 74.843008], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 627, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Mangalore<br>rank: 45<br>hazard index: 0.000627")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mangalore">Mangalore</a>')

var circle_46 = L.circle([13.007082, 76.099270], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 569, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Hassan<br>rank: 46<br>hazard index: 0.000570")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hassan">Hassan</a>')

var circle_47 = L.circle([13.341917, 74.747323], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 561, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Udupi<br>rank: 47<br>hazard index: 0.000561")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udupi">Udupi</a>')

var circle_48 = L.circle([17.500000, 80.333333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 560, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Khammam<br>rank: 48<br>hazard index: 0.000560")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khammam">Khammam</a>')

var circle_49 = L.circle([15.426365, 75.630079], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 540, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Gadag<br>rank: 49<br>hazard index: 0.000541")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gadag">Gadag</a>')

var circle_50 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 536, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Coimbatore<br>rank: 50<br>hazard index: 0.000536")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_51 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 517, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Bhubaneswar<br>rank: 51<br>hazard index: 0.000518")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_52 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 516, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Ahmedabad<br>rank: 52<br>hazard index: 0.000517")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_53 = L.circle([16.870988, 79.561398], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 515, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Miryalaguda<br>rank: 53<br>hazard index: 0.000516")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Miryalaguda">Miryalaguda</a>')

var circle_54 = L.circle([15.266493, 76.387230], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 496, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Hospet<br>rank: 54<br>hazard index: 0.000496")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hospet">Hospet</a>')

var circle_55 = L.circle([18.793568, 80.815939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 494, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Bijapur<br>rank: 55<br>hazard index: 0.000494")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bijapur">Bijapur</a>')

var circle_56 = L.circle([17.005045, 81.780473], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 480, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Rajahmundry<br>rank: 56<br>hazard index: 0.000481")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajahmundry">Rajahmundry</a>')

var circle_57 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 455, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Kochi<br>rank: 57<br>hazard index: 0.000455")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_58 = L.circle([14.654623, 77.556260], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 422, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Anantapur<br>rank: 58<br>hazard index: 0.000422")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Anantapur">Anantapur</a>')

var circle_59 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 397, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Vasco Da Gama<br>rank: 59<br>hazard index: 0.000398")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_60 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 375, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Nagpur<br>rank: 60<br>hazard index: 0.000375")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_61 = L.circle([19.918233, 75.868625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 366, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Jalna<br>rank: 61<br>hazard index: 0.000367")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalna">Jalna</a>')

var circle_62 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 363, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Jaipur<br>rank: 62<br>hazard index: 0.000364")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_63 = L.circle([8.576971, 77.050125], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 323, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Thiruvananthapuram<br>rank: 63<br>hazard index: 0.000323")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thiruvananthapuram">Thiruvananthapuram</a>')

var circle_64 = L.circle([15.857267, 74.506934], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 313, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Belgaum<br>rank: 64<br>hazard index: 0.000314")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Belgaum">Belgaum</a>')

var circle_65 = L.circle([13.826383, 77.493772], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 285, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Hindupur<br>rank: 65<br>hazard index: 0.000286")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hindupur">Hindupur</a>')

var circle_66 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 283, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Varanasi<br>rank: 66<br>hazard index: 0.000283")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_67 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 276, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Raipur<br>rank: 67<br>hazard index: 0.000277")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_68 = L.circle([13.318014, 75.773874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 263, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Chikmagalur<br>rank: 68<br>hazard index: 0.000263")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chikmagalur">Chikmagalur</a>')

var circle_69 = L.circle([15.119651, 77.455290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 262, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Guntakal<br>rank: 69<br>hazard index: 0.000263")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guntakal">Guntakal</a>')

var circle_70 = L.circle([9.926115, 78.114098], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 250, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Madurai<br>rank: 70<br>hazard index: 0.000250")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Madurai">Madurai</a>')

var circle_71 = L.circle([20.166670, 79.172114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 245, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Bhadravati<br>rank: 71<br>hazard index: 0.000245")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhadravati">Bhadravati</a>')

var circle_72 = L.circle([11.369204, 77.676627], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 241, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Erode<br>rank: 72<br>hazard index: 0.000241")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Erode">Erode</a>')

var circle_73 = L.circle([14.475294, 78.821686], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 240, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Kadapa<br>rank: 73<br>hazard index: 0.000240")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kadapa">Kadapa</a>')

var circle_74 = L.circle([16.676135, 81.170868], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 234, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Eluru<br>rank: 74<br>hazard index: 0.000234")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Eluru">Eluru</a>')

var circle_75 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 233, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Lucknow<br>rank: 75<br>hazard index: 0.000234")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_76 = L.circle([13.160105, 79.155551], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 215, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Chittoor<br>rank: 76<br>hazard index: 0.000216")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chittoor">Chittoor</a>')

var circle_77 = L.circle([14.449372, 79.987376], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 213, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Nellore<br>rank: 77<br>hazard index: 0.000213")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nellore">Nellore</a>')

var circle_78 = L.circle([16.850253, 74.594888], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 212, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Sangli<br>rank: 78<br>hazard index: 0.000213")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sangli">Sangli</a>')

var circle_79 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 212, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Jhansi<br>rank: 79<br>hazard index: 0.000213")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_80 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 206, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Guwahati<br>rank: 80<br>hazard index: 0.000207")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_81 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 205, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Patna<br>rank: 81<br>hazard index: 0.000206")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_82 = L.circle([12.794811, 79.000641], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 198, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Vellore<br>rank: 82<br>hazard index: 0.000199")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vellore">Vellore</a>')

var circle_83 = L.circle([15.431506, 76.532774], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 188, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Gangawati<br>rank: 83<br>hazard index: 0.000189")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gangawati">Gangawati</a>')

var circle_84 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 183, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Indore<br>rank: 84<br>hazard index: 0.000183")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_85 = L.circle([16.237773, 80.646422], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 181, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Tenali<br>rank: 85<br>hazard index: 0.000181")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tenali">Tenali</a>')

var circle_86 = L.circle([13.573260, 78.479146], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 181, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Madanapalle<br>rank: 86<br>hazard index: 0.000181")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Madanapalle">Madanapalle</a>')

var circle_87 = L.circle([12.792907, 78.699917], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 166, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Ambur<br>rank: 87<br>hazard index: 0.000166")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambur">Ambur</a>')

var circle_88 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 164, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Akola<br>rank: 88<br>hazard index: 0.000164")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')

var circle_89 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 154, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Ranchi<br>rank: 89<br>hazard index: 0.000155")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_90 = L.circle([11.101781, 77.345192], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Tiruppur<br>rank: 90<br>hazard index: 0.000154")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruppur">Tiruppur</a>')

var circle_91 = L.circle([15.475377, 78.478558], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Nandyal<br>rank: 91<br>hazard index: 0.000153")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nandyal">Nandyal</a>')

var circle_92 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 151, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Thane<br>rank: 92<br>hazard index: 0.000151")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_93 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 139, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Surat<br>rank: 93<br>hazard index: 0.000140")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_94 = L.circle([12.227213, 79.070156], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 138, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Tiruvannamalai<br>rank: 94<br>hazard index: 0.000138")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruvannamalai">Tiruvannamalai</a>')

var circle_95 = L.circle([16.702841, 74.240533], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 130, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Kolhapur<br>rank: 95<br>hazard index: 0.000131")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolhapur">Kolhapur</a>')

var circle_96 = L.circle([19.877263, 75.339024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 128, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Aurangabad<br>rank: 96<br>hazard index: 0.000129")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aurangabad">Aurangabad</a>')

var circle_97 = L.circle([16.432998, 80.993715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 124, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Gudivada<br>rank: 97<br>hazard index: 0.000124")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gudivada">Gudivada</a>')

var circle_98 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 120, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Bhopal<br>rank: 98<br>hazard index: 0.000120")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_99 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 111, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Jabalpur<br>rank: 99<br>hazard index: 0.000111")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_100 = L.circle([14.906956, 78.009707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 108, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Tadipatri<br>rank: 100<br>hazard index: 0.000109")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tadipatri">Tadipatri</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Davanagere">Davanagere</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Latur">Latur</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ranibennur">Ranibennur</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Adoni">Adoni</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Osmanabad">Osmanabad</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Hubli">Hubli</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mysore">Mysore</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bidar">Bidar</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Gulbarga. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>