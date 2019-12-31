#updated info for blacklists and regex (30 December 2019)
#Current Blacklists

	https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts	
	https://mirror1.malwaredomains.com/files/justdomains	
	http://sysctl.org/cameleon/hosts	
	https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt	
	https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt	
	https://hosts-file.net/ad_servers.txt	
	https://zeustracker.abuse.ch/blocklist.php?download=domainblocklist	
	https://hosts-file.net/grm.txt	
	https://reddestdream.github.io/Projects/MinimalHosts/etc/MinimalHostsBlocker/minimalhosts	
	https://raw.githubusercontent.com/StevenBlack/hosts/master/data/KADhosts/hosts	
	https://raw.githubusercontent.com/StevenBlack/hosts/master/data/add.Spam/hosts	
	https://adaway.org/hosts.txt	
	https://raw.githubusercontent.com/anudeepND/blacklist/master/adservers.txt	
	https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts;showintro=0	
	https://raw.githubusercontent.com/StevenBlack/hosts/master/data/UncheckyAds/hosts	
	https://github.com/crazy-max/WindowsSpyBlocker/blob/master/data/hosts/spy.txt	
	https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt	
	https://raw.githubusercontent.com/StevenBlack/hosts/master/data/add.2o7Net/hosts	
	https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt	
	https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt	
	https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt	
	https://s3.amazonaws.com/lists.disconnect.me/simple_malvertising.txt	
	https://hosts-file.net/exp.txt	
	https://hosts-file.net/emd.txt	
	https://hosts-file.net/psh.txt	
	https://mirror.cedia.org.ec/malwaredomains/immortal_domains.txt	
	https://bitbucket.org/ethanr/dns-blacklists/raw/8575c9f96e5b4a1308f2f12394abd86d0927a4a0/bad_lists/Mandiant_APT1_Report_Appendix_D.txt	
	https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-malware.txt	
	https://ransomwaretracker.abuse.ch/downloads/RW_DOMBL.txt	
	https://ransomwaretracker.abuse.ch/downloads/CW_C2_DOMBL.txt	
	https://ransomwaretracker.abuse.ch/downloads/LY_C2_DOMBL.txt	
	https://ransomwaretracker.abuse.ch/downloads/TC_C2_DOMBL.txt	
	https://raw.githubusercontent.com/StevenBlack/hosts/master/data/add.Risk/hosts	
	https://zerodot1.gitlab.io/CoinBlockerLists/hosts




#REGEX Entries:

^(.+[-_.])??adse?rv(er?|ice)?s?[0-9]*[-.]
^(.+[-_.])??m?ad[sxv]?[0-9]*[-_.]
^(.+[-_.])??telemetry[-.]
^(.+[-_.])??xn--
^adim(age|g)s?[0-9]*[-_.]
^adtrack(er|ing)?[0-9]*[-.]
^advert(s|is(ing|ements?))?[0-9]*[-_.]
^aff(iliat(es?|ion))?[-.]
^analytics?[-.]
^banners?[-.]
^beacons?[0-9]*[-.]
^count(ers?)?[0-9]*[-.]
^pixels?[-.]
^stat(s|istics)?[0-9]*[-.]
^track(ers?|ing)?[0-9]*[-.]
^traff(ic)?[-.]


#Current Whitelist:

ads-e-darwin.hulustream.com
api.facebook.com
apicache.vudu.com
clients1.google.com
graph.facebook.com
netflix.com
nrdp.nccp.netflix.com
s.click.aliexpress.com
us.lgtvsdp.com
