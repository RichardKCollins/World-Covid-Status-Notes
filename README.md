# World-Covid-Status-Notes
As I am tracking the global status and making videos, I will put things here to share.  
Richard Collins, Director, The Internet Foundation

The current version of the sheet is named "Master"
The names of the other files will correspond to the name of the video.

World Covid Status 17 Apr 2020 with Terminal Velocity and Forward Projections

Video:  https://youtu.be/jJmQSWYy8YM

I first tried using a model based on terminal velocity from physics. That did not work - yet.  But the formal language for rates of change (velocities) and rates of change of rates of change (acceleration) is useful.  For the short term I chose a simple polynomial projection of the CumulativeCases, then took the first difference of that to give the DailyCaseVelocity.  I can do the same with deaths.  I am mutilpying the ActualCumulativeCases or ProjectedCumulativeCases by (CumulativeDeaths/CumulativeCases)/(CumulativeDeathsPerInfected) where CumulativeDeathsPerInfected is set at 1.00% currently. The DailyCaseVelocity is the difference between todays actual and yesterdays actual CumulativeCases.  Since I am using an equation for the CumulativeCases, I can differentiate analytically to have an equation to use for the DailyCaseVelocity or CasesPerDay.  I plan to switch to convert to a Javascript model and have that export to a spreadsheet.  Maybe by tomorrow or Sunday at latest.  But I will keep adding to the spreadsheet for a little while. It is just clumsy when every cell can have a whole set of sources, contraints, types of data and modelling languages.  Spreadsheets are too rigid for exploration.  

Come on, Microsoft and Google, get your sheets up to 2020 instead of 1995. Come on, WHO, get your website where it is suitable for analysis, modelling and accounting for global processes.  Don't "publish" - share tools, evidence, data and your thoughts.
