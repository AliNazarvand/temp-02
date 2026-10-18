# Usage & Budget — Final Completed State

- وضعیت: تکمیل‌شده تا فاز ۳ و آماده بررسی دستی
- baseline: `440e3e0d6a57c9b529e8bb1aef55df451edc0389`
- شاخه: `ai/full-completion`
- آخرین commit: `51cff8280bfed4201d73e0582f2146bc892a6e5a`
- مصرف API خارجی: صفر
- فراخوانی مدل خارجی: صفر
- تست کامل: ۵۳ passed، coverage برابر ۹۷٫۹۶٪
- تست قابلیت‌ها: ۱۹ passed
- Ruff نهایی: موفق، بدون finding
- mypy نهایی: موفق، ۲۲ فایل source بدون issue
- Schemaهای اعتبارسنجی‌شده: ۲۱
- رکوردهای JSONL اعتبارسنجی‌شده: ۲۵۲۲
- اجرای generator نهایی: idempotent، ۰ فایل تغییرکرده در اجرای دوم
- smoke compile هدرهای C++17: موفق
- encoding/secret/license/size scan: انجام‌شده؛ secret scan از نوع basic regex بود چون gitleaks و detect-secrets نصب نبودند.
- push/PR/Issue/Release/Gist/آپلود خارجی: انجام نشد.

جزئیات ماشین‌خوان در `usage.json`، محدودیت‌ها در `budget.yaml` و دسته‌بندی lint/mypy در `lint-mypy-categorization.md` است.
