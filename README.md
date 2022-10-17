## gBanker background-services
### Two type background Service
Tab Collection
Daily Process
### To run a background service do followings
copy service-apps directory in you target OS environment (eg. Ubuntu Server)
copy all files within services directory to /etc/systemd/system
execute following commands sudo systemctrl enable name_of_service.service sudo systemctrl start name_of_service.service
### To write new service for new vendor
make copy of any file from sevices directory
change necessary file path for necessary .jar file to execute service for the particular service-app
execute following commands sudo systemctrl enable name_of_service.service sudo systemctrl start name_of_service.service
### To compile source
Required minimum JDK 1.8
Intelij Community Edition (It will setup Maven automatically with IDE)
Open tab-collection or daily-process project
After Opening Project need to Build using maven command
From Inetlij IDE right pannel called maven use clean command from lifecycle group
Then Run install from lifecycle group under maven pannel
with target directory under project root direct new jar will be available.
