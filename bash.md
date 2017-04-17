Changing wpa password for wifi: `sudo nano /etc/wpa_supplicant/wpa_supplicant.conf`

Scan for wifi networks: `sudo iwlist wlan0 scan`

### BLUETOOTH
`sudo apt-get install bluetooth` Install BlueZ stack

`service bluetooth status` Check if bluetooth service is running

`sudo hciconfig hci0 up` Run bluetooth interface

`sudo hciconfig hci0 down` Stop bluetooth interface

`sudo hcitool lescan` scan for BLE devices
