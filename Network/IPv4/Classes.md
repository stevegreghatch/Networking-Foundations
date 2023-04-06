
### Class A
* Large Network Size

| Subnet Mask | CIDR | IP Range                  | Private IP Range (RFC 1918) | Loopback Range (Local Host) | Standard Loopback Address | Available Hosts |
| ----------- | ---- | ------------------------- | --------------------------- | --------------------------- | ------------------------- | --------------- |
| 255.0.0.0   | /8   | 1.0.0.0 - 127.255.255.255 | 10.0.0.0 - 10.255.255.255   | 127.0.0.0 - 127.255.255.255 | 127.0.0.1                 | 16,777,216      |


### Class B
* Medium Network Size

| Subnet Mask | CIDR | IP Range                    | Private IP Range (RFC 1918) | APIPA IP Range                | Available Hosts |
| ----------- | ---- | --------------------------- | --------------------------- | ----------------------------  | --------------- |
| 255.255.0.0 | /16  | 128.0.0.0 - 191.255.255.255 | 172.16.0.0 - 172.31.255.255 | 169.254.0.0 - 169.254.255.255 | 65,536          |    
 
### Class C
* Small Network Size (smaller businesses and home users)

| Subnet Mask   | CIDR | IP Range                    | Private IP Range (RFC 1918)   | Available Hosts |
| -----------   | ---- | --------------------------- | ----------------------------- | --------------- |
| 255.255.255.0 | /24  | 192.0.0.0 - 223.255.255.255 | 192.168.0.0 - 192.168.255.255 |      256        |

### Class D
* Used as a multicast IP addressing solution
* Can not be assigned to a network device or a host on the network
* Only one-to-many

| Subnet Mask     | CIDR | IP Range                     |
| --------------  | ---- | ---------------------------- |
| 255.255.255.255 | /32  | 224.0.0.0 to 239.255.255.255 |

### Class E
* Not used in a production environment
* Reserved for future use

| IP Range                     |
| ---------------------------- | 
| 240.0.0.0 - 255.255.255.255 | 
