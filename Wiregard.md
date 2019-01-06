# Something about Wireguard and indtallation Wireguad in ubuntu, usage in client.

## Office Site of Wireguard

https://www.wireguard.com

## Onekey installation of wiregurad in ubuntu. 

https://github.com/atrandys/wireguard


## Generate server and client private、public keys:

   > wg genkey | tee sprivatekey | wg pubkey > spublickey
   
   > wg genkey | tee cprivatekey | wg pubkey > cpublickey
   
## Some files in /etc/wirguard, client.conf and key files.

configuration files: wg0.conf    client.conf

> wg-quick up wg0

> wg-quick down wg0

> wg  ## show wg

----------


