# COMMAND INSTALL
# SUPPORT : DEBIAN 10 , 11 & UBUNTU 20
#
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/freedomX7/v5/main/anime.sh && chmod +x anime.sh && sed -i -e 's/\r$//' anime.sh && screen -S anime ./anime.sh</code></pre>