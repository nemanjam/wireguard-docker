# Wireguard Docker setup

### Tutorials

- Create your own VPN server with WireGuard in Docker - The Digital Life [Youtube](https://www.youtube.com/watch?v=GZRTnP4lyuo), [Github](https://github.com/xcad2k/videos/tree/main/wireguard-docker)
- How to add/install Wireguard on Oracle Cloud to create your own VPN - Sauber-Lab UK [Youtube](https://www.youtube.com/watch?v=ocsVUGjVSpI)
- Run WireGuard VPN Server in Docker Container with Docker Compose [tutorial](https://techviewleo.com/run-wireguard-server-in-docker-container)
- get public IP command [stackexchange](https://unix.stackexchange.com/questions/22615/how-can-i-get-my-external-ip-address-in-a-shell-script)


```bash
# ~/.bashrc

# export server public IP v4
export MY_PUBLIC_SERVER_IP_V4=$(dig @resolver4.opendns.com myip.opendns.com +short)
```



