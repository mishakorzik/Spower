<img width="99.9%" src="https://raw.githubusercontent.com/mishakorzik/Spower/main/export202209301252058087.png"/>

<p align="center">
<a href="https://github.com/mishakorzik/IpHack"><img title="Version" src="https://img.shields.io/badge/Build-done-darkgreen?style=for-the-badge&logo="></a>
<a href="https://github.com/mishakorzik/IpHack/blob/main/LICENSE"><img title="License" src="https://img.shields.io/badge/Apache-License 2.0-green?style=for-the-badge&logo=apache"></a>
<a href=""><img title="Python" src="https://img.shields.io/badge/Made in-Ukraine-green?style=for-the-badge&logo=None"></a>
<a href="https://github.com/mishakorzik"><img title="Report" src="https://img.shields.io/badge/Copyring-2022-lightgreen?style=for-the-badge&logo=github"></a>
<a href="https://github.com/mishakorzik"><img title="Autor" src="https://img.shields.io/badge/Author-mishakorzik-lightgreen?style=for-the-badge&logo=github"></a>

## Installing

**With pip**
```bash
pip install spower
```

**With manual**
```bash
pip install googlesearcher
pip install shodan
pip install urllib3
wget --no-check-certificate "https://raw.githubusercontent.com/mishakorzik/Spower/main/install.sh"
bash install.sh
```

- [x] Easy to use
- [x] Fuctional search
- [x] more results +75
- [x] Fast result
- [x] no API keys are required
- [x] does not take up much memory
- [ ] Support Bing, Yandex search

## Usage

**easy search using this library**
```python

#Search with Google
>>> from spower import *
>>> search.google("mishakorzik")
['https://github.com/mishakorzik', 'https://github.com/mishakorzik/AllHackingTools', ...
>>>

#Search with DuckDuckGo
>>> from spower import *
>>> search.duckduckgo("mishakorzik")
'["https://github.com/mishakorzik/IpHack", "https://github.com/mishakorzik/virus.bat", ...
>>>

#Search with Shodan
>>> from spower import *
>>> search.shodan("github")
[+] IP        : 192.30.25*.***
[+] Port      : 80
[+] Org       : GitHub, Inc.
[+] Country   : United States
[+] longitude : -77.0****
[+] latitude  : 38.8****
[+] City      : Washington
[+] Layer     : tcp
[+] Domains   : ['github.com']
[+] Hostnames : ['lb-192-30-25*-***-iad.github.com']
>>>

```
