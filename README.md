# GeoIP Redirection & Locker

### Howto Install: 
Download the "Ready to paste" package from your customer's area, unzip it
and upload the all files in 'app/code/Webiators/GeoIpRedirection' folder to your Magento install
dir.
### Update the Database: 
Move to Magento Root directory with CLI and use below commands
• php bin/magento setup:upgrade
• php bin/magento cache:flush
• php bin/magento setup:static-content:deploy
### HowtoUse:
GotoStore->Configuration->Webiators->GeoIP Enable
GeoIp Lock if you want to avoid visitors from selected countries.
Enable Geo IP Redirection If you want to redirect Visitors to specific country’ Store
NOTE FOR REDIRECTION: if you want the redirection to work you have to Make you
Store View Code as Country code.
Example: For United State of America Store code will be US
 For India Store code will be IN
