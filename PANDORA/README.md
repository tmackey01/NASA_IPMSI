**FIRST TIME USERS: Start w/ Open_Pandora_Current.ipynb** 

Below is a quick guide to the Pandora Webpage, and how to find and download data  

1. Pandora Data is accessed through their data downloader website: https://downloader.pandonia-global-network.org
2. Using the Pandora Map, zoom to the region of your Pandora Instrument (American West, Europe, etc.)
3. Directly below the map, a table will show all instruments currently visible on the map - locate your Pandora in this table 
4. Below this table is a "Status and Deployment Timelines" graph.
    This allows a quick check on instrument operational outages, as well as the cause (maintenance, out of operation, etc)
5. Scroll down to the 'Select Dataset' table to view the data products available for your site, and select the desired variable(s). 
    Yes, you can chose more than 1! However, when you download the data, you'll get one file for each variable
6. A new plot should generate below this table, labeled 'Data Availability'
    This shows the quality of the data collected over time, which is adjustable below the plot
7. Fill the 'start' and 'end' date boxes with your desired time range
8. At the bottom of the page, the 'Summary and Download' box should be filled with the following information:
   PanID, Spectrometer, Location, Data Products,Time Range \n
   For example, getting the HCHO Total Column Data from Houston, TX for the month of January 2025 would read:
   PanID - 25
   Spectrometer -1
   Location - HoustonTX
   Data Products - HCHO vertical column (rfus5p1-8)
   Time Range - 2024-12-31 to 2025-01-31
   Or, getting the NO2 Total Column and NO2 Vertical Profile Data from Houston, TX for the month of January 2025 would read:
   PanID - 25
   Spectrometer -1
   Location - HoustonTX
   Data Products - HCHO tropospheric column (rfuh5p1-8)
                   NO2 tropospheric column (rnvh3p1-8)
   Time Range - 2024-12-31 to 2025-01-31
10. Select "Download" to save the file(s) to .txt on your computer
