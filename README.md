# Solutions
Solution for some errors
Just type folowing command:
sudo modprobe ath10k_pci
#if it will get unloaded after restart:
check modules configuration:
cd /etc/lib/modules/
ls
#look wlan confifuration file,for example:
my file is ath10k_pci.conf
check the configuration:
type in the file by following:
sudo nano ath10k_pci.conf
#type 
options ath10k_pci
save it.
then looking for any ath10k_pci blacklist file ,if it exists
remove it by type the command:
sudo rm ath10k_pciblacklist
##In this my module is ath10k_pci, follow this steps with your wlan module


