Here you see the final dataset file and some raw files stored from the middle stages of data extraction.
**For your analysis, use the final file.** 

The features are:        
**App:** The name of the application      
**Category:** The name of the category which app belongs to      
**Rating:** A number between 0 to 5 that shows how satisfied the users with the app     
**Reviews:** How many users had voted to rate this app     
**Size:** The volume of application in Megabytes    
**Installs:** The class of installs number in terms of the CafeBazaar formula     
**Type:** Shows the app in terms of price, which would be either free, paid, or in-app purchase     
**Price:** The price of the app in Tomans     
**Developer:** The name of the developer     
**DeveloperLinkPage:** The developer link page on the CafeBazaar website     
**pkg_name:** The unique package name of the app     
**Kind:** Indicates whether the app is an application or a game            
**InstallsNum:** Computed based on Installs column to enable us to work with numeric data     
**Current_Ver:** shows the current version of the app      
**Data_Flow:** Computed based on Size * InstallsNum      
**SellAmount:** Computed based on Price * InstallsNum     
**Review_Install_Ratio:** Computed based on Reviews divided by InstallsNum to estimate the number of active users for each app        
