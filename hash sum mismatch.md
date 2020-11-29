# Hash sum mismatch
The issue caused by windows hypervisor platform to solve this issue you have to turn off the hypervisor platform, if you do that thenyou cant run windows subsystem Linux, to make both of them work you need to do the following steps in terminal.
### run bash as sudo(admin)
```
$sudo bash
```
### make a gcrypt dir in etc(config)
```
$mkdir /etc/gcrypt
```
### denying opt
Since apt use sha256 strategy from libgcrypto20, yet upgraded excessively.
using configuration file /etc/gcrypt/hwf.deny
```
$echo all >> /etc/gcrypt/hwf.deny
```
### now try to update using below command:
```
$sudo apt-get update
```
