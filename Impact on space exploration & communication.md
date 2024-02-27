Similarly to Satnav positioning, accurate time is needed to measure the distance to Earth, however there aren't other different objects to measure different times from to determine the time in the same method as Satnav.

The usual method to control a spacecraft [^1] is to send a radio signal to a spacecraft, send it back, and measure the total flight time and other parameters to determine the position of the spacecraft accurately. This is used to update the Earth-based models of the current trajectory and provide correction instructions if needed. Note this requires 1.5 round trips to give course corrections to the spacecraft.

Issues arise for long distance space travel, for example Mars can have round trip times of up to 45 minutes which makes it impractical for smaller corrections. Instead, the measurement of doppler and time of flight could be made at the spacecraft itself, known as one-way radiometric navigation [^2], allowing for autonomous corrections without the need to communicate back to Earth. 

This requires an accurate clock with as little drift as possible. An example of this was the Deep Space Atomic Clock (DSAC) [^3], a mercury trapped ion clock being used due to the low drift and small size and mass [^4].


[^1]: A very insightful review of radio-based tracking for deep space exploration, although slightly outdated. https://descanso.jpl.nasa.gov/monograph/series1/Descanso1_all.pdf
[^2]: An overview of one way radiometric navigation https://www.researchgate.net/publication/271137858_One-Way_Radiometric_Navigation_with_the_Deep_Space_Atomic_Clock
[^3]: DSAC article https://www.nature.com/articles/s41586-021-03571-7
[^4]: Overview of DSAC success https://ieeexplore.ieee.org/document/7437483