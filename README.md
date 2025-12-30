# Car crashes and weather - Pyds25
By Mathias Pisch and Anthony Gerbier
Project supervised by Aldric Labarthe, for the Lino Galiana course « Python for Data Science ». 

# Motivations

The objective of this study is to investigate the primary factors contributing to road accidents, with a particular focus on meteorological conditions.

Weather plays a crucial role in driver attention. Most drivers can recall days when heavy rainfall required heightened caution on the road. Similarly, media reports frequently highlight road conditions during snowfall in urban areas, such as Paris, where accident rates tend to increase.

Since changing weather conditions directly affect driving difficulty, it is natural to ask how they influence the occurrence of traffic accidents. Are certain weather conditions associated with a higher risk of accidents? To what extent do extreme weather events impact road safety?

These questions form the core of this study.

# Scientific Approach

To address these questions, we focus on a well-defined geographical area: Montgomery County, Maryland, chosen for its rich and detailed traffic accident dataset. Our aim is to identify the main factors contributing to road accidents, with a particular emphasis on weather. The study follows a structured experimental procedure.

First, the dataset undergoes thorough preprocessing to ensure completeness and consistency. This includes cleaning, handling missing values, and standardizing formats. Once prepared, the dataset is enriched with high-resolution meteorological data obtained via API calls. To respect API request limits and maintain efficiency, we perform this enrichment on a representative sample of Montgomery County accident records.

Next, we perform descriptive statistical analyses to explore the dataset, examine variable distributions, and identify potential patterns or correlations, particularly between weather variables and accident occurrences.

Finally, we proceed to a modeling stage aimed at quantifying the effect of weather on road accidents. Focusing on causal inference, we seek to determine whether specific weather conditions increase the likelihood of accidents, and to what extent. Regression-based methods are employed to estimate the marginal effect of each weather variable while controlling for other relevant factors. The ultimate goal is to provide a robust, data-driven understanding of how weather conditions influence road safety.
