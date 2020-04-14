# wk_agg_deaths_plot
This plots total weekly deaths in Enlgand and Wales (_i.e._ United Kingdom excluding Northern Ireland and Scotland) by week of the year.
* Week 1 is the first week of January.
## Data
* Source for the data is the ONS [Deaths registered weekly in England and Wales, provisional](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/datasets/weeklyprovisionalfiguresondeathsregisteredinenglandandwales).
  * _Example timing:_ Week 13 2020 records deaths from Saturday 21/03/2020 to Friday 27/03/2020. They are recorded from death certificates submitted up to 01/04/2020. This reflects that deaths must be registered within 5 days of the death (see https://www.gov.uk/after-a-death).

## Plotting software
* The plots are created using the `TikZ-PGF` vector-plotting package for `TeX`. 
  * `TikZ-PGF` repositiory here: https://github.com/pgf-tikz/pgf.
  * `TikZ-PGF` manual here: https://pgf-tikz.github.io/.
