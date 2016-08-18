[**calendar.csv**](https://github.com/mikalaiyurkin/csv/blob/master/calendar.csv)

Calendar of Belarus from 2011 to 2016

* _`is_day_off`_ - identifier is the current day is day off
* _`month`_ - number of month (1-12)
* _`day`_ - number of day (1-28/29/30/31)
* _`year`_ - number of year, in 2-digits format
* _`weekday`_ - number of day in week (0-6)
* _`day_off_in_row`_ - integrative counter of days off in row (like Saturday is first day off in row, Sunday is second and so on)
* _`days_off_in_future_from_today`_ - counter of days off in future, starting from today
* _`days_off_in_future_from_tomorrow`_ - counter of days off in future, starting from tomorrow

[**calendar-crimes.csv**](https://github.com/mikalaiyurkin/csv/blob/master/calendar-crimes.csv)

Reduced variant of calendar.csv (Feb 2011 - Dec 2014) with crimes statistics in Belarus. Contains the same fields as **calendar.csv** does + 1 additional field

* _`crimes`_ - total number of crimes in that day
