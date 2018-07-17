# Fork of [Flatpickr](https://flatpickr.js.org/)
### [Original README](https://github.com/flatpickr/flatpickr)

### Fork Changes:
- Changes ["range mode"](https://flatpickr.js.org/examples/#range-calendar) to allow disabled dates within the range
  - Original Docs:
    ```
    ...disabled dates (by either minDate, maxDate, enable or disable) will not be allowed in selections.
    ```
  - This allows you to permit date ranges that contain disabled dates
  - For our uses, we wanted to only allow users to pick dates that start and ended on the same day of the week, but to pick as many weeks as they wanted
- Added dist folder to repo to allow compiled output to be used in an HTML script tag
