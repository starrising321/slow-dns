# SLOW-DNS By STAR_JANI ( ENGLISH )

* SLOWDNS SCRIPT



THIS IS A SCRIPT FOR AUTO INSTALLATION OF SLOWDNS (DNSTT SERVER) WITH:

-SSH
-SSL
-DROPBEAR


**DNSTT Script**

## :heavy_exclamation_mark: Requirements

* A Linux-based operating system (Ubuntu) 
* Ubuntu 20.04 Server x86_64 / 18.04 Server x86_64
* Version 8.5 Preffered Ubuntu 20.04 Server x86_64
* It is recommended to use a new or formatted distro

# Installation
```
rm -rf install; apt update; wget https://github.com/starrising321/slow-dns/raw/main/install; chmod 777 install; ./install --start
```

# After Installation Command

```
iptables -I INPUT -p udp --dport 5300 -j ACCEPT

iptables -t nat -I PREROUTING -p udp --dport 53 -j REDIRECT --to-ports 5300

lsof -i :5300
```

## :octocat: Translated and Modded by STAR_JANI
<!DOCTYPE html>
<html>
<body>
   <center>
      <h2>Telegram 👇🗿</h2>
      <a href="https://t.me/Star_Jani"><img src="https://icon-library.com/images/telegram-icon-png/telegram-icon-png-7.jpg" alt="Tutorialspoint" style="width:50px;height:60px;"></a>
   </center>
</body>
</html>
 

## :octocat: Credits

1. [@LaelsonCG )
