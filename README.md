# Automated-Recon
```bash        
______                         
| ___ \                      
| |_/ /___  ___ ___  _ __    
|    // _ \/ __/ _ \|  _ \  
| |\ \  __/ (_| (_) | | | | 
\_| \_\___|\___\___/|_| |_| Ranger Automated Recon

```
This script is an attempt at automating some of the first steps for bug bounty hunting.

To use this tool , create a directory for all your targets in the following format. The roots file will contain your chosen subdomains.
```bash

│   ├── Hackerone
│   │   ├── roots.txt 
│   ├── Bugcrowd
│   │   ├── roots.txt
│   ├── Intigriti
│   │   ├── roots.txt 
```
Recon script will create folders in the same location as roots with the output results. 

Ensure you can execute the script 


```bash
chmod +x scanner.sh
```
