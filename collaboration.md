# همکاری تیمی در GitHub

## افزودن Collaborator
مالک مخزن از مسیر Settings > Collaborators > Add people دیگران را دعوت می‌کند. فرد دعوت‌شده باید دعوت‌نامه را (از ایمیل یا GitHub) بپذیرد.

## Issue
Issue برای ثبت وظایف، باگ‌ها و ایده‌هاست. هر Issue عنوان، توضیح و مسئول (Assignee) دارد و می‌توان آن را به Pull Request وصل کرد.

=== کامیت دوم: (پیام پیشنهادی) Add pull request and review workflow ===
این متن را به انتهای فایل اضافه کنید:

## Pull Request (PR)
PR درخواستی است برای ادغام شاخهٔ شما در main. مراحل کار:
1. روی شاخهٔ خودتان کامیت کنید و Push کنید.
2. در GitHub روی Compare & pull request بزنید.
3. عنوان و توضیح بنویسید و در صورت امکان بنویسید `Closes #شماره-issue`.
4. دیگران PR را Review می‌کنند (Comment یا Approve).
5. بعد از تأیید، Merge pull request را بزنید.

## گردش کار پیشنهادی تیم
Issue ← Branch ← چند Commit ← Push ← Pull Request ← Review ← Merge



## گردش‌کار (Workflow) همکاری
1. `main` را به‌روز کنید: `git pull`
2. شاخهٔ جدید بسازید: `git switch -c feature-x`
3. تغییرات را کامیت و Push کنید
4. Pull Request بفرستید
5. هم‌تیمی Review کند و Approve بدهد
6. Merge کنید و شاخه را پاک کنید

## Issues و Pull Requests
- **Issue:** برای گزارش باگ یا پیشنهاد ویژگی
- **Pull Request:** برای ارسال تغییرات و درخواست Merge
- در توضیح PR بنویسید `Closes #شماره` تا Issue خودکار بسته شود

## قوانین همکاری خوب
- قبل از شروع کار، `main` را Pull کنید
- هر PR را کوچک و متمرکز نگه دارید
- پیام کامیت گویا بنویسید
- Review دیگران را جدی بگیرید
- در صورت Conflict، هم‌تیمی را در جریان بگذارید