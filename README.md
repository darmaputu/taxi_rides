# taxi_rides

DATA:
Table 'company':
- `company_name`
- `trips_amount`

Table 'location':
- `dropoff_location_name`
- `average_trips`

Table 'weather':
- `start_ts`
- `weather_condition`
- `duration_seconds`

GOALS:
  1. Find the top 10 regions for destination.
  2. Find the taxi company with the most number of trips.
  3. Test the hypothesis for average trips in the busiest areas when the weather is rainy and sunny.

LIBRARY USED:
  - pandas
  - seaborn
  - matplotlib
  - numpy
  - scipy, stats

First data observation using PostgreSQL
