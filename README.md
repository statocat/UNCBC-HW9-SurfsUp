# Surf's Up Challaenge

## Overview of the Statistical Analysis

This analysis was conducted to support a business plan pitch for a "Surf and Shake Shop" on Oahu. A potential investor in the venture, W. Avy, wanted an analysis for the historical weather trends on the island to ensure there will not be too many chilly days for the business to thrive.

## Results

SQLAlchemy was used to gather all temperature measurements in the provided SQLite databse made in the months of July and December. The analysis revealed:

 * While on average June temperatures are slightly higher than those in December (μ<sub>J</sub> = 74.9, μ<sub>D</sub> = 71.0), the temperature on the island is moderate year-round. 

 * The standard deviation of temperature measurements in June is similar that in December (σ<sub>J</sub> = 3.25, σ<sub>D</sub> = 3.75), so a similar vairation in temperature is expected year-round

* The lowest temperature observed in December was 56°F, a full 9°F lower than the minimum temperature observed in June. So while most days in December are in the 70s, some occasional chilly days can be expected.

* A histogram plot of the data shows that even in December, most days on the island are in the mid-60s and above, even reaching 80 °F!

![Temp_Hist](/Users/catherinesmith/Desktop/unc_bootcamp/module_9/UNCBC-HW9-SurfsUp/histogram.png)


## Summary

In summary, this data shows that seasonal temperatures in Oahu are moderate year-round, making the island's waters a great place to surf year-round. It would be insteresting to also look at measurements of ocean temperature to determine if the water is too cold to surf without a wetsuit in winter. It would also be interesting to look at temperature measurements collected in March and September to get a sense of spring and fall weather on the island. Some winter days might be a bit too chilly for ice cream, but the Surf and Shake shop could still entice customers by adding hot chocolate to the menu!