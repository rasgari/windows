# windows

صفحه در حال به روز رسانی می باشد

windows :


دستورات کاربردی ویندوز

cmd ===>>> Command Prompt


%temp% ===>>> trash

temp ===>>> trash

prefetch ===>>> trash

Start ===>>> Disk Cleanup → انتخاب درایو → پاک‌کردن Temporary files، Thumbnail

ncpa.cpl ===>>> config network

cmd ===>>> ping "ipaddress"

cmd ===>>> tracert -d "ipaddress"

appwiz.cpl ===>>> config application

firewall.cpl ===>>> config firewall

mstsc ===>>> Microsoft Terminal Services Client

dxdiag ===>>> DirectX Diagnostic Tool

shell:startup

winver ===>>> Windows Version

history:recent

winget install {name program}

Services.msc  ===>>> windows update ===>>> stop

Services.msc  ===>>> SysMain ===>>> stop

service ===>>> cmd ===>>> net stop elasticsearch , net start elasticsearch & task manager ===>>> service ===>>> application 

tasklist ===>>> list program

taskkill /IM firefox.exe  /F ===>>> remove program <<<=== taskkill /IM program.exe  /F

netplwiz ===>>> create user

diskmgmt.msc ===>>> disk management

winget upgrade --all ===>>> winget upgrade


msinfo32 ===>>> system information
mrt ===>>>  virus Quick Scan 
shutdown -a ===>>> shut down

active connections ===>>> netstat -a

sysdm.cpl ===>>> advance ===>>> setting  Performance ===>>>  Adjust for best performance

setting ===>>> windows + I 

Windows Sandbox ===>>> Control Panel ===>>> Turn Windows features on or off ===>>> Windows Sandbox


WINDOWS SPEED:


- update windows ===>>> windows + I ===>>> update& security
  
- background appp ===>>> disable

- task manager ===>>> startup ===>>> disable
  
- windows + R ===>>> msconfig ===>>> disable software windows ===>>> services
  
- windows + R ===>>> mrt ===>>> malicious software removal tool

- windows + R ===>>> task scheduler 

- windows + R ===>>> Administrator ===>>> net status software ===>>> status ( start, stop, restart ) ===>>> net start Acunetix

increase power GPU:


- Win + I ===>>> System → Display → Graphics ===>>> browser ===>>> programmer


windows update blocker ===>>> software install

=============================================================

notepad++
- close: alt + 1
- open: alt + shift + 1

=============================================================

کلید M + Windows :
همه نرم افزار هارو Minimize میکنه برات

کلید کلید Space + Windows :
یه شورت‌کات جدید برای تغییر زبان کیبورد

کلید D + Windows :
هرجایی باشی میبرتت به دسکتاپ

کلید S + Shift + Windows : 
گرفتن اسکرین شات از صفحه یا انتخاب بخشی

کلید U + U + X + Windows :
سریع ترین راه برای خاموش کردن کامپیوتر

کلید G + Windows 
نمایش تمامی ویدیو هایی که داری

کلید B + Shift + Ctrl + Windows 
 برای ریست کردن کارت گرافیک و حل بلک اسکرین

کلید L + Windows
اگه داشتی فیلم آموزشی میدی یهو کسی اومد تو اتاق 

کلید P + Windows 
اگه میخوایی تصویر رو روی مانیتور دوم بندازی

کلید Ctrl + Shift + Esc
اگه میخوای شناسایی پردازش‌های سنگین تو Task Manager



=============================================================


یکی از مشکلات ادمینها و بخصوص امنیت کارها اینکه نمی دونند کدام نرم افزارهای یک سیستم نیاز به بروزرسانی داره، خوب این کار خیلی راحته اول یه cmd ادمینی باز کنید و دستور
```bash
winget upgrade
```
رو بزنید، لیست اپ ها و نرم افزارهائیکه نیاز به بروزرسانی دارند رو نشون میده، حالا ممکنه بخواهید همشون بروزرسانی بشن می تونید از دستور
```bash
winget upgrade  --all
```
استفاده کنید.



=============================================================

قبل از انجام این مراحل، مطمئن شوید که فلش مورد نظر را انتخاب کرده‌اید. چون تمام داده‌های آن پاک خواهند شد.
مراحل:

باز کردن diskpart

لیست کردن دیسک‌ها: list disk

انتخاب دیسک مورد نظر: select disk X (به جای X شماره دیسک فلش را وارد کنید)

پاک کردن تمام داده‌ها: clean

ایجاد پارتیشن اولیه: create partition primary

انتخاب پارتیشن: select partition 1

فرمت کردن: format fs=ntfs quick (یا fs=fat32 یا fs=exfat)

اختصاص حرف درایو: assign

خروج: exit

=============================================================

 اگر بخواهید سرویس های ویندوز فعال، غیرفعال یا ریستارت کنید 
 قسمت task manager بخش services میتونید با کلیک راست این 3تا عمل اجرایی کنید

=============================================================

✨ کلیدهای میانبر کاربردی ویندوز که کارتو راحت می‌کنن 👇

🖥 Win + D → رفتن سریع به دسکتاپ
📂 Win + E → باز کردن فایل اکسپلورر
🔒 Win + L → قفل کردن فوری سیستم
📊 Ctrl + Shift + Esc → باز کردن Task Manager
📸 Win + Shift + S → اسکرین‌شات انتخابی
↔️ Alt + Tab → جابه‌جایی سریع بین برنامه‌ها
⚙️ Win + I → ورود سریع به تنظیمات
↔️↕️ Win + Arrow Keys → چسباندن پنجره‌ها به اطراف صفحه

===========================================
