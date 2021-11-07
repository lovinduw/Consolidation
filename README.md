# Consolidation of European Power Data
European Network of Transmission System Operators for Electricity (ENTSO-E) publishes electricity generation,load, transmission and other data of 35 countries in their operating region.
These data have missing observations and mismatched in the data.
In this project, a model has been developed to fill the missing observations in the data using a polynomial linear regression model.
Gap filled data have been modified to incorporate energy ceonservation theory at all time steps using a Pyomo based linear optimization model.
