# WiFi workaround for Droidian
By @Eugenio

Download [enable-ipa.service](https://raw.githubusercontent.com/droidian-perseus/enable-ipa/master/enable-ipa.service)\
Open terminal and type below command:
> sudo -s\
> cp enable-ipa.service /etc/systemd/system/enable-ipa.service\
> systemctl enable enable-ipa\
> reboot -f
