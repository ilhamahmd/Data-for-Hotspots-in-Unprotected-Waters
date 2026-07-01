# Data-for-Hotspots-in-Unprotected-Waters
BRUV data collected by Indo Ocean Project from 2022 - 2024 in Tanjung Bira, South Sulawesi, Indonesia that is used for research titled "Hotspots in Unprotected Waters: Spatial Patterns of Elasmobranch Diversity and Distribution in Tanjung Bira, South Sulawesi"

The "BRUV Bira 2022 - 2024 info.csv" is the general description of each BRUV deployment, consisting:
  - **date**: date of BRUV deployment in a mm/dd/yyyy format
  - **site**: site at which BRUV was deployed
  - **code**: short abbreviation code for site
  - **locality**: locality at which the site falls into
  - **bruv_id**: BRUV deployment unique ID
  - **longitude, latitude**: Coordinates for BRUV deployment. Retrieved through GPS collected at the location of Surface Marker Buoy (SMB) indicating BRUV                                  location
  - **depth**: depth at which BRUV is deployed
  - **soak_time**: Total effective recording period. Begins once divers exited the camera's field of view and also no audible breathing bubbles, continues                        until the end of the recording.

While the "BRUV Bira 2022 - 2024 MaxN.csv" is the MaxN number for sharks and rays at each BRUV deployment, consisting:
  - **date, site, code, locality, and bruv_id** which are the same as "BRUV Bira 2022 - 2024 info.csv" 
  - **type**: the type of elasmobranch (shark/ray) recorded
  - **species**: the species of elasmobranch recorded
  - **MaxN**: Total number of individuals of a single species in a single video frame at any point of the recording.
