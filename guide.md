# Use ventoy boot device and boot into it.

# Initialize the live environ
## Networking 
```bash 
ip addr show 
```

### wifi
```bash
iwctl
device list 
station wlan0 scan 
station wlan0 get-networks 
station wlan0 connect SSID 
ip addr show 
ping -c 5 www.archlinux.org
```
```
