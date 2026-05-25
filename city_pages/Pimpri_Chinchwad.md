---
layout: page
title: "Outbreak location: Pimpri Chinchwad"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([18.627929, 73.800983],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Pimpri Chinchwad").openTooltip();

var circle_1 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 163273, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Pune<br>rank: 1<br>hazard index: 0.163273")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_2 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121465, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Mumbai<br>rank: 2<br>hazard index: 0.121465")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_3 = L.circle([17.849907, 75.276320], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18110, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Solapur<br>rank: 3<br>hazard index: 0.018111")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a>')

var circle_4 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17567, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Thane<br>rank: 4<br>hazard index: 0.017568")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_5 = L.circle([19.439885, 72.880383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9394, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Vasai<br>rank: 5<br>hazard index: 0.009395")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a>')

var circle_6 = L.circle([19.295200, 72.854400], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7401, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Mira-Bhayandar<br>rank: 6<br>hazard index: 0.007401")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mira-Bhayandar">Mira-Bhayandar</a>')

var circle_7 = L.circle([19.362531, 73.078475], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6482, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Bhiwandi<br>rank: 7<br>hazard index: 0.006482")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwandi">Bhiwandi</a>')

var circle_8 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5839, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Nashik<br>rank: 8<br>hazard index: 0.005840")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_9 = L.circle([19.261944, 73.194760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4628, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Ulhas Nagar<br>rank: 9<br>hazard index: 0.004628")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ulhas_Nagar">Ulhas Nagar</a>')

var circle_10 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3461, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Delhi<br>rank: 10<br>hazard index: 0.003461")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_11 = L.circle([17.636129, 74.298278], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3197, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Satara<br>rank: 11<br>hazard index: 0.003197")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satara">Satara</a>')

var circle_12 = L.circle([19.794750, 75.077922], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2756, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Gangapur<br>rank: 12<br>hazard index: 0.002756")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gangapur">Gangapur</a>')

var circle_13 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2463, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Bangalore<br>rank: 13<br>hazard index: 0.002464")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_14 = L.circle([19.143607, 73.295535], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2278, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Ambarnath<br>rank: 14<br>hazard index: 0.002278")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambarnath">Ambarnath</a>')

var circle_15 = L.circle([19.250000, 74.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2231, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Ahmadnagar<br>rank: 15<br>hazard index: 0.002232")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmadnagar">Ahmadnagar</a>')

var circle_16 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2085, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Surat<br>rank: 16<br>hazard index: 0.002086")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_17 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2055, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Ahmedabad<br>rank: 17<br>hazard index: 0.002056")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_18 = L.circle([20.325704, 78.116914], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1964, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Yavatmal<br>rank: 18<br>hazard index: 0.001965")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yavatmal">Yavatmal</a>')

var circle_19 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1922, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Hyderabad<br>rank: 19<br>hazard index: 0.001923")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_20 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1581, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Chennai<br>rank: 20<br>hazard index: 0.001581")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_21 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1396, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Vasco Da Gama<br>rank: 21<br>hazard index: 0.001397")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_22 = L.circle([18.793568, 80.815939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1221, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Bijapur<br>rank: 22<br>hazard index: 0.001222")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bijapur">Bijapur</a>')

var circle_23 = L.circle([16.850253, 74.594888], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1094, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Sangli<br>rank: 23<br>hazard index: 0.001095")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sangli">Sangli</a>')

var circle_24 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 984, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Nagpur<br>rank: 24<br>hazard index: 0.000985")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_25 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 897, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Kolkata<br>rank: 25<br>hazard index: 0.000898")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_26 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 795, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Vadodara<br>rank: 26<br>hazard index: 0.000796")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_27 = L.circle([20.432402, 73.141172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 760, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Valsad<br>rank: 27<br>hazard index: 0.000760")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Valsad">Valsad</a>')

var circle_28 = L.circle([16.702841, 74.240533], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 678, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Kolhapur<br>rank: 28<br>hazard index: 0.000678")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolhapur">Kolhapur</a>')

var circle_29 = L.circle([12.869810, 74.843008], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 583, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Mangalore<br>rank: 29<br>hazard index: 0.000583")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mangalore">Mangalore</a>')

var circle_30 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 520, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Jhansi<br>rank: 30<br>hazard index: 0.000521")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_31 = L.circle([15.857267, 74.506934], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 460, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Belgaum<br>rank: 31<br>hazard index: 0.000460")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Belgaum">Belgaum</a>')

var circle_32 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 437, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Lucknow<br>rank: 32<br>hazard index: 0.000438")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_33 = L.circle([19.877263, 75.339024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 415, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Aurangabad<br>rank: 33<br>hazard index: 0.000415")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aurangabad">Aurangabad</a>')

var circle_34 = L.circle([25.895924, 82.437716], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 414, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Badlapur<br>rank: 34<br>hazard index: 0.000414")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Badlapur">Badlapur</a>')

var circle_35 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 413, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Nanded Waghala<br>rank: 35<br>hazard index: 0.000413")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_36 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 399, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Jaipur<br>rank: 36<br>hazard index: 0.000400")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_37 = L.circle([15.351838, 75.137985], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 368, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Hubli<br>rank: 37<br>hazard index: 0.000369")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hubli">Hubli</a>')

var circle_38 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 364, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Kochi<br>rank: 38<br>hazard index: 0.000364")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_39 = L.circle([18.351469, 76.755121], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 358, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Latur<br>rank: 39<br>hazard index: 0.000359")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Latur">Latur</a>')

var circle_40 = L.circle([8.576971, 77.050125], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 337, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Thiruvananthapuram<br>rank: 40<br>hazard index: 0.000337")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thiruvananthapuram">Thiruvananthapuram</a>')

var circle_41 = L.circle([16.695935, 74.455575], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 329, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Ichalkaranji<br>rank: 41<br>hazard index: 0.000330")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ichalkaranji">Ichalkaranji</a>')

var circle_42 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 306, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Allahabad<br>rank: 42<br>hazard index: 0.000306")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_43 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 293, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Bhopal<br>rank: 43<br>hazard index: 0.000293")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_44 = L.circle([11.258608, 75.778874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 290, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Kozhikode<br>rank: 44<br>hazard index: 0.000290")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kozhikode">Kozhikode</a>')

var circle_45 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 287, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Jabalpur<br>rank: 45<br>hazard index: 0.000288")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_46 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 285, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Varanasi<br>rank: 46<br>hazard index: 0.000286")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_47 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 250, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Indore<br>rank: 47<br>hazard index: 0.000251")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_48 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 237, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Kanpur<br>rank: 48<br>hazard index: 0.000238")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_49 = L.circle([19.290314, 76.602903], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 237, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Parbhani<br>rank: 49<br>hazard index: 0.000237")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Parbhani">Parbhani</a>')

var circle_50 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 231, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Akola<br>rank: 50<br>hazard index: 0.000231")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')

var circle_51 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 229, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Patna<br>rank: 51<br>hazard index: 0.000229")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_52 = L.circle([26.732501, 77.036312], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 215, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Hindaun<br>rank: 52<br>hazard index: 0.000215")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hindaun">Hindaun</a>')

var circle_53 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 209, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Raipur<br>rank: 53<br>hazard index: 0.000210")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_54 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 209, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Jalgaon<br>rank: 54<br>hazard index: 0.000209")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_55 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 204, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Coimbatore<br>rank: 55<br>hazard index: 0.000204")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_56 = L.circle([16.185317, 75.696792], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 188, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Bagalkot<br>rank: 56<br>hazard index: 0.000189")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagalkot">Bagalkot</a>')

var circle_57 = L.circle([22.305199, 70.802834], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 174, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Rajkot<br>rank: 57<br>hazard index: 0.000175")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a>')

var circle_58 = L.circle([24.578721, 73.686257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 170, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Udaipur<br>rank: 58<br>hazard index: 0.000171")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a>')

var circle_59 = L.circle([15.426365, 75.630079], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 164, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Gadag<br>rank: 59<br>hazard index: 0.000164")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gadag">Gadag</a>')

var circle_60 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 148, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Bhubaneswar<br>rank: 60<br>hazard index: 0.000149")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_61 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 143, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Chandigarh<br>rank: 61<br>hazard index: 0.000144")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_62 = L.circle([10.525626, 76.213254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 142, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Thrissur<br>rank: 62<br>hazard index: 0.000142")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thrissur">Thrissur</a>')

var circle_63 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Bhusawal<br>rank: 63<br>hazard index: 0.000141")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_64 = L.circle([12.305183, 76.655361], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 115, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Mysore<br>rank: 64<br>hazard index: 0.000116")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mysore">Mysore</a>')

var circle_65 = L.circle([8.887951, 76.595501], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 113, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Kollam<br>rank: 65<br>hazard index: 0.000113")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kollam">Kollam</a>')

var circle_66 = L.circle([18.182992, 75.743925], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 111, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Barshi<br>rank: 66<br>hazard index: 0.000111")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barshi">Barshi</a>')

var circle_67 = L.circle([16.083333, 77.166667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 111, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Raichur<br>rank: 67<br>hazard index: 0.000111")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raichur">Raichur</a>')

var circle_68 = L.circle([19.918233, 75.868625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Jalna<br>rank: 68<br>hazard index: 0.000110")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalna">Jalna</a>')

var circle_69 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 106, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Visakhapatnam<br>rank: 69<br>hazard index: 0.000106")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_70 = L.circle([18.169844, 76.117963], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 105, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Osmanabad<br>rank: 70<br>hazard index: 0.000105")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Osmanabad">Osmanabad</a>')

var circle_71 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 104, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Amritsar<br>rank: 71<br>hazard index: 0.000104")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_72 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 101, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Kota<br>rank: 72<br>hazard index: 0.000101")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_73 = L.circle([26.055318, 82.993139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 95, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Nizamabad<br>rank: 73<br>hazard index: 0.000096")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a>')

var circle_74 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 93, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Jodhpur<br>rank: 74<br>hazard index: 0.000094")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_75 = L.circle([13.341917, 74.747323], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 93, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Udupi<br>rank: 75<br>hazard index: 0.000093")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udupi">Udupi</a>')

var circle_76 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 86, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Guwahati<br>rank: 76<br>hazard index: 0.000086")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_77 = L.circle([17.980609, 79.598212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 76, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Warangal<br>rank: 77<br>hazard index: 0.000077")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Warangal">Warangal</a>')

var circle_78 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Satna<br>rank: 78<br>hazard index: 0.000075")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_79 = L.circle([16.181939, 81.135130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 72, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Machilipatnam<br>rank: 79<br>hazard index: 0.000073")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Machilipatnam">Machilipatnam</a>')

var circle_80 = L.circle([21.154541, 77.644296], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 72, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Amravati<br>rank: 80<br>hazard index: 0.000073")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amravati">Amravati</a>')

var circle_81 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 66, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Gorakhpur<br>rank: 81<br>hazard index: 0.000066")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_82 = L.circle([11.664300, 78.146000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 65, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Salem<br>rank: 82<br>hazard index: 0.000066")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Salem">Salem</a>')

var circle_83 = L.circle([9.926115, 78.114098], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 65, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Madurai<br>rank: 83<br>hazard index: 0.000065")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Madurai">Madurai</a>')

var circle_84 = L.circle([13.340077, 77.100621], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Tumkur<br>rank: 84<br>hazard index: 0.000063")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tumkur">Tumkur</a>')

var circle_85 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 61, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Alwar<br>rank: 85<br>hazard index: 0.000061")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_86 = L.circle([14.475294, 78.821686], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 58, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Kadapa<br>rank: 86<br>hazard index: 0.000059")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kadapa">Kadapa</a>')

var circle_87 = L.circle([26.698885, 88.320030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 57, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Bagdogra<br>rank: 87<br>hazard index: 0.000057")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagdogra">Bagdogra</a>')

var circle_88 = L.circle([23.247245, 69.668339], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 57, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Bhuj<br>rank: 88<br>hazard index: 0.000057")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhuj">Bhuj</a>')

var circle_89 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 55, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Ranchi<br>rank: 89<br>hazard index: 0.000055")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_90 = L.circle([20.952407, 72.932383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Navsari<br>rank: 90<br>hazard index: 0.000054")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Navsari">Navsari</a>')

var circle_91 = L.circle([21.977864, 76.568828], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Khandwa<br>rank: 91<br>hazard index: 0.000053")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khandwa">Khandwa</a>')

var circle_92 = L.circle([17.910400, 77.519900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 51, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Bidar<br>rank: 92<br>hazard index: 0.000052")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidar">Bidar</a>')

var circle_93 = L.circle([22.473242, 70.055210], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Jamnagar<br>rank: 93<br>hazard index: 0.000051")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamnagar">Jamnagar</a>')

var circle_94 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Dehradun<br>rank: 94<br>hazard index: 0.000050")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_95 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Agra<br>rank: 95<br>hazard index: 0.000050")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_96 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Faridabad<br>rank: 96<br>hazard index: 0.000049")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_97 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 48, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Gurgaon<br>rank: 97<br>hazard index: 0.000049")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_98 = L.circle([21.750000, 73.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 47, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Bharuch<br>rank: 98<br>hazard index: 0.000048")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharuch">Bharuch</a>')

var circle_99 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Jamshedpur<br>rank: 99<br>hazard index: 0.000045")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_100 = L.circle([20.825623, 78.613146], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Wardha<br>rank: 100<br>hazard index: 0.000045")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Wardha">Wardha</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mira-Bhayandar">Mira-Bhayandar</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhiwandi">Bhiwandi</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ulhas_Nagar">Ulhas Nagar</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Pimpri Chinchwad. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>