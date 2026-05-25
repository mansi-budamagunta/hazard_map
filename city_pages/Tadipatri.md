---
layout: page
title: "Outbreak location: Tadipatri"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([14.906956, 78.009707],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Tadipatri").openTooltip();

var circle_1 = L.circle([14.475294, 78.821686], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 130923, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Kadapa<br>rank: 1<br>hazard index: 0.130923")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kadapa">Kadapa</a>')

var circle_2 = L.circle([15.143395, 76.919388], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30768, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Bellary<br>rank: 2<br>hazard index: 0.030769")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bellary">Bellary</a>')

var circle_3 = L.circle([13.631637, 79.423171], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26958, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Tirupati<br>rank: 3<br>hazard index: 0.026959")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tirupati">Tirupati</a>')

var circle_4 = L.circle([14.654623, 77.556260], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26100, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Anantapur<br>rank: 4<br>hazard index: 0.026100")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Anantapur">Anantapur</a>')

var circle_5 = L.circle([15.266493, 76.387230], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15484, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Hospet<br>rank: 5<br>hazard index: 0.015485")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hospet">Hospet</a>')

var circle_6 = L.circle([15.830925, 78.042537], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14708, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Kurnool<br>rank: 6<br>hazard index: 0.014709")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kurnool">Kurnool</a>')

var circle_7 = L.circle([14.422347, 77.720069], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12137, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Dharmavaram<br>rank: 7<br>hazard index: 0.012137")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dharmavaram">Dharmavaram</a>')

var circle_8 = L.circle([13.340077, 77.100621], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10454, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Tumkur<br>rank: 8<br>hazard index: 0.010455")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tumkur">Tumkur</a>')

var circle_9 = L.circle([15.119651, 77.455290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9663, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Guntakal<br>rank: 9<br>hazard index: 0.009663")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guntakal">Guntakal</a>')

var circle_10 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9484, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Chennai<br>rank: 10<br>hazard index: 0.009484")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_11 = L.circle([16.083333, 77.166667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8247, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Raichur<br>rank: 11<br>hazard index: 0.008247")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raichur">Raichur</a>')

var circle_12 = L.circle([15.475377, 78.478558], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7360, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Nandyal<br>rank: 12<br>hazard index: 0.007360")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nandyal">Nandyal</a>')

var circle_13 = L.circle([15.426365, 75.630079], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7072, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Gadag<br>rank: 13<br>hazard index: 0.007073")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gadag">Gadag</a>')

var circle_14 = L.circle([14.752266, 78.548552], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5969, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Proddatur<br>rank: 14<br>hazard index: 0.005970")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Proddatur">Proddatur</a>')

var circle_15 = L.circle([15.631900, 77.275900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5907, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Adoni<br>rank: 15<br>hazard index: 0.005908")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Adoni">Adoni</a>')

var circle_16 = L.circle([14.449372, 79.987376], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5857, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Nellore<br>rank: 16<br>hazard index: 0.005857")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nellore">Nellore</a>')

var circle_17 = L.circle([13.826383, 77.493772], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5190, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Hindupur<br>rank: 17<br>hazard index: 0.005191")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hindupur">Hindupur</a>')

var circle_18 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5073, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Hyderabad<br>rank: 18<br>hazard index: 0.005074")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_19 = L.circle([14.226644, 76.400512], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4783, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Chitradurga<br>rank: 19<br>hazard index: 0.004783")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chitradurga">Chitradurga</a>')

var circle_20 = L.circle([13.137000, 78.133961], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4736, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Kolar<br>rank: 20<br>hazard index: 0.004737")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolar">Kolar</a>')

var circle_21 = L.circle([13.573260, 78.479146], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4637, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Madanapalle<br>rank: 21<br>hazard index: 0.004638")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Madanapalle">Madanapalle</a>')

var circle_22 = L.circle([15.431506, 76.532774], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3035, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Gangawati<br>rank: 22<br>hazard index: 0.003035")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gangawati">Gangawati</a>')

var circle_23 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2599, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Vijayawada<br>rank: 23<br>hazard index: 0.002599")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_24 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2522, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Bangalore<br>rank: 24<br>hazard index: 0.002523")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_25 = L.circle([13.160105, 79.155551], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2429, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Chittoor<br>rank: 25<br>hazard index: 0.002429")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chittoor">Chittoor</a>')

var circle_26 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2223, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Mumbai<br>rank: 26<br>hazard index: 0.002224")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_27 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1655, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Visakhapatnam<br>rank: 27<br>hazard index: 0.001656")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_28 = L.circle([16.291519, 80.454159], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1615, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Guntur<br>rank: 28<br>hazard index: 0.001615")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guntur">Guntur</a>')

var circle_29 = L.circle([15.351838, 75.137985], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1245, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Hubli<br>rank: 29<br>hazard index: 0.001246")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hubli">Hubli</a>')

var circle_30 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1039, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Coimbatore<br>rank: 30<br>hazard index: 0.001040")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_31 = L.circle([15.507554, 80.060800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 937, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Ongole<br>rank: 31<br>hazard index: 0.000938")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ongole">Ongole</a>')

var circle_32 = L.circle([11.664300, 78.146000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 888, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Salem<br>rank: 32<br>hazard index: 0.000889")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Salem">Salem</a>')

var circle_33 = L.circle([8.576971, 77.050125], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 737, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Thiruvananthapuram<br>rank: 33<br>hazard index: 0.000737")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thiruvananthapuram">Thiruvananthapuram</a>')

var circle_34 = L.circle([12.955100, 78.269900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 619, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Robertson Pet<br>rank: 34<br>hazard index: 0.000619")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Robertson_Pet">Robertson Pet</a>')

var circle_35 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 555, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Pune<br>rank: 35<br>hazard index: 0.000555")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_36 = L.circle([16.702841, 74.240533], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 485, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Kolhapur<br>rank: 36<br>hazard index: 0.000485")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolhapur">Kolhapur</a>')

var circle_37 = L.circle([13.932609, 75.574978], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 451, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Shimoga<br>rank: 37<br>hazard index: 0.000451")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shimoga">Shimoga</a>')

var circle_38 = L.circle([16.850253, 74.594888], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 444, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Sangli<br>rank: 38<br>hazard index: 0.000444")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sangli">Sangli</a>')

var circle_39 = L.circle([11.101781, 77.345192], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 435, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Tiruppur<br>rank: 39<br>hazard index: 0.000435")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruppur">Tiruppur</a>')

var circle_40 = L.circle([15.857267, 74.506934], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 431, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Belgaum<br>rank: 40<br>hazard index: 0.000431")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Belgaum">Belgaum</a>')

var circle_41 = L.circle([17.849907, 75.276320], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 424, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Solapur<br>rank: 41<br>hazard index: 0.000424")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a>')

var circle_42 = L.circle([9.926115, 78.114098], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 415, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Madurai<br>rank: 42<br>hazard index: 0.000415")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Madurai">Madurai</a>')

var circle_43 = L.circle([14.466127, 75.920636], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 397, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Davanagere<br>rank: 43<br>hazard index: 0.000397")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Davanagere">Davanagere</a>')

var circle_44 = L.circle([12.794811, 79.000641], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 390, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Vellore<br>rank: 44<br>hazard index: 0.000391")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vellore">Vellore</a>')

var circle_45 = L.circle([10.804973, 78.687030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 345, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Tiruchirappalli<br>rank: 45<br>hazard index: 0.000346")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruchirappalli">Tiruchirappalli</a>')

var circle_46 = L.circle([8.887951, 76.595501], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 341, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Kollam<br>rank: 46<br>hazard index: 0.000342")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kollam">Kollam</a>')

var circle_47 = L.circle([17.005045, 81.780473], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 329, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Rajahmundry<br>rank: 47<br>hazard index: 0.000329")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajahmundry">Rajahmundry</a>')

var circle_48 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 317, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Thane<br>rank: 48<br>hazard index: 0.000317")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_49 = L.circle([8.188047, 77.429049], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 311, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Nagercoil<br>rank: 49<br>hazard index: 0.000311")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagercoil">Nagercoil</a>')

var circle_50 = L.circle([10.525626, 76.213254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 309, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Thrissur<br>rank: 50<br>hazard index: 0.000309")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thrissur">Thrissur</a>')

var circle_51 = L.circle([12.227213, 79.070156], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 299, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Tiruvannamalai<br>rank: 51<br>hazard index: 0.000300")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruvannamalai">Tiruvannamalai</a>')

var circle_52 = L.circle([16.238924, 80.047288], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 288, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Narasaraopet<br>rank: 52<br>hazard index: 0.000288")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Narasaraopet">Narasaraopet</a>')

var circle_53 = L.circle([19.290314, 76.602903], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 259, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Parbhani<br>rank: 53<br>hazard index: 0.000259")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Parbhani">Parbhani</a>')

var circle_54 = L.circle([16.695935, 74.455575], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 254, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Ichalkaranji<br>rank: 54<br>hazard index: 0.000254")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ichalkaranji">Ichalkaranji</a>')

var circle_55 = L.circle([19.918233, 75.868625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 240, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Jalna<br>rank: 55<br>hazard index: 0.000241")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalna">Jalna</a>')

var circle_56 = L.circle([13.318014, 75.773874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 210, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Chikmagalur<br>rank: 56<br>hazard index: 0.000210")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chikmagalur">Chikmagalur</a>')

var circle_57 = L.circle([16.676135, 81.170868], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 205, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Eluru<br>rank: 57<br>hazard index: 0.000205")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Eluru">Eluru</a>')

var circle_58 = L.circle([20.166670, 79.172114], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 201, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Bhadravati<br>rank: 58<br>hazard index: 0.000201")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhadravati">Bhadravati</a>')

var circle_59 = L.circle([17.166667, 77.083333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 195, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Gulbarga<br>rank: 59<br>hazard index: 0.000196")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gulbarga">Gulbarga</a>')

var circle_60 = L.circle([8.701220, 77.579269], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 193, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Tirunelveli<br>rank: 60<br>hazard index: 0.000194")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tirunelveli">Tirunelveli</a>')

var circle_61 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 178, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Delhi<br>rank: 61<br>hazard index: 0.000179")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_62 = L.circle([18.793568, 80.815939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 173, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Bijapur<br>rank: 62<br>hazard index: 0.000173")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bijapur">Bijapur</a>')

var circle_63 = L.circle([17.910400, 77.519900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 169, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Bidar<br>rank: 63<br>hazard index: 0.000169")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidar">Bidar</a>')

var circle_64 = L.circle([16.237773, 80.646422], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 161, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Tenali<br>rank: 64<br>hazard index: 0.000161")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tenali">Tenali</a>')

var circle_65 = L.circle([11.369204, 77.676627], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 153, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Erode<br>rank: 65<br>hazard index: 0.000154")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Erode">Erode</a>')

var circle_66 = L.circle([16.432998, 80.993715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 146, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Gudivada<br>rank: 66<br>hazard index: 0.000147")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gudivada">Gudivada</a>')

var circle_67 = L.circle([13.125476, 80.094090], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 135, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Avadi<br>rank: 67<br>hazard index: 0.000135")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Avadi">Avadi</a>')

var circle_68 = L.circle([13.156387, 80.300528], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 129, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Tiruvottiyur<br>rank: 68<br>hazard index: 0.000129")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruvottiyur">Tiruvottiyur</a>')

var circle_69 = L.circle([10.787898, 76.474087], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 128, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Palakkad<br>rank: 69<br>hazard index: 0.000128")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palakkad">Palakkad</a>')

var circle_70 = L.circle([12.305183, 76.655361], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 118, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Mysore<br>rank: 70<br>hazard index: 0.000119")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mysore">Mysore</a>')

var circle_71 = L.circle([17.980609, 79.598212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Warangal<br>rank: 71<br>hazard index: 0.000111")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Warangal">Warangal</a>')

var circle_72 = L.circle([12.869810, 74.843008], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 109, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Mangalore<br>rank: 72<br>hazard index: 0.000110")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mangalore">Mangalore</a>')

var circle_73 = L.circle([16.181939, 81.135130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 109, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Machilipatnam<br>rank: 73<br>hazard index: 0.000109")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Machilipatnam">Machilipatnam</a>')

var circle_74 = L.circle([26.055318, 82.993139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 104, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Nizamabad<br>rank: 74<br>hazard index: 0.000105")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a>')

var circle_75 = L.circle([12.792907, 78.699917], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 99, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Ambur<br>rank: 75<br>hazard index: 0.000099")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambur">Ambur</a>')

var circle_76 = L.circle([16.876586, 81.545145], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 99, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Tadepalligudem<br>rank: 76<br>hazard index: 0.000099")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tadepalligudem">Tadepalligudem</a>')

var circle_77 = L.circle([16.094950, 80.165878], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 97, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Chilakaluripet<br>rank: 77<br>hazard index: 0.000097")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chilakaluripet">Chilakaluripet</a>')

var circle_78 = L.circle([11.715950, 79.767053], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 96, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Cuddalore Port<br>rank: 78<br>hazard index: 0.000096")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuddalore_Port">Cuddalore Port</a>')

var circle_79 = L.circle([14.625888, 75.635724], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 94, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Ranibennur<br>rank: 79<br>hazard index: 0.000094")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranibennur">Ranibennur</a>')

var circle_80 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 93, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Kolkata<br>rank: 80<br>hazard index: 0.000094")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_81 = L.circle([16.542769, 81.527344], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 90, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Bhimavaram<br>rank: 81<br>hazard index: 0.000091")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhimavaram">Bhimavaram</a>')

var circle_82 = L.circle([18.112082, 83.405220], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 90, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Vizianagaram<br>rank: 82<br>hazard index: 0.000090")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vizianagaram">Vizianagaram</a>')

var circle_83 = L.circle([10.330330, 78.067398], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 84, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Dindigul<br>rank: 83<br>hazard index: 0.000085")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dindigul">Dindigul</a>')

var circle_84 = L.circle([18.437436, 77.110521], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 83, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Udgir<br>rank: 84<br>hazard index: 0.000083")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udgir">Udgir</a>')

var circle_85 = L.circle([12.929903, 80.111823], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 82, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Tambaram<br>rank: 85<br>hazard index: 0.000083")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tambaram">Tambaram</a>')

var circle_86 = L.circle([13.341917, 74.747323], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 81, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Udupi<br>rank: 86<br>hazard index: 0.000082")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udupi">Udupi</a>')

var circle_87 = L.circle([16.743454, 77.992319], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Mahbubnagar<br>rank: 87<br>hazard index: 0.000075")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mahbubnagar">Mahbubnagar</a>')

var circle_88 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 68, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Vasco Da Gama<br>rank: 88<br>hazard index: 0.000068")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_89 = L.circle([16.185317, 75.696792], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 64, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Bagalkot<br>rank: 89<br>hazard index: 0.000065")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagalkot">Bagalkot</a>')

var circle_90 = L.circle([18.761516, 79.478785], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 61, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Ramagundam<br>rank: 90<br>hazard index: 0.000062")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ramagundam">Ramagundam</a>')

var circle_91 = L.circle([12.989816, 80.100987], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 57, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Pallavaram<br>rank: 91<br>hazard index: 0.000057")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pallavaram">Pallavaram</a>')

var circle_92 = L.circle([12.836393, 79.705330], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 52, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Kanchipuram<br>rank: 92<br>hazard index: 0.000052")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanchipuram">Kanchipuram</a>')

var circle_93 = L.circle([10.786027, 79.138150], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 48, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Thanjavur<br>rank: 93<br>hazard index: 0.000049")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thanjavur">Thanjavur</a>')

var circle_94 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Nanded Waghala<br>rank: 94<br>hazard index: 0.000043")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_95 = L.circle([16.943738, 82.235061], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 41, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Kakinada<br>rank: 95<br>hazard index: 0.000042")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kakinada">Kakinada</a>')

var circle_96 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Surat<br>rank: 96<br>hazard index: 0.000038")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_97 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Ahmedabad<br>rank: 97<br>hazard index: 0.000038")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_98 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 36, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Bhubaneswar<br>rank: 98<br>hazard index: 0.000037")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_99 = L.circle([19.261944, 73.194760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 35, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Ulhas Nagar<br>rank: 99<br>hazard index: 0.000036")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ulhas_Nagar">Ulhas Nagar</a>')

var circle_100 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 35, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Kochi<br>rank: 100<br>hazard index: 0.000036")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Kadapa">Kadapa</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bellary">Bellary</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Tirupati">Tirupati</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Anantapur">Anantapur</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Hospet">Hospet</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kurnool">Kurnool</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Dharmavaram">Dharmavaram</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Tumkur">Tumkur</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Guntakal">Guntakal</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Tadipatri. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>