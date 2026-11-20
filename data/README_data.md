# Data Files for Modules 12-13

The flight examples use the `nycflights13` package. The two files in this folder are used in the Module 12 Final Practice and the Module 13 Applied Practice.

## `bike_sharing_daily.csv` (731 rows, one row per day, 2011-2012)

Source: Fanaee-T, H. (2013). *Bike Sharing* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5W894. License: CC BY 4.0. Based on Capital Bikeshare data, Washington, D.C.

Changes for this course: the normalized weather values were converted back to their units and rounded to one decimal (`temp_c` = temp x 41, `humidity_pct` = hum x 100, `windspeed_kmh` = windspeed x 67); `season` and `weather` codes were replaced by names (season 1-4 = winter, spring, summer, fall; the seasons start on about Dec 21, Mar 21, Jun 21, and Sep 23 - the original UCI documentation labels these codes differently, but the dates show that 1 = winter; weather 1-3 = clear, mist_cloudy, light_rain_snow); `dteday`, `mnth`, `weathersit`, and `cnt` were renamed `date`, `month`, `weather`, and `rentals`; `yr` became `year` (2011 or 2012). The columns `instant`, `weekday`, and `atemp` were dropped. All holidays in this data fall on weekdays. `casual + registered = rentals` on every day.

## `bank_marketing.csv` (45,211 rows, one row per client contacted in a campaign)

Source: Moro, S., Rita, P., & Cortez, P. (2014). *Bank Marketing* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306. License: CC BY 4.0. Phone campaigns of a Portuguese bank, May 2008 - November 2010.

Changes for this course: the file `bank-full.csv` was saved with commas instead of semicolons, and the target column `y` was renamed `subscribed` (yes/no: did the client subscribe to a term deposit). No rows or other columns were changed. `pdays = -1` means the client was not contacted in an earlier campaign. `duration` is the length of the call in seconds; it is known only after the call.
