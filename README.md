# ghno
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
[![python](https://img.shields.io/badge/python-2.7-blue.svg)](https://www.python.org/downloads/)
[![GitHub version](https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=6.0.1&v=6.0.1&x2=0)](http://badge.fury.io/gh/boennemann%2Fbadges)
[![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)

**A cross-platform python based utility for information gathering and penetration automation!**
### Output

### Requirements

- Python (2.7.*)
- Python `pip`
- Python module `requests`
- Python module `colorama`
- Python module `dnspython`
- Python module `lxml`
- Python module `bs4`

### Install modules

	pip install -r requirements.txt
	
### Tested on

- Windows 7/8/8.1
- Kali linux (2017.2)	
### Updates

- Changed The Whole Script Into Python (Previously It Was Written In PHP)
- Exceptions Covered for both User Interrupting && Internel Issues!
- Removed NetCraft Module as We need to use selinium and phantomJS for it (Ultimately making script slow!)
- Changed the Problem Of Responce Code Of '200' for most sites in Admin Panel Finder Module && Shell Finder Module


### Change-log

- Added New Features For Reverse IP (Via HackerTarget && YouGetSignal)
- Added New Features For Crawling (Via Google, Bing && Manually With My Hands ;) 
- Added New Method For Subdomains Scanning! (Takes Some Time Though :p)


### Usage

***Initializing Script***

	python ghno.py
	

### Advanced Usage

<pre><code>
Author: theviperxxsy

Usage: python ghno.py
A cross-platform python based utility for information gathering and penetration automation!

Options:

 1). Cloudflare Bypass. 
 2). Website Crawler.
  	 |____ Google Based Crawling
 	 |____ Bing Based Crawling
 	 |____ Manually Crawling
 3). Reverse IP.
  	 |____ YouGetSignal Based
 	 |____ HackerTarget's API Based
 4). Information Gathering.
  	 |____ Whois Lookup
 	 |____ BrowserSpy Report
 5). Nameservers.
 6). WebSite Speed.
 7). Subdomains Scanner
 8). Shell Finder.
 9). Admin Panel Finder.
 10). Grab Banner.
 11). All Things.
  
  Example:
	python ghno.py
</code></pre>