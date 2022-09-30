## Installing

**With pip**
```bash
pip install spower
```

**With manual**
```

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
