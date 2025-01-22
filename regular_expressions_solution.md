**Exercise 1**

kutayyalciner@Kutays-MacBook-Air ~ % ls ~ | grep '^[A-Z]'
Applications
Desktop
Documents
Downloads
Library
Movies
Music
Pictures
PlayOnMac's virtual drives
Postman
Public

**Exercise 2**
kutayyalciner@Kutays-MacBook-Air ~ % ls -A ~ | grep '^\.'
.CFUserTextEncoding
.DS_Store
.Trash
.android
.anydesk
.boto
.cache
.cocoapods
.config
.continue
.dart
.dart-tool
.dartServer
.emulator_console_auth_token
.flutter
.flutter-devtools
.gem
.gitconfig
.gradle
.local
.npm
.npmrc
.nvm
.pub-cache
.swiftpm
.viminfo
.vscode
.zcompdump
.zhprofile
.zprofile
.zprofile.save
.zsh_history
.zsh_sessions
.zshrc
.zshrc.backup

**Exercise 3**

kutayyalciner@Kutays-MacBook-Air ~ % ls -A ~ | grep '^\. ' | wc -l

       0
       
**Exercise 4**

kutayyalciner@Kutays-MacBook-Air ~ % ls ~ | grep '^[a-zA-Z]*$'
Applications
Desktop
Documents
Downloads
Library
Movies
Music
Pictures
Postman
Public

**Exercise 5**

kutayyalciner@Kutays-MacBook-Air ~ % ls ~ | grep -v '[A-Z]'
folder_list.txt
kutay.txt
neurodiverse-education
yalciner.txt

**Exercise 6**
kutayyalciner@Kutays-MacBook-Air ~ % ls ~ | grep -v '\.[a-zA-Z]\{3\}$'
Applications
Desktop
Documents
Downloads
Library
Movies
Music
Pictures
PlayOnMac's virtual drives
Postman
Public
neurodiverse-education

**Exercise 7**
kutayyalciner@Kutays-MacBook-Air ~ % ls /etc | grep '^c.*y$'

**Exercise 8**
kutayyalciner@Kutays-MacBook-Air ~ % ls /etc | grep 'ss'

master.passwd
passwd
ssh
ssl

**Exercise 9**
grep '^.\{1\}[A-Z].\{1\}[A-Z].\{1\}e$'

**Exercise 10**
ls ~ | grep '^[a-zA-Z0-9]\{4\}$'

**Exercise 11**
kutayyalciner@Kutays-MacBook-Air ~ % ls /var/log | grep '\.log$'
alf.log
fsck_apfs.log
fsck_apfs_error.log
fsck_hfs.log
install.log
shutdown_monitor.log
system.log
wifi.log


