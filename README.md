# crackswap
Also known as zram...
This works with most debian and ubuntu releases which improperly assign swap values
Putting your /usr/bin down with the set :fire: {if ram=$# then + swap(*x)}
100% more :fire: in your Ghz.

##
``` sudo wget -O /usr/bin/zram https://raw.githubusercontent.com/diveyez/crackswap/master/zram ```
##
``` sudo chmod +x /usr/bin/zram ```
##
add add line before exit 0 in /etc/rc.local
```
/usr/bin/zram.sh &
```

## Launch first time
```
sudo /usr/bin/zram
```

### Does not work with all systems 
##
``` sudo sed -i '/exit 0/c\/usr/bin/zram &\nexit 0' /etc/rc.local ```
