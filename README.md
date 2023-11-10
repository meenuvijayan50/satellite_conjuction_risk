# satellite_conjuction_risk

conjuction risk is predicted using relative distance between satellites.

relative distance = maximum of apogee - maximum of perigee
ConjunctionRisk = IF([RelativeDistance] < 50, "High Risk", "Low Risk") // 50 is an example to show conjuction risk.
if relative distance is less than 50 , then the satellite is at high risk.
power bi dashboard is used to visualize the conjuction risk for satellites.

