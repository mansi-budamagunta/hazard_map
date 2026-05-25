---
layout: page
title: "Outbreak location: Darbhanga"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([26.083143, 86.032571],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Darbhanga").openTooltip();

var circle_1 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 56940, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Patna<br>rank: 1<br>hazard index: 0.056940")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_2 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53937, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Kolkata<br>rank: 2<br>hazard index: 0.053938")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_3 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 32754, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Delhi<br>rank: 3<br>hazard index: 0.032755")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_4 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30949, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Muzaffarpur<br>rank: 4<br>hazard index: 0.030949")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_5 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20573, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Mumbai<br>rank: 5<br>hazard index: 0.020574")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_6 = L.circle([26.000000, 87.500000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11779, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Purnia<br>rank: 6<br>hazard index: 0.011779")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Purnia">Purnia</a>')

var circle_7 = L.circle([25.560900, 87.647654], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9973, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Katihar<br>rank: 7<br>hazard index: 0.009973")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Katihar">Katihar</a>')

var circle_8 = L.circle([25.286698, 87.132254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7252, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Bhagalpur<br>rank: 8<br>hazard index: 0.007252")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a>')

var circle_9 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6518, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Kanpur<br>rank: 9<br>hazard index: 0.006519")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_10 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6411, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Hyderabad<br>rank: 10<br>hazard index: 0.006412")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_11 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5629, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Asansol<br>rank: 11<br>hazard index: 0.005629")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_12 = L.circle([25.832642, 86.614893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5277, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Saharsa<br>rank: 12<br>hazard index: 0.005278")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharsa">Saharsa</a>')

var circle_13 = L.circle([23.535048, 87.338043], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5174, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Durgapur<br>rank: 13<br>hazard index: 0.005175")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a>')

var circle_14 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5127, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Varanasi<br>rank: 14<br>hazard index: 0.005128")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_15 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4947, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Ludhiana<br>rank: 15<br>hazard index: 0.004948")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_16 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4723, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Lucknow<br>rank: 16<br>hazard index: 0.004724")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_17 = L.circle([23.795281, 86.430964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4369, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Dhanbad<br>rank: 17<br>hazard index: 0.004370")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhanbad">Dhanbad</a>')

var circle_18 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4236, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Allahabad<br>rank: 18<br>hazard index: 0.004237")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_19 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4038, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Ranchi<br>rank: 19<br>hazard index: 0.004038")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_20 = L.circle([23.250000, 87.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3782, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Barddhaman<br>rank: 20<br>hazard index: 0.003783")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barddhaman">Barddhaman</a>')

var circle_21 = L.circle([24.796436, 85.007956], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3753, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Gaya<br>rank: 21<br>hazard index: 0.003754")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a>')

var circle_22 = L.circle([25.720581, 85.255560], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3238, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Hajipur<br>rank: 22<br>hazard index: 0.003238")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hajipur">Hajipur</a>')

var circle_23 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3144, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Amritsar<br>rank: 23<br>hazard index: 0.003145")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_24 = L.circle([19.194329, 72.970178], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2998, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Thane<br>rank: 24<br>hazard index: 0.002999")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thane">Thane</a>')

var circle_25 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2809, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Ahmedabad<br>rank: 25<br>hazard index: 0.002810")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_26 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2753, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Bareilly<br>rank: 26<br>hazard index: 0.002754")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_27 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2727, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Moradabad<br>rank: 27<br>hazard index: 0.002728")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_28 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2643, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Jalandhar<br>rank: 28<br>hazard index: 0.002643")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_29 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2529, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Jabalpur<br>rank: 29<br>hazard index: 0.002530")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_30 = L.circle([25.512719, 86.090571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2428, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Begusarai<br>rank: 30<br>hazard index: 0.002429")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Begusarai">Begusarai</a>')

var circle_31 = L.circle([25.205305, 85.514612], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2404, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Biharsharif<br>rank: 31<br>hazard index: 0.002405")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Biharsharif">Biharsharif</a>')

var circle_32 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2253, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Gorakhpur<br>rank: 32<br>hazard index: 0.002254")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_33 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2240, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Chapra<br>rank: 33<br>hazard index: 0.002241")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_34 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2151, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Jhansi<br>rank: 34<br>hazard index: 0.002152")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_35 = L.circle([20.011247, 73.790236], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2127, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Nashik<br>rank: 35<br>hazard index: 0.002128")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nashik">Nashik</a>')

var circle_36 = L.circle([25.623400, 85.041700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2063, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Dinapur Nizamat<br>rank: 36<br>hazard index: 0.002064")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dinapur_Nizamat">Dinapur Nizamat</a>')

var circle_37 = L.circle([26.298638, 87.953148], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1865, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Kishanganj<br>rank: 37<br>hazard index: 0.001866")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kishanganj">Kishanganj</a>')

var circle_38 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1723, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Surat<br>rank: 38<br>hazard index: 0.001723")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_39 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1653, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Saharanpur<br>rank: 39<br>hazard index: 0.001653")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_40 = L.circle([22.591260, 88.390964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1579, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Bidhan Nagar<br>rank: 40<br>hazard index: 0.001579")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidhan_Nagar">Bidhan Nagar</a>')

var circle_41 = L.circle([25.623457, 84.596839], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1573, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Arrah<br>rank: 41<br>hazard index: 0.001574")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Arrah">Arrah</a>')

var circle_42 = L.circle([23.699128, 85.991069], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1557, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Bokaro<br>rank: 42<br>hazard index: 0.001557")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bokaro">Bokaro</a>')

var circle_43 = L.circle([22.890183, 88.426939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1465, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Naihati<br>rank: 43<br>hazard index: 0.001466")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Naihati">Naihati</a>')

var circle_44 = L.circle([26.791073, 84.560107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1447, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Bettiah<br>rank: 44<br>hazard index: 0.001448")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bettiah">Bettiah</a>')

var circle_45 = L.circle([26.716413, 88.430992], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1406, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Siliguri<br>rank: 45<br>hazard index: 0.001406")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siliguri">Siliguri</a>')

var circle_46 = L.circle([26.669512, 84.957411], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1376, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Motihari<br>rank: 46<br>hazard index: 0.001376")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Motihari">Motihari</a>')

var circle_47 = L.circle([25.133173, 86.525040], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1227, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Kharagpur<br>rank: 47<br>hazard index: 0.001228")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kharagpur">Kharagpur</a>')

var circle_48 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1215, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Aligarh<br>rank: 48<br>hazard index: 0.001216")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_49 = L.circle([25.220812, 86.517204], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1131, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Munger<br>rank: 49<br>hazard index: 0.001132")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Munger">Munger</a>')

var circle_50 = L.circle([25.877933, 84.119959], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1104, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Ballia<br>rank: 50<br>hazard index: 0.001105")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ballia">Ballia</a>')

var circle_51 = L.circle([24.476642, 86.606732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 954, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Deoghar<br>rank: 51<br>hazard index: 0.000955")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoghar">Deoghar</a>')

var circle_52 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 950, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Raipur<br>rank: 52<br>hazard index: 0.000951")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_53 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 921, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Pune<br>rank: 53<br>hazard index: 0.000921")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_54 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 910, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Shahjahanpur<br>rank: 54<br>hazard index: 0.000911")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_55 = L.circle([25.329791, 86.456777], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 900, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Jamalpur<br>rank: 55<br>hazard index: 0.000901")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamalpur">Jamalpur</a>')

var circle_56 = L.circle([26.131004, 84.391257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 881, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Siwan<br>rank: 56<br>hazard index: 0.000882")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siwan">Siwan</a>')

var circle_57 = L.circle([22.472223, 88.093845], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 789, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Uluberia<br>rank: 57<br>hazard index: 0.000790")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Uluberia">Uluberia</a>')

var circle_58 = L.circle([20.843512, 75.525927], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 770, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Jalgaon<br>rank: 58<br>hazard index: 0.000771")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalgaon">Jalgaon</a>')

var circle_59 = L.circle([25.152471, 85.006878], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 738, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Jehanabad<br>rank: 59<br>hazard index: 0.000738")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jehanabad">Jehanabad</a>')

var circle_60 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 707, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Bhubaneswar<br>rank: 60<br>hazard index: 0.000708")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_61 = L.circle([25.680654, 88.124646], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 679, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Raiganj<br>rank: 61<br>hazard index: 0.000679")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raiganj">Raiganj</a>')

var circle_62 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 672, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Satna<br>rank: 62<br>hazard index: 0.000672")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_63 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 587, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Nagpur<br>rank: 63<br>hazard index: 0.000588")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_64 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 580, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Bangalore<br>rank: 64<br>hazard index: 0.000581")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_65 = L.circle([22.754995, 88.341667], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 530, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Serampore<br>rank: 65<br>hazard index: 0.000531")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Serampore">Serampore</a>')

var circle_66 = L.circle([20.468600, 85.879200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 511, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Cuttack<br>rank: 66<br>hazard index: 0.000512")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuttack">Cuttack</a>')

var circle_67 = L.circle([26.505476, 93.977739], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 483, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Chandan Nagar<br>rank: 67<br>hazard index: 0.000483")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandan_Nagar">Chandan Nagar</a>')

var circle_68 = L.circle([22.695034, 88.377060], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 472, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Panihati<br>rank: 68<br>hazard index: 0.000472")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panihati">Panihati</a>')

var circle_69 = L.circle([25.603508, 83.507454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 472, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Ghazipur<br>rank: 69<br>hazard index: 0.000472")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ghazipur">Ghazipur</a>')

var circle_70 = L.circle([21.977864, 76.568828], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 467, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Khandwa<br>rank: 70<br>hazard index: 0.000468")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khandwa">Khandwa</a>')

var circle_71 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 463, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Gurgaon<br>rank: 71<br>hazard index: 0.000463")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_72 = L.circle([20.993276, 75.839983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 437, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Bhusawal<br>rank: 72<br>hazard index: 0.000438")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhusawal">Bhusawal</a>')

var circle_73 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 425, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Faridabad<br>rank: 73<br>hazard index: 0.000425")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_74 = L.circle([27.504639, 80.829466], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 416, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Sitapur<br>rank: 74<br>hazard index: 0.000417")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sitapur">Sitapur</a>')

var circle_75 = L.circle([24.965712, 88.127778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 386, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("English Bazar<br>rank: 75<br>hazard index: 0.000386")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/English_Bazar">English Bazar</a>')

var circle_76 = L.circle([22.670728, 88.376342], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 384, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Kamarhati<br>rank: 76<br>hazard index: 0.000384")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kamarhati">Kamarhati</a>')

var circle_77 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 378, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Guwahati<br>rank: 77<br>hazard index: 0.000379")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_78 = L.circle([22.646958, 88.343612], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 351, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Bally<br>rank: 78<br>hazard index: 0.000352")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bally">Bally</a>')

var circle_79 = L.circle([22.794910, 88.331772], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 350, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Baidyabati<br>rank: 79<br>hazard index: 0.000350")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baidyabati">Baidyabati</a>')

var circle_80 = L.circle([19.261944, 73.194760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 338, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Ulhas Nagar<br>rank: 80<br>hazard index: 0.000339")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ulhas_Nagar">Ulhas Nagar</a>')

var circle_81 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 337, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Rohtak<br>rank: 81<br>hazard index: 0.000337")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_82 = L.circle([26.269721, 82.994425], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 332, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Burhanpur<br>rank: 82<br>hazard index: 0.000332")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Burhanpur">Burhanpur</a>')

var circle_83 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 322, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Chennai<br>rank: 83<br>hazard index: 0.000323")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_84 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 319, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Ambala<br>rank: 84<br>hazard index: 0.000320")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_85 = L.circle([22.508621, 88.253218], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 313, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Maheshtala<br>rank: 85<br>hazard index: 0.000314")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Maheshtala">Maheshtala</a>')

var circle_86 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 310, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Bilaspur<br>rank: 86<br>hazard index: 0.000311")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_87 = L.circle([25.562071, 84.015672], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 307, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Buxar<br>rank: 87<br>hazard index: 0.000308")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Buxar">Buxar</a>')

var circle_88 = L.circle([21.735348, 81.944459], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 295, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Bhatpara<br>rank: 88<br>hazard index: 0.000296")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhatpara">Bhatpara</a>')

var circle_89 = L.circle([22.974972, 88.434591], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 291, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Kalyani<br>rank: 89<br>hazard index: 0.000291")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kalyani">Kalyani</a>')

var circle_90 = L.circle([18.627929, 73.800983], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 288, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Pimpri Chinchwad<br>rank: 90<br>hazard index: 0.000288")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pimpri_Chinchwad">Pimpri Chinchwad</a>')

var circle_91 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 285, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Meerut<br>rank: 91<br>hazard index: 0.000285")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_92 = L.circle([26.724789, 82.793269], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 284, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Basti<br>rank: 92<br>hazard index: 0.000285")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Basti">Basti</a>')

var circle_93 = L.circle([27.109667, 81.918329], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 283, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Gonda<br>rank: 93<br>hazard index: 0.000284")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gonda">Gonda</a>')

var circle_94 = L.circle([22.870214, 88.419608], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 283, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Barrackpur<br>rank: 94<br>hazard index: 0.000284")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barrackpur">Barrackpur</a>')

var circle_95 = L.circle([23.405848, 88.495893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 271, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Krishnanagar<br>rank: 95<br>hazard index: 0.000272")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Krishnanagar">Krishnanagar</a>')

var circle_96 = L.circle([31.608574, 75.846442], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 259, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Hoshiarpur<br>rank: 96<br>hazard index: 0.000260")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hoshiarpur">Hoshiarpur</a>')

var circle_97 = L.circle([30.211200, 77.286390], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 257, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Yamunanagar<br>rank: 97<br>hazard index: 0.000257")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a>')

var circle_98 = L.circle([22.214285, 84.872437], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 257, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Raurkela<br>rank: 98<br>hazard index: 0.000257")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raurkela">Raurkela</a>')

var circle_99 = L.circle([24.379576, 88.585573], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 256, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Baharampur<br>rank: 99<br>hazard index: 0.000257")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baharampur">Baharampur</a>')

var circle_100 = L.circle([21.199035, 81.397955], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 252, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Durg<br>rank: 100<br>hazard index: 0.000253")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durg">Durg</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Purnia">Purnia</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Katihar">Katihar</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Darbhanga. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>