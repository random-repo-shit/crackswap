# crackswap
# This works with most debian and ubuntu releases which improperly assign swap values
# Putting your /usr/bin down with the set :fire: {if ram=$# then + swap(*x)}
# 100% more :fire: in your Ghz. 
##
``` sudo wget -O /usr/bin/crackswap https://raw.githubusercontent.com/diveyez/crackswap/master/crackswap ```
##
``` sudo chmod +x /usr/bin/crackswap ```
##
``` sudo sed -i '/exit 0/c\/usr/bin/crackswap &\nexit 0' /etc/rc.local ```
