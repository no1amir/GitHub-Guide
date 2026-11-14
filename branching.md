# Branch در Git

## Branch چیست؟
Branch یک شاخهٔ مستقل از پروژه است. با آن می‌توانید روی یک قابلیت جدید کار کنید بدون اینکه نسخهٔ اصلی (main) خراب شود. وقتی کارتان تمام شد، شاخه را با main ادغام می‌کنید.

## چرا از Branch استفاده کنیم؟
- هر نفر روی کار خودش بدون دخالت در کار دیگران کار می‌کند.
- نسخهٔ اصلی همیشه سالم می‌ماند.
- بررسی تغییرات (Review) ساده‌تر می‌شود.

=== کامیت دوم: (پیام پیشنهادی) Add branch commands to branching ===
این متن را به انتهای فایل اضافه کنید:

## دستورات Branch
```bash
git branch                       # فهرست شاخه‌ها
git branch feature-login         # ساخت شاخه
git switch feature-login         # رفتن به شاخه
git switch -c feature-login      # ساخت و رفتن هم‌زمان
git push -u origin feature-login # ارسال شاخه به GitHub
git branch -d feature-login      # حذف شاخهٔ ادغام‌شده
```

## نام‌گذاری شاخه‌ها
نام‌ها را گویا انتخاب کنید: `feature/login`، `fix/typo`، `docs/branching`.
