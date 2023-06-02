# Recently Archived Ads

## Ads Recently_Archived.xlsx
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
