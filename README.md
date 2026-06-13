# Life OS - Age 38 PWA

این نسخه یک PWA واقعی است و شامل این فایل‌هاست:

- index.html
- manifest.webmanifest
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png

## آیا می‌توانم روی Google Drive آپلود کنم؟

برای نگهداری فایل‌ها بله، اما برای نصب شدن مثل اپ معمولاً نه.
Google Drive دیگر سرویس web hosting مستقیم ندارد و PWA برای نصب باید از یک آدرس HTTPS واقعی اجرا شود.

## پیشنهاد ساده

بهترین گزینه‌های رایگان:
1. GitHub Pages
2. Netlify Drop
3. Cloudflare Pages

## روش سریع با Netlify Drop

1. فایل ZIP را باز کن.
2. پوشه `life-os-age-38-pwa` را بکش و داخل Netlify Drop رها کن.
3. لینک https که می‌دهد را در Chrome اندروید باز کن.
4. منوی سه نقطه را بزن و Install app یا Add to Home screen را انتخاب کن.

## روش GitHub Pages

1. یک repository جدید بساز.
2. فایل‌های داخل پوشه `life-os-age-38-pwa` را در ریشه repository آپلود کن.
3. از Settings > Pages، branch را روی main و folder را روی root بگذار.
4. لینک GitHub Pages را روی گوشی باز کن.
5. از Chrome گزینه Install app یا Add to Home screen را بزن.

## بکاپ داده‌ها

داده‌ها در مرورگر/اپ ذخیره می‌شوند. هر چند وقت یک بار از بخش «داده‌ها» خروجی JSON بگیر.
