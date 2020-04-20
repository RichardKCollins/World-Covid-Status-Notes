# World-Covid-Status-Notes
As I am tracking the global status and making videos, I will put things here to share.  
Richard Collins, Director, The Internet Foundation

The current version of the sheet is named "Master"
The names of the other files will correspond to the name of the video.

World Covid Status 17 Apr 2020 with Terminal Velocity and Forward Projections
Video:  https://youtu.be/jJmQSWYy8YM

World Covid Status 18 Apr 2020 with Differentiation of Cases and Reported Velocities
https://youtu.be/BKDU9F9Mtm0

Notes 17: I first tried using a model based on terminal velocity from physics. That did not work - yet.  But the formal language for rates of change (velocities) and rates of change of rates of change (acceleration) is useful.  For the short term I chose a simple polynomial projection of the CumulativeCases, then took the first difference of that to give the DailyCaseVelocity.  I can do the same with deaths.  I am mutilpying the ActualCumulativeCases or ProjectedCumulativeCases by (CumulativeDeaths/CumulativeCases)/(CumulativeDeathsPerInfected) where CumulativeDeathsPerInfected is set at 1.00% currently. The DailyCaseVelocity is the difference between todays actual and yesterdays actual CumulativeCases.  Since I am using an equation for the CumulativeCases, I can differentiate analytically to have an equation to use for the DailyCaseVelocity or CasesPerDay.  I plan to switch to convert to a Javascript model and have that export to a spreadsheet.  Maybe by tomorrow or Sunday at latest.  But I will keep adding to the spreadsheet for a little while. It is just clumsy when every cell can have a whole set of sources, contraints, types of data and modelling languages.  Spreadsheets are too rigid for exploration.  

Come on, Microsoft and Google, get your sheets up to 2020 instead of 1995. Come on, WHO, get your website where it is suitable for analysis, modelling and accounting for global processes.  Don't "publish" - share tools, evidence, data and your thoughts.

Notes 18: This is an update on the numbers, but it is also a detailed, if somewhat haphazard description of some of the global problems of tracking and responding and correcting this Covid situation.

I extended my ideas about differentiating the polynomial (or function) that represents the cumulative cases to date. When that is differentiated, it should match a one lower order equation for the daily new cases, the cases per day, the case velocity.  The numbers are kind of lining up. At least the coefficients have the correct signs and magnitudes.

A global site to collect all the Covid data (globally neutral) could be set up at fairly low cost. I ask for someone with deep enough pockets to do that and do it right.  I suggested creating apps so that all the people in the world can report directly to the central site.

I am so tired, perhaps I should not even try.  But this is useless for me to do if I do not at least try to share it.  You are supposed to go do your part without supervision -- think on your own what needs to be done and start doing it.  Will it be wasteful and inefficient?  We can only try to do our best.
