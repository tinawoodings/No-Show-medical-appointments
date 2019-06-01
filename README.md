# No-Show-medical-appointments
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment

## Dataset

https://www.kaggle.com/joniarroba/noshowappointments

## Summary of Findings

* 80% of the appointments were attended, meaning 20% were no-shows.
* Though 2/3 of the appointments were booked by women, gender does not seem to play a role in no-shows.
* The number of days prior to the appointment does affect the likelyhood whether one attends. If the appointment is booked day of, one was 95% likely to attend. This number drops to just below 80% at one day prior and then drops below 70% at day 10.
* One with more chronic health conditions was more likely to attend the appointment, than one with no chronic medical conditions.
* Those between the ages of 10 and 40 were less likely to attend the appointment.
* Looking at the entire dataset, receiving an SMS reminder message actually reduced the likelyhood one would attend. With further investigation, it did seem to improve attendance with those over the age of 40.

## Limitations
This study was exploratory and is meant to provide insights to warrant further analysis. Therefore there are many limitations.
* The relationships between features were not sufficiently investigated. Regressions were not performed on the characteristics, so we do not know exactly how correlated the data is and what the confidence interval is.
* It would also be useful to have a data set that was for a longer period of time. The appointments ranged from April 29 2016 to June 8 2016, a period of 40 days.
* The analysis of this data set did tell us that it would be of benefit to further study these trends. Next steps would be to use a bigger dataset spanning a longer period of time and utilizations of regressions and predictive modeling.
