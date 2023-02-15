# project-01

Project 1 repo for STA/ISS 313 - Spring 2023.

### Data Dictionary

The following data dictionary is adapted from TidyTuesday's [README file](https://github.com/rfordatascience/tidytuesday/blob/master/data/2022/2022-10-25/readme.md#data-dictionary) and the ["bakeoff" package documentation](https://cloud.r-project.org/web/packages/bakeoff/bakeoff.pdf). It presents all the variables in each of the datasets of the "bakeoff" package.

# challenges

| variable    | class     | description                                                                                                                                                               |
|:------------------------|:---------------------|:------------------------|
| series      | integer   | UK series number (1-10)                                                                                                                                                   |
| episode     | integer   | episode number within a series                                                                                                                                            |
| baker       | character | baker's given name or nickname                                                                                                                                            |
| result      | character | denoting in baker was IN, OUT, STAR BAKER, or SICK for a given episode. For finale, values are WINNER or Runner-up. NA indicates the baker didn't appear in given episode |
| signature   | character | bake for the signature challenge for that baker/episode. NA indicates the baker didn't appear in given episode                                                            |
| technical   | integer   | rank on the technical challenge for the baker/episode. 1 means winner of the challenge. NA indicates the baker didn't appear in given episode                             |
| showstopper | character | bake for the showstopper challenge for that baker/episode. NA indicates the baker didn't appear in given episode                                                          |

# bakers

| variable                  | class     | description                                                                                                                                               |
|:--------------------------|:-----------------|:--------------------------|
| series                    | double    | UK series number (1-10)                                                                                                                                   |
| baker                     | character | baker's given name or nickname                                                                                                                            |
| star_baker                | integer   | number of times baker won Star Baker                                                                                                                      |
| technical_winner          | integer   | number of times a given baker won first place in the technical challenge                                                                                  |
| technical_top3            | integer   | number of times a given baker was in the top 3 on the technical challenge                                                                                 |
| technical_bottom          | integer   | number of times a given baker was in the bottom 3 on the technical challenge                                                                              |
| technical_highest         | double    | best technical rank earned by a given baker across all episodes appeared (higher is better)                                                               |
| technical_lowest          | double    | worst technical rank earned by a given baker across all episodes appeared (higher is better)                                                              |
| technical_median          | double    | median technical rank earned by a given baker across all episodes appeared (higher is better)                                                             |
| series_winner             | integer   | 0 if not the series winner, 1 if series winner                                                                                                            |
| series_runner_up          | integer   | 0 if not the series runner-up, 1 if series runner-up                                                                                                      |
| total_episodes_appeared   | double    | total number of episodes in which a given baker appeared                                                                                                  |
| first_date_appeared       | double    | date denoting original airdate of the first episode in which a given baker appeared (equivalent to the series premiere episode in the UK.)                |
| last_date_appeared        | double    | original airdate of the last episode in which a given baker appeared (in the UK)                                                                          |
| first_date_us             | double    | original airdate of the first episode in which a given baker appeared (equivalent to the series premiere episode in the US)                               |
| last_date_us              | double    | original airdate of the last episode in which a given baker appeared (in the US)                                                                          |
| percent_episodes_appeared | double    | number of episodes in a given series in which a given baker appeared out of all episodes aired in that series                                             |
| percent_technical_top3    | double    | number of episodes in which a given baker placed in the top 3 for the technical challenge, out of the number of total episodes that the baker appeared in |
| baker_full                | character | baker's full name                                                                                                                                         |
| age                       | double    | age in years at first episode appeared                                                                                                                    |
| occupation                | character | baker's occupation                                                                                                                                        |
| hometown                  | character | baker's hometown                                                                                                                                          |
| baker_last                | character | baker's last name                                                                                                                                         |
| baker_first               | character | baker's first name                                                                                                                                        |

# ratings

| variable             | class     | description                                                            |
|:--------------------------|:-----------------|:--------------------------|
| series               | double    | UK series number (1-10)                                                |
| episode              | double    | episode number within the series                                       |
| uk_airdate           | double    | original airdate of episode in the UK                                  |
| viewers_7day         | double    | number of viewers in millions within a 7-day window from airdate       |
| viewers_28day        | double    | number of viewers in millions within a 28-day window from airdate      |
| network_rank         | double    | episode's weekly ranking within network                                |
| channels_rank        | double    | episode's weekly ranking across all channels.                          |
| bbc_iplayer_requests | double    | number of BBC iPlayer requests (only for series that aired on the BBC) |
| episode_count        | double    | continuous episode number across series (1-94)                         |
| us_season            | double    | US season (1-5)                                                        |
| us_airdate           | character | original airdate of episode in the US                                  |

# episodes

| variable          | class     | description                                                                                   |
|:--------------------------|:-----------------|:--------------------------|
| series            | double    | UK series number (1-10)                                                                       |
| episode           | double    | episode number within the seriesn                                                             |
| bakers_appeared   | integer   | number of bakers who appeared in a given episode                                              |
| bakers_out        | integer   | number of bakers were either eliminated, left at will, or left due to illness in that episode |
| bakers_remaining  | integer   | number of bakers who remained at the end of a given episode                                   |
| star_bakers       | integer   | number of bakers crowned Star Baker in a given episode                                        |
| technical_winners | integer   | number of bakers who placed first in the technical challenge                                  |
| sb_name           | character | names of the bakers who won Star Baker in a given episode, separated by commas                |
| winner_name       | character | name of the series winner (Only for final episodes within series)                             |
| eliminated        | character | name of the bakers who left a given episode, separated by commas                              |
