به نام خداوند جان و خرد

نام و نام خانوادگی	تاریخ آزمایش	شماره آزمایش
مینا زواری	چهارشنبه 22 اسفند	آزمایش شماره 8


عنوان: 
طراحی و پیاده‌سازی مدار رقص نور با استفاده از آردوینو
هدف آزمایش:
هدف اصلی این آزمایش، طراحی و پیاده‌سازی یک مدار رقص نور ساده با استفاده از برد آردوینو و چهار عدد لامپ LED که بر اساس یک الگوی از پیش تعریف شده روشن و خاموش می‌شوند.
تئوری آزمایش:
•	برد آردوینو UNO: این برد یک میکروکنترلر است که می‌تواند ورودی‌ها را از طریق پین‌های خود دریافت کرده و خروجی‌ها را کنترل کند. در این آزمایش، از پین‌های دیجیتال آردوینو برای کنترل لامپ‌های LED استفاده می‌شود.
•	لامپ LED: این قطعه یک دیود نورگسیل است که با عبور جریان الکتریکی از آن، نور تولید می‌کند.
•	مقاومت: برای محدود کردن جریان عبوری از LED و جلوگیری از سوختن آن، از یک مقاومت استفاده می‌شود.
•	کلید فشاری: از یک کلید فشاری برای ایجاد یک رویداد (فشردن کلید) و تولید یک عدد تصادفی استفاده می‌شود.
•	آرایه دوبعدی: در کد از یک آرایه دوبعدی به نام dancinglight1  برای تعریف الگوی روشن و خاموش شدن LED ها در مراحل مختلف استفاده شده است.




شرح مدار و قطعات مورد استفاده:
•	برد آردوینو UNO
•	4 عدد لامپ  LED 
•	4 عدد مقاومت (180 اهم و 10 کیلواهم)
•	یک عدد کلید فشاری
•	سیم‌های مخابراتی
•	برد بورد

روش انجام آزمایش:

روش انجام آزمایش:
1.	اتصالات سخت افزاری:
o	لامپ‌های LED را روی برد بورد قرار می‌دهیم.
o	یک سر مقاومت‌ها را به پایه آند (پایه بلندتر) هر یک از LED ها متصل می‌کنیم.
o	سر دیگر مقاومت مربوط به هر LED را با استفاده از سیم مخابراتی به پین‌های دیجیتال 0، 1، 2 و 3 برد آردوینو متصل می‌کنیم. به طور دقیق (بر اساس رنگ سیم‌ها در تصویر): 
	LED اول (بالا سمت چپ) به پین 0 (سیم زرد).
	LED دوم (بالا سمت راست) به پین 1 (سیم قهوه‌ای).
	LED سوم (پایین سمت چپ) به پین 2 (سیم قرمز).
	LED چهارم (پایین سمت راست) به پین 3 (سیم طلایی).
o	پایه کاتد (پایه کوتاه‌تر) هر چهار LED را با استفاده از سیم مخابراتی به یک ردیف مشترک روی برد بورد متصل می‌کنیم.
o	یک سر کلید فشاری را به یکی از ردیف‌های برد بورد متصل می‌کنیم. سر دیگر آن را به یک ردیف دیگر.
o	از مقاومت داخلی (10 کیلو اهم) Pull-up برای کلید (پایه B) استفاده شده است، بنابراین یک پایه کلید مستقیماً به پین 5V آردوینو (سیم آبی) متصل می‌شود.
o	پایه D  کلید فشاری نیز از طرف دیگر به پین 8  آردیونو متصل میشود.
o	پایه دیگر کلید فشاری (پایه C) به ردیف مشترک برد بورد متصل میشود (سیم مشکی).
o	ردیف زمین LED ها را با یک سیم قرمز به پین زمین (GND) برد آردوینو متصل می‌کنیم.





	
















2. برنامه نویسی آردوینو: 
o	برنامه آردوینو IDE را باز کنید.
o	کدهای زیر را در آن وارد کنید:










نتیجه گیری:
نتیجه‌گیری کلی آزمایش: در این آزمایش، هدف، طراحی و پیاده‌سازی یک مدار رقص نور با استفاده از برد آردوینو و چهار لامپ LED بود. نتایج به دست آمده نشان می‌دهد که:
•	مدار طراحی شده به درستی عمل می‌کند و با فشردن کلید، چهار لامپ LED بر اساس الگوی تعریف شده در آرایه dancinglight1 به صورت متوالی روشن می‌شوند و یک افکت رقص نور ساده ایجاد می‌کنند.
•	با استفاده از برد آردوینو و لامپ‌های LED، می‌توان الگوهای نورپردازی مختلف و پویا را پیاده‌سازی کرد.
•	کدهای نوشته شده برای آردوینو به درستی عمل کرده و با خواندن وضعیت کلید و اعمال الگوی نور به پین‌های خروجی، خروجی مورد نظر (رقص نور) را تولید می‌کنند.
•	این آزمایش نشان می‌دهد که می‌توان با استفاده از برد آردوینو و قطعات الکترونیکی ساده، مدارهای با رفتارهای نوری جذاب و قابل کنترل (از طریق ورودی مانند کلید) طراحی و پیاده‌سازی کرد.




![pull down](https://github.com/user-attachments/assets/e5eb38fb-4f51-4eb9-8bd5-b88c9b387c7c)
[pull down.pdf](https://github.com/user-attachments/files/19659029/pull.down.pdf)


https://github.com/user-attachments/assets/6051e1b0-655c-4221-857b-8a3c0c1ed084


