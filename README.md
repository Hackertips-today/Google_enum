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
## Google Headers

- Authorization  
- Content-ID  
- Content-Transfer-Encoding  
- Content-Type  
- Date  
- OriginToken  
- hotrod-board-name  
- hotrod-chrome-cpu-model  
- hotrod-chrome-processors  
- WWW-Authenticate  
- X-Ad-Manager-Impersonation  
- X-Ad-Manager-Debug-Info  
- X-ClientDetails  
- X-Cloudaicompanion-Trace-Id  
- X-Compass-Routing-Destination  
- X-Goog-AuthUser  
- X-Goog-Encode-Response-If-Executable  
- X-Google-Consent  
- X-Google-EOM  
- X-Goog-Meeting-ABR  
- X-Goog-Meeting-Botguardid  
- X-Goog-Meeting-Bot-Info  
- X-Goog-Meeting-ClientInfo  
- X-Goog-Meeting-ClientVersion  
- X-Goog-Meeting-Debugid  
- X-Goog-Meeting-Identifier  
- X-Goog-Meeting-Interop-Cohorts  
- X-Goog-Meeting-Interop-Type  
- X-Goog-Meeting-OidcIdToken  
- X-Goog-Meeting-RtcClient  
- X-Goog-Meeting-StartSource  
- X-Goog-Meeting-Token  
- X-Goog-Meeting-Viewer-Token  
- X-Goog-PageId  
- X-Goog-Safety-Content-Type  
- X-Goog-Safety-Encoding  
- X-Goog-Drive-Client-Version  
- X-Goog-Drive-Resource-Keys  
- X-HTTP-Method-Override  
- X-JavaScript-User-Agent  
- X-Origin  
- X-Referer  
- X-Requested-With  
- X-Use-HTTP-Status-Code-Override  
- X-Server-Timeout  
- X-Goog-First-Party-Reauth  
- X-Server-Token  
- x-goog-chat-space-id  
- x-goog-pan-request-context  
- X-AppInt-Credentials  
- X-Goog-Earth-Gcp-Project

-------
# General Headers
access-control-allow-headers: Authorization, Content-Type, Range, X-Firebase-Storage-Version, X-Firebase-Storage-XSRF, X-Firebase-AppCheck, X-Firebase-GMPID, X-Goog-AuthUser, X-Goog-Upload-Command, X-Goog-Upload-Header-Content-Length, X-Goog-Upload-Header-Content-Type, X-Goog-Upload-Protocol
access-control-max-age: 3600
access-control-expose-headers: Content-Range, X-Firebase-Storage-XSRF
access-control-allow-origin: *

# Custom Google Headers
X-Supportcontent-Allowapicookieauth: 'true'

# Hashing Information (CRC and MD5)
x-goog-generation: 1686839683298295
x-goog-hash: crc32c=Ifjtuw==, md5=HxdfBtIANuU0i2lQLZ3fWw==
x-goog-hash: crc32c=VhEI8Q==, md5=kpgpWibNC7ksF/7EhKcrIA==
x-goog-hash: crc32c=HfXXXX==, md5=SrWAtu+ZXXXXpGPOJAMvfQ==

# Storage and Meta Information
x-goog-metageneration: 2
x-goog-storage-class: MULTI_REGIONAL
x-goog-stored-content-encoding: gzip
x-goog-stored-content-length: 1527
x-goog-stored-content-length: 2332179
x-goog-generation: 1415838198105000
x-goog-storage-class: STANDARD
x-goog-stored-content-encoding: identity
x-auto-login: realm=com.google&args=service%3Dmail%26continue%3Dhttps://mail.google.com/mail/u/0/

# Uploader Information
x-guploader-uploadid: AHmUCY3C3kddcNe0csLNnsp0xAWJ6M6C6XczgZS8PDfy7IEUdI5knR4d4m4Nng64RCwayKCRfNY
x-guploader-uploadid: ABPtcPr_Ngj-uHmqt44Y2xb2EecrLUrIYMgRb0ldxR1Gd1UoDqehBlittk9LuF73f7Joew9_NQ62dAG5lw
x-auto-login: realm=com.google&args=service%3Dclassroom%26continue%3Dhttps://classroom.google.com/c/NjE3NTMzMjYyMTU5/a/NjI5NTU2OTA0NTk0/details

# Content and Language Information
content-language: en

# Response Headers (CORS and Content)
vary: origin
vary: referer
vary: x-origin
access-control-allow-origin: https://
access-control-expose-headers: content-encoding, date, server, content-length, vary

# User-Agent and Client Information
X-Javascript-User-Agent: google-api-javascript-client/1.1.0
user-agent: google-api-javascript-client/1.1.0
X-Cloud-Trace-Context: 3b9e6....bbbb4e6b5de7d188479311

# XSRF and Security Tokens
X-SupportContent-XsrfToken: Authorization, Content-Type, If-None-Match, X-SupportContent-AllowApiCookieAuth, x-googapps-allowed-domains

# CORS Headers for Allowing Specific Requests
access-control-allow-headers: X-SupportContent-XsrfToken, Authorization, Content-Type, If-None-Match, X-SupportContent-AllowApiCookieAuth, x-googapps-allowed-domains

# Addon Service Headers (Specific to Google Addons)
addons-pa.clients6.google.com/$rpc/google.internal.apps.addons.v1.AddOnService/ListInstallations: authorization, content-type, x-goog-api-key, x-goog-authuser, x-user-agent

---------
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
- **x-goog-generation: `1415838198105000`
- **x-goog-stored-content-encoding: `identity`
- **x-goog-stored-content-length: `2332179`
- **x-goog-storage-class: `STANDARD`
- **Access-Control-Allow-Origin: `https://<host>`
- **Vary: `origin`
- **Vary: `referer`
- **Vary: `x-origin`
- **Access-Control-Expose-Headers: `content-encoding,date,server,content-length,vary,vary,vary`
- **X-Javascript-User-Agent: `google-api-javascript-client/1.1.0`
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

- **X-Playlog-Web,authorization,authorization,x-goog-authuser,origin
- **X-Playlog-Web,authorization,authorization,content-encoding,content-type,x-goog-authuser,origin
- **X-SupportContent-XsrfToken, Authorization, Content-Type, If-None-Match, X-SupportContent-AllowApiCookieAuth, x-googapps-allowed-domains
- **access-control-allow-headers: X-SupportContent-XsrfToken, Authorization, Content-Type, If-None-Match, X-SupportContent-AllowApiCookieAuth
- **x-googapps-allowed-domains

- **Client-Protocol: HTTP/2, HTTP/1.1, QUIC
- **Content-Length: 0, 512, 1024, 2048
- **Content-Type: application/json, application/xml, text/plain, text/html
- **X-Bandwidth-Est: 5000, 10000, 20000, 50000
- **X-Bandwidth-Est2: 5000, 10000, 20000, 50000
- **X-Bandwidth-Est3: 5000, 10000, 20000, 50000
- **X-Bandwidth-App-Limited: 0, 1
- **X-Bandwidth-Est-App-Limited: 0, 1
- **X-Bandwidth-Est-Comp: 3000, 6000, 12000, 24000
- **X-Bandwidth-Avg: 4000, 8000, 16000, 32000
- **X-Head-Time-Millis: 0, 500, 1000, 1500
- **X-Head-Time-Sec: 0, 1, 2, 5
- **X-Head-Seqnum: 1, 10, 100, 1000
- **X-Response-Itag: 18, 22, 36, 37, 135, 136, 137
- **X-Restrict-Formats-Hint: mp4, webm, 3gp, flv
- **X-Sequence-Num: 1, 2, 3, 10, 20, 30
- **X-Segment-Lmt: 0, 10000, 20000, 50000
- **X-Walltime-Ms: 0, 500, 1000, 5000, 10000
- ** authorization,content-type,x-goog-api-key,x-goog-authuser,x-user-agent

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
 Accept-Language
 Authorization
 Cache-Control
 Content-Disposition
 Content-Encoding
 Content-Language
 Content-Length
 Content-MD5
 Content-Range
 Content-Type
 Date
 developer-token
 financial-institution-id
 X-Goog-Sn-Metadata
 X-Goog-Sn-PatientId
 GData-Version
 google-cloud-resource-prefix
 linked-customer-id
 login-customer-id
 x-goog-request-params
 Host
 If-Match
 If-Modified-Since
 If-None-Match
 If-Unmodified-Since
 Origin
 OriginToken
 Pragma
 Range
 request-id
 Slug
 Transfer-Encoding
 hotrod-board-name
 hotrod-chrome-cpu-model
 hotrod-chrome-processors
 Want-Digest
 X-Ad-Manager-Impersonation
 x-chrome-connected
 X-ClientDetails
 X-Client-Pctx
 X-Client-Version
 x-debug-settings-metadata
 X-Firebase-Locale
 X-Goog-Firebase-Installations-Auth
 X-Firebase-Client
 X-Firebase-Client-Log-Type
 X-Firebase-GMPID
 X-Firebase-Auth-Token
 X-Firebase-AppCheck
 X-Firebase-Token
 X-Goog-Drive-Client-Version
 X-Goog-Drive-Resource-Keys
 X-GData-Client
 X-GData-Key
 X-GoogApps-Allowed-Domains
 X-Goog-AdX-Buyer-Impersonation
 X-Goog-Api-Client
 X-Goog-Visibilities
 X-Goog-AuthUser
 X-Google-EOM
 x-goog-ext-124712974-jspb
 x-goog-ext-467253834-jspb
 x-goog-ext-353267353-bin
 x-goog-ext-353267353-jspb
 x-goog-ext-251363160-jspb
 x-goog-ext-259736195-jspb
 x-goog-ext-477772811-jspb
 x-goog-ext-359275022-bin
 x-goog-ext-328800237-jspb
 x-goog-ext-202735639-bin
 x-goog-ext-223435598-bin
 X-Goog-PageId
 X-Goog-Encode-Response-If-Executable
 X-Goog-Correlation-Id
 X-Goog-Request-Info
 X-Goog-Request-Reason
 X-Goog-Request-Time
 X-Goog-Experiments
 x-goog-iam-authority-selector
 x-goog-iam-authorization-token
 X-Goog-Spatula
 X-Goog-Travel-Bgr
 X-Goog-Travel-Settings
 X-Goog-Upload-Command
 X-Goog-Upload-Content-Disposition
 X-Goog-Upload-Content-Length
 X-Goog-Upload-Content-Type
 X-Goog-Upload-File-Name
 X-Goog-Upload-Header-Content-Encoding
 X-Goog-Upload-Header-Content-Length
 X-Goog-Upload-Header-Content-Type
 X-Goog-Upload-Header-Transfer-Encoding
 X-Goog-Upload-Offset
 X-Goog-Upload-Protocol
 x-goog-user-project
 X-Goog-Visitor-Id
 X-Goog-FieldMask
 X-Google-Project-Override
 x-goog-maps-api-salt
 x-goog-maps-api-signature
 x-goog-maps-client-id
 X-Goog-Api-Key
 x-goog-spanner-database-role
 X-HTTP-Method-Override
 X-JavaScript-User-Agent
 X-Pan-Versionid
 X-Proxied-User-IP
 X-Origin
 X-Referer
 X-Requested-With
 X-Stadia-Client-Context
 X-Upload-Content-Length
 X-Upload-Content-Type
 X-Use-Alt-Service
 X-Use-HTTP-Status-Code-Override
 X-Ios-Bundle-Identifier
 X-Places-Ios-Sdk
 X-Android-Package
 X-Android-Cert
 X-Places-Android-Sdk
 X-Goog-Maps-Ios-Uuid
 X-Goog-Maps-Android-Uuid
 X-Ariane-Xsrf-Token
 X-YouTube-Bootstrap-Logged-In
 X-Youtube-Client-Version
 X-Youtube-Lava-Device-Context
 X-YouTube-VVT
 X-YouTube-Page-CL
 X-YouTube-Page-Label
 X-YouTube-Page-Timestamp
 X-Compass-Routing-Destination
 x-framework-xsrf-token
 X-Goog-Meeting-ABR
 X-Goog-Meeting-Botguardid
 X-Goog-Meeting-Bot-Info
 X-Goog-Meeting-ClientInfo
 X-Goog-Meeting-ClientVersion
 X-Goog-Meeting-Debugid
 X-Goog-Meeting-Identifier
 X-Goog-Meeting-Interop-Cohorts
 X-Goog-Meeting-Interop-Type
 X-Goog-Meeting-OidcIdToken
 X-Goog-Meeting-RtcClient
 X-Goog-Meeting-StartSource
 X-Goog-Meeting-Token
 X-Goog-Meeting-Viewer-Token
 X-Client-Data
 x-sdm-id-token
 X-Sfdc-Authorization
 MIME-Version
 Content-Transfer-Encoding
 X-Earth-Engine-App-ID-Token
 X-Earth-Engine-Computation-Profile
 X-Earth-Engine-Computation-Profiling
 X-Play-Console-Experiments-Override
 X-Play-Console-Session-Id
 x-alkali-account-key
 x-alkali-application-key
 x-alkali-auth-apps-namespace
 x-alkali-auth-entities-namespace
 x-alkali-auth-entity
 x-alkali-client-locale
 EES-S7E-MODE
 cast-device-capabilities
 X-Server-Timeout
 x-foyer-client-environment
 x-goog-greenenergyuserappservice-metadata
 x-goog-sherlog-context
 X-Server-Token
 x-rfui-request-context
 x-goog-nest-jwt
 X-Cloud-Trace-Context
 traceparent
 x-goog-chat-space-id
 x-goog-pan-request-context
 X-AppInt-Credential


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


