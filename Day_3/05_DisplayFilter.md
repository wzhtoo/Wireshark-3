# 05_DisplayFilter

- tcp.port eq 80
- ip.addr == 1923168.1.111
- ip.src == 192.168.1.111 or ip.dst == 10.4.6.11
- ip.src == 192.168.0.0/16 and ip.dst == 192.168.0.0/16
- ip.addr != 192.168.1.111
- ip.src != 192.138.1.111 or ip.dst != 10.43.54.65
- ! (ip.addr == 192.168.1.111)
- smb || dns
- ip.src != xxx.xxx.xxx.xxx && ip.dst != xxx.xxx.xxx.xxx && sip
- sip.To contains "a1762"
