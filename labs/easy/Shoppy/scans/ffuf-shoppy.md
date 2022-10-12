# FFUF Report

  Command line : `ffuf -w /usr/share/seclists/Discovery/Web-Content/dirsearch.txt:FUZZ -u http://shoppy.htb/FUZZ -of md -o ffuf-shoppy.md -c`
  Time: 2022-10-03T08:51:09&#43;09:00

  | FUZZ | URL | Redirectlocation | Position | Status Code | Content Length | Content Words | Content Lines | Content Type | Duration | ResultFile |
  | :- | :-- | :--------------- | :---- | :------- | :---------- | :------------- | :------------ | :--------- | :----------- |
  | ADMIN/ | http://shoppy.htb/ADMIN/ | /login | 1669 | 302 | 28 | 4 | 1 | text/plain; charset=utf-8 | 187.526082ms |  |
  | Admin | http://shoppy.htb/Admin | /login | 1714 | 302 | 28 | 4 | 1 | text/plain; charset=utf-8 | 183.778319ms |  |
  | Admin/ | http://shoppy.htb/Admin/ | /login | 1716 | 302 | 28 | 4 | 1 | text/plain; charset=utf-8 | 183.500252ms |  |
  | LogIn | http://shoppy.htb/LogIn |  | 2224 | 200 | 1074 | 152 | 26 | text/html; charset=UTF-8 | 184.982388ms |  |
  | Login | http://shoppy.htb/Login |  | 2230 | 200 | 1074 | 152 | 26 | text/html; charset=UTF-8 | 186.08735ms |  |
  | Login/ | http://shoppy.htb/Login/ |  | 2234 | 200 | 1074 | 152 | 26 | text/html; charset=UTF-8 | 184.577517ms |  |
  | admin/ | http://shoppy.htb/admin/ | /login | 3218 | 302 | 28 | 4 | 1 | text/plain; charset=utf-8 | 183.474311ms |  |
  | css | http://shoppy.htb/css | /css/ | 5091 | 301 | 173 | 7 | 11 | text/html; charset=UTF-8 | 182.623367ms |  |
  | favicon.ico | http://shoppy.htb/favicon.ico |  | 6003 | 200 | 213054 | 56 | 89 | image/x-icon | 184.819972ms |  |
  | images | http://shoppy.htb/images | /images/ | 6934 | 301 | 179 | 7 | 11 | text/html; charset=UTF-8 | 183.207465ms |  |
  | js | http://shoppy.htb/js | /js/ | 7345 | 301 | 171 | 7 | 11 | text/html; charset=UTF-8 | 182.986262ms |  |
  | login/ | http://shoppy.htb/login/ |  | 7697 | 200 | 1074 | 152 | 26 | text/html; charset=UTF-8 | 189.19526ms |  |
  