# Water_Quality_Analysis
The data set contains 900 observations of a river with five sections. It comes from the file
waterquality.csv provided by TU Dortmund University for the application task of the sum-
mer semester 2027. Each row records the concentrations of nitrate and oxygen (in mg/L) mea-
sured in one of five sections of the river, ranging from the headwaters (A1) to the mouth (A5),
during one of four seasons. The four seasons are spring, summer, autumn and winter.

The variables in the data set are ID, river_section (ordinal scale), saison (nominal scale),
oxygen_mgL (ratio scale) and nitrate_mgL (ratio scale). Since ID is an identifier with no
analytical meaning, it has no scale level. The file uses the German name “saison” for the
season. There are no missing values, and the design is balanced with 45 measurements per
combination of section and season (5 × 4 × 45 = 900). The task does not describe how the
measurements were collected.

We investigate two questions:
1. Do the mean nitrate concentration and the mean oxygen concentration differ between
spring and autumn?
2. Does the mean concentration of nitrate and of oxygen differ between the five sections? If
yes, which sections differ from each other?
Question 1 uses only the spring and autumn rows (225 each, 450 in total), and Question 2 uses
all 900 rows of the data set.

