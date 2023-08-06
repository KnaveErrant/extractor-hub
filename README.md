# extractor-hub
Auto-updating personal tool.

This is a tool I used as part of my work with LinkIt!, an education technology company. 

The tool queries the company SQL database, runs data analysis on the results, and saves a formatted Excel file to be used for internal company reports.

I originally developed the tool to streamline the process of creating these reports, which had been done with manual SQL queries and an Excel file full of formulas (which required multiple manual steps, after each of which the computer would chug for several minutes before becoming usable again). The old method took up to thirty minutes of manual work to complete a single report. This tool allowed me to produce identical reports in under 60 seconds, during which time the computer was fully usable for other tasks.

Once I had the tool working, I decided to make it available to my coworkers, as we all had to run these reports regularly. Since many of my colleagues are not programmers, I decided to package the tool with a simple UI and an auto-update functionality through Google Drive. Once the program was installed (a simple unzipping of a file), any time it launched it would check for updates and auto-install any new version, which was necessary as requirements for reports and security information changed.

I maintained the software for the entirety of my time at LinkIt!, saving hundreds of man-hours of labor in the process, and enabling new custom reports we did not previously offer.
