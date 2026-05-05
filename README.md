<div align="center">
  <img src="https://raw.githubusercontent.com/amiraction0938/Downloader-file/main/dl-icon.gif" width="200" alt="News Archive" />
  <h1>🗞️ آرشیو مطبوعات آزاد – بدون فیلتر، بدون VPN</h1>
  <p>
    <a href="https://github.com/amiraction0938/Downloader-file/actions"><img src="https://img.shields.io/github/actions/workflow/status/amiraction0938/Downloader-file/news-archiver.yml?label=News%20Archiver&logo=github" alt="News Archiver" /></a>
    <a href="https://actionfamily.lol/"><img src="https://img.shields.io/badge/Site-actionfamily.lol-ff6b6b?logo=google-chrome" alt="Website" /></a>
    <img src="https://img.shields.io/badge/Proxy-WARP-cyan?logo=cloudflare" alt="WARP Proxy" />
    <img src="https://img.shields.io/badge/Status-Online-brightgreen" alt="Online" />
  </p>
  <p><i>با یک کلیک، از مهم‌ترین رسانه‌های خبری فارسی‌زبان جهان اسکرین‌شات بگیر و برای همیشه در گیت‌هاب خودت آرشیو کن.</i></p>
</div>

---

## 🌐 فهرست رسانه‌های خبری فارسی‌زبان (خارج از کشور)

> تمامی این رسانه‌ها در ایران فیلتر هستند اما با ابزار **News Archiver** این ریپازیتوری بدون هیچ دردسری در دسترس شما قرار می‌گیرند.  
> کافیست روی نام هر رسانه کلیک کنید تا به وب‌سایت اصلی آن هدایت شوید، یا از workflow برای آرشیو روزانه استفاده نمایید.

| 📡 رسانه | 🏷️ توضیح | 🌍 لینک اصلی | 🖼️ آخرین اسکرین‌شات |
|----------|-----------|--------------|----------------------|
| **BBC Persian** | بخش فارسی بی‌بی‌سی، پوشش گسترده اخبار ایران و جهان | [bbc.com/persian](https://www.bbc.com/persian) | *(با اجرای دستی workflow)* |
| **VOA Persian** | صدای آمریکا (بخش فارسی) | [ir.voanews.com](https://ir.voanews.com) | *–* |
| **Radio Farda** | رادیو فردا (اخبار، پادکست، تحلیل) | [radiofarda.com](https://www.radiofarda.com) | *–* |
| **Iran International** | ایران اینترنشنال (پوشش ۲۴ ساعته ایران) | [iranintl.com](https://www.iranintl.com) | *–* |
| **Manoto TV** | من و تو (خبر و سرگرمی) | [manoto.tv](https://www.manoto.tv) | *–* |
| **Kayhan London** | کیهان لندن | [kayhan.london](https://kayhan.london) | *–* |
| **Radio Zamaneh** | رادیو زمانه (تحلیل و گزارش) | [radiozamaneh.com](https://www.radiozamaneh.com) | *–* |
| **Radio Koochek** | رادیو کوچک (موسیقی و خبر) | [radiokoocheh.com](https://radiokoocheh.com) | *–* |
| **Independent Persian** | ایندیپندنت فارسی | [independentpersian.com](https://www.independentpersian.com) | *–* |
| **Euronews Persian** | یورونیوز فارسی | [euronews.com/persian](https://per.euronews.com) | *–* |

---

## ⚡ چطور از آرشیو خبری استفاده کنم؟

1. به تب **Actions** بروید.
2. workflow با نام **`📰 News Archiver (Screenshot blocked sites)`** را انتخاب کنید.
3. روی **Run workflow** کلیک کنید.
4. آدرس کامل یکی از رسانه‌های بالا را وارد کنید (مثلاً `https://www.bbc.com/persian`).
5. منتظر بمانید تا workflow سبز شود.
6. به پوشه `news/` در ریپازیتوری بروید، اسکرین‌شات صفحه را ببینید و برای همیشه نگه دارید.

> ✨ می‌توانید با تنظیم **cron** در فایل workflow، از هر رسانه به‌طور خودکار هر روز اسکرین‌شات تهیه کنید.

---

## 📥 خروجی‌ها کجا ذخیره می‌شوند؟

هر بار اجرای workflow، یک پوشه‌ی جدید در مسیر `news/<domain>/<timestamp>/` می‌سازد که شامل:

- `screenshot.png` → عکس کامل تمام صفحه (Full Page)
- `thumb.png` → نمای بالای صفحه (تصویر کوچک)
- `info.txt` → عنوان صفحه و زمان ثبت

---

<div align="center">
  <p>🌟 <strong>بدون VPN، بدون فیلتر، بدون هیچ هزینه‌ای</strong> – فقط با قدرت گیت‌هاب و پروکسی WARP</p>
  <p><sub>Made with ❤️ by <strong>amiraction</strong> | <a href="https://actionfamily.lol/">actionfamily.lol</a></sub></p>
</div>
