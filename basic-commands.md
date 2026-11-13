# دستورات پایه Git

# دستورات پایه Git

## Git چیست؟
Git یک سیستم کنترل نسخه است. یعنی تاریخچهٔ تغییرات پروژهٔ شما را نگه می‌دارد و اجازه می‌دهد به نسخه‌های قبلی برگردید یا چند نفر هم‌زمان روی یک پروژه کار کنند. GitHub سایتی است که پروژه‌های Git را روی اینترنت نگه می‌دارد و کار تیمی را ساده می‌کند.

## نصب و تنظیم اولیه
بعد از نصب Git از git-scm.com، نام و ایمیل خود را یک بار تنظیم کنید:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

## ساخت یا دریافت پروژه
```bash
git init
git clone <repository-url>
```
## دستورات روزمره
```bash
git status                    # دیدن وضعیت فایل‌ها
git add file.txt              # آماده‌سازی یک فایل برای ثبت
git add .                     # آماده‌سازی همهٔ تغییرات
git commit -m "Add login page"  # ثبت تغییرات با یک پیام معنادار
git log --oneline             # دیدن تاریخچه
git push                      # ارسال کامیت‌ها به GitHub
git pull                      # دریافت آخرین تغییرات از GitHub
```

## نوشتن پیام کامیت خوب
پیام کامیت باید کوتاه و گویا باشد، مثلا `Fix typo in README` بهتر از `update` است.

## دستورات روزمره
```bash
git status                    # دیدن وضعیت فایل‌ها
git add file.txt              # آماده‌سازی یک فایل برای ثبت
git add .                     # آماده‌سازی همهٔ تغییرات
git commit -m "Add login page"  # ثبت تغییرات با یک پیام معنادار
git log --oneline             # دیدن تاریخچه
git push                      # ارسال کامیت‌ها به GitHub
git pull                      # دریافت آخرین تغییرات از GitHub
```

## نوشتن پیام کامیت خوب
پیام کامیت باید کوتاه و گویا باشد، مثلا `Fix typo in README` بهتر از `update` است.
