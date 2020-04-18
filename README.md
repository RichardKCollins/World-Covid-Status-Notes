# World-Covid-Status-Notes
As I am tracking the global status and making videos, I will put things here to share

The current version of the sheet is named "Master"
The names of the other files will correspond to the name of the video.

World Covid Status 17 Apr 2020 with Terminal Velocity and Forward Projections
https://youtu.be/jJmQSWYy8YM

I first tried a using a model based on terminal velocity from physics. That did not work.  But the formal language for rates of change (velocities) and rates of change of rates of change (acceleration) is useful.  For the short term I chose a simple polynomial projection of the cumulative cases, then took the first difference of that to give the daily cases.  I can do the same with deaths.  I am mutilpying the actual or projected cumulative cases by (CumulativeDeaths/CumulativeCases)/(CumulativeDeathsPerInfected) where CumulativeDeathsPerInfected is 1.00%
