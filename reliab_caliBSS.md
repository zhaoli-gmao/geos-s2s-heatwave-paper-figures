Project: GEOS-S2S heatwave predictability
Event: TX90 any-day in week
Lead: week3 (15–21) week4 (22–28)
Dataset: VERIFY_week*_1991_2020_init0506_0809.nc
Metrics: ROC, TSS, SEDI, BSS
Goal: add reliability + calibrated BSS

location of VERIFY files: 
/nobackup/zli7/Heatwave/V3/HW_event/VERIFY_week*_1991_2020_init0506_0809.nc

file structure:
Dimensions:  (case: 600, lat: 361, lon: 720)
Coordinates:
  * case     (case) <U8 19kB '19910506' '19910511' ... '20200804' '20200809'
  * lat      (lat) float64 3kB -90.0 -89.5 -89.0 -88.5 ... 88.5 89.0 89.5 90.0
  * lon      (lon) float64 6kB -180.0 -179.5 -179.0 -178.5 ... 178.5 179.0 179.5
Data variables:
    o        (case, lat, lon) float32 624MB ...
    p        (case, lat, lon) float32 624MB ...
Attributes:
    description:  Forecast vs observation verification bundle
    cases:        1991-2020 init 0506-0809

ensemble size info:
5 members most inits
15 members end-month

region desired:
CONUS
Texas / Southern Plains
Global

preferred plotting style
Matplotlib or Cartopy.


