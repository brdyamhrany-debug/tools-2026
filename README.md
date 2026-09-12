# 🛡️ Ultimate Cyber Security Toolkit (50+ Tools)

مجموعه‌ای کامل از ابزارهای تست نفوذ و امنیت که برای سیستم‌عامل‌های مبتنی بر دبیان (Debian/Kali/Termux) گردآوری شده است. این لیست برای متخصصان امنیت و علاقه‌مندان به پن تست جهت دسترسی سریع طبقه‌بندی شده است.

---

## 📂 دسته‌بندی ابزارها

### 1. شناسایی و اسکن شبکه (Recon & Scanning)
1. **Nmap** - اسکن شبکه و کشف سرویس‌ها
2. **Masscan** - اسکنر پورت بسیار سریع
3. **RustScan** - اسکنر پورت سریع و مدرن
4. **Netcat (nc)** - چاقوی سوئیسی شبکه
5. **Zenmap** - رابط گرافیکی Nmap
6. **Nikto** - اسکنر آسیب‌پذیری وب‌سرور
7. **Angry IP Scanner** - اسکنر IP شبکه
8. **Sublist3r** - جستجوی ساب‌دامین‌ها
9. **Amass** - نگاشت سطح حمله (Attack Surface Mapping)
10. **Amap** - شناسایی اپلیکیشن‌های شبکه

### 2. تست نفوذ وب (Web Exploitation)
11. **Burp Suite** - پروکسی برای تست نفوذ وب
12. **OWASP ZAP** - اسکنر خودکار امنیت وب
13. **SQLmap** - تزریق خودکار SQL
14. **Gobuster** - پیدا کردن دایرکتوری‌ها و فایل‌ها
15. **Dirsearch** - اسکنر مسیرهای وب
16. **Wfuzz** - ابزار Brute Force وب
17. **XSStrike** - شناسایی و تست XSS
18. **Commix** - تست تزریق دستور (Command Injection)
19. **WhatWeb** - شناسایی تکنولوژی‌های سایت
20. **Arjun** - کشف پارامترهای مخفی HTTP

### 3. اکسپلویت و نفوذ (Exploitation)
21. **Metasploit Framework** - چارچوب قدرتمند اکسپلویت
22. **Searchsploit** - جستجوی اکسپلویت‌ها در Exploit-DB
23. **Beef-XSS** - چارچوب بهره‌برداری از مرورگر
24. **Social Engineering Toolkit (SET)** - ابزارهای مهندسی اجتماعی
25. **Empire** - عامل پس‌نفوذ (Post-Exploitation)
26. **Msfvenom** - تولید Payload
27. **Armitage** - رابط گرافیکی Metasploit
28. **Bettercap** - ابزار قدرتمند Man-in-the-Middle
29. **Evil-WinRM** - مدیریت از راه دور ویندوز
30. **Fluxion** - حمله به شبکه‌های Wi-Fi (مهندسی اجتماعی)

### 4. رمزنگاری و شکستن پسورد (Cracking & Hash)
31. **John the Ripper** - کرکر پسورد کلاسیک
32. **Hashcat** - سریع‌ترین ابزار کرک هش
33. **Hydra** - ابزار Brute Force شبکه
34. **Medusa** - ابزار تست پسورد موازی
35. **Cewl** - ساخت Wordlist از صفحات وب
36. **Crunch** - تولید Wordlist سفارشی
37. **RainbowCrack** - کرک هش با استفاده از Rainbow Tables
38. **RSATool** - ابزارهای رمزنگاری RSA
39. **CyberChef** - آچار فرانسه رمزنگاری و کدگذاری
40. **Cupp** - تولید لیست پسورد بر اساس اطلاعات کاربر

### 5. امنیت وایرلس (Wireless/WiFi)
41. **Aircrack-ng** - مجموعه ابزار تست امنیت وای‌فای
42. **Wifite2** - اتوماسیون حملات وای‌فای
43. **Kismet** - شناسایی و مانیتورینگ شبکه
44. **Reaver** - حمله به WPS
45. **Airgeddon** - اسکریپت چند منظوره وایرلس
46. **MDK4** - ابزارهای استرس و حمله به شبکه Wi-Fi
47. **Fern Wifi Cracker** - رابط گرافیکی برای حملات وای‌فای
48. **Cowpatty** - کرک WPA-PSK
49. **Hashid** - شناسایی نوع هش
50. **Pyrit** - محاسبات موازی WPA/WPA2

*(توجه: برای لیست کامل ۱۰۰ ابزار، می‌توانید سایر دسته‌ها نظیر Forensic، Anonymity و Android Hacking را به همین ترتیب اضافه کنید...)*

---

## 🛠️ نحوه نصب (مثال برای Debian/Kali)
برای نصب ابزارها معمولاً از apt استفاده می‌شود:
```bash
sudo apt update
sudo apt install nmap sqlmap metasploit-framework hydra

