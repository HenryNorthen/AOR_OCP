# Analyzing the Ammonia Oxidation Reaction using the Open Catalyst Project

Ammonia (NH₃) is an appealing alternative to hydrogen for fuel cells and energy production. Hydrogen storage requires compression to extremely high pressures or cooling to very low temperatures, whereas ammonia remains liquid at room temperature under just 9 bar of pressure, making it easier and more affordable to store. Additionally, ammonia is already the second-most-produced chemical globally due to its widespread use in fertilizers, meaning production, transportation, and storage infrastructures are already well-developed.

Hydrogen fuel cell vehicles have appeared commercially but have largely failed, primarily because of the challenging infrastructure requirements. Hydrogen refueling stations cost millions to build due to intense storage conditions, resulting in limited availability. Consumers are reluctant to purchase vehicles they must drive considerable distances to refuel, leading manufacturers to abandon hydrogen vehicle development.

Without these infrastructure barriers, hydrogen vehicles could have been far more successful. Ammonia offers higher energy density compared to hydrogen, along with significantly simpler storage and transportation. These characteristics position ammonia as an excellent candidate for fuel cell applications, where it can be oxidized cleanly into nitrogen gas and water without carbon emissions or harmful byproducts.

However, the Ammonia Oxidation Reaction (AOR) currently suffers from slow reaction kinetics with existing catalysts, which typically rely on expensive precious metals. Additionally, these catalysts are susceptible to poisoning by nitrogen-containing intermediates, reducing their efficiency. Resolving these catalytic challenges is essential before ammonia fuel cells can be successfully commercialized.

For over a year we have been running and interpreting adsorption energy calculations using the Open Catalyst Project (OCP), a project by Facebook AI Research that uses machine learning models to estimate Density Functional Theory (DFT) calculations. In doing this it shortens calculations times from days to minutes, while maintaing relatively high levels of accuracy. This allows for a new method of electrocatalyst discovery: high-throughput computations first, followed by experimental verification. 

We have screened through the over 11,000 materials supported by OCP, running calculations between them and the various adsorbates involved in the AOR. By doing this we’ve obtained a macroscopic view of the reaction thermodynamics, and have created a library of the adsorption energies of the 170 most promising materials with 15 different adsorbates. From this we have narrowed the list to a few select materials that have theoretically similar performance to Pt-group netals while being much more abundant in nature. Furthermore, we've identified major trends in structure between appealing catalysts and found ways to possibly predict reaction pathways and product selectivity from adsorption energies.

We hope to begin doing experimental work based on the findings of the calculations in the near future. 

