- Connected to jsonplaceholder.typicode.com (188.114.97.7) port 443 (#0)
- ALPN, offering h2
- ALPN, offering http/1.1
- CAfile: /etc/ssl/certs/ca-certificates.crt
- CApath: /etc/ssl/certs
- TLSv1.0 (OUT), TLS header, Certificate Status (22):
- TLSv1.3 (OUT), TLS handshake, Client hello (1):
- TLSv1.2 (IN), TLS header, Certificate Status (22):
- TLSv1.3 (IN), TLS handshake, Server hello (2):
- TLSv1.2 (IN), TLS header, Finished (20):
- TLSv1.2 (IN), TLS header, Supplemental data (23):
- TLSv1.3 (IN), TLS handshake, Encrypted Extensions (8):
- TLSv1.3 (IN), TLS handshake, Certificate (11):
- TLSv1.3 (IN), TLS handshake, CERT verify (15):
- TLSv1.3 (IN), TLS handshake, Finished (20):
- TLSv1.2 (OUT), TLS header, Finished (20):
- TLSv1.3 (OUT), TLS change cipher, Change cipher spec (1):
- TLSv1.2 (OUT), TLS header, Supplemental data (23):
- TLSv1.3 (OUT), TLS handshake, Finished (20):
- SSL connection using TLSv1.3 / TLS_AES_256_GCM_SHA384
- ALPN, server accepted to use h2
- Server certificate:
- subject: C=US; ST=California; L=San Francisco; O=Cloudflare, Inc.; CN=sni.cloudflaressl.com
- start date: Jun 6 00:00:00 2022 GMT
- expire date: Jun 5 23:59:59 2023 GMT
- subjectAltName: host "jsonplaceholder.typicode.com" matched cert's "\*.typicode.com"
- issuer: C=US; O=Cloudflare, Inc.; CN=Cloudflare Inc ECC CA-3
- SSL certificate verify ok.
- Using HTTP2, server supports multiplexing
- Connection state changed (HTTP/2 confirmed)
- Copying HTTP/2 data in stream buffer to connection buffer after upgrade: len=0
- TLSv1.2 (OUT), TLS header, Supplemental data (23):
- TLSv1.2 (OUT), TLS header, Supplemental data (23):
- TLSv1.2 (OUT), TLS header, Supplemental data (23):
- Using Stream ID: 1 (easy handle 0x5559ef08d560)
- TLSv1.2 (OUT), TLS header, Supplemental data (23):
  > GET /posts/1/comments HTTP/2
  > Host: jsonplaceholder.typicode.com
  > user-agent: curl/7.81.0
  > accept: _/_
- TLSv1.2 (IN), TLS header, Supplemental data (23):
- TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
- TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
- old SSL session ID is stale, removing
- TLSv1.2 (IN), TLS header, Supplemental data (23):
- Connection state changed (MAX_CONCURRENT_STREAMS == 256)!
- TLSv1.2 (OUT), TLS header, Supplemental data (23):
- TLSv1.2 (IN), TLS header, Supplemental data (23):
- TLSv1.2 (IN), TLS header, Supplemental data (23):
  <!-- HEADER -->
  < HTTP/2 200
  < date: Sun, 12 Mar 2023 11:39:14 GMT
  < content-type: application/json; charset=utf-8
  < x-powered-by: Express
  < x-ratelimit-limit: 1000
  < x-ratelimit-remaining: 998
  < x-ratelimit-reset: 1678579375
  < vary: Origin, Accept-Encoding
  < access-control-allow-credentials: true
  < cache-control: max-age=43200
  < pragma: no-cache
  < expires: -1
  < x-content-type-options: nosniff
  < etag: W/"5e6-4bSPS5tq8F8ZDeFJULWh6upjp7U"
  < via: 1.1 vegur
  < cf-cache-status: HIT
  < age: 8617
  < server-timing: cf-q-config;dur=5.9999874792993e-06
  < report-to: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v3?s=tk2N8cuIKlPKVpwv0eDUwm1NFz7ifZq5z2CL51lIZ1eziXkTw3IJYZPjpIE03mDNhTem6DE6MuKqk4yMYvM3yGkMQAJH3nl5Eu9wm8yIv85ty0z3KeATwTwUnSLAipv34EdxtpKQrDVM2hYXZ7Lo"}],"group":"cf-nel","max_age":604800}
  < nel: {"success_fraction":0,"report_to":"cf-nel","max_age":604800}
  < server: cloudflare
  < cf-ray: 7a6bc16a8e573744-MXP
  < alt-svc: h3=":443"; ma=86400, h3-29=":443"; ma=86400
  <
  [
  {
  "postId": 1,
  "id": 1,
  "name": "id labore ex et quam laborum",
  "email": "Eliseo@gardner.biz",
  "body": "laudantium enim quasi est quidem magnam voluptate ipsam eos\ntempora quo necessitatibus\ndolor quam autem quasi\nreiciendis et nam sapiente accusantium"
  },
  {
  "postId": 1,
  "id": 2,
  "name": "quo vero reiciendis velit similique earum",
  "email": "Jayne_Kuhic@sydney.com",
  "body": "est natus enim nihil est dolore omnis voluptatem numquam\net omnis occaecati quod ullam at\nvoluptatem error expedita pariatur\nnihil sint nostrum voluptatem reiciendis et"
  },
  {
  "postId": 1,
  "id": 3,
- TLSv1.2 (IN), TLS header, Supplemental data (23):
  "name": "odio adipisci rerum aut animi",
  "email": "Nikita@garfield.biz",
  "body": "quia molestiae reprehenderit quasi aspernatur\naut expedita occaecati aliquam eveniet laudantium\nomnis quibusdam delectus saepe quia accusamus maiores nam est\ncum et ducimus et vero voluptates excepturi deleniti ratione"
  },
  {
  "postId": 1,
  "id": 4,
  "name": "alias odio sit",
  "email": "Lew@alysha.tv",
  "body": "non et atque\noccaecati deserunt quas accusantium unde odit nobis qui voluptatem\nquia voluptas consequuntur itaque dolor\net qui rerum deleniti ut occaecati"
  },
  {
  "postId": 1,
  "id": 5,
  "name": "vero eaque aliquid doloribus et culpa",
  "email": "Hayden@althea.biz",
  "body": "harum non quasi et ratione\ntempore iure ex voluptates in ratione\nharum architecto fugit inventore cupiditate\nvoluptates magni quo et"
  }
- TLSv1.2 (IN), TLS header, Supplemental data (23):
- Connection #0 to host jsonplaceholder.typicode.com left intact
