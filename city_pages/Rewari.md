---
layout: page
title: "Outbreak location: Rewari"
---
<div class="flex-container">
<div class="flex-item-left" id="mapid">
<script src="https://buda-magenta.github.io/hazard_map/load_map.js"></script>

<script>
var marker_outbreak = L.marker([28.195647, 76.616518],{"autoPan": true}).addTo(map); marker_outbreak.bindTooltip("Rewari").openTooltip();

var circle_1 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 96219, "stroke": true, "weight": 3}).addTo(map);
circle_1.bindTooltip("Delhi<br>rank: 1<br>hazard index: 0.096219")
circle_1.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Delhi">Delhi</a>')

var circle_2 = L.circle([29.168807, 75.746110], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 53177, "stroke": true, "weight": 3}).addTo(map);
circle_2.bindTooltip("Hisar<br>rank: 2<br>hazard index: 0.053178")
circle_2.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a>')

var circle_3 = L.circle([28.793170, 76.139128], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44925, "stroke": true, "weight": 3}).addTo(map);
circle_3.bindTooltip("Bhiwani<br>rank: 3<br>hazard index: 0.044926")
circle_3.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhiwani">Bhiwani</a>')

var circle_4 = L.circle([27.662826, 75.027926], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 25357, "stroke": true, "weight": 3}).addTo(map);
circle_4.bindTooltip("Sikar<br>rank: 4<br>hazard index: 0.025358")
circle_4.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sikar">Sikar</a>')

var circle_5 = L.circle([28.901090, 76.580193], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18747, "stroke": true, "weight": 3}).addTo(map);
circle_5.bindTooltip("Rohtak<br>rank: 5<br>hazard index: 0.018748")
circle_5.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a>')

var circle_6 = L.circle([26.296772, 73.035143], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17477, "stroke": true, "weight": 3}).addTo(map);
circle_6.bindTooltip("Jodhpur<br>rank: 6<br>hazard index: 0.017477")
circle_6.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a>')

var circle_7 = L.circle([28.015929, 73.317137], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16949, "stroke": true, "weight": 3}).addTo(map);
circle_7.bindTooltip("Bikaner<br>rank: 7<br>hazard index: 0.016950")
circle_7.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a>')

var circle_8 = L.circle([30.179115, 75.047102], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14783, "stroke": true, "weight": 3}).addTo(map);
circle_8.bindTooltip("Bathinda<br>rank: 8<br>hazard index: 0.014784")
circle_8.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a>')

var circle_9 = L.circle([28.079690, 75.541768], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12724, "stroke": true, "weight": 3}).addTo(map);
circle_9.bindTooltip("Jhunjhunun<br>rank: 9<br>hazard index: 0.012724")
circle_9.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhunjhunun">Jhunjhunun</a>')

var circle_10 = L.circle([29.583333, 75.083333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9480, "stroke": true, "weight": 3}).addTo(map);
circle_10.bindTooltip("Sirsa<br>rank: 10<br>hazard index: 0.009480")
circle_10.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sirsa">Sirsa</a>')

var circle_11 = L.circle([29.367200, 74.298364], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8806, "stroke": true, "weight": 3}).addTo(map);
circle_11.bindTooltip("Hanumangarh<br>rank: 11<br>hazard index: 0.008807")
circle_11.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hanumangarh">Hanumangarh</a>')

var circle_12 = L.circle([26.915458, 75.818982], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7328, "stroke": true, "weight": 3}).addTo(map);
circle_12.bindTooltip("Jaipur<br>rank: 12<br>hazard index: 0.007328")
circle_12.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jaipur">Jaipur</a>')

var circle_13 = L.circle([28.428262, 77.002700], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6967, "stroke": true, "weight": 3}).addTo(map);
circle_13.bindTooltip("Gurgaon<br>rank: 13<br>hazard index: 0.006967")
circle_13.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gurgaon">Gurgaon</a>')

var circle_14 = L.circle([28.206144, 74.691907], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5627, "stroke": true, "weight": 3}).addTo(map);
circle_14.bindTooltip("Churu<br>rank: 14<br>hazard index: 0.005628")
circle_14.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Churu">Churu</a>')

var circle_15 = L.circle([29.000653, 77.768229], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2809, "stroke": true, "weight": 3}).addTo(map);
circle_15.bindTooltip("Meerut<br>rank: 15<br>hazard index: 0.002810")
circle_15.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Meerut">Meerut</a>')

var circle_16 = L.circle([30.145054, 74.195660], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2362, "stroke": true, "weight": 3}).addTo(map);
circle_16.bindTooltip("Abohar<br>rank: 16<br>hazard index: 0.002363")
circle_16.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Abohar">Abohar</a>')

var circle_17 = L.circle([27.639077, 76.614452], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2244, "stroke": true, "weight": 3}).addTo(map);
circle_17.bindTooltip("Alwar<br>rank: 17<br>hazard index: 0.002245")
circle_17.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Alwar">Alwar</a>')

var circle_18 = L.circle([23.493079, 74.348402], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2089, "stroke": true, "weight": 3}).addTo(map);
circle_18.bindTooltip("Banswara<br>rank: 18<br>hazard index: 0.002090")
circle_18.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Banswara">Banswara</a>')

var circle_19 = L.circle([27.633333, 77.583333], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1997, "stroke": true, "weight": 3}).addTo(map);
circle_19.bindTooltip("Mathura<br>rank: 19<br>hazard index: 0.001998")
circle_19.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mathura">Mathura</a>')

var circle_20 = L.circle([30.283140, 74.522997], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1954, "stroke": true, "weight": 3}).addTo(map);
circle_20.bindTooltip("Muktsar<br>rank: 20<br>hazard index: 0.001954")
circle_20.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muktsar">Muktsar</a>')

var circle_21 = L.circle([26.469100, 74.639000], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1877, "stroke": true, "weight": 3}).addTo(map);
circle_21.bindTooltip("Ajmer<br>rank: 21<br>hazard index: 0.001877")
circle_21.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ajmer">Ajmer</a>')

var circle_22 = L.circle([29.301826, 76.338471], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1868, "stroke": true, "weight": 3}).addTo(map);
circle_22.bindTooltip("Jind<br>rank: 22<br>hazard index: 0.001868")
circle_22.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jind">Jind</a>')

var circle_23 = L.circle([26.460914, 80.321759], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1833, "stroke": true, "weight": 3}).addTo(map);
circle_23.bindTooltip("Kanpur<br>rank: 23<br>hazard index: 0.001833")
circle_23.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kanpur">Kanpur</a>')

var circle_24 = L.circle([30.909016, 75.851601], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1765, "stroke": true, "weight": 3}).addTo(map);
circle_24.bindTooltip("Ludhiana<br>rank: 24<br>hazard index: 0.001766")
circle_24.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ludhiana">Ludhiana</a>')

var circle_25 = L.circle([27.701115, 74.464936], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1686, "stroke": true, "weight": 3}).addTo(map);
circle_25.bindTooltip("Sujangarh<br>rank: 25<br>hazard index: 0.001686")
circle_25.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sujangarh">Sujangarh</a>')

var circle_26 = L.circle([19.075990, 72.877393], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1651, "stroke": true, "weight": 3}).addTo(map);
circle_26.bindTooltip("Mumbai<br>rank: 26<br>hazard index: 0.001652")
circle_26.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Mumbai">Mumbai</a>')

var circle_27 = L.circle([27.175255, 78.009816], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1405, "stroke": true, "weight": 3}).addTo(map);
circle_27.bindTooltip("Agra<br>rank: 27<br>hazard index: 0.001406")
circle_27.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Agra">Agra</a>')

var circle_28 = L.circle([26.838100, 80.934600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1259, "stroke": true, "weight": 3}).addTo(map);
circle_28.bindTooltip("Lucknow<br>rank: 28<br>hazard index: 0.001259")
circle_28.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Lucknow">Lucknow</a>')

var circle_29 = L.circle([28.402979, 77.310384], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1254, "stroke": true, "weight": 3}).addTo(map);
circle_29.bindTooltip("Faridabad<br>rank: 29<br>hazard index: 0.001254")
circle_29.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Faridabad">Faridabad</a>')

var circle_30 = L.circle([25.531031, 78.652689], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1028, "stroke": true, "weight": 3}).addTo(map);
circle_30.bindTooltip("Jhansi<br>rank: 30<br>hazard index: 0.001028")
circle_30.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jhansi">Jhansi</a>')

var circle_31 = L.circle([12.979120, 77.591300], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 869, "stroke": true, "weight": 3}).addTo(map);
circle_31.bindTooltip("Bangalore<br>rank: 31<br>hazard index: 0.000869")
circle_31.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bangalore">Bangalore</a>')

var circle_32 = L.circle([28.863842, 78.805778], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 867, "stroke": true, "weight": 3}).addTo(map);
circle_32.bindTooltip("Moradabad<br>rank: 32<br>hazard index: 0.000868")
circle_32.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Moradabad">Moradabad</a>')

var circle_33 = L.circle([29.391275, 76.977167], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 850, "stroke": true, "weight": 3}).addTo(map);
circle_33.bindTooltip("Panipat<br>rank: 33<br>hazard index: 0.000850")
circle_33.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Panipat">Panipat</a>')

var circle_34 = L.circle([30.733442, 76.779714], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 782, "stroke": true, "weight": 3}).addTo(map);
circle_34.bindTooltip("Chandigarh<br>rank: 34<br>hazard index: 0.000782")
circle_34.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chandigarh">Chandigarh</a>')

var circle_35 = L.circle([27.876990, 78.137290], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 779, "stroke": true, "weight": 3}).addTo(map);
circle_35.bindTooltip("Aligarh<br>rank: 35<br>hazard index: 0.000779")
circle_35.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Aligarh">Aligarh</a>')

var circle_36 = L.circle([30.885100, 74.660141], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 749, "stroke": true, "weight": 3}).addTo(map);
circle_36.bindTooltip("Firozpur<br>rank: 36<br>hazard index: 0.000749")
circle_36.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozpur">Firozpur</a>')

var circle_37 = L.circle([22.541418, 88.357691], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 733, "stroke": true, "weight": 3}).addTo(map);
circle_37.bindTooltip("Kolkata<br>rank: 37<br>hazard index: 0.000734")
circle_37.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kolkata">Kolkata</a>')

var circle_38 = L.circle([29.988077, 77.508130], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 647, "stroke": true, "weight": 3}).addTo(map);
circle_38.bindTooltip("Saharanpur<br>rank: 38<br>hazard index: 0.000647")
circle_38.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Saharanpur">Saharanpur</a>')

var circle_39 = L.circle([27.060786, 74.176675], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 631, "stroke": true, "weight": 3}).addTo(map);
circle_39.bindTooltip("Nagaur<br>rank: 39<br>hazard index: 0.000632")
circle_39.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagaur">Nagaur</a>')

var circle_40 = L.circle([25.609324, 85.123525], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 624, "stroke": true, "weight": 3}).addTo(map);
circle_40.bindTooltip("Patna<br>rank: 40<br>hazard index: 0.000624")
circle_40.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patna">Patna</a>')

var circle_41 = L.circle([23.021624, 72.579707], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 624, "stroke": true, "weight": 3}).addTo(map);
circle_41.bindTooltip("Ahmedabad<br>rank: 41<br>hazard index: 0.000624")
circle_41.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ahmedabad">Ahmedabad</a>')

var circle_42 = L.circle([17.388786, 78.461065], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 608, "stroke": true, "weight": 3}).addTo(map);
circle_42.bindTooltip("Hyderabad<br>rank: 42<br>hazard index: 0.000608")
circle_42.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hyderabad">Hyderabad</a>')

var circle_43 = L.circle([28.570784, 77.327107], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 573, "stroke": true, "weight": 3}).addTo(map);
circle_43.bindTooltip("Noida<br>rank: 43<br>hazard index: 0.000574")
circle_43.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Noida">Noida</a>')

var circle_44 = L.circle([29.003314, 77.016732], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 552, "stroke": true, "weight": 3}).addTo(map);
circle_44.bindTooltip("Sonipat<br>rank: 44<br>hazard index: 0.000553")
circle_44.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sonipat">Sonipat</a>')

var circle_45 = L.circle([28.733400, 77.298600], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 549, "stroke": true, "weight": 3}).addTo(map);
circle_45.bindTooltip("Loni<br>rank: 45<br>hazard index: 0.000549")
circle_45.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Loni">Loni</a>')

var circle_46 = L.circle([13.083694, 80.270186], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 530, "stroke": true, "weight": 3}).addTo(map);
circle_46.bindTooltip("Chennai<br>rank: 46<br>hazard index: 0.000530")
circle_46.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Chennai">Chennai</a>')

var circle_47 = L.circle([18.521428, 73.854454], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 517, "stroke": true, "weight": 3}).addTo(map);
circle_47.bindTooltip("Pune<br>rank: 47<br>hazard index: 0.000517")
circle_47.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pune">Pune</a>')

var circle_48 = L.circle([26.588559, 74.861097], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 512, "stroke": true, "weight": 3}).addTo(map);
circle_48.bindTooltip("Kishangarh<br>rank: 48<br>hazard index: 0.000513")
circle_48.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kishangarh">Kishangarh</a>')

var circle_49 = L.circle([30.370469, 75.504017], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 495, "stroke": true, "weight": 3}).addTo(map);
circle_49.bindTooltip("Barnala<br>rank: 49<br>hazard index: 0.000496")
circle_49.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Barnala">Barnala</a>')

var circle_50 = L.circle([25.438130, 81.833800], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 444, "stroke": true, "weight": 3}).addTo(map);
circle_50.bindTooltip("Allahabad<br>rank: 50<br>hazard index: 0.000444")
circle_50.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Allahabad">Allahabad</a>')

var circle_51 = L.circle([31.634308, 74.873679], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 439, "stroke": true, "weight": 3}).addTo(map);
circle_51.bindTooltip("Amritsar<br>rank: 51<br>hazard index: 0.000439")
circle_51.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amritsar">Amritsar</a>')

var circle_52 = L.circle([28.660965, 76.834676], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 436, "stroke": true, "weight": 3}).addTo(map);
circle_52.bindTooltip("Bahadurgarh<br>rank: 52<br>hazard index: 0.000436")
circle_52.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bahadurgarh">Bahadurgarh</a>')

var circle_53 = L.circle([28.753900, 77.399900], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 410, "stroke": true, "weight": 3}).addTo(map);
circle_53.bindTooltip("Khora<br>rank: 53<br>hazard index: 0.000411")
circle_53.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Khora">Khora</a>')

var circle_54 = L.circle([31.292011, 75.568058], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 389, "stroke": true, "weight": 3}).addTo(map);
circle_54.bindTooltip("Jalandhar<br>rank: 54<br>hazard index: 0.000390")
circle_54.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jalandhar">Jalandhar</a>')

var circle_55 = L.circle([29.448006, 77.740685], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 355, "stroke": true, "weight": 3}).addTo(map);
circle_55.bindTooltip("Muzaffarnagar<br>rank: 55<br>hazard index: 0.000355")
circle_55.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Muzaffarnagar">Muzaffarnagar</a>')

var circle_56 = L.circle([30.209087, 76.339872], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 341, "stroke": true, "weight": 3}).addTo(map);
circle_56.bindTooltip("Patiala<br>rank: 56<br>hazard index: 0.000342")
circle_56.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Patiala">Patiala</a>')

var circle_57 = L.circle([25.335649, 83.007629], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 321, "stroke": true, "weight": 3}).addTo(map);
circle_57.bindTooltip("Varanasi<br>rank: 57<br>hazard index: 0.000322")
circle_57.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Varanasi">Varanasi</a>')

var circle_58 = L.circle([24.578721, 73.686257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 313, "stroke": true, "weight": 3}).addTo(map);
circle_58.bindTooltip("Udaipur<br>rank: 58<br>hazard index: 0.000313")
circle_58.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Udaipur">Udaipur</a>')

var circle_59 = L.circle([28.457876, 79.405571], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 310, "stroke": true, "weight": 3}).addTo(map);
circle_59.bindTooltip("Bareilly<br>rank: 59<br>hazard index: 0.000311")
circle_59.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bareilly">Bareilly</a>')

var circle_60 = L.circle([15.398403, 73.812918], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 308, "stroke": true, "weight": 3}).addTo(map);
circle_60.bindTooltip("Vasco Da Gama<br>rank: 60<br>hazard index: 0.000309")
circle_60.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vasco_Da_Gama">Vasco Da Gama</a>')

var circle_61 = L.circle([26.180598, 91.753943], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 303, "stroke": true, "weight": 3}).addTo(map);
circle_61.bindTooltip("Guwahati<br>rank: 61<br>hazard index: 0.000303")
circle_61.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Guwahati">Guwahati</a>')

var circle_62 = L.circle([25.196826, 76.000893], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 300, "stroke": true, "weight": 3}).addTo(map);
circle_62.bindTooltip("Kota<br>rank: 62<br>hazard index: 0.000300")
circle_62.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kota">Kota</a>')

var circle_63 = L.circle([29.680327, 76.989625], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 299, "stroke": true, "weight": 3}).addTo(map);
circle_63.bindTooltip("Karnal<br>rank: 63<br>hazard index: 0.000299")
circle_63.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Karnal">Karnal</a>')

var circle_64 = L.circle([28.740613, 77.835426], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 282, "stroke": true, "weight": 3}).addTo(map);
circle_64.bindTooltip("Hapur<br>rank: 64<br>hazard index: 0.000283")
circle_64.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hapur">Hapur</a>')

var circle_65 = L.circle([28.826162, 77.541656], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 273, "stroke": true, "weight": 3}).addTo(map);
circle_65.bindTooltip("Modinagar<br>rank: 65<br>hazard index: 0.000274")
circle_65.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Modinagar">Modinagar</a>')

var circle_66 = L.circle([34.074744, 74.820444], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 270, "stroke": true, "weight": 3}).addTo(map);
circle_66.bindTooltip("Srinagar<br>rank: 66<br>hazard index: 0.000270")
circle_66.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Srinagar">Srinagar</a>')

var circle_67 = L.circle([23.258486, 77.401989], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 268, "stroke": true, "weight": 3}).addTo(map);
circle_67.bindTooltip("Bhopal<br>rank: 67<br>hazard index: 0.000268")
circle_67.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhopal">Bhopal</a>')

var circle_68 = L.circle([28.794068, 79.185930], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 254, "stroke": true, "weight": 3}).addTo(map);
circle_68.bindTooltip("Rampur<br>rank: 68<br>hazard index: 0.000255")
circle_68.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Rampur">Rampur</a>')

var circle_69 = L.circle([25.488773, 74.699613], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 252, "stroke": true, "weight": 3}).addTo(map);
circle_69.bindTooltip("Bhilwara<br>rank: 69<br>hazard index: 0.000252")
circle_69.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhilwara">Bhilwara</a>')

var circle_70 = L.circle([21.149813, 79.082056], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 251, "stroke": true, "weight": 3}).addTo(map);
circle_70.bindTooltip("Nagpur<br>rank: 70<br>hazard index: 0.000252")
circle_70.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Nagpur">Nagpur</a>')

var circle_71 = L.circle([27.177366, 78.389912], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 249, "stroke": true, "weight": 3}).addTo(map);
circle_71.bindTooltip("Firozabad<br>rank: 71<br>hazard index: 0.000249")
circle_71.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Firozabad">Firozabad</a>')

var circle_72 = L.circle([20.266777, 85.843559], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 245, "stroke": true, "weight": 3}).addTo(map);
circle_72.bindTooltip("Bhubaneswar<br>rank: 72<br>hazard index: 0.000245")
circle_72.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bhubaneswar">Bhubaneswar</a>')

var circle_73 = L.circle([30.325565, 78.043681], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 242, "stroke": true, "weight": 3}).addTo(map);
circle_73.bindTooltip("Dehradun<br>rank: 73<br>hazard index: 0.000243")
circle_73.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehradun">Dehradun</a>')

var circle_74 = L.circle([32.718561, 74.858092], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 238, "stroke": true, "weight": 3}).addTo(map);
circle_74.bindTooltip("Jammu<br>rank: 74<br>hazard index: 0.000239")
circle_74.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Jammu">Jammu</a>')

var circle_75 = L.circle([29.822821, 76.378310], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 226, "stroke": true, "weight": 3}).addTo(map);
circle_75.bindTooltip("Kaithal<br>rank: 75<br>hazard index: 0.000226")
circle_75.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kaithal">Kaithal</a>')

var circle_76 = L.circle([27.265212, 77.369126], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 225, "stroke": true, "weight": 3}).addTo(map);
circle_76.bindTooltip("Bharatpur<br>rank: 76<br>hazard index: 0.000225")
circle_76.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bharatpur">Bharatpur</a>')

var circle_77 = L.circle([23.370035, 85.325013], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 222, "stroke": true, "weight": 3}).addTo(map);
circle_77.bindTooltip("Ranchi<br>rank: 77<br>hazard index: 0.000223")
circle_77.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ranchi">Ranchi</a>')

var circle_78 = L.circle([29.938447, 78.145298], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 206, "stroke": true, "weight": 3}).addTo(map);
circle_78.bindTooltip("Haridwar<br>rank: 78<br>hazard index: 0.000206")
circle_78.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Haridwar">Haridwar</a>')

var circle_79 = L.circle([26.732501, 77.036312], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 205, "stroke": true, "weight": 3}).addTo(map);
circle_79.bindTooltip("Hindaun<br>rank: 79<br>hazard index: 0.000206")
circle_79.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hindaun">Hindaun</a>')

var circle_80 = L.circle([28.388861, 77.974798], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 198, "stroke": true, "weight": 3}).addTo(map);
circle_80.bindTooltip("Bulandshahr<br>rank: 80<br>hazard index: 0.000199")
circle_80.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bulandshahr">Bulandshahr</a>')

var circle_81 = L.circle([28.618753, 78.550874], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 197, "stroke": true, "weight": 3}).addTo(map);
circle_81.bindTooltip("Sambhal<br>rank: 81<br>hazard index: 0.000198")
circle_81.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Sambhal">Sambhal</a>')

var circle_82 = L.circle([26.698885, 88.320030], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 196, "stroke": true, "weight": 3}).addTo(map);
circle_82.bindTooltip("Bagdogra<br>rank: 82<br>hazard index: 0.000197")
circle_82.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Bagdogra">Bagdogra</a>')

var circle_83 = L.circle([23.749721, 91.876635], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 196, "stroke": true, "weight": 3}).addTo(map);
circle_83.bindTooltip("Ganganagar<br>rank: 83<br>hazard index: 0.000196")
circle_83.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ganganagar">Ganganagar</a>')

var circle_84 = L.circle([22.720362, 75.868200], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 185, "stroke": true, "weight": 3}).addTo(map);
circle_84.bindTooltip("Indore<br>rank: 84<br>hazard index: 0.000186")
circle_84.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Indore">Indore</a>')

var circle_85 = L.circle([21.170200, 72.831100], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 185, "stroke": true, "weight": 3}).addTo(map);
circle_85.bindTooltip("Surat<br>rank: 85<br>hazard index: 0.000186")
circle_85.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Surat">Surat</a>')

var circle_86 = L.circle([25.604091, 73.415609], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 184, "stroke": true, "weight": 3}).addTo(map);
circle_86.bindTooltip("Pali<br>rank: 86<br>hazard index: 0.000184")
circle_86.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Pali">Pali</a>')

var circle_87 = L.circle([26.653396, 77.624206], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 182, "stroke": true, "weight": 3}).addTo(map);
circle_87.bindTooltip("Dhaulpur<br>rank: 87<br>hazard index: 0.000182")
circle_87.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dhaulpur">Dhaulpur</a>')

var circle_88 = L.circle([30.533129, 75.880760], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 172, "stroke": true, "weight": 3}).addTo(map);
circle_88.bindTooltip("Malerkotla<br>rank: 88<br>hazard index: 0.000172")
circle_88.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Malerkotla">Malerkotla</a>')

var circle_89 = L.circle([26.203725, 78.157363], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 165, "stroke": true, "weight": 3}).addTo(map);
circle_89.bindTooltip("Gwalior<br>rank: 89<br>hazard index: 0.000165")
circle_89.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gwalior">Gwalior</a>')

var circle_90 = L.circle([9.931308, 76.267414], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 160, "stroke": true, "weight": 3}).addTo(map);
circle_90.bindTooltip("Kochi<br>rank: 90<br>hazard index: 0.000161")
circle_90.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Kochi">Kochi</a>')

var circle_91 = L.circle([30.384367, 76.770421], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 158, "stroke": true, "weight": 3}).addTo(map);
circle_91.bindTooltip("Ambala<br>rank: 91<br>hazard index: 0.000159")
circle_91.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Ambala">Ambala</a>')

var circle_92 = L.circle([28.923397, 78.488317], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 145, "stroke": true, "weight": 3}).addTo(map);
circle_92.bindTooltip("Amroha<br>rank: 92<br>hazard index: 0.000146")
circle_92.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Amroha">Amroha</a>')

var circle_93 = L.circle([24.170979, 72.436638], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 141, "stroke": true, "weight": 3}).addTo(map);
circle_93.bindTooltip("Palanpur<br>rank: 93<br>hazard index: 0.000142")
circle_93.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Palanpur">Palanpur</a>')

var circle_94 = L.circle([21.237947, 81.633683], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 140, "stroke": true, "weight": 3}).addTo(map);
circle_94.bindTooltip("Raipur<br>rank: 94<br>hazard index: 0.000140")
circle_94.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Raipur">Raipur</a>')

var circle_95 = L.circle([23.071874, 70.131715], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 135, "stroke": true, "weight": 3}).addTo(map);
circle_95.bindTooltip("Gandhidham<br>rank: 95<br>hazard index: 0.000136")
circle_95.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Gandhidham">Gandhidham</a>')

var circle_96 = L.circle([29.500882, 77.348383], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 130, "stroke": true, "weight": 3}).addTo(map);
circle_96.bindTooltip("Shamli<br>rank: 96<br>hazard index: 0.000130")
circle_96.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Shamli">Shamli</a>')

var circle_97 = L.circle([22.297314, 73.194257], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 128, "stroke": true, "weight": 3}).addTo(map);
circle_97.bindTooltip("Vadodara<br>rank: 97<br>hazard index: 0.000128")
circle_97.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Vadodara">Vadodara</a>')

var circle_98 = L.circle([29.154148, 77.305954], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 123, "stroke": true, "weight": 3}).addTo(map);
circle_98.bindTooltip("Baraut<br>rank: 98<br>hazard index: 0.000124")
circle_98.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Baraut">Baraut</a>')

var circle_99 = L.circle([27.573243, 78.111739], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 121, "stroke": true, "weight": 3}).addTo(map);
circle_99.bindTooltip("Hathras<br>rank: 99<br>hazard index: 0.000122")
circle_99.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Hathras">Hathras</a>')

var circle_100 = L.circle([28.651718, 77.221939], {"pane": "markerPane", "color": "red", "fill": true, "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 120, "stroke": true, "weight": 3}).addTo(map);
circle_100.bindTooltip("Dehri<br>rank: 100<br>hazard index: 0.000121")
circle_100.bindPopup('<a href="https://buda-magenta.github.io/hazard_map/Dehri">Dehri</a>')
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
<td><a href="https://buda-magenta.github.io/hazard_map/Hisar">Hisar</a></td>
</tr>

<tr>
<td>3</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bhiwani">Bhiwani</a></td>
</tr>

<tr>
<td>4</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Sikar">Sikar</a></td>
</tr>

<tr>
<td>5</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Rohtak">Rohtak</a></td>
</tr>

<tr>
<td>6</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jodhpur">Jodhpur</a></td>
</tr>

<tr>
<td>7</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bikaner">Bikaner</a></td>
</tr>

<tr>
<td>8</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Bathinda">Bathinda</a></td>
</tr>

<tr>
<td>9</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Jhunjhunun">Jhunjhunun</a></td>
</tr>

<tr>
<td>10</td>
<td><a href="https://buda-magenta.github.io/hazard_map/Sirsa">Sirsa</a></td>
</tr>

</table>
</div>
</div>


<p align="left">This hazard map shows top-100 cities that are at most risk if an infectious disease breaks out at Rewari. The size of red circle indicates the relative magnitude of risk. Bigger the circle, more the risk. The table on the side highlights the list of top-10 cities that are at most risk. Smaller the rank, more the risk. Thus, rank 3 is more at risk compared to rank 4, and so on.You can also click on any city to make that city an outbreak location. You will get a new hazard map with the chosen city/town as outbreak location.
</p>