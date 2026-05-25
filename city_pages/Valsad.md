---
layout: page
title: "Outbreak location: Valsad"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([20.432402, 73.141172],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Valsad").openTooltip();

var circle_1 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 161627, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Mumbai<br>rank: 1<br>hazard index: 0.161627")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_2 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 108490, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Surat<br>rank: 2<br>hazard index: 0.108491")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_3 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 34860, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Ahmedabad<br>rank: 3<br>hazard index: 0.034860")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_4 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23012, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Vadodara<br>rank: 4<br>hazard index: 0.023013")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_5 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9038, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Thane<br>rank: 5<br>hazard index: 0.009038")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_6 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6743, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Pune<br>rank: 6<br>hazard index: 0.006743")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_7 = L.circle([19.439885, 72.880383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5183, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Vasai<br>rank: 7<br>hazard index: 0.005184")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a>')

var circle_8 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3992, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Delhi<br>rank: 8<br>hazard index: 0.003992")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_9 = L.circle([20.952407, 72.932383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3918, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Navsari<br>rank: 9<br>hazard index: 0.003918")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Navsari">Navsari</a>')

var circle_10 = L.circle([21.750000, 73.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2507, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Bharuch<br>rank: 10<br>hazard index: 0.002507")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharuch">Bharuch</a>')

var circle_11 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2344, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Nashik<br>rank: 11<br>hazard index: 0.002345")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_12 = L.circle([18.627929, 73.800983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2266, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Pimpri Chinchwad<br>rank: 12<br>hazard index: 0.002266")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pimpri_Chinchwad">Pimpri Chinchwad</a>')

var circle_13 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1858, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Vasco Da Gama<br>rank: 13<br>hazard index: 0.001859")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_14 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1816, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Bangalore<br>rank: 14<br>hazard index: 0.001817")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_15 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1590, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Hyderabad<br>rank: 15<br>hazard index: 0.001591")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_16 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1491, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Jalgaon<br>rank: 16<br>hazard index: 0.001491")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_17 = L.circle([22.689507, 72.871520], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1360, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Nadiad<br>rank: 17<br>hazard index: 0.001361")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nadiad">Nadiad</a>')

var circle_18 = L.circle([22.305199, 70.802834], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1337, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Rajkot<br>rank: 18<br>hazard index: 0.001337")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajkot">Rajkot</a>')

var circle_19 = L.circle([19.295200, 72.854400], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1299, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Mira-Bhayandar<br>rank: 19<br>hazard index: 0.001300")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mira-Bhayandar">Mira-Bhayandar</a>')

var circle_20 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1269, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Jabalpur<br>rank: 20<br>hazard index: 0.001270")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_21 = L.circle([22.558499, 72.962563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1233, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Anand<br>rank: 21<br>hazard index: 0.001233")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Anand">Anand</a>')

var circle_22 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1203, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Jhansi<br>rank: 22<br>hazard index: 0.001204")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_23 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1194, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Kolkata<br>rank: 23<br>hazard index: 0.001194")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_24 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1167, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Chennai<br>rank: 24<br>hazard index: 0.001168")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_25 = L.circle([19.362531, 73.078475], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1151, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Bhiwandi<br>rank: 25<br>hazard index: 0.001152")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwandi">Bhiwandi</a>')

var circle_26 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1084, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Varanasi<br>rank: 26<br>hazard index: 0.001085")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_27 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1024, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Allahabad<br>rank: 27<br>hazard index: 0.001024")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_28 = L.circle([19.261944, 73.194760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1020, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Ulhas Nagar<br>rank: 28<br>hazard index: 0.001020")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ulhas_Nagar">Ulhas Nagar</a>')

var circle_29 = L.circle([21.771884, 72.141645], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 962, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Bhavnagar<br>rank: 29<br>hazard index: 0.000962")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhavnagar">Bhavnagar</a>')

var circle_30 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 892, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Nagpur<br>rank: 30<br>hazard index: 0.000892")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_31 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 887, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Bhopal<br>rank: 31<br>hazard index: 0.000888")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_32 = L.circle([17.636129, 74.298278], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 840, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Satara<br>rank: 32<br>hazard index: 0.000841")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satara">Satara</a>')

var circle_33 = L.circle([12.869810, 74.843008], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 776, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Mangalore<br>rank: 33<br>hazard index: 0.000776")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mangalore">Mangalore</a>')

var circle_34 = L.circle([21.365999, 74.284004], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 727, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Nandurbar<br>rank: 34<br>hazard index: 0.000727")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nandurbar">Nandurbar</a>')

var circle_35 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 619, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Kanpur<br>rank: 35<br>hazard index: 0.000619")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_36 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 613, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Bhusawal<br>rank: 36<br>hazard index: 0.000614")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_37 = L.circle([19.143607, 73.295535], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 593, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Ambarnath<br>rank: 37<br>hazard index: 0.000593")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambarnath">Ambarnath</a>')

var circle_38 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 582, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Lucknow<br>rank: 38<br>hazard index: 0.000583")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_39 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 531, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Jaipur<br>rank: 39<br>hazard index: 0.000532")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_40 = L.circle([23.666667, 72.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 530, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Mahesana<br>rank: 40<br>hazard index: 0.000531")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mahesana">Mahesana</a>')

var circle_41 = L.circle([22.778500, 73.624516], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 521, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Godhra<br>rank: 41<br>hazard index: 0.000522")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Godhra">Godhra</a>')

var circle_42 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 484, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Kochi<br>rank: 42<br>hazard index: 0.000484")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_43 = L.circle([8.576971, 77.050125], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 449, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Thiruvananthapuram<br>rank: 43<br>hazard index: 0.000449")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thiruvananthapuram">Thiruvananthapuram</a>')

var circle_44 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 433, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Jodhpur<br>rank: 44<br>hazard index: 0.000433")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_45 = L.circle([22.610318, 73.461706], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 386, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Kalol<br>rank: 45<br>hazard index: 0.000387")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kalol">Kalol</a>')

var circle_46 = L.circle([11.258608, 75.778874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 385, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Kozhikode<br>rank: 46<br>hazard index: 0.000386")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kozhikode">Kozhikode</a>')

var circle_47 = L.circle([23.223288, 72.649227], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 366, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Gandhinagar<br>rank: 47<br>hazard index: 0.000366")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhinagar">Gandhinagar</a>')

var circle_48 = L.circle([23.071874, 70.131715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 337, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Gandhidham<br>rank: 48<br>hazard index: 0.000338")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhidham">Gandhidham</a>')

var circle_49 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 333, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Indore<br>rank: 49<br>hazard index: 0.000334")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_50 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 320, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Muzaffarpur<br>rank: 50<br>hazard index: 0.000321")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_51 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 305, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Patna<br>rank: 51<br>hazard index: 0.000305")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_52 = L.circle([22.750000, 71.666667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 297, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Surendranagar<br>rank: 52<br>hazard index: 0.000297")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surendranagar">Surendranagar</a>')

var circle_53 = L.circle([17.849907, 75.276320], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 282, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Solapur<br>rank: 53<br>hazard index: 0.000283")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Solapur">Solapur</a>')

var circle_54 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 279, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Raipur<br>rank: 54<br>hazard index: 0.000279")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_55 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 271, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Coimbatore<br>rank: 55<br>hazard index: 0.000272")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_56 = L.circle([19.250000, 74.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 266, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Ahmadnagar<br>rank: 56<br>hazard index: 0.000267")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmadnagar">Ahmadnagar</a>')

var circle_57 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 255, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Satna<br>rank: 57<br>hazard index: 0.000255")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_58 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 245, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Bhubaneswar<br>rank: 58<br>hazard index: 0.000245")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_59 = L.circle([24.578721, 73.686257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 227, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Udaipur<br>rank: 59<br>hazard index: 0.000227")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a>')

var circle_60 = L.circle([25.895924, 82.437716], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 213, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Badlapur<br>rank: 60<br>hazard index: 0.000213")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Badlapur">Badlapur</a>')

var circle_61 = L.circle([23.774057, 71.683735], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 213, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Patan<br>rank: 61<br>hazard index: 0.000213")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patan">Patan</a>')

var circle_62 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 211, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Kota<br>rank: 62<br>hazard index: 0.000212")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_63 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 209, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Meerut<br>rank: 63<br>hazard index: 0.000209")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_64 = L.circle([22.168600, 71.668500], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 207, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Botad<br>rank: 64<br>hazard index: 0.000208")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Botad">Botad</a>')

var circle_65 = L.circle([24.170979, 72.436638], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 202, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Palanpur<br>rank: 65<br>hazard index: 0.000203")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palanpur">Palanpur</a>')

var circle_66 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 191, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Chandigarh<br>rank: 66<br>hazard index: 0.000191")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_67 = L.circle([10.525626, 76.213254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 189, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Thrissur<br>rank: 67<br>hazard index: 0.000189")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thrissur">Thrissur</a>')

var circle_68 = L.circle([22.473242, 70.055210], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 187, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Jamnagar<br>rank: 68<br>hazard index: 0.000187")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamnagar">Jamnagar</a>')

var circle_69 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 181, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Chapra<br>rank: 69<br>hazard index: 0.000182")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_70 = L.circle([26.469100, 74.639000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 175, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Ajmer<br>rank: 70<br>hazard index: 0.000175")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a>')

var circle_71 = L.circle([23.174597, 75.785142], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 168, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Ujjain<br>rank: 71<br>hazard index: 0.000169")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ujjain">Ujjain</a>')

var circle_72 = L.circle([19.877263, 75.339024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 166, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Aurangabad<br>rank: 72<br>hazard index: 0.000167")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aurangabad">Aurangabad</a>')

var circle_73 = L.circle([20.761862, 77.192172], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 157, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Akola<br>rank: 73<br>hazard index: 0.000158")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Akola">Akola</a>')

var circle_74 = L.circle([8.887951, 76.595501], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 150, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Kollam<br>rank: 74<br>hazard index: 0.000151")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kollam">Kollam</a>')

var circle_75 = L.circle([23.480592, 74.917790], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 147, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Ratlam<br>rank: 75<br>hazard index: 0.000148")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ratlam">Ratlam</a>')

var circle_76 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Visakhapatnam<br>rank: 76<br>hazard index: 0.000141")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_77 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 138, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Amritsar<br>rank: 77<br>hazard index: 0.000138")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_78 = L.circle([25.720581, 85.255560], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 132, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Hajipur<br>rank: 78<br>hazard index: 0.000133")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hajipur">Hajipur</a>')

var circle_79 = L.circle([13.341917, 74.747323], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 124, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Udupi<br>rank: 79<br>hazard index: 0.000124")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udupi">Udupi</a>')

var circle_80 = L.circle([23.247245, 69.668339], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 117, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Bhuj<br>rank: 80<br>hazard index: 0.000117")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhuj">Bhuj</a>')

var circle_81 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 114, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Guwahati<br>rank: 81<br>hazard index: 0.000115")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_82 = L.circle([24.268349, 72.204387], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 112, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Deesa<br>rank: 82<br>hazard index: 0.000113")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deesa">Deesa</a>')

var circle_83 = L.circle([19.169335, 77.311013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 112, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Nanded Waghala<br>rank: 83<br>hazard index: 0.000112")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nanded_Waghala">Nanded Waghala</a>')

var circle_84 = L.circle([21.154541, 77.644296], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 98, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Amravati<br>rank: 84<br>hazard index: 0.000099")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amravati">Amravati</a>')

var circle_85 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 96, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Bilaspur<br>rank: 85<br>hazard index: 0.000097")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_86 = L.circle([25.877933, 84.119959], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 94, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Ballia<br>rank: 86<br>hazard index: 0.000094")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ballia">Ballia</a>')

var circle_87 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 88, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Gorakhpur<br>rank: 87<br>hazard index: 0.000088")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_88 = L.circle([15.351838, 75.137985], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 87, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Hubli<br>rank: 88<br>hazard index: 0.000088")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hubli">Hubli</a>')

var circle_89 = L.circle([25.604091, 73.415609], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 87, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Pali<br>rank: 89<br>hazard index: 0.000088")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pali">Pali</a>')

var circle_90 = L.circle([9.926115, 78.114098], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 86, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Madurai<br>rank: 90<br>hazard index: 0.000087")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Madurai">Madurai</a>')

var circle_91 = L.circle([12.305183, 76.655361], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 85, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Mysore<br>rank: 91<br>hazard index: 0.000085")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mysore">Mysore</a>')

var circle_92 = L.circle([16.850253, 74.594888], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 82, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Sangli<br>rank: 92<br>hazard index: 0.000082")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sangli">Sangli</a>')

var circle_93 = L.circle([20.325704, 78.116914], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 81, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Yavatmal<br>rank: 93<br>hazard index: 0.000081")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yavatmal">Yavatmal</a>')

var circle_94 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 77, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Bikaner<br>rank: 94<br>hazard index: 0.000078")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_95 = L.circle([26.698885, 88.320030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 76, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Bagdogra<br>rank: 95<br>hazard index: 0.000076")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagdogra">Bagdogra</a>')

var circle_96 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 73, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Ranchi<br>rank: 96<br>hazard index: 0.000074")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_97 = L.circle([21.517410, 70.464275], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 70, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Junagadh<br>rank: 97<br>hazard index: 0.000071")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Junagadh">Junagadh</a>')

var circle_98 = L.circle([21.977864, 76.568828], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 70, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Khandwa<br>rank: 98<br>hazard index: 0.000071")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khandwa">Khandwa</a>')

var circle_99 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 66, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Dehradun<br>rank: 99<br>hazard index: 0.000067")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_100 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 65, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Agra<br>rank: 100<br>hazard index: 0.000066")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Vasai">Vasai</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Navsari">Navsari</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bharuch">Bharuch</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Valsad. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>