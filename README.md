# Capital-Bikeshare
The project mainly analyzes the bike-share industry before and during the pandemic and predicts its future after the pandemic using the data from Capital Bikeshare, a company that offers a bicycle sharing system in Washington, D.C. Transportation companies, including Uber, Lyft, Capital Bikeshare, were hit hard by the coronavirus pandemic since many people chose to work from home and to telework to protect themselves against infection. However, bikes and scooters seem to be safer than other tools when people want to keep social distance and still have the means to get to where they need to get to without a car. In addition, the sales of bikes and scooters are increasing according to reports. Once people return to work, they are more likely to use personal and shared bikes and scooters than taking public transit or services such as Uber or Lyft in order to feel a greater sense of protection against the virus.
# Datasets
The datasets used in this project is from January 2019 to April 2021. It can be downloaded from a repository of monthly CSV files provided by Capital Bikeshare. The link is https://s3.amazonaws.com/capitalbikeshare-data/index.html. Some data wrangling, to reduce columns and reformat, has been performed to condense these files to the core 12 columns used in this project. This makes the analysis and the evaluation in this project more straightforward.
- Start Time
- End Time
- Start Station Id
- Start Station Name
- End Station Id
- End Station Name
- Start Station latitude
- Start Station longtitude
- End Station latitude
- End Station longtitude
- Trip Duration (in seconds)
- Member Type (Member or Casual)
