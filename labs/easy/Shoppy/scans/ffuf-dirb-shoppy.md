# FFUF Report

  Command line : `ffuf -w /usr/share/dirb/wordlists/big.txt:FUZZ -u http://shoppy.htb/FUZZ -of md -o ffuf-dirb-shoppy.md -c`
  Time: 2022-10-03T09:04:23&#43;09:00

  | FUZZ | URL | Redirectlocation | Position | Status Code | Content Length | Content Words | Content Lines | Content Type | Duration | ResultFile |
  | :- | :-- | :--------------- | :---- | :------- | :---------- | :------------- | :------------ | :--------- | :----------- |
  | ADMIN | http://shoppy.htb/ADMIN | /login | 891 | 302 | 28 | 4 | 1 | text/plain; charset=utf-8 | 186.84425ms |  |
  | Admin | http://shoppy.htb/Admin | /login | 895 | 302 | 28 | 4 | 1 | text/plain; charset=utf-8 | 189.989852ms |  |
  | Login | http://shoppy.htb/Login |  | 970 | 200 | 1074 | 152 | 26 | text/html; charset=UTF-8 | 184.730284ms |  |
  | admin | http://shoppy.htb/admin | /login | 1816 | 302 | 28 | 4 | 1 | text/plain; charset=utf-8 | 185.86431ms |  |
  | assets | http://shoppy.htb/assets | /assets/ | 2716 | 301 | 179 | 7 | 11 | text/html; charset=UTF-8 | 185.186265ms |  |
  | css | http://shoppy.htb/css | /css/ | 5517 | 301 | 173 | 7 | 11 | text/html; charset=UTF-8 | 187.174817ms |  |
  | exports | http://shoppy.htb/exports | /exports/ | 7297 | 301 | 181 | 7 | 11 | text/html; charset=UTF-8 | 184.310029ms |  |
  | favicon.ico | http://shoppy.htb/favicon.ico |  | 7427 | 200 | 213054 | 56 | 89 | image/x-icon | 191.078541ms |  |
  | fonts | http://shoppy.htb/fonts | /fonts/ | 7795 | 301 | 177 | 7 | 11 | text/html; charset=UTF-8 | 183.591932ms |  |
  | images | http://shoppy.htb/images | /images/ | 9378 | 301 | 179 | 7 | 11 | text/html; charset=UTF-8 | 186.517241ms |  |
  | js | http://shoppy.htb/js | /js/ | 10190 | 301 | 171 | 7 | 11 | text/html; charset=UTF-8 | 183.455034ms |  |
  | login | http://shoppy.htb/login |  | 11054 | 200 | 1074 | 152 | 26 | text/html; charset=UTF-8 | 184.301189ms |  |
  