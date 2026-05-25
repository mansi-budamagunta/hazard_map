---
layout: page
title: "Outbreak location: Dhanbad"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([23.795281, 86.430964],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Dhanbad").openTooltip();

var circle_1 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 84849, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Ranchi<br>rank: 1<br>hazard index: 0.084850")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_2 = L.circle([22.801519, 86.202958], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 31949, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Jamshedpur<br>rank: 2<br>hazard index: 0.031950")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a>')

var circle_3 = L.circle([23.687130, 86.974659], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 29442, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Asansol<br>rank: 3<br>hazard index: 0.029442")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a>')

var circle_4 = L.circle([24.796436, 85.007956], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27322, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Gaya<br>rank: 4<br>hazard index: 0.027322")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a>')

var circle_5 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24826, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Kolkata<br>rank: 5<br>hazard index: 0.024826")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_6 = L.circle([23.699128, 85.991069], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19894, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Bokaro<br>rank: 6<br>hazard index: 0.019894")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bokaro">Bokaro</a>')

var circle_7 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18905, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Patna<br>rank: 7<br>hazard index: 0.018906")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_8 = L.circle([23.730215, 86.839671], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17112, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Kulti<br>rank: 8<br>hazard index: 0.017113")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kulti">Kulti</a>')

var circle_9 = L.circle([24.476642, 86.606732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11938, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Deoghar<br>rank: 9<br>hazard index: 0.011938")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoghar">Deoghar</a>')

var circle_10 = L.circle([25.286698, 87.132254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10631, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Bhagalpur<br>rank: 10<br>hazard index: 0.010631")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a>')

var circle_11 = L.circle([26.083143, 86.032571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8550, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Darbhanga<br>rank: 11<br>hazard index: 0.008551")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Darbhanga">Darbhanga</a>')

var circle_12 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6356, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Chennai<br>rank: 12<br>hazard index: 0.006357")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_13 = L.circle([23.160894, 79.949770], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5382, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Jabalpur<br>rank: 13<br>hazard index: 0.005383")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jabalpur">Jabalpur</a>')

var circle_14 = L.circle([23.535048, 87.338043], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4930, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Durgapur<br>rank: 14<br>hazard index: 0.004931")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Durgapur">Durgapur</a>')

var circle_15 = L.circle([25.205305, 85.514612], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4400, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Biharsharif<br>rank: 15<br>hazard index: 0.004401")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Biharsharif">Biharsharif</a>')

var circle_16 = L.circle([25.512719, 86.090571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3881, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Begusarai<br>rank: 16<br>hazard index: 0.003881")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Begusarai">Begusarai</a>')

var circle_17 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3347, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Lucknow<br>rank: 17<br>hazard index: 0.003347")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_18 = L.circle([22.782355, 86.159003], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3236, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Adityapur<br>rank: 18<br>hazard index: 0.003236")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Adityapur">Adityapur</a>')

var circle_19 = L.circle([23.250000, 87.750000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2851, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Barddhaman<br>rank: 19<br>hazard index: 0.002852")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barddhaman">Barddhaman</a>')

var circle_20 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2611, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Delhi<br>rank: 20<br>hazard index: 0.002612")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_21 = L.circle([23.967515, 85.438846], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2539, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Hazaribagh<br>rank: 21<br>hazard index: 0.002540")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hazaribagh">Hazaribagh</a>')

var circle_22 = L.circle([25.220812, 86.517204], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2530, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Munger<br>rank: 22<br>hazard index: 0.002530")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Munger">Munger</a>')

var circle_23 = L.circle([25.133173, 86.525040], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2354, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Kharagpur<br>rank: 23<br>hazard index: 0.002354")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kharagpur">Kharagpur</a>')

var circle_24 = L.circle([17.723128, 83.301284], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2349, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Visakhapatnam<br>rank: 24<br>hazard index: 0.002350")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Visakhapatnam">Visakhapatnam</a>')

var circle_25 = L.circle([25.329791, 86.456777], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1949, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Jamalpur<br>rank: 25<br>hazard index: 0.001950")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jamalpur">Jamalpur</a>')

var circle_26 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1798, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Varanasi<br>rank: 26<br>hazard index: 0.001798")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_27 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1637, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Ludhiana<br>rank: 27<br>hazard index: 0.001637")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_28 = L.circle([23.332200, 86.361600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1595, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Purulia<br>rank: 28<br>hazard index: 0.001596")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Purulia">Purulia</a>')

var circle_29 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1506, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Dehri<br>rank: 29<br>hazard index: 0.001506")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')

var circle_30 = L.circle([11.001812, 76.962842], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1441, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Coimbatore<br>rank: 30<br>hazard index: 0.001441")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Coimbatore">Coimbatore</a>')

var circle_31 = L.circle([16.508759, 80.618510], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1423, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Vijayawada<br>rank: 31<br>hazard index: 0.001423")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vijayawada">Vijayawada</a>')

var circle_32 = L.circle([22.214285, 84.872437], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1415, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Raurkela<br>rank: 32<br>hazard index: 0.001416")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raurkela">Raurkela</a>')

var circle_33 = L.circle([25.680654, 88.124646], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1350, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Raiganj<br>rank: 33<br>hazard index: 0.001350")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raiganj">Raiganj</a>')

var circle_34 = L.circle([24.197443, 82.666145], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1153, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Singrauli<br>rank: 34<br>hazard index: 0.001153")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Singrauli">Singrauli</a>')

var circle_35 = L.circle([11.664300, 78.146000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1128, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Salem<br>rank: 35<br>hazard index: 0.001129")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Salem">Salem</a>')

var circle_36 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1055, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Bareilly<br>rank: 36<br>hazard index: 0.001055")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_37 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1021, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Moradabad<br>rank: 37<br>hazard index: 0.001021")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_38 = L.circle([23.131954, 87.207397], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 937, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Bankura<br>rank: 38<br>hazard index: 0.000938")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bankura">Bankura</a>')

var circle_39 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 933, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Gorakhpur<br>rank: 39<br>hazard index: 0.000934")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_40 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 879, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Kanpur<br>rank: 40<br>hazard index: 0.000880")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_41 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 737, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Bhubaneswar<br>rank: 41<br>hazard index: 0.000737")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_42 = L.circle([25.720581, 85.255560], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 735, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Hajipur<br>rank: 42<br>hazard index: 0.000736")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hajipur">Hajipur</a>')

var circle_43 = L.circle([22.591260, 88.390964], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 726, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Bidhan Nagar<br>rank: 43<br>hazard index: 0.000727")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bidhan_Nagar">Bidhan Nagar</a>')

var circle_44 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 711, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Saharanpur<br>rank: 44<br>hazard index: 0.000712")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_45 = L.circle([14.449372, 79.987376], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 686, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Nellore<br>rank: 45<br>hazard index: 0.000686")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nellore">Nellore</a>')

var circle_46 = L.circle([25.623400, 85.041700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 685, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Dinapur Nizamat<br>rank: 46<br>hazard index: 0.000685")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dinapur_Nizamat">Dinapur Nizamat</a>')

var circle_47 = L.circle([24.935635, 82.647701], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 644, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Mirzapur<br>rank: 47<br>hazard index: 0.000645")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mirzapur">Mirzapur</a>')

var circle_48 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 605, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Bangalore<br>rank: 48<br>hazard index: 0.000605")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_49 = L.circle([11.101781, 77.345192], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 603, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Tiruppur<br>rank: 49<br>hazard index: 0.000604")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruppur">Tiruppur</a>')

var circle_50 = L.circle([25.560900, 87.647654], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 595, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Katihar<br>rank: 50<br>hazard index: 0.000596")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Katihar">Katihar</a>')

var circle_51 = L.circle([20.468600, 85.879200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 533, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Cuttack<br>rank: 51<br>hazard index: 0.000533")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Cuttack">Cuttack</a>')

var circle_52 = L.circle([25.623457, 84.596839], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 522, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Arrah<br>rank: 52<br>hazard index: 0.000523")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Arrah">Arrah</a>')

var circle_53 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 506, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Muzaffarpur<br>rank: 53<br>hazard index: 0.000506")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_54 = L.circle([17.005045, 81.780473], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 467, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Rajahmundry<br>rank: 54<br>hazard index: 0.000467")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rajahmundry">Rajahmundry</a>')

var circle_55 = L.circle([21.400000, 83.883333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 453, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Sambalpur<br>rank: 55<br>hazard index: 0.000454")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambalpur">Sambalpur</a>')

var circle_56 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 452, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Allahabad<br>rank: 56<br>hazard index: 0.000452")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_57 = L.circle([25.152471, 85.006878], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 449, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Jehanabad<br>rank: 57<br>hazard index: 0.000450")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jehanabad">Jehanabad</a>')

var circle_58 = L.circle([10.525626, 76.213254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 428, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Thrissur<br>rank: 58<br>hazard index: 0.000429")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thrissur">Thrissur</a>')

var circle_59 = L.circle([24.900100, 84.018211], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 417, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Sasaram<br>rank: 59<br>hazard index: 0.000417")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sasaram">Sasaram</a>')

var circle_60 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 392, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Jaipur<br>rank: 60<br>hazard index: 0.000392")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_61 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 385, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Hyderabad<br>rank: 61<br>hazard index: 0.000386")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_62 = L.circle([25.832642, 86.614893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 375, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Saharsa<br>rank: 62<br>hazard index: 0.000375")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharsa">Saharsa</a>')

var circle_63 = L.circle([27.912633, 79.746563], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 366, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Shahjahanpur<br>rank: 63<br>hazard index: 0.000367")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shahjahanpur">Shahjahanpur</a>')

var circle_64 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 363, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Rampur<br>rank: 64<br>hazard index: 0.000364")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_65 = L.circle([22.472223, 88.093845], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 363, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Uluberia<br>rank: 65<br>hazard index: 0.000363")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Uluberia">Uluberia</a>')

var circle_66 = L.circle([26.716413, 88.430992], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 360, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Siliguri<br>rank: 66<br>hazard index: 0.000360")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siliguri">Siliguri</a>')

var circle_67 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 340, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Pune<br>rank: 67<br>hazard index: 0.000340")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_68 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 336, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Bhopal<br>rank: 68<br>hazard index: 0.000336")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_69 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 335, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Mumbai<br>rank: 69<br>hazard index: 0.000336")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_70 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 310, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Nagpur<br>rank: 70<br>hazard index: 0.000310")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_71 = L.circle([18.112082, 83.405220], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 308, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Vizianagaram<br>rank: 71<br>hazard index: 0.000309")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vizianagaram">Vizianagaram</a>')

var circle_72 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 292, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Agra<br>rank: 72<br>hazard index: 0.000292")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_73 = L.circle([16.676135, 81.170868], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 291, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Eluru<br>rank: 73<br>hazard index: 0.000291")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Eluru">Eluru</a>')

var circle_74 = L.circle([22.890183, 88.426939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 283, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Naihati<br>rank: 74<br>hazard index: 0.000284")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Naihati">Naihati</a>')

var circle_75 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 280, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Chapra<br>rank: 75<br>hazard index: 0.000281")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_76 = L.circle([15.507554, 80.060800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 275, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Ongole<br>rank: 76<br>hazard index: 0.000275")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ongole">Ongole</a>')

var circle_77 = L.circle([9.500665, 76.412414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 236, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Alappuzha<br>rank: 77<br>hazard index: 0.000237")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alappuzha">Alappuzha</a>')

var circle_78 = L.circle([16.237773, 80.646422], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 223, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Tenali<br>rank: 78<br>hazard index: 0.000224")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tenali">Tenali</a>')

var circle_79 = L.circle([25.572433, 83.609605], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 221, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Medinipur<br>rank: 79<br>hazard index: 0.000222")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Medinipur">Medinipur</a>')

var circle_80 = L.circle([22.695034, 88.377060], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 217, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Panihati<br>rank: 80<br>hazard index: 0.000217")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panihati">Panihati</a>')

var circle_81 = L.circle([11.369204, 77.676627], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 213, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Erode<br>rank: 81<br>hazard index: 0.000213")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Erode">Erode</a>')

var circle_82 = L.circle([16.943738, 82.235061], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 209, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Kakinada<br>rank: 82<br>hazard index: 0.000210")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kakinada">Kakinada</a>')

var circle_83 = L.circle([25.280733, 83.125128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 207, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Mughal Sarai<br>rank: 83<br>hazard index: 0.000207")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a>')

var circle_84 = L.circle([24.500000, 81.000000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 203, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Satna<br>rank: 84<br>hazard index: 0.000204")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Satna">Satna</a>')

var circle_85 = L.circle([24.965712, 88.127778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 198, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("English Bazar<br>rank: 85<br>hazard index: 0.000198")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/English_Bazar">English Bazar</a>')

var circle_86 = L.circle([25.795593, 82.488341], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 187, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Jaunpur<br>rank: 86<br>hazard index: 0.000188")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaunpur">Jaunpur</a>')

var circle_87 = L.circle([22.383333, 82.133333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 187, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Bilaspur<br>rank: 87<br>hazard index: 0.000187")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bilaspur">Bilaspur</a>')

var circle_88 = L.circle([26.638076, 82.059024], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 187, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Faizabad<br>rank: 88<br>hazard index: 0.000187")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faizabad">Faizabad</a>')

var circle_89 = L.circle([26.131004, 84.391257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 187, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Siwan<br>rank: 89<br>hazard index: 0.000187")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Siwan">Siwan</a>')

var circle_90 = L.circle([26.423847, 83.762732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 180, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Deoria<br>rank: 90<br>hazard index: 0.000180")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Deoria">Deoria</a>')

var circle_91 = L.circle([10.787898, 76.474087], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 177, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Palakkad<br>rank: 91<br>hazard index: 0.000178")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palakkad">Palakkad</a>')

var circle_92 = L.circle([22.670728, 88.376342], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 176, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Kamarhati<br>rank: 92<br>hazard index: 0.000177")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kamarhati">Kamarhati</a>')

var circle_93 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 174, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Guwahati<br>rank: 93<br>hazard index: 0.000174")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_94 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 168, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Jhansi<br>rank: 94<br>hazard index: 0.000168")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_95 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 163, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Raipur<br>rank: 95<br>hazard index: 0.000164")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_96 = L.circle([22.646958, 88.343612], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 161, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Bally<br>rank: 96<br>hazard index: 0.000162")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bally">Bally</a>')

var circle_97 = L.circle([10.804973, 78.687030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 157, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Tiruchirappalli<br>rank: 97<br>hazard index: 0.000158")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tiruchirappalli">Tiruchirappalli</a>')

var circle_98 = L.circle([22.508621, 88.253218], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 144, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Maheshtala<br>rank: 98<br>hazard index: 0.000145")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Maheshtala">Maheshtala</a>')

var circle_99 = L.circle([27.338577, 80.097526], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Hardoi<br>rank: 99<br>hazard index: 0.000142")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hardoi">Hardoi</a>')

var circle_100 = L.circle([16.876586, 81.545145], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 140, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Tadepalligudem<br>rank: 100<br>hazard index: 0.000141")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Tadepalligudem">Tadepalligudem</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jamshedpur">Jamshedpur</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Asansol">Asansol</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bokaro">Bokaro</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Kulti">Kulti</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Deoghar">Deoghar</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Dhanbad. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>