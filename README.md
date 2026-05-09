<div align="center">
  <img src="https://raw.githubusercontent.com/amiraction/youtube-dl/main/video-icon.gif" width="400" alt="YouTube Downloader Magic" />
  <h1>✨ YouTube Magic Downloader ✨</h1>
  <p>
    <a href="https://github.com/amiraction0938/YT-dl"><img src="https://img.shields.io/github/stars/amiraction0938/YT-dl?style=social" alt="Stars" /></a>
    <a href="https://github.com/amiraction0938/YT-dl/actions"><img src="https://img.shields.io/github/actions/workflow/status/amiraction0938/YT-dl/YT-downloader.yml?branch=main&label=Workflow&logo=github" alt="Build" /></a>
    <a href="https://actionfamily.lol/"><img src="https://img.shields.io/badge/Official%20Site-actionfamily.lol-%23ff6b6b?style=flat&logo=google-chrome" alt="Website" /></a>
  </p>
</div>

---

**🎥 با این پروژۀ جادویی می‌توانید هر ویدئوی یوتیوب را به‌طور دائمی در ریپازیتوری خود ذخیره کنید و هر زمان که خواستید دانلود کنید یا به‌صورت آنلاین تماشا کنید.**

دیگر نگران حذف ویدئوها از یوتیوب نباشید! ویدئوهایتان مستقیماً وارد گیت‌هاب شخصی‌تان می‌شوند و برای همیشه می‌مانند.

### 🌟 ویژگی‌های کلیدی

- ✅ **ذخیره‌سازی تمام‌خودکار** – بدون نیاز به هیچ کار اضافه
- ✅ **نصب و راه‌اندازی فوق‌العاده ساده** (فقط یک Fork)
- ✅ **سرعت بالا** – کش کردن WARP، apt و pip (اجراهای بعدی چند برابر سریع‌تر)
- ✅ **تشخیص هوشمند WARP** – بررسی هر ۱ ثانیه به‌جای ۳۰ ثانیه صبر کردن
- ✅ **شکستن خودکار ویدئوهای حجیم** به قطعات ۹۰ مگابایتی و Zip شدن آن‌ها
- ✅ **ذخیره در شاخه جدید** (اختیاری) – شاخهٔ اصلی همیشه تمیز می‌ماند
- ✅ **سیستم عبور از محدودیت (bypass)** برای دانلود بی‌دردسر از یوتیوب
- ✅ **انتخاب کیفیت ویدئو** (از ۴۸۰p تا ۴K)
- ✅ **دانلود فقط صوت (mp3)** همراه با کاور
- ✅ **تاریخچهٔ کاملاً پاک و سبک** – حجم کلون حدود ۲۹ مگابایت

---

## ⚙️ نصب (فقط یک بار)

۱. روی دکمۀ **Fork** در بالای همین صفحه کلیک کنید.  
۲. نام دلخواه بگذارید و **Create fork** را بزنید.  
۳. پروژه شما آماده است!

> ⚠️ حجم هر ریپازیتوری گیت‌هاب ۴ گیگابایت است. اگر پر شد، یک فورک تازه از [همین پروژه](https://github.com/amiraction0938/YT-dl) بسازید.

---

## 🎞️ روش استفاده

۱. به تب **Actions** بروید.  
۲. از سمت چپ، روی **Youtube Downloader** کلیک کنید.  
۳. روی **Run workflow** کلیک کنید و تنظیمات زیر را انجام دهید:

| فیلد | توضیح | پیش‌فرض |
|------|-------|---------|
| `youtube_url` | آدرس ویدئو | *(الزامی)* |
| `quality` | `best`, `1080`, `720`, `480`, `audio` | `best` |
| `split_threshold_mb` | قطعات چند مگابایتی (۰ = بدون تقسیم) | `90` |
| `save_in_new_branch` | ذخیره در یک شاخهٔ جداگانه (پیشنهاد برای تست) | `false` |

۴. روی **Run workflow** کلیک کنید.  
۵. پس از سبز شدن تیک، ویدئو در پوشهٔ `videos` (شاخهٔ `main`) یا در شاخهٔ جدید (اگر فعال کرده باشید) قرار می‌گیرد.

> 💡 اگر `save_in_new_branch = true` را انتخاب کرده‌اید، برای دیدن ویدئو:  
> **Branches** ← روی شاخهٔ جدید کلیک کنید (نامش شبیه `video-20260510-143022-a1b2c3` است).

---

## 🧹 پاک کردن ویدیوها

برای خالی کردن پوشهٔ `videos`:  
۱. به **Actions** بروید.  
۲. روی **Clean videos folder** کلیک کنید.  
۳. **Run workflow** را بزنید.  
تمام محتویات پوشهٔ `videos` از شاخهٔ اصلی حذف خواهد شد.

---

## 🔔 همیشه به‌روز باشید

در ریپازیتوری فورک‌شده‌تان روی **Sync fork** ← **Update branch** کلیک کنید تا آخرین تغییرات را دریافت کنید.

---

## ❓ پرسش‌های رایج

<details>
<summary><strong>چرا حجم Clone اینقدر کم است؟</strong></summary>
تاریخچه با BFG پاکسازی شده و فایل‌های حجیم قدیمی کاملاً حذف شده‌اند.
</details>
<details>
<summary><strong>چطور فایل‌های Zip شده را باز کنم؟</strong></summary>
همهٔ پارت‌ها را در یک پوشه بگذارید و با 7-Zip یا WinRAR فایل `.zip` را استخراج کنید.
</details>
<details>
<summary><strong>می‌توانم ویدیوها را آنلاین ببینم؟</strong></summary></details>

---

---

<div align="center">
  <sub>Made with ❤️ by <strong>amiraction</strong> – برای همیشه در گیت‌هاب خودتان</sub>
</div>
