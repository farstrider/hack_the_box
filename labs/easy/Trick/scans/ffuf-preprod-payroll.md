# FFUF Report

  Command line : `ffuf -w /usr/share/dirb/wordlists/big.txt:FUZZ -u http://preprod-payroll.trick.htb/FUZZ -of md -o ffuf-preprod-payroll.md -e .php -c`
  Time: 2022-09-19T11:01:50&#43;09:00

  | FUZZ | URL | Redirectlocation | Position | Status Code | Content Length | Content Words | Content Lines | Content Type | Duration | ResultFile |
  | :- | :-- | :--------------- | :---- | :------- | :---------- | :------------- | :------------ | :--------- | :----------- |
  | ajax.php | http://preprod-payroll.trick.htb/ajax.php |  | 4260 | 200 | 0 | 1 | 1 | text/html; charset=UTF-8 | 183.952993ms |  |
  | assets | http://preprod-payroll.trick.htb/assets | http://preprod-payroll.trick.htb/assets/ | 5431 | 301 | 185 | 6 | 8 | text/html | 182.987888ms |  |
  | database | http://preprod-payroll.trick.htb/database | http://preprod-payroll.trick.htb/database/ | 11463 | 301 | 185 | 6 | 8 | text/html | 181.495326ms |  |
  | db_connect.php | http://preprod-payroll.trick.htb/db_connect.php |  | 11568 | 200 | 0 | 1 | 1 | text/html; charset=UTF-8 | 182.839244ms |  |
  | department.php | http://preprod-payroll.trick.htb/department.php |  | 11886 | 200 | 4844 | 244 | 179 | text/html; charset=UTF-8 | 187.815729ms |  |
  | employee.php | http://preprod-payroll.trick.htb/employee.php |  | 13766 | 200 | 2717 | 74 | 96 | text/html; charset=UTF-8 | 185.890602ms |  |
  | header.php | http://preprod-payroll.trick.htb/header.php |  | 17616 | 200 | 2548 | 145 | 46 | text/html; charset=UTF-8 | 182.226477ms |  |
  | home.php | http://preprod-payroll.trick.htb/home.php |  | 17910 | 200 | 486 | 180 | 27 | text/html; charset=UTF-8 | 185.656857ms |  |
  | index.php | http://preprod-payroll.trick.htb/index.php | login.php | 19126 | 302 | 9546 | 1453 | 267 | text/html; charset=UTF-8 | 183.160514ms |  |
  | login.php | http://preprod-payroll.trick.htb/login.php |  | 22108 | 200 | 5571 | 374 | 177 | text/html; charset=UTF-8 | 184.413642ms |  |
  | navbar.php | http://preprod-payroll.trick.htb/navbar.php |  | 24744 | 200 | 1382 | 68 | 24 | text/html; charset=UTF-8 | 185.249387ms |  |
  | payroll.php | http://preprod-payroll.trick.htb/payroll.php |  | 27090 | 200 | 3142 | 86 | 111 | text/html; charset=UTF-8 | 216.432935ms |  |
  | position.php | http://preprod-payroll.trick.htb/position.php |  | 28372 | 200 | 5549 | 260 | 196 | text/html; charset=UTF-8 | 201.878999ms |  |
  | users.php | http://preprod-payroll.trick.htb/users.php |  | 37812 | 200 | 2197 | 103 | 81 | text/html; charset=UTF-8 | 184.506213ms |  |
  