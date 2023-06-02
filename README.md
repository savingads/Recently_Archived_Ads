# Recently Archived Ads
None of these files are finalized yet. The links to the most recent version of these documents are provided.

## Ads_Recently_Archived.xlsx
Google Sheet (most recent version): [Ads Recently Archived From Live Web](https://docs.google.com/spreadsheets/d/1wkU4JNaZ7u7F5AWyRMEqXKTZ7CeSmM6BfBSpP0XFZzE/edit?usp=sharing)

This spreadsheet contains three sheets:
1. Overview_Table
    - This sheet includes overview information like:
        -  The web pages that were archived
        -  The tools used to archive and replay each web page
        -  The number of ads archived
        -  The number of ads that failed to load during replay
3. All_Ads_Seperated_By_Crawler
    - This sheet contains information for each individual ad:
        - Web Archiving Tool
        - Replay System	
        - Web Browser	
        - Containing Web Page URI-R
            - The URI for the live web page where the ads loaded during crawl time
        - Containing Web Page URI-M or WARC / WACZ URL
            - The URI, WARC, or WACZ file that can be used to load the archived web page
        - Ad Related URLs or Ad Text
            - The content associated with the archived advertisement like the images, videos, and text used for the ad
        - Recorded Session URLs
            - The recorded video that shows the archiving and replay of the containing web page
            - Most of these URLs should have a timestamp parameter that will show the exact point in the video where the ad was loaded during replay or during the archiving session
        - Successful Replay of Ad In Containing Web Page
            - Yes: If the ad is successfully and consistently loaded during replay of the containing web page
            - Sometimes: If the ad can be successfully loaded during replay of the containing web page, but sometimes does not load
            - No: If the ad always fail to load during replay of the containing web page
        - Replay Issues Description
            - Describes what could have prevented the ad from loading when replaying the containing web page
5. Partially_Archived_Ads
    - Similar to the All_Ads_Seperated_By_Crawler sheet except these ads are not fully archived and are missing most of the resources needed when replaying the ad

## All_Comments_For_Archived_Ads_Spreadsheet.pdf
Google Doc (most recent version): [All Comments For Archived Ads Spreadsheet](https://docs.google.com/document/d/1Vze0k3HUmhStlhbuL36ZTI34g6OngM1Ffog_PioM83g/edit?usp=sharing)

This document contains most of the notes associated with the advertisments that were archived.

## All_Ads_Seperated_By_Crawler.tsv
Google Sheet (most recent version): [All_Ads_Seperated_By_Crawler](https://docs.google.com/spreadsheets/d/1wkU4JNaZ7u7F5AWyRMEqXKTZ7CeSmM6BfBSpP0XFZzE/edit#gid=421299840)

This file contains details for each individual ad. It contains the same information as the "All_Ads_Seperated_By_Crawler" sheet in the "Ads_Recently_Archived.xlsx" file.

This file is currently a .tsv, because no tabs are in the ad text fields and the special characters like commas and double quotes have not been escaped yet.
