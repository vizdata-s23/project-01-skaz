# project-01

Project 1 repo for STA/ISS 313 - Spring 2023.

### Data Dictionary

The following data dictionary is taken from TidyTuesday's [README file](https://github.com/rfordatascience/tidytuesday/blob/master/data/2022/2022-10-25/readme.md#data-dictionary). It presents all the variables in each of the datasets of the "bakeoff" package. 

# challenges


|variable    |class     |description |
|:-----------|:---------|:-----------|
|series      |integer   | series    |
|episode     |integer   |episode    |
|baker       |character | baker    |
|result      |character |result    |
|signature   |character | signature    |
|technical   |integer   | technical    |
|showstopper |character | showstopper    |

# bakers


|variable                  |class     |description               |
|:-------------------------|:---------|:-------------------------|
|series                    |double    |series                    |
|baker                     |character |baker                     |
|star_baker                |integer   |star_baker                |
|technical_winner          |integer   |technical_winner          |
|technical_top3            |integer   |technical_top3            |
|technical_bottom          |integer   |technical_bottom          |
|technical_highest         |double    |technical_highest         |
|technical_lowest          |double    |technical_lowest          |
|technical_median          |double    |technical_median          |
|series_winner             |integer   |series_winner             |
|series_runner_up          |integer   |series_runner_up          |
|total_episodes_appeared   |double    |total_episodes_appeared   |
|first_date_appeared       |double    |first_date_appeared       |
|last_date_appeared        |double    |last_date_appeared        |
|first_date_us             |double    |first_date_us             |
|last_date_us              |double    |last_date_us              |
|percent_episodes_appeared |double    |percent_episodes_appeared |
|percent_technical_top3    |double    |percent_technical_top3    |
|baker_full                |character |baker_full                |
|age                       |double    |age                       |
|occupation                |character |occupation                |
|hometown                  |character |hometown                  |
|baker_last                |character |baker_last                |
|baker_first               |character |baker_first               |

# ratings


|variable             |class     |description          |
|:--------------------|:---------|:--------------------|
|series               |double    |series               |
|episode              |double    |episode              |
|uk_airdate           |double    |uk_airdate           |
|viewers_7day         |double    |viewers_7day         |
|viewers_28day        |double    |viewers_28day        |
|network_rank         |double    |network_rank         |
|channels_rank        |double    |channels_rank        |
|bbc_iplayer_requests |double    |bbc_iplayer_requests |
|episode_count        |double    |episode_count        |
|us_season            |double    |us_season            |
|us_airdate           |character |us_airdate           |

# episodes


|variable          |class     |description       |
|:-----------------|:---------|:-----------------|
|series            |double    |series            |
|episode           |double    |episode           |
|bakers_appeared   |integer   |bakers_appeared   |
|bakers_out        |integer   |bakers_out        |
|bakers_remaining  |integer   |bakers_remaining  |
|star_bakers       |integer   |star_bakers       |
|technical_winners |integer   |technical_winners |
|sb_name           |character |sb_name           |
|winner_name       |character |winner_name       |
|eliminated        |character |eliminated        |