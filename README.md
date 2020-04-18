# World-Covid-Status-Notes
As I am tracking the global status and making videos, I will put things here to share

The current version of the sheet is named "Master"
The names of the other files will correspond to the name of the video.

World Covid Status 17 Apr 2020 with Terminal Velocity and Forward Projections

Video:  https://youtu.be/jJmQSWYy8YM

I first tried a using a model based on terminal velocity from physics. That did not work - yet.  But the formal language for rates of change (velocities) and rates of change of rates of change (acceleration) is useful.  For the short term I chose a simple polynomial projection of the CumulativeCases, then took the first difference of that to give the DailyCaseVelocity.  I can do the same with deaths.  I am mutilpying the ActualCumulativeCases or ProjectedCumulativeCases by (CumulativeDeaths/CumulativeCases)/(CumulativeDeathsPerInfected) where CumulativeDeathsPerInfected is set at 1.00% currently. The DailyCaseVelocity is the difference between todays actual and yesterdays actual CumulativeCases.  Since I am using an equation for the CumulativeCases, I can differentiate analytically to have an equation to use for the DailyCaseVelocity.  I plan to switch to a Javascript model and export to a spreadsheet.  Maybe by tomorrow or Sunday at latest.
