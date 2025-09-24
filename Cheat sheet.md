📌 Cheat Sheet شبکه

🔹 ۱. مبانی (Fundamentals)

OSI, TCP/IP

IP Addressing (IPv4/IPv6)

Subnetting


🔹 ۲. تجهیزات (Devices)

Switch, Router, Firewall

Access Point, Hub, Bridge

کابل مسی / فیبر


🔹 ۳. پروتکل‌ها (Protocols)

TCP/UDP

DNS, DHCP, HTTP/HTTPS, FTP, SMTP

Routing: OSPF, BGP, RIP, EIGRP


🔹 ۴. طراحی و توپولوژی (Topology)

LAN, WAN, VLAN

VPN, MPLS

SDN


🔹 ۵. سیستم‌عامل‌ها و سرویس‌ها

Windows Server: AD, DNS, DHCP

Linux Networking: iptables, routing


🔹 ۶. امنیت شبکه (Security)

Firewall, IDS/IPS

VPN, Encryption

حملات: DoS, MITM, Spoofing


🔹 ۷. مانیتورینگ (Monitoring)

SNMP, Syslog

ابزارها: Wireshark, Nagios, Zabbix, PRTG


🔹 ۸. وایرلس و موبایل

Wi-Fi (802.11 a/b/g/n/ac/ax)

WPA2/WPA3

4G/5G


🔹 ۹. کلود و مجازی‌سازی

AWS VPC, Azure VNets, GCP VPC

VMware, Hyper-V

Docker / Kubernetes Networking


🔹 ۱۰. عیب‌یابی (Troubleshooting)

ابزارها: ping, traceroute, nslookup, nmap, netstat

روش لایه‌ای (OSI Layer by Layer)

---

📌 لایه‌های OSI (Open Systems Interconnection)

🔹 ۷ لایه از پایین به بالا:

1. Physical (فیزیکی)

وظیفه: انتقال بیت‌ها (0 و 1) روی رسانه فیزیکی

مثال: کابل شبکه (UTP, Fiber)، هاب، ریپیتر



2. Data Link (لینک داده)

وظیفه: انتقال فریم‌ها بین دستگاه‌های یک شبکه محلی

آدرس‌دهی: MAC Address

مثال: Switch, Ethernet, ARP, PPP



3. Network (شبکه)

وظیفه: مسیریابی بسته‌ها بین شبکه‌ها

آدرس‌دهی: IP Address

مثال: Router, IP, ICMP



4. Transport (انتقال)

وظیفه: اطمینان از تحویل داده به صورت صحیح و کامل

پروتکل‌ها: TCP (قابل اعتماد)، UDP (سریع)



5. Session (نشست)

وظیفه: مدیریت و نگهداری Session بین دو سیستم

مثال: NetBIOS, RPC



6. Presentation (ارائه)

وظیفه: تبدیل، فشرده‌سازی و رمزنگاری داده

مثال: SSL/TLS, JPEG, GIF



7. Application (کاربرد)

وظیفه: نزدیک‌ترین لایه به کاربر، سرویس‌ها و اپلیکیشن‌ها

مثال: HTTP, FTP, DNS, SMTP





---

📌 نکته سریع برای به‌خاطر سپردن ترتیب لایه‌ها:
🔽 از بالا به پایین: All People Seem To Need Data Processing
(Application – Presentation – Session – Transport – Network – Data Link – Physical)

---


