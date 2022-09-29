# FFUF Report

  Command line : `ffuf -w /usr/share/dirb/wordlists/big.txt -u http://10.10.11.166/FUZZ -c -of md -o ffuf-dirb.md`
  Time: 2022-09-18T08:11:18&#43;09:00

  | FUZZ | URL | Redirectlocation | Position | Status Code | Content Length | Content Words | Content Lines | Content Type | Duration | ResultFile |
  | :- | :-- | :--------------- | :---- | :------- | :---------- | :------------- | :------------ | :--------- | :----------- |
  | assets | http://10.10.11.166/assets | http://10.10.11.166/assets/ | 2716 | 301 | 185 | 6 | 8 | text/html | 180.220576ms |  |
  | css | http://10.10.11.166/css | http://10.10.11.166/css/ | 5517 | 301 | 185 | 6 | 8 | text/html | 180.074309ms |  |
  | js | http://10.10.11.166/js | http://10.10.11.166/js/ | 10190 | 301 | 185 | 6 | 8 | text/html | 179.365662ms |  |
  