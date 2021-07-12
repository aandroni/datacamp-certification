# DataCamp Certification

This was a fun project that I then submitted to DataCamp to complete the "Data
Scientist Certification" process. The challenge consisted in choosing one of the
datasets that DataCamp provided, clean it, and analyze it with a technique of my
choosing.

In my case, I decided to use the "Belgium Train Times" dataset, which
contains arrival and departure information about trains circulating in Belgium
on February 22nd 2021. I then built and compared four predictive models to
forecast if a train will accrue a delay of more than one minute when stopping
at a station. The models are:

1. Random Forests
2. Gradient Boosting (in particular XGBoost)
3. K-Nearest Neighbors
4. Neural Networks

The project/report was written in R Markdown and relies on five main R libraries:
**tidyverse** for general data manipulation and wrangling; **lubridate**
for handling dates; **cowplot** for arranging multiple figures together;
**tidymodels** for machine learning; and **vip** to extract feature
importance from the final model.
