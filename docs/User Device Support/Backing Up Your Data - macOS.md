---
tags:
  - employees-only
authors: Sye Williams
title: Backing Up Your Data on macOS
slug: /user-device-support/backup-macOS
sidebar_position: 2
---
export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '2px',
      color: '#fff',
      padding: '0.2rem',
    }}>
    {children}
  </span>
);

Before upgrading/replacing your computer, we advise backing up your data. 

While we will perform a data backup, we will only backup your user folder. *This doesn't include your browser bookmarks*. If you save data elsewhere or under another login, you either need to specify to us what logins or perform the backup yourself. 

## Step 1: Back Up Your Bookmarks
The easiest way to backup your bookmarks is to sign into the browser(s) you use with your ASC email and sync the data. Doing so will mean that your bookmarks will go with you whenever you sign into the browser(s) on your new computer. 

Click the appropriate link to learn how to backup your browser bookmarks:
- *Google Chrome*: https://support.google.com/chrome/answer/185277
- *Firefox*: https://support.mozilla.org/en-US/kb/how-do-i-set-sync-my-computer
- *Safari*: https://support.apple.com/guide/icloud/set-up-safari-mm5400ef10c4/icloud

## Step 2: Back Up Your Files

:::warning
Do not use a network share (aka "the W drive") to backup your files. A network share is designed to share documents amongst your department and storage space is limited.
:::


There are multiple ways to backup your data, but the two best options are as follows:

| Option                     | Best For...                                                  | Tools Needed                                                 |
| -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| External Storage           | Those that have many and/or large files that will not upload quickly to Google Drive. Additionally, this is the best option if you use specialized software with unique file extensions. | A blank 1 TB External Hard Drive (HD)                        |
| Google Drive Cloud Storage | Those that have a small number of documents (PDF and Word files) and images. | [Google Drive Desktop](https://www.google.com/drive/download/) |
### External Storage Backup

1. <Highlight color="#402B6F">If your old computer is a MacBook</Highlight>, make sure it's plugged in for the duration of this process.
2. Sign into your Mac
3. Plug in the 1 TB external HD into your Mac.
4. Click the Apple icon in the upper left-corner of your screen then select System Settings from the menu.
5. In the Search bar within the Settings window, type *Time Machine* and click the matching result.
6. Click Add Backup Disk
7. Select the 1 TB external HD then click Set Up Disk
8. Follow the instructions found [here](https://support.apple.com/en-us/HT201250). 
9. Once the **Time Machine backup** has been completed, eject the external HD.

### Google Drive Cloud Storage
1. While signed into your ASC account, download **Google Drive Desktop** and follow the prompts.
2. Select the checkbox beside each folder on your computer that you want backed-up to the cloud.
3. Wait for the files to upload to Google Drive. You may continue using your computer while the files are uploaded.
4. To verify that your files have been backed up, go to your ASC **Google Drive** and then click **Computers** on the left-side of the screen. 
5. You should see a folder entitled your computer name, and, within it, all of the files you've backed up. 

## Step 3: Restore Your Files
Once you've received your new computer, it's time to restore your files!

Here's how:

### Restoring from an External Storage Backup

:::warning
Please follow the instructions below. *Do not* do the default Time Machine restore because that can mess up ASC-specific configurations for your new Mac.
:::

1.  <Highlight color="#402B6F">If your new computer is a MacBook</Highlight>, connect it to a charger for the duration of this process.
2. Plug the external HD with your Time Machine backup into your <Highlight color="#402B6F">new</Highlight> Mac.
3. Open **Migration Assistant** on your Mac by typing *Migration Assistant* into the **Spotlight** search text box.
4. When asked how you want to transfer your information, click the following option: **From a Mac, Time Machine backup or Startup disk**. Then click **Continue**.
5. Select your Time Machine backup then click **Continue**.
6. Choose the latest backup then click **Continue**.
7. In the next window, <Highlight color="#402B6F">only</Highlight> select your user folder. <Highlight color="#402B6F">DO NOT</Highlight> select the other options.
8. Select **Replace** when asked what you want to do with the user profile from the old computer.
9. If asked to input an administrator password to transfer your user account, type in *your current network password*.
10. Click **Continue** to start the transfer. Depending on how much data you have, file restoration may take a while.
11. Once the Migration Assistant process is finished, you may be prompted to restart your computer. Do so. 
12. Once the computer has restarted, log in using *your username and current password*. 
13. Your files have been restored.
### Restoring from a Google Drive Cloud Backup
1. Sign into your new computer. 
2. Using *your ASC credentials*, sign into **Google Drive**. 
3. Navigate to the **Computers** folder on the left side of the screen. 
4. Click the three dots on the folder entitled your old computer name. Select **Download** within the menu that appears.
5. Wait while the ZIP file downloads. Once the ZIP file has been downloaded, double-click it. The ZIP file will automatically extract its contents.
7. Copy and paste the files into their appropriate folder(s) on your computer. 