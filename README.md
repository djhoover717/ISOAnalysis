ISOAnalysis is a pipeline designed to generate a simulated population of interstellar objects and perform orbit integrations on them as they pass through 
the inner solar system.

generate_skymap.ipynb generates the galactic kinematic distribution and draws initial velocities from that distribution.
integrate.ipynb uses those initial velocities and integrates (using REBOUND) all simulated objects for a given period, outputting the properties of only the 
objects that reach an apparent magnitude below 24.
isoanalysis_v4 illustrates the distributions of various properties in our detectable sample.
