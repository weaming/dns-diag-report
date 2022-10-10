# Find Quickest DNS Server

Using tool from https://github.com/farrokhi/dnsdiag: `pip3 install dnsdiag`

```
wget https://public-dns.info/nameserver/hk.txt
dnseval.py --dnssec -t A -f hk.txt -c10 --tcp dl-cdn.alpinelinux.org
```
