Aptoide-Downloader
==================

Aptoide Downloader lets Linux users download .apk files directly on their computer from Aptoide.com site.
Phone versions requires Busybox and a terminal emulator. Tested only on Galaxy S2.


Usage
===

1. First you need to change the browser User Agent to "AptoideLite/44" on PC. You can search on the web how to do this. You basically need to install a browser extension and add the User Agent there.
2. Go to https://m.aptoide.com/ on PC and search the application you want to download.
3. Copy the link from the URL bar.
4. Make the script executable and run the script with the link as the first argument. The script will download the APK in ~/Downloads or ~ if ~/Downloads folder doesn't exist.

Example
===
How to download Instagram:

1. Download [this extension](https://chrome.google.com/webstore/detail/user-agent-switcher-for-c/djflhoibgkdhkhhcedjiklpkjnoahfmg) for Chrome and add the User Agent.
![alt text](https://github.com/StefanescuCristian/Aptoide-Downloader/raw/master/Annotation%202019-05-02%20214215.png "adding chrome UA")

2. Search for instagram.

3. Copy the link
![alt text](https://github.com/StefanescuCristian/Aptoide-Downloader/raw/master/Annotation%202019-05-02%20214056.png "Copy the Link")

4. ./aptoide http://m.mark8.store.aptoide.com/app/market/com.instagram.android/152750149/45569083/Instagram
![alt text](https://github.com/StefanescuCristian/Aptoide-Downloader/raw/master/Annotation%202019-05-02%20214417.png "example of usage")

PS: A big thanks to the guys that improved this script.
