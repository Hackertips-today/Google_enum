

# HTTP Response Headers Example

# HTTP Response Headers Example

**Status:** `HTTP/1.1 200 OK`

### Headers:
- **Date:** `Fri, 15 Nov 2024 02:39:49 GMT`
- **Content-Type:** `text/html`
- **Transfer-Encoding:** `chunked`  
  _Attempt request smuggling by manipulating chunked encoding_
- **Connection:** `close`  
  _Attempt to force this to `keep-alive`_
- **CF-Ray:** `8e2bdf7d3d6a2aa0-LAX`  
  _Cloudflare specific_
- **CF-Cache-Status:** `DYNAMIC`  
  _Cloudflare specific_
- **Cache-Control:** `public, max-age=60`
- **ETag:** `W/"9298295a26cd0bb92c17fec484a72b20"`
- **Expires:** `Fri, 15 Nov 2024 02:40:49 GMT`
- **Last-Modified:** `Thu, 15 Jun 2023 14:34:43 GMT`
- **Set-Cookie:** `GCLB=CLCKqrv2nIipYhAD; path=/; HttpOnly; domain=.cloudflareworkers.com`
- **Strict-Transport-Security:** `max-age=15552000; includeSubDomains; preload`
- **Vary:** `Accept-Encoding`
- **Via:** `1.1 google`
- **X-Content-Type-Options:** `nosniff`
- **X-Frame-Options:** `deny`

### Firebase Response Headers:
- **Access-Control-Allow-Headers:**
-----

**Status:** `HTTP/1.1 200 OK`

- **Date:** `Fri, 15 Nov 2024 02:39:49 GMT`
- **Content-Type:** `text/html`
- **Transfer-Encoding:** `chunked`  
  *- Attempt request smuggling by manipulating chunked encoding*
- **Connection:** `close`  
  *- Attempt to force this to `keep-alive`*
- **CF-Ray:** `8e2bdf7d3d6a2aa0-LAX`  
  *- Cloudflare specific*
- **CF-Cache-Status:** `DYNAMIC`  
  *- Cloudflare specific*
- **Cache-Control:** `public, max-age=60`
- **ETag:** `W/"9298295a26cd0bb92c17fec484a72b20"`
- **Expires:** `Fri, 15 Nov 2024 02:40:49 GMT`
- **Last-Modified:** `Thu, 15 Jun 2023 14:34:43 GMT`
- **Set-Cookie:** `GCLB=CLCKqrv2nIipYhAD; path=/; HttpOnly; domain=.cloudflareworkers.com`
- **Strict-Transport-Security:** `max-age=15552000; includeSubDomains; preload`
- **Vary:** `Accept-Encoding`
- **Via:** `1.1 google`
- **X-Content-Type-Options:** `nosniff`
- **X-Frame-Options:** `deny`

Firebase
< access-control-allow-headers: 
Authorization, 
Content-Type, Range, X-Firebase-Storage-Version, X-Firebase-Storage-XSRF, X-Firebase-AppCheck, X-Firebase-GMPID, X-Goog-AuthUser, X-Goog-Upload-Command, X-Goog-Upload-Header-Content-Length, X-Goog-Upload-Header-Content-Type, X-Goog-Upload-Protocol
< access-control-max-age: 3600
< access-control-expose-headers: Content-Range, X-Firebase-Storage-XSRF
< access-control-allow-origin: *


---
## Custom Google Response Headers
- **X-Supportcontent-Allowapicookieauth: 'true'
- **x-goog-generation:** `1686839683298295`
- **X-Goog-Hash: crc32c=Ifjtuw==
- **X-Goog-Hash: md5=HxdfBtIANuU0i2lQLZ3fWw==
- **x-goog-hash:** `crc32c=VhEI8Q==`
- **x-goog-hash:** `md5=kpgpWibNC7ksF/7EhKcrIA==`
- **x-goog-hash: crc32c=HfXXXX==
- **x-goog-hash: md5=SrWAtu+ZXXXXpGPOJAMvfQ==
- **x-goog-metageneration:** `2`
- **x-goog-storage-class:** `MULTI_REGIONAL`
- **x-goog-stored-content-encoding:** `gzip`
- **x-goog-stored-content-length:** `1527`
- **x-guploader-uploadid:** `AHmUCY3C3kddcNe0csLNnsp0xAWJ6M6C6XczgZS8PDfy7IEUdI5knR4d4m4Nng64RCwayKCRfNY`
- **x-goog-generation: 1415838198105000
- **x-goog-stored-content-encoding: identity
- **x-goog-stored-content-length: 2332179
- **x-goog-storage-class: STANDARD
- **Access-Control-Allow-Origin: https://<host>
- **Vary: origin
- **Vary: referer
- **Vary: x-origin
- **Access-Control-Expose-Headers: content-encoding,date,server,content-length,vary,vary,vary
- **X-Javascript-User-Agent: google-api-javascript-client/1.1.0
- **User-Agent: google-api-javascript-client/1.1.0
- **X-Cloud-Trace-Context: 3b9e6....bbbb4e6b5de7d188479311
- **X-Guploader-Uploadid: ABPtcPr_Ngj-uHmqt44Y2xb2EecrLUrIYMgRb0ldxR1Gd1UoDqehBlittk9LuF73f7Joew9_NQ62dAG5lw
- **X-Goog-Generation: 1615827068484460
- **X-Goog-Metageneration: 1
- **X-Goog-Stored-Content-Encoding: identity
- **X-Goog-Stored-Content-Length: 16384
- **Content-Language: en
- **X-Goog-Storage-Class: STANDARD


- **X-Playlog-Web**: authorization, authorization, x-goog-authuser, origin  
- **X-Playlog-Web**: authorization, authorization, content-encoding, content-type, x-goog-authuser, origin  
- **X-SupportContent-XsrfToken**: Authorization, Content-Type, If-None-Match, X-SupportContent-AllowApiCookieAuth, x-googapps-allowed-domains  
- **access-control-allow-headers**: X-SupportContent-XsrfToken, Authorization, Content-Type, If-None-Match, X-SupportContent-AllowApiCookieAuth, x-googapps-allowed-domains  

**addons-pa.clients6.google.com/$rpc/google.internal.apps.addons.v1.AddOnService/ListInstallations**
- authorization, content-type, x-goog-api-key, x-goog-authuser, x-user-agent

X-Playlog-Web,authorization,authorization,x-goog-authuser,origin
X-Playlog-Web,authorization,authorization,content-encoding,content-type,x-goog-authuser,origin
X-SupportContent-XsrfToken, Authorization, Content-Type, If-None-Match, X-SupportContent-AllowApiCookieAuth, x-googapps-allowed-domains
access-control-allow-headers: X-SupportContent-XsrfToken, Authorization, Content-Type, If-None-Match, X-SupportContent-AllowApiCookieAuth
x-googapps-allowed-domains

addons-pa.clients6.google.com/$rpc/google.internal.apps.addons.v1.AddOnService/ListInstallations
authorization,content-type,x-goog-api-key,x-goog-authuser,x-user-agent

## Googlevideo headers
#### rr3---sn-2imern7d.googlevideo.com
### Custom headers for googlevideo
- Client-Protocol  
- Content-Length  
- Content-Type  
- X-Bandwidth-Est  
- X-Bandwidth-Est2  
- X-Bandwidth-Est3  
- X-Bandwidth-App-Limited  
- X-Bandwidth-Est-App-Limited  
- X-Bandwidth-Est-Comp  
- X-Bandwidth-Avg  
- X-Head-Time-Millis  
- X-Head-Time-Sec  
- X-Head-Seqnum  
- X-Response-Itag  
- X-Restrict-Formats-Hint  
- X-Sequence-Num  
- X-Segment-Lmt  
- X-Walltime-Ms


## Try these headers
Client-Protocol: HTTP/2, HTTP/1.1, QUIC
Content-Length: 0, 512, 1024, 2048
Content-Type: application/json, application/xml, text/plain, text/html
X-Bandwidth-Est: 5000, 10000, 20000, 50000
X-Bandwidth-Est2: 5000, 10000, 20000, 50000
X-Bandwidth-Est3: 5000, 10000, 20000, 50000
X-Bandwidth-App-Limited: 0, 1
X-Bandwidth-Est-App-Limited: 0, 1
X-Bandwidth-Est-Comp: 3000, 6000, 12000, 24000
X-Bandwidth-Avg: 4000, 8000, 16000, 32000
X-Head-Time-Millis: 0, 500, 1000, 1500
X-Head-Time-Sec: 0, 1, 2, 5
X-Head-Seqnum: 1, 10, 100, 1000
X-Response-Itag: 18, 22, 36, 37, 135, 136, 137
X-Restrict-Formats-Hint: mp4, webm, 3gp, flv
X-Sequence-Num: 1, 2, 3, 10, 20, 30
X-Segment-Lmt: 0, 10000, 20000, 50000
X-Walltime-Ms: 0, 500, 1000, 5000, 10000


