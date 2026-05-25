---
layout: page
title: Hazard Map Project
---

Welcome to the Hazard Map project carried out at the Indian Institute of Science Education and Research (IISER), Pune.<br>

This project attempts to design a simple strategy to use mobility data to assign a risk score to cities given a knowledge of an outbreak in another city/town. This project was funded by a special MATRICS grant of the Science and Engineering Research Board (SERB), Government of India.


**What is a hazard map?**<br>
A map of these risk scores is a hazard map. Suppose an infectious disease outbreak is reported in some city/town, which other cities/towns are in the risk of getting the infection ? This project has produced a map of the risk faced by 446 cities and towns in India with a population of 1 lakh or more. This project is not meant to predict the number of infection cases, case loads or severity of infection.

**What is a hazard rank?**<br>
The Hazard rank (shown in the hazard map) indicates the risk faced by the cities/towns due to spreading infection. Given an outbreak location, a hazard rank is assigned to each one of the cities/towns with respect to that outbreak location.<br>
A city/town with a lower rank has the higher risk, compared to a city/town with a higher rank. For example, with respect to some outbreak location, if Bangalore is assigned rank 5, and Hyderabad is given rank 8. Then, Bangalore is at a higher risk of getting the infection than Hyderabad. This means that Bangalore is more likely to get the infection first before Hyderabad gets it.

**Is the hazard map useful for anything?**<br>
Firstly, once the severity of infection is known, hazard map can be used to estimate the following : how many will it take for an infection to travel from its outbreak location to other cities/towns ? This can serve as an early warning tool. This can be used to selectively stop transport in some sectors (instead of all over India) so that the speed of infection spreading can be slowed down.

**Is the hazard map accurate?**<br>
Even with an enormous amount of real data and computing resources, making reliable predictions about infection spreading is difficult. The spread is a random process and there can be pronounced deviations from the model's predictions. Yet, within the constraints of model approximations and sparse data, the empirical models show some robust patterns on which reliable prediction of any attribute can be made. For instance, the relative ranking of cities in the hazard map is reasonably accurate. Improving accuracy is a continuous process, and we are at it.

**What is the science behind this hazard map ?**<br>
The basic idea behind the algorithm is fairly simple : mobility of the people is responsible for the spread of infection. Then, if mobility patterns of people are known, the geographical spread of infection can be mapped out.<br>
A hazard rank is assigned using a combination of mathematical models and use of transportation and mobility data. A compartmental infectious disease spreading model, the SIR model, augmented with India's long distance transportation network and real mobility data is employed for this purpose. Data from three major modes of transport - trains, air, and roads - are used in this work. However, the local mobility within a city or district is not taken into account. For a pictorial view of the algorithm, see [how it works](https://mansi-budamagunta.github.io/hazard_map/how-it-works).

**How do I find out more details ?**<br>
For a technical description of the hazard map project and work, please read our paper at arXiv link. As of May 2021, this paper has been submitted for publication, but is not published yet.
