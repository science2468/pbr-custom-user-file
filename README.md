# smartdns+pbr+openvpn/wireguard在openwrt上可以如所有通用代理软件那样使用。使用模式就是如黑名单模式，增加需要代理的域名或者ip/cidr，不推荐使用asn，会让asn下的所有IP段全部走代理，但是Akamai公司的IP有的可以在国内访问，例如steam就使用了，全部走代理会让steam走代理，这不是我想要的。所以还是推荐使用配置文件中增加手动增加IP段的方法！

常用的ASN
### Google：
```
15169
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
