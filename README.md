# WhatsApp Google Drive Extractor
Allows WhatsApp users on Android to extract their backed up WhatsApp data from Google Drive.  

###### BRANCH UPDATES:
v1.0 - Initial release.  
v1.1 - Added Python 3 support.  
v2.0 - Fixed gDriveFileMap after Whatsapp q requirements update.
       Fixed downloadurl (the script is working again!).   
v2.5 - Added multi-threading support.
v2.6 - Better errors description, logging system deprecated.

###### PREREQUISITES:
 1. O/S: Windows Vista, Windows 7, Windows 8, Windows 10, Mac OS X or Linux  
 2. Python 3.x - If not installed: https://www.python.org/downloads/  
 3. Android device with WhatsApp installed and the Google Drive backup feature enabled  
 4. Google services device id (if you want to reduce the risk of being logged out of Google)  
     Search Google Play for "device id" for plenty of apps that can reveal this information  
 5. Google account login credentials (username and password)  
 6. Whatsapp cellphone number as shown in backup tab on google drive website.


###### INSTRUCTIONS:
 1. Extract "WhatsApp-GD-Extractor-master.zip".
 2. Install dependencies `pip install -r requirements.txt` (or using your distribution package manager)
 3. Edit the [auth] section in "settings.cfg".
 4. Run python WhatsAppGDExtract.py from your command console.
 5. Read the usage examples that are displayed.
 6. Run any of the examples.


###### TROUBLESHOOTING:
 1. Check you have the required imports installed (configparser and requests).  
     I.E.: pip install configparser requests  
 2. If you have `Error:Need Browser`, go to this url to solve the issue:
     [https://accounts.google.com/b/0/DisplayUnlockCaptcha]


###### CREDITS:
 AUTHOR: TripCode  

###### CREDITS:
 CONTRIBUTORS: DrDeath1122 from XDA for the multi-threading backbone part,
               YuriCosta for reverse engineering the new restore system
