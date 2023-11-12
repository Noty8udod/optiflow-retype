---
icon: shield-check
order: -1
---
# Backup and Restore

---
!!!Warning
***Hey there! If you're planning to make some changes to your PC's registry or experiment with settings, it's essential to have a safety net in place. Let me guide you on how to back up your registry and create a restore point, so you can freely optimize without worries***
!!!

---

### Creating a Restore Point:

1. Press `Windows + R` to open the "Run" dialog.
2. Type `sysdm.cpl` and hit `Enter` to open "System Properties."
3. In the "System Properties" window, go to the "System Protection" tab.
4. Under These Settings, select your system drive (usually C:) and "Create."
5. Name the restore point (e.g., "Pre-Registry Edit Backup") and "Create."
6. Windows will now create the restore point, which may take a bit.

---

### Backing up the Registry:

1. Press `Windows + R` to open the "Run" dialog.
2. Type `regedit` and hit `Enter` to open the Registry Editor.
3. In the Registry Editor, click on "File" in the top-left corner.
4. Choose "Export" and select a location to save the backup.
5. Name the backup file and make sure to choose "All" under "Export range."
6. Click "Save" to create the backup. Now, your registry is safely backed up!
---

### Restoring Registry Backup:

1. Press `Windows + R` to open the "Run" dialog.
2. Type `regedit` and hit `Enter` to open the Registry Editor.
3. In the Registry Editor, click on "File" in the top-left corner.
4. Choose "Import" and navigate to the location of your registry backup file.
5. Select the backup file and hit "Open" to restore your old registry settings.
---

### Restoring from Restore Point:

1. Press `Windows + R` to open the "Run" dialog.
2. Type `rstrui` and hit `Enter` to open the "System Restore" window.
3. Click "Next" to view available restore points.
4. Select desired restore point (e.g., "Pre-Registry Edit Backup") hit "Next"
5. Review the restore details and hit "Finish" to start the restoration process.
6. Your system will restart, and the restore process will begin.
---

***Having backups and restore points gives you the confidence to explore and optimize your PC without fear of irreversible consequences. If you encounter any issues during the restoration process or need further assistance, don't hesitate to seek help from a tech-savvy friend or a professional.***


---
!!! Read
:icon-light-bulb: [**Click Here**](https://support.microsoft.com/en-gb/topic/how-to-back-up-and-restore-the-registry-in-windows-855140ad-e318-2a13-2829-d428a2ab0692#:~:text=Back%20up%20the%20registry%20manually&text=Select%20File%20%3E%20Export.,Select%20Save.) for up-to-date information on how to back up any windows OS registry from Microsoft themselves.
!!!