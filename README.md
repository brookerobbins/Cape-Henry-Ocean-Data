# Cape-Henry-Ocean-Data-STATS3800
This dataset contains daily ocean and atmospheric observations near Cape Henry, Virginia, for 2025. It was developed for an engineering statistics project investigating relationships between wave conditions, wind conditions, and seasonal variability.
Project Overview

This dataset contains daily ocean and atmospheric observations near Cape Henry, Virginia, for 2025. It was developed for an engineering statistics project investigating relationships between wave conditions, wind conditions, and seasonal variability.

# Data Sources

NOAA National Data Buoy Center (NDBC): Cape Henry offshore wave buoy (Station 44099)

NOAA CO-OPS / PORTS: Cape Henry wind station (Station CHYV2)

<img width="782" height="580" alt="image" src="https://github.com/user-attachments/assets/b5ade6a0-d324-478b-80e6-afd6984d836d" />

# Variables

WVHT - Significant wave height (meters)

DPD - Dominant wave period (seconds)

WSPD - Wind speed (meters per second)

GST - Wind gust (meters per second)

PRES - Atmospheric pressure (hPa)

ATMP - Air temperature (°C)

Season - season

# Data Processing

Original NOAA observations were cleaned by replacing designated missing-value codes with missing values. Wave and wind observations were matched by timestamp, and daily median values were calculated. Each daily observation represents the median of available matched measurements for that day.

Season was assigned based on meteorological seasons:

Winter: December–February

Spring: March–May

Summer: June–August

Fall: September–November

# Limitations

The wave and wind stations are 16 nautical miles apart. Therefore, the observations represent regional conditions near Cape Henry rather than measurements taken at the exact same location. The dataset includes only days with usable paired observations.

# Sources

NOAA NDBC Station 44099: https://www.ndbc.noaa.gov/station_page.php?station=44099

NOAA Cape Henry Station CHYV2: https://www.ndbc.noaa.gov/station_page.php?station=chyv2
