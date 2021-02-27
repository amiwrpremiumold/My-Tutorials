# گرفتن api id و api hash
ابتدا وارد سایت تلگرام میشویم.
<br>
https://my.telegram.org/auth
<br>
<br>
شماره موبایل را وارد کرده و در مرحله بعد کد تایید را وارد میکنیم.
<br>
<br>
روی گزینه‌ی 'API development tools' کلیک میکنیم.
<br>
<br>
app title و short name را به دلخواه وارد میکنیم.
<br>
url و platform مهم نیستند.
<br>
<br>
در نهایت دکمه create application را میزنیم.
<br>
<br>
در صفحه بعد، 'App api_id' و 'App api_hash' را در جایی ذخیره میکنیم.
<br>
<br>
<hr>

# تنظیمات سورس کد
فایل `config.py` را باز کرده و:
<br>
<br>
YOUR_API_ID_HERE ~> را با api id که در مرحله قبل گرفتیم عوض میکنیم
<br>
YOUR_API_HASH_HERE ~> را با api hash که در مرحله قبل گرفتیم عوض میکنیم
<br>
<br>
<hr>

# پیشنیاز ها
برای اجرای برنامه نیاز داریم python روی سیستم نصب باشد.
<br>
برای انجام اینکار روی لینک مورد نظر کلیک کنید:
<br>
[ویندوز](https://www.python.org/ftp/python/3.9.2/python-3.9.2-embed-amd64.zip)
<br>
[مک](https://www.python.org/ftp/python/3.9.2/python-3.9.2-macosx10.9.pkg)
<br>
<br>
<br>
بعد از نصب python ترمینال یا خط فرمان را باز کرده و دستور زیر را وارد میکنیم:
<br>
<br>
`pip install telethon`
<br>
`pip install prettytable`
<br>
`pip install termcolor`
<br>
`pip install colorama`
<br>
