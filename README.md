# MULTIPORT - WEBSOCKET / SSH / SSL / XRAY

![Screenshot 2022-09-13 183821](https://user-images.githubusercontent.com/89133643/189892111-b68076e6-0971-4f28-ae7c-5951554953dd.jpg)

# SCRIPT
<pre><code>apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/SSHSEDANG4/multiws/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh</code></pre>

# TESTED ON OS 
- DEBIAN 10

# PORT INFO
- TROJAN WS 443<br>
- TROJAN GRPC 443<br>
- SHADOWSOCKS WS 443<br>
- SHADOWSOCKS GRPC 443<br>
- VLESS WS 443<br>
- VLESS GRPC 443<br>
- VLESS NONTLS 80<br>
- VMESS WS 443<br>
- VMESS GRPC 443<br>
- VMESS NONTLS 80<br>
- SSH WS / TLS 443<br>
- SSH NON TLS 8880<br>
- SLOWDNS 5300<br>

# SETTING CLOUDFLARE 
- SSL/TLS : FULL<br>
- SSL/TLS Recommender : OFF<br>
- GRPC : ON<br>
- WEBSOCKET : ON<br>
- Always Use HTTPS : OFF<br>
- UNDER ATTACK MODE : 0FF<br>

# NOT WORKING FOR VPS SIMILAR 
- IDCLOUDHOST

# REQUEST ACCESS 
- https://t.me/sshsedang
