# LinuxScanIP
## Scan your used ip addresses of your organization 

* This tool build to display all used ip addresses in your home or your organization
* The tool find inet and netmask address and send ping to all of ip's and print them if there are used
* All of used ip's will be written in log text file

## Required

* Linux OS (tried in ubuntu 20.04)
* Net-tools installed for "ifconfig" command

## Code Explanation

### Get Inet Line
Run "ifconfig" command to find the line that inlcudes inet and netmask address  
Function Definition:
```python
def get_inet_line():
```

### Get Inet Address
``sdsa``
Use `get_inet_line()` function to search inet address between the word `inet` and `netmask`
```python
def get_inet_address():
```
