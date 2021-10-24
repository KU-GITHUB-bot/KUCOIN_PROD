A trial version, which does not require a license, will be released soon!


Hint: Use keepassx (https://www.keepassx.org/) to store all of your password credentials on your local machine
keepassx can be used to generate and save complicated passwords and use them with ease.

Installation / Set-Up

1) Create a new email using Protonmail (https://account.protonmail.com/signup). 
Verifiy Protonmail account using tempMail (https://mytemp.email/ --> Start Here)
2) Use ProtonMail account to create KUCOIN Account (https://www.kucoin.com/ucenter/signup)
3) Login to Account and set trading password (save that PWD in keepassx) and google 2FA. 
Save the password for the google 2FA in keepassx in case your phone gets stolen etc.
4) Create API (activate "Trade" click box). Store all information in keypassx (api-passphrase, api-key, api-secret)
5) Enter your wifi password to your raspberry pi zero
5.1) Connect the micro SD to your computer. Open the file "/media/<userName>/rootfs/etc/wpa_supplicant/wpa_supplicant.conf"
5.2) The mentioned file could be modified using the command line command "sudo nano /media/<userName>/rootfs/etc/wpa_supplicant/wpa_supplicant.conf"
5.3) Enter your wifi information
6) Place the micro SD card back to your piZero and plug it into some usb charger. It will connect to your internet.
7) Connect to your piZero using "ssh pi@raspberry". Password "piZERO123". If there is more than one raspberry pi within your network, you have to find the specific ip of your pi first.
7.1) You can find the ip of your piZero by connecting with your router. Then ssh to your piZero.
8) Once connected via ssh, modify file "gitHUBLink/KUpwd.txt". This can be done using the command
"nano gitHUBLink/KUpwd.txt". 
8.1) Enter the previously saved "api-passphrase", "api-key" and "api-secret" information. You might also add your personal email address (sentTo).


Note: This readMe will be extended and will provide an extensive description of all editable parameters (There are a lot)
