# weibo-private-api


300+ API endpoints fully (login, register, follow, like, comment, repost, DM, groups, hot search, video, super topics)<br>
 authentication (parameters, tokens, session management)<br><br>

S-Value (Rust native request signing), WeiboPin (Rust device PIN), I-Value (JNI device hash), MFP (RSA encrypted device fingerprint), DeviceID (JNI native generation), SecurityPsd (Rust + RSA password encryption)

<h3> Encryption  </h3>

RSA/ECB/PKCS1Padding (MFP, 117-byte chunk split), RSA public key callback (password), Rust black-box hashing (S-Value, Pin), Base64 encoding, MD5 (legacy)

<h3> login methods </h3>

email/password, phone/SMS, QR code scan, QQ OAuth, alt token, GSID refresh, guest mode

<h3> Anti-bot  </h3>

uicode randomization, S-Value seed caching, HttpDNS, TLS hostname bypass, MFP consistency checks, captcha


 <h3> https://t.me/nullcods  </h3> 
