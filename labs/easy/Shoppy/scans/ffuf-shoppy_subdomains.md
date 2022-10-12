# FFUF Report

  Command line : `ffuf -w /usr/share/seclists/Discovery/DNS/namelist.txt:FUZZ -u http://shoppy.htb -H Host: FUZZ.shoppy.htb -fs 169 -of md -o ffuf-shoppy_subdomains.md -c`
  Time: 2022-10-09T15:34:37&#43;09:00

  | FUZZ | URL | Redirectlocation | Position | Status Code | Content Length | Content Words | Content Lines | Content Type | Duration | ResultFile |
  | :- | :-- | :--------------- | :---- | :------- | :---------- | :------------- | :------------ | :--------- | :----------- |
  | mattermost | http://shoppy.htb |  | 82865 | 200 | 3122 | 141 | 1 | text/html; charset=utf-8 | 183.335815ms |  |
  