# Proxy is a high performance  proxy server implemented by golang.

Proxy is a high performance HTTP, HTTPS, HTTPS, websocket, TCP, UDP, Socks5, ss proxy server implemented by golang. It supports parent proxy,nat forward,TCP/UDP port forwarding, SSH transfer, TLS encrypted transmission, protocol conversion. you can expose a local server behind a NAT or firewall to the internet, secure DNS proxy.  

## Office site

https://github.com/snail007/goproxy

## Chinese Manual

https://github.com/snail007/goproxy/blob/master/README_ZH.md

## Download

https://github.com/snail007/goproxy/releases

## Fast Start

### Automate installation in VPS with Linux64:

> curl -L https://raw.githubusercontent.com/snail007/goproxy/master/install_auto.sh | bash  

### Manual installation 

> cd /root/proxy/  

> wget download-link

### VPS's .bashrc add this line for GoProxy:

> alias goproxy='proxy http -t tls -p ":443" -C /etc/proxy/proxy.crt -K /etc/proxy/proxy.key --forever --log /etc/proxy/proxy.log --daemon'

### macOS command line:

> ./proxy http -t tcp -p ":8080" -T tls -P "1.2.3.4:443" -C proxy.crt -K proxy.key -b blocked.txt -d direct.txt

