- GPS makes use of multiple RAFS atomic clocks to synchronise so the location is the most accurate.
- This also allows it to be used for time synchronisation to UTC.
- Time accuracy can be measured to around 100 nanoseconds [^1]
- Time transfer error should be $\leq 30ns$ 95% of the time [^2]

[^1]: https://www.mdpi.com/1424-8220/20/22/6498
[^2]: https://www.gps.gov/technical/ps/2020-SPS-performance-standard.pdf

Satnav relies on accurate measurements of time of flight (ToF) from several different satellites. This is achieved by sending the time of transmission (ToT) and position data for the satellite which is detected by the ground receiver. To get an accurate ToF this means a very accurate synchronisation between the receiver and satellite, which would require another atomic clock to get the nanosecond scale accuracy required.

Instead multiple satellites are used to measure the ToF which can be used to determine accurately the position of the receiver. This 


Extra notes:

Information about GPS time accuracy
http://gpsinformation.net/main/gpstime.htm

More general GPS accuracy information
https://www.gps.gov/systems/gps/performance/accuracy/#:~:text=The%20government%20distributes%20UTC%20as,%2C%2095%25%20of%20the%20time

Deep Space Atomic Clock
https://www.nasa.gov/directorates/somd/space-communications-navigation-program/deep-space-atomic-clock-dsac-overview/

Clocks used on GPS III
https://www.gpsworld.com/new-players-trigger-new-space-race-gps-iii-update/

GPS position accuracy
https://www.mdpi.com/1424-8220/20/22/6498