# satellite_conjuction_risk

conjuction risk is predicted using relative distance between satellites.

Conjunctions in space occur when two or more Resident Space Objects
(RSOs) in the Earth's orbit pass dangerously close to one another, resulting in
possible collision scenarios. With the rapid increase in the number of RSOs in recent
times, the number of predicted conjunctions has significantly increased. The
interpretation and visualisation of around 250,000 conjunctions per day is a
challenging data analytics problem. A sample data set of predicted conjunctions of
active satellites in space can be downloaded from CelesTrak (a not-for-profit
organisation) using the following link:
http://celestrak.org/SOCRATES/socrates-format.php

relative distance = maximum of apogee - maximum of perigee
ConjunctionRisk = IF([RelativeDistance] < 50, "High Risk", "Low Risk") // 50 is an example to show conjuction risk.


if relative distance is less than 50 , then the satellite is at high risk.


power bi dashboard is used to visualize the conjuction risk for satellites.

