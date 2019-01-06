# Proxy is a high performance  proxy server implemented by golang.

https://github.com/snail007/goproxy

Proxy is a high performance HTTP, HTTPS, HTTPS, websocket, TCP, UDP, Socks5, ss proxy server implemented by golang. It supports parent proxy,nat forward,TCP/UDP port forwarding, SSH transfer, TLS encrypted transmission, protocol conversion. you can expose a local server behind a NAT or firewall to the internet, secure DNS proxy.  

## Chinese Manual

https://github.com/snail007/goproxy/blob/master/README_ZH.md

## Download

https://github.com/snail007/goproxy/releases

## Fast Start



## VPS's .bashrc add this line for GoProxy:

> alias goproxy='proxy http -t tls -p ":443" -C /etc/proxy/proxy.crt -K /etc/proxy/proxy.key --forever --log /etc/proxy/proxy.log --daemon'

