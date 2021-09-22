# Nmap

```bash
map -A -sV -sC -T4 $ipaddr -oA nmap.${ipaddr} 
map -A -sV -sC -T4 -p- $ipaddr -oA nmap.${ipaddr} 
```
