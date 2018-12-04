OpenCL Platform #1: NVIDIA Corporation
======================================
* Device #1: GeForce RTX 2080 Ti, 2816/11264 MB allocatable, 68MCU

OpenCL Platform #2: Intel(R) Corporation
========================================
* Device #2: Intel(R) UHD Graphics 630, skipped.
* Device #3: Intel(R) Core(TM) i7-8086K CPU @ 4.00GHz, skipped.

Benchmark relevant options:
===========================
* --benchmark-all
* --optimized-kernel-enable

Hashmode: 0 - MD5

Speed.#1.........: 61603.4 MH/s (36.78ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 10 - md5($pass.$salt)

Speed.#1.........: 61390.3 MH/s (36.95ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 11 - Joomla < 2.5.18

Speed.#1.........: 61221.8 MH/s (37.05ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 12 - PostgreSQL

Speed.#1.........: 61137.5 MH/s (37.10ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 20 - md5($salt.$pass)

Speed.#1.........: 31873.3 MH/s (71.07ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 21 - osCommerce, xt:Commerce

Speed.#1.........: 31732.7 MH/s (71.37ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 22 - Juniper NetScreen/SSG (ScreenOS)

Speed.#1.........: 31502.5 MH/s (71.90ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 23 - Skype

Speed.#1.........: 31664.4 MH/s (35.56ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 30 - md5(utf16le($pass).$salt)

Speed.#1.........: 57453.6 MH/s (39.15ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 40 - md5($salt.utf16le($pass))

Speed.#1.........: 31761.1 MH/s (71.32ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 50 - HMAC-MD5 (key = $pass)

Speed.#1.........:  9240.3 MH/s (61.23ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 60 - HMAC-MD5 (key = $salt)

Speed.#1.........: 19222.5 MH/s (58.83ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 100 - SHA1

Speed.#1.........: 17975.0 MH/s (62.97ms) @ Accel:128 Loops:512 Thr:256 Vec:2

Hashmode: 101 - nsldap, SHA-1(Base64), Netscape LDAP SHA

Speed.#1.........: 17967.8 MH/s (62.98ms) @ Accel:128 Loops:512 Thr:256 Vec:2

Hashmode: 110 - sha1($pass.$salt)

Speed.#1.........: 17886.2 MH/s (31.43ms) @ Accel:128 Loops:256 Thr:256 Vec:2

Hashmode: 111 - nsldaps, SSHA-1(Base64), Netscape LDAP SSHA

Speed.#1.........: 17961.9 MH/s (63.01ms) @ Accel:128 Loops:512 Thr:256 Vec:2

Hashmode: 112 - Oracle S: Type (Oracle 11+)

Speed.#1.........: 18005.5 MH/s (62.86ms) @ Accel:128 Loops:512 Thr:256 Vec:2

Hashmode: 120 - sha1($salt.$pass)

Speed.#1.........: 13732.4 MH/s (82.54ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 121 - SMF (Simple Machines Forum) > v1.1

Speed.#1.........: 13602.4 MH/s (41.44ms) @ Accel:128 Loops:256 Thr:256 Vec:4

Hashmode: 122 - macOS v10.4, macOS v10.5, MacOS v10.6

Speed.#1.........: 13731.5 MH/s (82.53ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 124 - Django (SHA-1)

Speed.#1.........: 13631.0 MH/s (41.37ms) @ Accel:128 Loops:256 Thr:256 Vec:4

Hashmode: 125 - ArubaOS

Speed.#1.........: 13724.6 MH/s (82.56ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 130 - sha1(utf16le($pass).$salt)

Speed.#1.........: 18145.8 MH/s (62.33ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 131 - MSSQL (2000)

Speed.#1.........: 18113.1 MH/s (62.45ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 132 - MSSQL (2005)

Speed.#1.........: 18105.4 MH/s (62.48ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 133 - PeopleSoft

Speed.#1.........: 18121.2 MH/s (62.42ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 140 - sha1($salt.utf16le($pass))

Speed.#1.........: 13715.1 MH/s (82.64ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 141 - Episerver 6.x < .NET 4

Speed.#1.........: 13714.9 MH/s (82.64ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 150 - HMAC-SHA1 (key = $pass)

Speed.#1.........:  3773.6 MH/s (75.03ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 160 - HMAC-SHA1 (key = $salt)

Speed.#1.........:  7036.4 MH/s (80.52ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 200 - MySQL323

Speed.#1.........:   173.7 GH/s (12.74ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 300 - MySQL4.1/MySQL5

Speed.#1.........:  7838.9 MH/s (72.19ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 400 - phpass, WordPress (MD5), phpBB3 (MD5), Joomla (MD5) (Iterations: 2048)

Speed.#1.........: 15603.3 kH/s (66.58ms) @ Accel:128 Loops:1024 Thr:256 Vec:1

Hashmode: 500 - md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5) (Iterations: 1000)

Speed.#1.........: 23246.3 kH/s (85.36ms) @ Accel:1024 Loops:1000 Thr:32 Vec:1

Hashmode: 501 - Juniper IVE (Iterations: 1000)

Speed.#1.........: 24818.7 kH/s (80.39ms) @ Accel:1024 Loops:1000 Thr:32 Vec:1

Hashmode: 600 - BLAKE2b

Speed.#1.........:  3948.4 MH/s (71.69ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 900 - MD4

Speed.#1.........: 85436.6 MH/s (26.29ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 1000 - NTLM

Speed.#1.........: 83747.2 MH/s (26.84ms) @ Accel:128 Loops:1024 Thr:256 Vec:2

Hashmode: 1100 - Domain Cached Credentials (DCC), MS Cache

Speed.#1.........: 23734.3 MH/s (95.56ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 1300 - SHA2-224

Speed.#1.........:  7862.2 MH/s (35.79ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 1400 - SHA2-256

Speed.#1.........:  8056.0 MH/s (70.24ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 1410 - sha256($pass.$salt)

Speed.#1.........:  8087.2 MH/s (70.03ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 1411 - SSHA-256(Base64), LDAP {SSHA256}

Speed.#1.........:  8066.2 MH/s (70.17ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 1420 - sha256($salt.$pass)

Speed.#1.........:  7158.8 MH/s (79.07ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 1421 - hMailServer

Speed.#1.........:  7161.1 MH/s (79.09ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 1430 - sha256(utf16le($pass).$salt)

Speed.#1.........:  8007.9 MH/s (70.66ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 1440 - sha256($salt.utf16le($pass))

Speed.#1.........:  7172.1 MH/s (79.00ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 1441 - Episerver 6.x >= .NET 4

Speed.#1.........:  7132.2 MH/s (39.50ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 1450 - HMAC-SHA256 (key = $pass)

Speed.#1.........:  1490.8 MH/s (47.37ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 1460 - HMAC-SHA256 (key = $salt)

Speed.#1.........:  3035.9 MH/s (93.30ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 1500 - descrypt, DES (Unix), Traditional DES

Speed.#1.........:  1859.7 MH/s (76.01ms) @ Accel:8 Loops:1024 Thr:256 Vec:1

Hashmode: 1600 - Apache $apr1$ MD5, md5apr1, MD5 (APR) (Iterations: 1000)

Speed.#1.........: 23372.8 kH/s (85.80ms) @ Accel:1024 Loops:1000 Thr:32 Vec:1

Hashmode: 1700 - SHA2-512

Speed.#1.........:  2557.3 MH/s (55.26ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 1710 - sha512($pass.$salt)

Speed.#1.........:  2557.1 MH/s (55.27ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 1711 - SSHA-512(Base64), LDAP {SSHA512}

Speed.#1.........:  2559.2 MH/s (55.19ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 1720 - sha512($salt.$pass)

Speed.#1.........:  2346.3 MH/s (60.27ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 1722 - macOS v10.7

Speed.#1.........:  2348.9 MH/s (60.23ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 1730 - sha512(utf16le($pass).$salt)

Speed.#1.........:  2587.9 MH/s (54.58ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 1731 - MSSQL (2012, 2014)

Speed.#1.........:  2591.6 MH/s (54.53ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 1740 - sha512($salt.utf16le($pass))

Speed.#1.........:  2480.8 MH/s (56.98ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 1750 - HMAC-SHA512 (key = $pass)

Speed.#1.........:   475.0 MH/s (74.50ms) @ Accel:64 Loops:32 Thr:256 Vec:1

Hashmode: 1760 - HMAC-SHA512 (key = $salt)

Speed.#1.........:  1067.3 MH/s (66.19ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 1800 - sha512crypt $6$, SHA512 (Unix) (Iterations: 5000)

Speed.#1.........:   348.6 kH/s (78.94ms) @ Accel:512 Loops:128 Thr:32 Vec:1

Hashmode: 2100 - Domain Cached Credentials 2 (DCC2), MS Cache 2 (Iterations: 10240)

Speed.#1.........:   690.5 kH/s (80.17ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 2400 - Cisco-PIX MD5

Speed.#1.........: 41484.4 MH/s (54.49ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 2410 - Cisco-ASA MD5

Speed.#1.........: 42507.7 MH/s (53.18ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 2500 - WPA-EAPOL-PBKDF2 (Iterations: 4096)

Speed.#1.........:   850.0 kH/s (81.33ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 2501 - WPA-EAPOL-PMK (Iterations: 1)

Speed.#1.........:   162.6 MH/s (0.01ms) @ Accel:128 Loops:1 Thr:256 Vec:1

Hashmode: 2600 - md5(md5($pass))

Speed.#1.........: 16465.9 MH/s (68.77ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 2611 - vBulletin < v3.8.5

Speed.#1.........: 16461.8 MH/s (68.79ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 2612 - PHPS

Speed.#1.........: 16481.0 MH/s (68.71ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 2711 - vBulletin >= v3.8.5

Speed.#1.........: 11618.5 MH/s (48.61ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 2811 - IPB2+ (Invision Power Board), MyBB 1.2+

Speed.#1.........: 12145.3 MH/s (46.49ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 3000 - LM

Speed.#1.........: 47870.4 MH/s (46.91ms) @ Accel:128 Loops:1024 Thr:256 Vec:1

Hashmode: 3100 - Oracle H: Type (Oracle 7+)

Speed.#1.........:  1719.6 MH/s (82.38ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 3200 - bcrypt $2*$, Blowfish (Unix) (Iterations: 32)

Speed.#1.........:    29183 H/s (36.34ms) @ Accel:16 Loops:4 Thr:8 Vec:1

Hashmode: 3710 - md5($salt.md5($pass))

Speed.#1.........: 15409.1 MH/s (73.49ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 3711 - MediaWiki B type

Speed.#1.........: 15400.5 MH/s (73.50ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 3800 - md5($salt.$pass.$salt)

Speed.#1.........: 31647.8 MH/s (71.59ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 3910 - md5(md5($pass).md5($salt))

Speed.#1.........: 11729.2 MH/s (96.58ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 4010 - md5($salt.md5($salt.$pass))

Speed.#1.........: 12435.8 MH/s (45.39ms) @ Accel:128 Loops:256 Thr:256 Vec:4

Hashmode: 4110 - md5($salt.md5($pass.$salt))

Speed.#1.........: 13795.7 MH/s (82.17ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 4300 - md5(strtoupper(md5($pass)))

Speed.#1.........: 16461.3 MH/s (68.75ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 4400 - md5(sha1($pass))

Speed.#1.........:  9745.8 MH/s (58.00ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 4500 - sha1(sha1($pass))

Speed.#1.........:  7005.2 MH/s (80.82ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 4520 - sha1($salt.sha1($pass))

Speed.#1.........:  5798.6 MH/s (97.77ms) @ Accel:128 Loops:256 Thr:256 Vec:2

Hashmode: 4521 - Redmine

Speed.#1.........:  5812.6 MH/s (97.56ms) @ Accel:128 Loops:256 Thr:256 Vec:2

Hashmode: 4522 - PunBB

Speed.#1.........:  5934.0 MH/s (47.57ms) @ Accel:128 Loops:128 Thr:256 Vec:2

Hashmode: 4700 - sha1(md5($pass))

Speed.#1.........: 10132.8 MH/s (55.82ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 4800 - iSCSI CHAP authentication, MD5(CHAP)

Speed.#1.........: 34352.9 MH/s (65.90ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 4900 - sha1($salt.$pass.$salt)

Speed.#1.........: 13415.6 MH/s (84.42ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 5100 - Half MD5

Speed.#1.........: 36168.7 MH/s (62.55ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 5200 - Password Safe v3 (Iterations: 2048)

Speed.#1.........:  3242.0 kH/s (84.50ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 5300 - IKE-PSK MD5

Speed.#1.........:  4542.1 MH/s (62.26ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 5400 - IKE-PSK SHA1

Speed.#1.........:  1633.4 MH/s (86.74ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 5500 - NetNTLMv1 / NetNTLMv1+ESS

Speed.#1.........: 46185.1 MH/s (48.82ms) @ Accel:128 Loops:1024 Thr:256 Vec:1

Hashmode: 5600 - NetNTLMv2

Speed.#1.........:  4110.8 MH/s (68.86ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 5700 - Cisco-IOS type 4 (SHA256)

Speed.#1.........:  8058.8 MH/s (70.24ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 5800 - Samsung Android Password/PIN (Iterations: 1023)

Speed.#1.........: 12362.9 kH/s (56.55ms) @ Accel:128 Loops:511 Thr:256 Vec:1

Hashmode: 6000 - RIPEMD-160

Speed.#1.........: 10676.2 MH/s (52.94ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 6100 - Whirlpool

Speed.#1.........:   441.0 MH/s (80.33ms) @ Accel:128 Loops:16 Thr:256 Vec:1

Hashmode: 6211 - TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit (Iterations: 2000)

Speed.#1.........:   590.1 kH/s (54.72ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 6212 - TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 1024 bit (Iterations: 2000)

Speed.#1.........:   367.2 kH/s (95.27ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 6213 - TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 1536 bit (Iterations: 2000)

Speed.#1.........:   253.9 kH/s (69.39ms) @ Accel:64 Loops:32 Thr:256 Vec:1

Hashmode: 6221 - TrueCrypt PBKDF2-HMAC-SHA512 + XTS 512 bit (Iterations: 1000)

Speed.#1.........:   984.7 kH/s (57.66ms) @ Accel:64 Loops:62 Thr:256 Vec:1

Hashmode: 6222 - TrueCrypt PBKDF2-HMAC-SHA512 + XTS 1024 bit (Iterations: 1000)

Speed.#1.........:   462.8 kH/s (60.23ms) @ Accel:64 Loops:31 Thr:256 Vec:1

Hashmode: 6223 - TrueCrypt PBKDF2-HMAC-SHA512 + XTS 1536 bit (Iterations: 1000)

Speed.#1.........:   288.4 kH/s (96.22ms) @ Accel:64 Loops:31 Thr:256 Vec:1

Hashmode: 6231 - TrueCrypt PBKDF2-HMAC-Whirlpool + XTS 512 bit (Iterations: 1000)

Speed.#1.........:    68730 H/s (250.15ms) @ Accel:32 Loops:31 Thr:256 Vec:1

Hashmode: 6232 - TrueCrypt PBKDF2-HMAC-Whirlpool + XTS 1024 bit (Iterations: 1000)

Speed.#1.........:    34217 H/s (242.77ms) @ Accel:32 Loops:15 Thr:256 Vec:1

Hashmode: 6233 - TrueCrypt PBKDF2-HMAC-Whirlpool + XTS 1536 bit (Iterations: 1000)

Speed.#1.........:    23123 H/s (179.86ms) @ Accel:16 Loops:15 Thr:256 Vec:1

Hashmode: 6241 - TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit + boot-mode (Iterations: 1000)

Speed.#1.........:  1129.5 kH/s (48.55ms) @ Accel:64 Loops:62 Thr:256 Vec:1

Hashmode: 6242 - TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 1024 bit + boot-mode (Iterations: 1000)

Speed.#1.........:   587.1 kH/s (86.78ms) @ Accel:64 Loops:62 Thr:256 Vec:1

Hashmode: 6243 - TrueCrypt PBKDF2-HMAC-RIPEMD160 + XTS 1536 bit + boot-mode (Iterations: 1000)

Speed.#1.........:   400.0 kH/s (63.44ms) @ Accel:64 Loops:31 Thr:256 Vec:1

Hashmode: 6300 - AIX {smd5} (Iterations: 1000)

Speed.#1.........: 23428.4 kH/s (84.61ms) @ Accel:1024 Loops:1000 Thr:32 Vec:1

Hashmode: 6400 - AIX {ssha256} (Iterations: 64)

Speed.#1.........: 40706.3 kH/s (42.93ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 6500 - AIX {ssha512} (Iterations: 64)

Speed.#1.........: 15551.7 kH/s (60.22ms) @ Accel:64 Loops:64 Thr:256 Vec:1

Hashmode: 6600 - 1Password, agilekeychain (Iterations: 1000)

Speed.#1.........:  6769.7 kH/s (78.02ms) @ Accel:128 Loops:250 Thr:256 Vec:1

Hashmode: 6700 - AIX {ssha1} (Iterations: 64)

Speed.#1.........: 71958.2 kH/s (20.05ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 6800 - LastPass + LastPass sniffed (Iterations: 500)

Speed.#1.........:  6254.3 kH/s (82.80ms) @ Accel:128 Loops:125 Thr:256 Vec:1

Hashmode: 6900 - GOST R 34.11-94

Speed.#1.........:   436.6 MH/s (81.12ms) @ Accel:128 Loops:16 Thr:256 Vec:1

Hashmode: 7000 - FortiGate (FortiOS)

Speed.#1.........: 14771.5 MH/s (76.71ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 7100 - macOS v10.8+ (PBKDF2-SHA512) (Iterations: 35000)

Speed.#1.........:    31875 H/s (63.35ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 7200 - GRUB 2 (Iterations: 10000)

Speed.#1.........:   111.2 kH/s (63.53ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 7300 - IPMI2 RAKP HMAC-SHA1

Speed.#1.........:  3478.3 MH/s (81.46ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 7400 - sha256crypt $5$, SHA256 (Unix) (Iterations: 5000)

Speed.#1.........:  1096.9 kH/s (49.90ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 7500 - Kerberos 5 AS-REQ Pre-Auth etype 23

Speed.#1.........:   668.5 MH/s (52.91ms) @ Accel:128 Loops:64 Thr:64 Vec:1

Hashmode: 7700 - SAP CODVN B (BCODE)

Speed.#1.........:  3223.8 MH/s (87.94ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 7701 - SAP CODVN B (BCODE) mangled from RFC_READ_TABLE

Speed.#1.........:  3471.2 MH/s (81.61ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 7800 - SAP CODVN F/G (PASSCODE)

Speed.#1.........:  2730.2 MH/s (51.75ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 7801 - SAP CODVN F/G (PASSCODE) mangled from RFC_READ_TABLE

Speed.#1.........:  3924.8 MH/s (72.13ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 7900 - Drupal7 (Iterations: 16384)

Speed.#1.........:   135.6 kH/s (63.74ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 8000 - Sybase ASE

Speed.#1.........:   955.5 MH/s (74.14ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 8100 - Citrix NetScaler

Speed.#1.........: 15443.0 MH/s (73.38ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 8200 - 1Password, cloudkeychain (Iterations: 40000)

Speed.#1.........:    26487 H/s (66.70ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 8300 - DNSSEC (NSEC3)

Speed.#1.........:  6740.9 MH/s (41.86ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 8400 - WBB3 (Woltlab Burning Board)

Speed.#1.........:  2732.0 MH/s (51.76ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 8500 - RACF

Speed.#1.........:  5198.3 MH/s (54.42ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 8600 - Lotus Notes/Domino 5

Speed.#1.........:   387.7 MH/s (91.48ms) @ Accel:64 Loops:32 Thr:256 Vec:1

Hashmode: 8700 - Lotus Notes/Domino 6

Speed.#1.........:   130.8 MH/s (67.70ms) @ Accel:64 Loops:8 Thr:256 Vec:1

Hashmode: 8800 - Android FDE <= 4.3 (Iterations: 2000)

Speed.#1.........:  1727.8 kH/s (78.69ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 8900 - scrypt (Iterations: 1)

Speed.#1.........:  1240.0 kH/s (9.52ms) @ Accel:16 Loops:1 Thr:16 Vec:1

Hashmode: 9000 - Password Safe v2 (Iterations: 1000)

Speed.#1.........:   634.4 kH/s (35.82ms) @ Accel:256 Loops:250 Thr:8 Vec:1

Hashmode: 9100 - Lotus Notes/Domino 8 (Iterations: 5000)

Speed.#1.........:  1408.0 kH/s (77.91ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 9200 - Cisco-IOS $8$ (PBKDF2-SHA256) (Iterations: 20000)

Speed.#1.........:   164.7 kH/s (86.02ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 9300 - Cisco-IOS $9$ (scrypt) (Iterations: 1)

Speed.#1.........:    64830 H/s (91.62ms) @ Accel:16 Loops:1 Thr:8 Vec:1

Hashmode: 9400 - MS Office 2007 (Iterations: 50000)

Speed.#1.........:   283.4 kH/s (80.14ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 9500 - MS Office 2010 (Iterations: 100000)

Speed.#1.........:   141.6 kH/s (80.19ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 9600 - MS Office 2013 (Iterations: 100000)

Speed.#1.........:    24242 H/s (58.40ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 9700 - MS Office <= 2003 $0/$1, MD5 + RC4

Speed.#1.........:   612.4 MH/s (57.82ms) @ Accel:128 Loops:64 Thr:64 Vec:1

Hashmode: 9710 - MS Office <= 2003 $0/$1, MD5 + RC4, collider #1

Speed.#1.........:   670.2 MH/s (52.41ms) @ Accel:128 Loops:64 Thr:64 Vec:1

Hashmode: 9720 - MS Office <= 2003 $0/$1, MD5 + RC4, collider #2

Speed.#1.........:  4727.1 MH/s (59.81ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 9800 - MS Office <= 2003 $3/$4, SHA1 + RC4

Speed.#1.........:   691.3 MH/s (51.19ms) @ Accel:128 Loops:64 Thr:64 Vec:1

Hashmode: 9810 - MS Office <= 2003 $3, SHA1 + RC4, collider #1

Speed.#1.........:   748.5 MH/s (94.17ms) @ Accel:256 Loops:64 Thr:64 Vec:1

Hashmode: 9820 - MS Office <= 2003 $3, SHA1 + RC4, collider #2

Speed.#1.........:  7201.4 MH/s (78.72ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 9900 - Radmin2

Speed.#1.........: 20519.7 MH/s (55.11ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 10000 - Django (PBKDF2-SHA256) (Iterations: 20000)

Speed.#1.........:   164.1 kH/s (86.32ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 10100 - SipHash

Speed.#1.........: 63967.1 MH/s (35.22ms) @ Accel:128 Loops:1024 Thr:256 Vec:1

Hashmode: 10200 - CRAM-MD5

Speed.#1.........:  9252.9 MH/s (61.12ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 10300 - SAP CODVN H (PWDSALTEDHASH) iSSHA-1 (Iterations: 1023)

Speed.#1.........: 12152.8 kH/s (34.69ms) @ Accel:128 Loops:255 Thr:256 Vec:1

Hashmode: 10400 - PDF 1.1 - 1.3 (Acrobat 2 - 4)

Speed.#1.........:   791.1 MH/s (89.65ms) @ Accel:256 Loops:64 Thr:64 Vec:1

Hashmode: 10410 - PDF 1.1 - 1.3 (Acrobat 2 - 4), collider #1

Speed.#1.........:   813.1 MH/s (86.54ms) @ Accel:256 Loops:64 Thr:64 Vec:1

Hashmode: 10420 - PDF 1.1 - 1.3 (Acrobat 2 - 4), collider #2

Speed.#1.........: 17713.2 MH/s (63.92ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 10500 - PDF 1.4 - 1.6 (Acrobat 5 - 8) (Iterations: 70)

Speed.#1.........: 34127.3 kH/s (55.32ms) @ Accel:512 Loops:70 Thr:64 Vec:1

Hashmode: 10600 - PDF 1.7 Level 3 (Acrobat 9)

Speed.#1.........:  8108.7 MH/s (34.75ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 10700 - PDF 1.7 Level 8 (Acrobat 10 - 11) (Iterations: 64)

Speed.#1.........:    78329 H/s (110.82ms) @ Accel:8 Loops:4 Thr:256 Vec:1

Hashmode: 10800 - SHA2-384

Speed.#1.........:  2524.3 MH/s (56.04ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 10900 - PBKDF2-HMAC-SHA256 (Iterations: 999)

Speed.#1.........:  3259.1 kH/s (73.80ms) @ Accel:128 Loops:124 Thr:256 Vec:1

Hashmode: 11000 - PrestaShop

Speed.#1.........: 20401.8 MH/s (55.45ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 11100 - PostgreSQL CRAM (MD5)

Speed.#1.........: 16109.8 MH/s (70.33ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 11200 - MySQL CRAM (SHA1)

Speed.#1.........:  4758.7 MH/s (59.43ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 11300 - Bitcoin/Litecoin wallet.dat (Iterations: 199999)

Speed.#1.........:    12079 H/s (58.59ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 11400 - SIP digest authentication (MD5)

Speed.#1.........:  7654.9 MH/s (74.04ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 11500 - CRC32

Speed.#1.........: 13088.2 MH/s (43.21ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 11600 - 7-Zip (Iterations: 524288)

Speed.#1.........:    22944 H/s (94.23ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 11700 - GOST R 34.11-2012 (Streebog) 256-bit

Speed.#1.........: 92499.1 kH/s (95.87ms) @ Accel:32 Loops:16 Thr:256 Vec:1

Hashmode: 11800 - GOST R 34.11-2012 (Streebog) 512-bit

Speed.#1.........: 92812.2 kH/s (95.61ms) @ Accel:32 Loops:16 Thr:256 Vec:1

Hashmode: 11900 - PBKDF2-HMAC-MD5 (Iterations: 999)

Speed.#1.........: 17814.7 kH/s (37.37ms) @ Accel:128 Loops:499 Thr:256 Vec:1

Hashmode: 12000 - PBKDF2-HMAC-SHA1 (Iterations: 999)

Speed.#1.........:  6635.9 kH/s (63.65ms) @ Accel:128 Loops:249 Thr:256 Vec:1

Hashmode: 12001 - Atlassian (PBKDF2-HMAC-SHA1) (Iterations: 9999)

Speed.#1.........:   704.7 kH/s (78.49ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 12100 - PBKDF2-HMAC-SHA512 (Iterations: 999)

Speed.#1.........:  1128.3 kH/s (57.16ms) @ Accel:64 Loops:62 Thr:256 Vec:1

Hashmode: 12200 - eCryptfs (Iterations: 65535)

Speed.#1.........:    36898 H/s (58.55ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 12300 - Oracle T: Type (Oracle 12+) (Iterations: 4095)

Speed.#1.........:   260.0 kH/s (66.20ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 12400 - BSDi Crypt, Extended DES (Iterations: 2899)

Speed.#1.........:  2849.3 kH/s (127.94ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 12500 - RAR3-hp (Iterations: 262144)

Speed.#1.........:    69901 H/s (62.01ms) @ Accel:4 Loops:16384 Thr:256 Vec:1

Hashmode: 12600 - ColdFusion 10+

Speed.#1.........:  4513.0 MH/s (62.74ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 12700 - Blockchain, My Wallet (Iterations: 10)

Speed.#1.........: 86863.1 kH/s (6.51ms) @ Accel:128 Loops:10 Thr:256 Vec:1

Hashmode: 12800 - MS-AzureSync PBKDF2-HMAC-SHA256 (Iterations: 99)

Speed.#1.........: 25933.2 kH/s (63.80ms) @ Accel:128 Loops:99 Thr:256 Vec:1

Hashmode: 12900 - Android FDE (Samsung DEK) (Iterations: 4095)

Speed.#1.........:   805.1 kH/s (85.74ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 13000 - RAR5 (Iterations: 32767)

Speed.#1.........:   100.5 kH/s (86.05ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 13100 - Kerberos 5 TGS-REP etype 23

Speed.#1.........:   665.3 MH/s (53.19ms) @ Accel:128 Loops:64 Thr:64 Vec:1

Hashmode: 13200 - AxCrypt (Iterations: 10000)

Speed.#1.........:   189.3 kH/s (74.98ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 13300 - AxCrypt in-memory SHA1

Speed.#1.........: 15748.5 MH/s (71.94ms) @ Accel:128 Loops:512 Thr:256 Vec:4

Hashmode: 13400 - KeePass 1 (AES/Twofish) and KeePass 2 (AES) (Iterations: 6000)

Speed.#1.........:   235.4 kH/s (100.65ms) @ Accel:512 Loops:128 Thr:32 Vec:1

Hashmode: 13500 - PeopleSoft PS_TOKEN

Speed.#1.........:  6695.5 MH/s (84.68ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 13600 - WinZip (Iterations: 1000)

Speed.#1.........:  2248.4 kH/s (56.93ms) @ Accel:128 Loops:62 Thr:256 Vec:1

Hashmode: 13711 - VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit (Iterations: 655331)

Speed.#1.........:     1973 H/s (54.29ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 13712 - VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 1024 bit (Iterations: 655331)

Speed.#1.........:     1132 H/s (94.05ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 13713 - VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 1536 bit (Iterations: 655331)

Speed.#1.........:      773 H/s (69.54ms) @ Accel:64 Loops:32 Thr:256 Vec:1

Hashmode: 13721 - VeraCrypt PBKDF2-HMAC-SHA512 + XTS 512 bit (Iterations: 500000)

Speed.#1.........:     2238 H/s (63.04ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 13722 - VeraCrypt PBKDF2-HMAC-SHA512 + XTS 1024 bit (Iterations: 500000)

Speed.#1.........:     1125 H/s (62.85ms) @ Accel:64 Loops:32 Thr:256 Vec:1

Hashmode: 13723 - VeraCrypt PBKDF2-HMAC-SHA512 + XTS 1536 bit (Iterations: 500000)

Speed.#1.........:      690 H/s (102.51ms) @ Accel:64 Loops:32 Thr:256 Vec:1

Hashmode: 13731 - VeraCrypt PBKDF2-HMAC-Whirlpool + XTS 512 bit (Iterations: 500000)

Speed.#1.........:      135 H/s (261.04ms) @ Accel:64 Loops:16 Thr:256 Vec:1

Hashmode: 13732 - VeraCrypt PBKDF2-HMAC-Whirlpool + XTS 1024 bit (Iterations: 500000)

Speed.#1.........:       69 H/s (257.25ms) @ Accel:32 Loops:16 Thr:256 Vec:1

Hashmode: 13733 - VeraCrypt PBKDF2-HMAC-Whirlpool + XTS 1536 bit (Iterations: 500000)

Speed.#1.........:       46 H/s (194.02ms) @ Accel:32 Loops:8 Thr:256 Vec:1

Hashmode: 13741 - VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 512 bit + boot-mode (Iterations: 327661)

Speed.#1.........:     3994 H/s (53.68ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 13742 - VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 1024 bit + boot-mode (Iterations: 327661)

Speed.#1.........:     2278 H/s (93.61ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 13743 - VeraCrypt PBKDF2-HMAC-RIPEMD160 + XTS 1536 bit + boot-mode (Iterations: 327661)

Speed.#1.........:     1567 H/s (68.61ms) @ Accel:64 Loops:32 Thr:256 Vec:1

Hashmode: 13751 - VeraCrypt PBKDF2-HMAC-SHA256 + XTS 512 bit (Iterations: 500000)

Speed.#1.........:     3050 H/s (46.39ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 13752 - VeraCrypt PBKDF2-HMAC-SHA256 + XTS 1024 bit (Iterations: 500000)

Speed.#1.........:     1521 H/s (93.00ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 13753 - VeraCrypt PBKDF2-HMAC-SHA256 + XTS 1536 bit (Iterations: 500000)

Speed.#1.........:      997 H/s (71.03ms) @ Accel:64 Loops:32 Thr:256 Vec:1

Hashmode: 13761 - VeraCrypt PBKDF2-HMAC-SHA256 + XTS 512 bit + boot-mode (Iterations: 200000)

Speed.#1.........:     7686 H/s (92.24ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 13762 - VeraCrypt PBKDF2-HMAC-SHA256 + XTS 1024 bit + boot-mode (Iterations: 200000)

Speed.#1.........:     3806 H/s (92.96ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 13763 - VeraCrypt PBKDF2-HMAC-SHA256 + XTS 1536 bit + boot-mode (Iterations: 200000)

Speed.#1.........:     2506 H/s (70.71ms) @ Accel:64 Loops:32 Thr:256 Vec:1

Hashmode: 13800 - Windows Phone 8+ PIN/password

Speed.#1.........:  1869.1 MH/s (75.91ms) @ Accel:128 Loops:64 Thr:256 Vec:2

Hashmode: 13900 - OpenCart

Speed.#1.........:  4445.0 MH/s (63.79ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 14000 - DES (PT = $salt, key = $pass)

Speed.#1.........: 48357.2 MH/s (46.72ms) @ Accel:128 Loops:1024 Thr:256 Vec:1

Hashmode: 14100 - 3DES (PT = $salt, key = $pass)

Speed.#1.........:  2297.2 MH/s (61.68ms) @ Accel:8 Loops:1024 Thr:256 Vec:1

Hashmode: 14400 - sha1(CX)

Speed.#1.........:   759.7 MH/s (93.37ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 14600 - LUKS (Iterations: 163044)

Speed.#1.........:    20316 H/s (9.78ms) @ Accel:2 Loops:1024 Thr:256 Vec:1

Hashmode: 14700 - iTunes backup < 10.0 (Iterations: 9999)

Speed.#1.........:   351.9 kH/s (80.56ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 14800 - iTunes backup >= 10.0 (Iterations: 9999999)

Speed.#1.........:      321 H/s (2.54ms) @ Accel:2 Loops:250 Thr:256 Vec:1

Hashmode: 14900 - Skip32 (PT = $salt, key = $pass)

Speed.#1.........:  9635.7 MH/s (1.57ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 15000 - FileZilla Server >= 0.9.55

Speed.#1.........:  2491.5 MH/s (56.87ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 15100 - Juniper/NetBSD sha1crypt (Iterations: 19999)

Speed.#1.........:   359.4 kH/s (79.00ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 15200 - Blockchain, My Wallet, V2 (Iterations: 5000)

Speed.#1.........:   702.1 kH/s (78.67ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 15300 - DPAPI masterkey file v1 (Iterations: 23999)

Speed.#1.........:   150.5 kH/s (78.47ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 15400 - ChaCha20

Speed.#1.........:  8580.6 MH/s (66.01ms) @ Accel:128 Loops:256 Thr:256 Vec:1

Hashmode: 15500 - JKS Java Key Store Private Keys (SHA1)

Speed.#1.........: 17241.9 MH/s (65.77ms) @ Accel:128 Loops:512 Thr:256 Vec:1

Hashmode: 15600 - Ethereum Wallet, PBKDF2-HMAC-SHA256 (Iterations: 262143)

Speed.#1.........:    12624 H/s (85.62ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 15700 - Ethereum Wallet, SCRYPT (Iterations: 1)

Speed.#1.........:       10 H/s (3568.12ms) @ Accel:1 Loops:1 Thr:1 Vec:1

Hashmode: 15900 - DPAPI masterkey file v2 (Iterations: 7999)

Speed.#1.........:   129.1 kH/s (68.74ms) @ Accel:256 Loops:128 Thr:32 Vec:1

Hashmode: 16000 - Tripcode

Speed.#1.........:   330.0 MH/s (53.68ms) @ Accel:64 Loops:16 Thr:256 Vec:1

Hashmode: 16100 - TACACS+

Speed.#1.........: 32991.2 MH/s (68.77ms) @ Accel:128 Loops:1024 Thr:256 Vec:1

Hashmode: 16200 - Apple Secure Notes (Iterations: 19999)

Speed.#1.........:   166.3 kH/s (85.29ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 16300 - Ethereum Pre-Sale Wallet, PBKDF2-HMAC-SHA256 (Iterations: 1999)

Speed.#1.........:  1626.1 kH/s (82.83ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 16400 - CRAM-MD5 Dovecot

Speed.#1.........: 59065.6 MH/s (38.26ms) @ Accel:128 Loops:1024 Thr:256 Vec:4

Hashmode: 16500 - JWT (JSON Web Token)

Speed.#1.........:  1432.4 MH/s (49.37ms) @ Accel:128 Loops:32 Thr:256 Vec:1

Hashmode: 16600 - Electrum Wallet (Salt-Type 1-3)

Speed.#1.........:   332.1 MH/s (53.34ms) @ Accel:64 Loops:16 Thr:256 Vec:1

Hashmode: 16700 - FileVault 2 (Iterations: 19999)

Speed.#1.........:   165.9 kH/s (85.49ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 16800 - WPA-PMKID-PBKDF2 (Iterations: 4096)

Speed.#1.........:   861.8 kH/s (80.26ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 16801 - WPA-PMKID-PMK (Iterations: 1)

Speed.#1.........:   165.7 MH/s (0.01ms) @ Accel:128 Loops:1 Thr:256 Vec:1

Hashmode: 16900 - Ansible Vault (Iterations: 9999)

Speed.#1.........:   333.3 kH/s (85.12ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Hashmode: 17300 - SHA3-224

Speed.#1.........:  1847.4 MH/s (76.75ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 17400 - SHA3-256

Speed.#1.........:  1851.2 MH/s (76.61ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 17500 - SHA3-384

Speed.#1.........:  1857.3 MH/s (76.36ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 17600 - SHA3-512

Speed.#1.........:  1850.6 MH/s (76.60ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 17700 - Keccak-224

Speed.#1.........:  1850.7 MH/s (76.62ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 17800 - Keccak-256

Speed.#1.........:  1839.5 MH/s (77.07ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 17900 - Keccak-384

Speed.#1.........:  1849.7 MH/s (76.64ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 18000 - Keccak-512

Speed.#1.........:  1845.4 MH/s (76.81ms) @ Accel:128 Loops:64 Thr:256 Vec:1

Hashmode: 18100 - TOTP (HMAC-SHA1)

Speed.#1.........:  3118.5 MH/s (90.96ms) @ Accel:128 Loops:128 Thr:256 Vec:1

Started: Mon Dec 03 21:35:38 2018
Stopped: Mon Dec 03 22:25:30 2018