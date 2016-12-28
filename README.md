# Ad-block - Block unwanted URLS keep internet safe
ABP, Ghostry etc extension consume CPU and memory which might result in low performance.
Also few websites detect such extensions and can use alternate methods to show ads.
Block all ads by replacing hosts file.
Easiest way to block ads :) No app or proxy required.

Total entries Unified hosts + fakenews + gambling + porn # 92345+  

Extending and consolidating hosts files from a variety of sources like adaway.org, mvps.org, malwaredomainlist.com, someonewhocares.org, yoyo.org, and potentially others. You can optionally invoke extensions to block additional sites by category. 

Last updated : #December 28 2016.

## Sources of hosts data unified in this variant

Updated `hosts` files from the following locations are always unified and 
included:

Host file source | Description | Home page | Raw hosts | Update frequency 
-----------------|-------------|:---------:|:---------:|:-------:
AdAway | AdAway is an open source ad blocker for Android using the hosts file. |[link](https://adaway.org/) | [raw](https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt) | occasionally 
add.2o7Net | 2o7Net tracking sites based on http://www.hostsfile.org/hosts.html content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts) | occasionally 
add.Dead | Dead sites based on http://www.hostsfile.org/hosts.html content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Dead/hosts) | occasionally 
add.Risk | Risk content sites based on http://www.hostsfile.org/hosts.html content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts) | occasionally 
add.Spam | Spam sites based on http://www.hostsfile.org/hosts.html content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts) | occasionally 
KADhosts | Fraud/adware/scam websites. |[link](https://github.com/azet12/KADhosts) | [raw](https://raw.githubusercontent.com/azet12/KADhosts/master/KADhosts.txt) | frequently 
Malware Domain List | Malware Domain List is a non-commercial community project. |[link](http://www.malwaredomainlist.com/) | [raw](https://www.malwaredomainlist.com/hostslist/hosts.txt) | weekly 
MVPS hosts file | The purpose of this site is to provide the user with a high quality custom HOSTS file. |[link](http://winhelp2002.mvps.org/) | [raw](http://winhelp2002.mvps.org/hosts.txt) | monthly 
Dan Pollock – someonewhocares.org | How to make the internet not suck (as much). |[link](http://someonewhocares.org/hosts/) | [raw](http://someonewhocares.org/hosts/zero/hosts) | frequently 
SpotifyAds | Spotify ads sources sites based on https://github.com/Xeroday/Spotify-Ad-Blocker content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/SpotifyAds/hosts) | occasionally 
Steven Black's ad-hoc list | Additional sketch domains as I come across them. |[link](https://github.com/StevenBlack/hosts/blob/master/data/StevenBlack/hosts) | [raw](https://raw.githubusercontent.com/StevenBlack/hosts/master/data/StevenBlack/hosts) | occasionally 
tyzbit | Microsoft tracking domains.  A fork of this repo providing additional data. |[link](https://github.com/tyzbit/hosts/blob/master/data/tyzbit/hosts) | [raw](https://raw.githubusercontent.com/tyzbit/hosts/master/data/tyzbit/hosts) | rarely 
UncheckyAds | Windows installers ads sources sites based on https://unchecky.com/ content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts) | occasionally 
WindowsSpyBlocker::SPY:WIN10 | Set of rules to block Windows spy/telemetry via hosts.SPY rules for WIN10 |[link](https://github.com/crazy-max/WindowsSpyBlocker) | [raw](https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/win10/spy.txt) | frequently 
WindowsSpyBlocker::SPY:WIN81 | Set of rules to block Windows spy/telemetry via hosts.SPY rules for WIN81 |[link](https://github.com/crazy-max/WindowsSpyBlocker) | [raw](https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/win81/spy.txt) | frequently 
yoyo.org | Blocking with ad server and tracking server hostnames. |[link](https://pgl.yoyo.org/adservers/) | [raw](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&mimetype=plaintext&useip=0.0.0.0) | frequently 
Fake News | An in-progress collection of fake news outlets. |[link](https://github.com/marktron/fakenews) | [raw](https://raw.githubusercontent.com/marktron/fakenews/master/fakenews) | occasional 
Sinfonietta's gambling blocking hosts file | A collection of category-specific host files. |[link](https://github.com/Sinfonietta/hostfiles) | [raw](https://raw.githubusercontent.com/Sinfonietta/hostfiles/master/gambling-hosts) | occasional 
pornhosts -- a consolidated anti porn hosts file | This is an endeavour to find all porn domains and compile them into a single hosts to allow for easy blocking of porn on your local machine or on a network. |[link](https://github.com/Clefspeare13/pornhosts) | [raw](https://raw.githubusercontent.com/Clefspeare13/pornhosts/master/0.0.0.0/hosts) | occasional 
Sinfonietta's porn blocking hosts file | A collection of category-specific host files. |[link](https://github.com/Sinfonietta/hostfiles) | [raw](https://raw.githubusercontent.com/Sinfonietta/hostfiles/master/pornography-hosts) | occasional 
Sinfonietta's social media blocking hosts file | A collection of category-specific host files. |[link](https://github.com/Sinfonietta/hostfiles) | [raw](https://raw.githubusercontent.com/Sinfonietta/hostfiles/master/social-hosts) | occasional 


# Steps
1. Find the hosts file - root/etc/hosts
2. Replace your hosts file with above hosts file

# Found a Phishing website or link ?
Open issue. OR Follow the convention provided below to add the link.
Block malicious links or website. One step to safe internet.

# How to contribute ?
Open a issue OR add urls in the hosts file
you may leave a comment and your name if you wish name (optional)
e.g 

0.0.0.0 www.annoyinglinksads.com ##[ScamFraudAlert] Submitted by abc

                   OR

0.0.0.0 www.annoyinglinksads.com ##[Misleading url]  
