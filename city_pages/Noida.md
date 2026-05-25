---
layout: page
title: "Outbreak location: Noida"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([28.570784, 77.327107],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Noida").openTooltip();

var circle_1 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 110983, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Delhi<br>rank: 1<br>hazard index: 0.110984")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_2 = L.circle([25.603508, 83.507454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 96984, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Ghazipur<br>rank: 2<br>hazard index: 0.096985")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ghazipur">Ghazipur</a>')

var circle_3 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14262, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Agra<br>rank: 3<br>hazard index: 0.014262")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_4 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12709, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Faridabad<br>rank: 4<br>hazard index: 0.012709")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_5 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12534, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Varanasi<br>rank: 5<br>hazard index: 0.012534")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_6 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11843, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Meerut<br>rank: 6<br>hazard index: 0.011844")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_7 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8136, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Moradabad<br>rank: 7<br>hazard index: 0.008136")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_8 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7933, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Gurgaon<br>rank: 8<br>hazard index: 0.007933")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_9 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7895, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Aligarh<br>rank: 9<br>hazard index: 0.007895")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_10 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6363, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Saharanpur<br>rank: 10<br>hazard index: 0.006364")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_11 = L.circle([25.877933, 84.119959], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4818, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Ballia<br>rank: 11<br>hazard index: 0.004818")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ballia">Ballia</a>')

var circle_12 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4471, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Loni<br>rank: 12<br>hazard index: 0.004471")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_13 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4406, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Firozabad<br>rank: 13<br>hazard index: 0.004406")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_14 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3667, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Rohtak<br>rank: 14<br>hazard index: 0.003667")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_15 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3470, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Kanpur<br>rank: 15<br>hazard index: 0.003471")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_16 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3260, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Muzaffarnagar<br>rank: 16<br>hazard index: 0.003261")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_17 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3218, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Rampur<br>rank: 17<br>hazard index: 0.003219")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_18 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2790, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Mathura<br>rank: 18<br>hazard index: 0.002790")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_19 = L.circle([25.773344, 84.784977], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2591, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Chapra<br>rank: 19<br>hazard index: 0.002591")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chapra">Chapra</a>')

var circle_20 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2577, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Panipat<br>rank: 20<br>hazard index: 0.002578")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_21 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2551, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Alwar<br>rank: 21<br>hazard index: 0.002551")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_22 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2427, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Sonipat<br>rank: 22<br>hazard index: 0.002427")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_23 = L.circle([29.680327, 76.989625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2274, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Karnal<br>rank: 23<br>hazard index: 0.002275")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karnal">Karnal</a>')

var circle_24 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2190, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Haridwar<br>rank: 24<br>hazard index: 0.002190")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_25 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2143, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Hisar<br>rank: 25<br>hazard index: 0.002144")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_26 = L.circle([27.265212, 77.369126], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2139, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Bharatpur<br>rank: 26<br>hazard index: 0.002140")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharatpur">Bharatpur</a>')

var circle_27 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2116, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Hapur<br>rank: 27<br>hazard index: 0.002117")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_28 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1998, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Allahabad<br>rank: 28<br>hazard index: 0.001999")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_29 = L.circle([30.129326, 77.245483], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1996, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Jagadhri<br>rank: 29<br>hazard index: 0.001996")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jagadhri">Jagadhri</a>')

var circle_30 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1905, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Mumbai<br>rank: 30<br>hazard index: 0.001905")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_31 = L.circle([28.388861, 77.974798], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1802, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Bulandshahr<br>rank: 31<br>hazard index: 0.001803")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bulandshahr">Bulandshahr</a>')

var circle_32 = L.circle([28.793170, 76.139128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1787, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Bhiwani<br>rank: 32<br>hazard index: 0.001788")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwani">Bhiwani</a>')

var circle_33 = L.circle([25.795593, 82.488341], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1777, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Jaunpur<br>rank: 33<br>hazard index: 0.001778")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaunpur">Jaunpur</a>')

var circle_34 = L.circle([28.618753, 78.550874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1749, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Sambhal<br>rank: 34<br>hazard index: 0.001749")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambhal">Sambhal</a>')

var circle_35 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1618, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Bahadurgarh<br>rank: 35<br>hazard index: 0.001618")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_36 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1568, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Khora<br>rank: 36<br>hazard index: 0.001568")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_37 = L.circle([28.923397, 78.488317], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1562, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Amroha<br>rank: 37<br>hazard index: 0.001562")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amroha">Amroha</a>')

var circle_38 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1452, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Lucknow<br>rank: 38<br>hazard index: 0.001453")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_39 = L.circle([28.068312, 79.046073], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1402, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Budaun<br>rank: 39<br>hazard index: 0.001403")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Budaun">Budaun</a>')

var circle_40 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1368, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Jind<br>rank: 40<br>hazard index: 0.001369")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_41 = L.circle([29.993039, 76.829223], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1350, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Thanesar<br>rank: 41<br>hazard index: 0.001350")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Thanesar">Thanesar</a>')

var circle_42 = L.circle([28.079690, 75.541768], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1291, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Jhunjhunun<br>rank: 42<br>hazard index: 0.001292")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhunjhunun">Jhunjhunun</a>')

var circle_43 = L.circle([29.822821, 76.378310], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1269, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Kaithal<br>rank: 43<br>hazard index: 0.001270")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kaithal">Kaithal</a>')

var circle_44 = L.circle([30.211200, 77.286390], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1253, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Yamunanagar<br>rank: 44<br>hazard index: 0.001253")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Yamunanagar">Yamunanagar</a>')

var circle_45 = L.circle([28.195647, 76.616518], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1240, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Rewari<br>rank: 45<br>hazard index: 0.001240")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rewari">Rewari</a>')

var circle_46 = L.circle([29.211757, 78.961731], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1215, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Kashipur<br>rank: 46<br>hazard index: 0.001215")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kashipur">Kashipur</a>')

var circle_47 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1185, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Jhansi<br>rank: 47<br>hazard index: 0.001186")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_48 = L.circle([27.573243, 78.111739], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1180, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Hathras<br>rank: 48<br>hazard index: 0.001181")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hathras">Hathras</a>')

var circle_49 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1174, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Dehri<br>rank: 49<br>hazard index: 0.001174")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')

var circle_50 = L.circle([28.176959, 77.373112], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1151, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Palwal<br>rank: 50<br>hazard index: 0.001152")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palwal">Palwal</a>')

var circle_51 = L.circle([29.869350, 77.890212], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1138, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Roorkee<br>rank: 51<br>hazard index: 0.001139")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Roorkee">Roorkee</a>')

var circle_52 = L.circle([26.148658, 85.340013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1128, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Muzaffarpur<br>rank: 52<br>hazard index: 0.001129")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarpur">Muzaffarpur</a>')

var circle_53 = L.circle([28.826162, 77.541656], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1075, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Modinagar<br>rank: 53<br>hazard index: 0.001076")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Modinagar">Modinagar</a>')

var circle_54 = L.circle([28.488378, 78.735249], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1024, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Chandausi<br>rank: 54<br>hazard index: 0.001024")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandausi">Chandausi</a>')

var circle_55 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1020, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Patna<br>rank: 55<br>hazard index: 0.001020")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_56 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1003, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Ludhiana<br>rank: 56<br>hazard index: 0.001003")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_57 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1002, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Bangalore<br>rank: 57<br>hazard index: 0.001003")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_58 = L.circle([29.500882, 77.348383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 980, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Shamli<br>rank: 58<br>hazard index: 0.000981")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shamli">Shamli</a>')

var circle_59 = L.circle([28.205907, 77.875714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 948, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Khurja<br>rank: 59<br>hazard index: 0.000949")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khurja">Khurja</a>')

var circle_60 = L.circle([29.154148, 77.305954], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 919, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Baraut<br>rank: 60<br>hazard index: 0.000920")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baraut">Baraut</a>')

var circle_61 = L.circle([27.883846, 78.634890], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 896, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Kasganj<br>rank: 61<br>hazard index: 0.000896")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kasganj">Kasganj</a>')

var circle_62 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 846, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Kolkata<br>rank: 62<br>hazard index: 0.000846")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_63 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 720, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Ahmedabad<br>rank: 63<br>hazard index: 0.000720")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_64 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 701, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Hyderabad<br>rank: 64<br>hazard index: 0.000702")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_65 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 681, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Jaipur<br>rank: 65<br>hazard index: 0.000681")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_66 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 611, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Chennai<br>rank: 66<br>hazard index: 0.000611")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_67 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 596, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Pune<br>rank: 67<br>hazard index: 0.000597")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_68 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 591, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Chandigarh<br>rank: 68<br>hazard index: 0.000592")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_69 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 510, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Bareilly<br>rank: 69<br>hazard index: 0.000511")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_70 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 506, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Amritsar<br>rank: 70<br>hazard index: 0.000507")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_71 = L.circle([25.720581, 85.255560], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 479, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Hajipur<br>rank: 71<br>hazard index: 0.000480")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hajipur">Hajipur</a>')

var circle_72 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 463, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Gwalior<br>rank: 72<br>hazard index: 0.000464")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_73 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 449, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Jalandhar<br>rank: 73<br>hazard index: 0.000449")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_74 = L.circle([26.671329, 83.364583], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 357, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Gorakhpur<br>rank: 74<br>hazard index: 0.000358")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gorakhpur">Gorakhpur</a>')

var circle_75 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 355, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Vasco Da Gama<br>rank: 75<br>hazard index: 0.000356")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_76 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 349, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Guwahati<br>rank: 76<br>hazard index: 0.000350")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_77 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 345, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Dehradun<br>rank: 77<br>hazard index: 0.000345")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_78 = L.circle([25.954628, 83.647350], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 343, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Maunath Bhanjan<br>rank: 78<br>hazard index: 0.000344")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Maunath_Bhanjan">Maunath Bhanjan</a>')

var circle_79 = L.circle([26.083143, 86.032571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 316, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Darbhanga<br>rank: 79<br>hazard index: 0.000317")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Darbhanga">Darbhanga</a>')

var circle_80 = L.circle([34.074744, 74.820444], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 311, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Srinagar<br>rank: 80<br>hazard index: 0.000312")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srinagar">Srinagar</a>')

var circle_81 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 309, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Bhopal<br>rank: 81<br>hazard index: 0.000309")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_82 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 290, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Nagpur<br>rank: 82<br>hazard index: 0.000290")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_83 = L.circle([25.280733, 83.125128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 285, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Mughal Sarai<br>rank: 83<br>hazard index: 0.000285")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mughal_Sarai">Mughal Sarai</a>')

var circle_84 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 282, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Bhubaneswar<br>rank: 84<br>hazard index: 0.000283")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_85 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 275, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Jammu<br>rank: 85<br>hazard index: 0.000275")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_86 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 269, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Ambala<br>rank: 86<br>hazard index: 0.000269")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_87 = L.circle([24.796436, 85.007956], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 263, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Gaya<br>rank: 87<br>hazard index: 0.000263")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gaya">Gaya</a>')

var circle_88 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 257, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Ranchi<br>rank: 88<br>hazard index: 0.000257")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_89 = L.circle([27.504639, 80.829466], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 229, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Sitapur<br>rank: 89<br>hazard index: 0.000229")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sitapur">Sitapur</a>')

var circle_90 = L.circle([30.179115, 75.047102], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 227, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Bathinda<br>rank: 90<br>hazard index: 0.000228")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a>')

var circle_91 = L.circle([26.698885, 88.320030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 226, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Bagdogra<br>rank: 91<br>hazard index: 0.000227")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagdogra">Bagdogra</a>')

var circle_92 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 226, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Surat<br>rank: 92<br>hazard index: 0.000226")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_93 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 214, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Indore<br>rank: 93<br>hazard index: 0.000214")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_94 = L.circle([30.209087, 76.339872], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 205, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Patiala<br>rank: 94<br>hazard index: 0.000206")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a>')

var circle_95 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 185, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Kochi<br>rank: 95<br>hazard index: 0.000185")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_96 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 170, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Kota<br>rank: 96<br>hazard index: 0.000171")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_97 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 165, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Jodhpur<br>rank: 97<br>hazard index: 0.000165")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_98 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 161, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Raipur<br>rank: 98<br>hazard index: 0.000162")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_99 = L.circle([26.055318, 82.993139], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 160, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Nizamabad<br>rank: 99<br>hazard index: 0.000161")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nizamabad">Nizamabad</a>')

var circle_100 = L.circle([25.286698, 87.132254], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 154, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Bhagalpur<br>rank: 100<br>hazard index: 0.000155")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhagalpur">Bhagalpur</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a></td>
</tr>

<tr>
<td>2</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Ghazipur">Ghazipur</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Noida. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>