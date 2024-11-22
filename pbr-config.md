常用的ASN
### Google：
```
15159
54113
396982
```
### cloudflare
```
13335
```
### twitter
```
13414
```
### github
```
36459
```


config policy
        option name 'telegram'
        option dest_addr '91.108.56.0/22 91.108.4.0/22 91.108.8.0/22 91.108.16.0/22 91.108.12.0/22 91.108.20.0/22 91.105.192.0/22 149.154.160.0/20 185.76.151.0/24'
        option interface 'vpnclient'
        option dest_port '80 443'

config policy
        option name 'github'
        option dest_addr 'github.com githubusercontent.com githubassets.com'
        option dest_port '443'
        option interface 'vpnclient'

config policy
        option name 'copilot'
        option dest_addr 'copilot.microsoft.com'
        option interface 'vpnclient'

config policy
        option name 'google'
        option dest_addr '142.250.0.0/15 172.217.0.0/16 173.194.0.0/16 74.125.0.0/16 216.239.32.0/19'
        option interface 'vpnclient'

config policy
        option name 'chatgpt'
        option dest_addr '104.18.32.0/24 172.64.155.0/24 172.64.146.0/24 172.64.152.0/24'
        option interface 'vpnclient'
        option dest_port '443'

config policy
        option name 'twitter'
        option dest_addr '209.237.192.0/19 104.244.40.0/21 146.75.0.0/16 151.101.0.0/16'
        option interface 'vpnclient'

config policy
        option name 'tiktok'
        option dest_addr '3.163.125.0/24 23.45.173.0/24 23.72.90.0/24 23.214.170.0/24 23.217.118.0/24 23.219.38.0/24 23.220.75.0/24 23.233.198.0/23 34.36.76.0/24 96.16.55.0/24 146.75.94.0/24 147.160.177.0/21 147.160.190.0/24 173.222.162.0/24 184.28.81.0/24 184.28.146.0/24 103.136.220.0/22 118.26.132.0/24 71.18.0.0/16 130.44.212.0/22 139.177.225.0/20 180.240.234.0/22 192.64.15.0/24 199.103.24.0/22
'
        option interface 'vpnclient'
