#Please read the following points on how to use group 13's dashboard tableau workbook
1. Tableau workbook file is created on version 2022.1
2. The tableauu workbook is published as packaged tableau workbook in .twbx format; 
All worksheet, dashboards, and story should be able to load and display without requiring connecting to data files
3. In case the package_dashboard_group13.twbx is not working, please refer for dashboard_group13.twb
3.1 Edit the data connection to the corresponding csv files provided in this folder (the csv file names are same with each data connection names)
3.2 The table join relationship should be formed automatically. If not, please update with these relationships
+ Listing_Cleaned.csv (#Id) = amenties_included.csv (#listing ID)
+ Listing_Cleaned.csv (#Id) = Calendar_cleaned.csv (#listing ID)
+ Listing_Cleaned.csv (#Id) = calculated_occupancy.csv (#Id)
+ Listing_Cleaned.csv (#Neighborhood) = neighbourhoods.geojson (#Neighbourhood)
+ Listing_Cleaned.csv (#Id) = q5a2.csv (#ID)
+ Listing_Cleaned.csv (#Id) = reviews_sum.csv (#Listing ID)


4. The main dashboard tab is named as "Assignment2dashboard"
5. Dashboard is organised as tabview.
+ In presentation, click on each tab should be enough to go to that tab. 
+ In normal/edit mode, to open a tab, Alt + Click should be used. 
6. Story is named as Story1

7. drive link for dataset: https://drive.google.com/drive/folders/1QPsybdxLiAzsMILqs_YkjI3ZQhfAHNEx?usp=sharing