**Exercise 1**

kutayyalciner@Kutays-MacBook-Air ~ % cd ~
kutayyalciner@Kutays-MacBook-Air ~ % ls -l
total 0
drwxr-xr-x@   8 kutayyalciner  staff   256 Dec 26 21:04 Applications
drwx------@  20 kutayyalciner  staff   640 Dec 31 08:04 Desktop
drwx------+   6 kutayyalciner  staff   192 Nov 17 21:57 Documents
drwx------+  74 kutayyalciner  staff  2368 Jan 22 13:15 Downloads
drwx------@ 106 kutayyalciner  staff  3392 Jan 22 12:18 Library
drwx------    8 kutayyalciner  staff   256 Nov 24 10:21 Movies
drwx------+   5 kutayyalciner  staff   160 Nov 17 22:14 Music
drwx------+   6 kutayyalciner  staff   192 Nov 17 22:14 Pictures
lrwxr-xr-x@   1 kutayyalciner  staff    51 Oct  3 08:57 PlayOnMac's virtual drives -> /Users/kutayyalciner/Library/PlayOnMac//wineprefix/
drwxr-xr-x@   3 kutayyalciner  staff    96 Sep 20 20:12 Postman
drwxr-xr-x+   4 kutayyalciner  staff   128 Dec 21  2023 Public
drwxr-xr-x   23 kutayyalciner  staff   736 Nov 23 18:52 neurodiverse-education

**Exercise 2**

kutayyalciner@Kutays-MacBook-Air ~ % sudo du -h /var/log/* | sort -h
Password:
  0B	/var/log/CoreDuet
  0B	/var/log/PrivacyPreservingMeasurement
  0B	/var/log/alf.log
  0B	/var/log/apache2
  0B	/var/log/com.apple.wifivelocity
  0B	/var/log/cups
  0B	/var/log/dm
  0B	/var/log/fsck_apfs_error.log
  0B	/var/log/mDNSResponder
  0B	/var/log/ppp
  0B	/var/log/uucp
4.0K	/var/log/shutdown_monitor.log
4.0K	/var/log/system.log.0.gz
4.0K	/var/log/system.log.1.gz
4.0K	/var/log/system.log.2.gz
4.0K	/var/log/system.log.3.gz
4.0K	/var/log/system.log.4.gz
4.0K	/var/log/system.log.5.gz
4.0K	/var/log/system.log.6.gz
4.0K	/var/log/wifi.log.1.bz2
4.0K	/var/log/wifi.log.4.bz2
4.0K	/var/log/wifi.log.6.bz2
8.0K	/var/log/system.log
 28K	/var/log/fsck_hfs.log
 36K	/var/log/asl/Logs
 52K	/var/log/fsck_apfs.log
 56K	/var/log/wifi.log.0.bz2
 56K	/var/log/wifi.log.2.bz2
 56K	/var/log/wifi.log.7.bz2
 64K	/var/log/wifi.log.5.bz2
 76K	/var/log/wifi.log.3.bz2
 92K	/var/log/wifi.log.10.bz2
 92K	/var/log/wifi.log.9.bz2
116K	/var/log/wifi.log.8.bz2
248K	/var/log/asl
644K	/var/log/wifi.log
1.1M	/var/log/DiagnosticMessages
 18M	/var/log/com.apple.xpc.launchd
 20M	/var/log/install.log
 20M	/var/log/powermanagement

**Exercise 3**

kutayyalciner@Kutays-MacBook-Air ~ % nano kutay.txt
kutayyalciner@Kutays-MacBook-Air ~ % cat kutay.txt 
Kutay

**Exercise 4**

kutayyalciner@Kutays-MacBook-Air ~ % echo "yalciner" > yalciner.txt
kutayyalciner@Kutays-MacBook-Air ~ % cat yalciner.txt
yalciner

**Exercise 5**
kutayyalciner@Kutays-MacBook-Air ~ % cat kutay.txt yalciner.txt
Kutay
yalciner

**Exercise 6**
kutayyalciner@Kutays-MacBook-Air ~ % cat yalciner.txt >> kutay.txt             
kutayyalciner@Kutays-MacBook-Air ~ % cat kutay.txt    
Kutay
yalciner

**Exercise 7**
kutayyalciner@Kutays-MacBook-Air ~ % ls -d ~/*/ > folder_list.txt
kutayyalciner@Kutays-MacBook-Air ~ % cat folder_list.txt
/Users/kutayyalciner/Applications/
/Users/kutayyalciner/Desktop/
/Users/kutayyalciner/Documents/
/Users/kutayyalciner/Downloads/
/Users/kutayyalciner/Library/
/Users/kutayyalciner/Movies/
/Users/kutayyalciner/Music/
/Users/kutayyalciner/Pictures/
/Users/kutayyalciner/PlayOnMac's virtual drives/
/Users/kutayyalciner/Postman/
/Users/kutayyalciner/Public/
/Users/kutayyalciner/neurodiverse-education/







