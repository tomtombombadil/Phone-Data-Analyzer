# Phone-Data-Analyzer
This simple tool analyzes and visualizes your call and SMS history from an Android phone. This tool relies on the output of the 'SMS Backup & Restore' app, which can be found on the Google Play Store here:
https://play.google.com/store/apps/details?id=com.riteshsahu.SMSBackupRestore

# How It Works
Use the SMS Backup & Restore app to backup your call and message logs/history. (Do NOT include attachments and media!) That creates a pair of XML files, a calls file and an SMS file. One at a time, drag & drop those files into the box on the webpage created by the Phone-Data-Analyzer.html file and it will show you pretty graphs and stats about your calling and texting.

# Instructions:
1. On your Android phone (iPhone is not supported) install the SMS Backup & Restore app
2. Open SMS Backup & Restore and tap Get Started
3. If asked, grant it permission to access your phone call logs, contacts and accounts, send notifications, make & manage calls, send and view SMS messages (all these are needed to backup your phone calls and SMS messages)
4. Tap Set Up A Backup, make sure both Messages and Call Logs are turned on, and tap "Advanced Options" and turn off "Attachments and Media". This is important. If you don't turn this off, your backups will be too large for the Phone Data Analyzer tool and it will crash.
5. Tap Next then select where you want to the backup files to go. The simplest is Google Drive.
6. As you turn on the Google Drive selection, it will ask you to login (tap Log In)
7. When you tap Log In it will ask about permissions, select the first option (Only access to files and folders opened or created with SMS Backup & Restore), and tap OK.
8. (Select which Google account you're going to use, if you have multiple on your phone)
9. Tap Select A Folder. You can use the 3-dot menu in the upper right to create a new folder. Once you're in the folder where you want your backups to go, tap "Use This Folder". That will return you to the Setup screen, which will show the folder's name that you selected.
10. Leave the rest of the settings at their defaults, then tap Save. That will return you to the Set Up Backup screen, and it will show which storage you've got setup. Tap Next.
11. Turn off the Schedule Recurring Backups (if you don't want this to backup regularly)
12. Tap Back Up Now to start the backup and you'll see a progress bar as it does it's work. It will say Backup Complete when it is done. It can take a few minutes, so be patient.
13. Once it is done, you can set your phone aside. We're done with it. Move over to your computer, login to Google Drive and download the two .xml files you just created/backed-up.
14. Once you've downloaded your .xml files, you can drag and drop them onto this web page to have your data analyzed.  

No data is sent anywhere you don't want it. The backups themselves are in your cloud storage or on your computer. Delete them when you're done. At no time is any information sent anywhere you don't tell it to be.

Before Loading Your Info:
<img width="1291" height="413" alt="Phone-Data-Alayzer-Blank" src="https://github.com/user-attachments/assets/6e8b66cc-fbf8-4c2f-8bd6-6b461de5dd86" />

Call Analysis:
<img width="1293" height="2214" alt="Phone-Data-Analyzer-Calls" src="https://github.com/user-attachments/assets/603682c1-58ab-4916-b316-f14b181f4a52" />

SMS Analysis:
<img width="1291" height="2112" alt="Phone-Data-Analyzer-SMS" src="https://github.com/user-attachments/assets/82346fb4-53fe-4fd5-9ac3-9d2196ac64b3" />

# FAQ:
  Q: Can you change the number of the Top 5 lists?  
  A: Yes! You can use the drop-down to select 5, 10, 25, or 50  

  Q: Can you turn off things on the graph?  
  A: Yes! The color boxes in the legend can be clicked to toggle that dataset on or off in the graph  

  Q: Can you see BOTH call and SMS data at the same time?  
  A: No, it's a one or the other situation. But you can switch back and forth pretty quickly by clicking the dropbox drop-down and dragging your SMS or call xml file over and dropping it in. It will refresh the page with the new data.  
