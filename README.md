# Battmobility ride search API

Given the following endpoint: https://api.battmobility.com/web-api/booking/v1/vehicles/public/searches
with optional query params:
- `start`: url-encoded datetime for the start time. eg. https://api.battmobility.com/web-api/booking/v1/vehicles/public/searches?start=2024-09-18T17:50:00%2B01:00%5BEurope/Brussels%5D. default: current time
- `end`: same as start. default 1 day after start
- `minimumRange`: default 0, min range in km

Write a Flutter application to search the available vehicles by start time, end time and minimum range. This can be a list view, a map view, or both.
Extra assignment: create a CI pipeline that produces a a build of the app (eg. as an APK, or hosted as a web app).
