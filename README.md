## dom-red
Small script to check a list of domains against open redirect vulnerability.

## Install
```basic
$ git clone https://github.com/Naategh/dom-red.git
$ cd dom-red && pip install -r requirements.txt
$ python dom-red.py -h

________                       ________     _________
___  __ \____________ ___      ___  __ \__________  /
__  / / /  __ \_  __ `__ \     __  /_/ /  _ \  __  / 
_  /_/ // /_/ /  / / / / /     _  _, _//  __/ /_/ /  
/_____/ \____//_/ /_/ /_/      /_/ |_| \___/\__,_/   
                
                Author :: Naategh                                                     

usage: dom-red.py [-h] -d DOMAIN -p PAYLOAD [-i] [-v]

optional arguments:
  -h, --help            show this help message and exit
  -d DOMAIN, --domain DOMAIN
                        Path of domains list
  -p PAYLOAD, --payload PAYLOAD
                        Path of payloads list
  -i, --include         Include a slash at end of URLs
  -v, --verbose         Show more results
```

## Features
- Include a slash at end of URLs to avoid some errors
- Verbose output

## Examples
```powershell 
$ python dom-red.py -d /root/domains.txt -p /root/payloads.list -i
$ python dom-red.py -d /root/domains.txt -p /root/payloads.txt -v -i
```

## How it can be useful?
- https://hackerone.com/reports/692154
- https://hackerone.com/reports/469803

## Contact
- Email: manamtabeshekan@gmail.com
- Telegram: [@Naategh](http://t.me/Naategh)
- Twitter: [@Naategh_](https://twitter.com/Naategh_)
