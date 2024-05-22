# نام و نام خانوادگی:فرید موسوی
# موضوع: data type ها در پایگاه داده
توی پایگاه داده، data type ها (نوع داده) برای مشخص کردن نوع اطلاعاتی که هر ستون در یک جدول می‌تونه ذخیره کنه، استفاده می‌شن. مثلا یه ستون می‌تونه اعداد صحیح، تاریخ، متن یا یه رشته باینری رو ذخیره کنه.

انتخاب data type مناسب برای هر ستون خیلی مهمه، چون نه تنها بر کارایی پایگاه داده، بلکه بر دقت و صحت اطلاعات ذخیره شده هم تاثیر می‌ذاره.

در اینجا یه خلاصه از رایج‌ترین data type ها در پایگاه داده ارائه شده:

1.اعداد:
<h4 dir="rtl"> INT: برای ذخیره اعداد صحیح بین -2,147,483,648 تا 2,147,483,647 استفاده می‌شه.</h4>
<h4 dir="rtl"> BIGINT: برای ذخیره اعداد صحیح بزرگتر بین -9,223,372,036,854,775,808 تا 9,223,372,036,854,775,807 استفاده می‌شه.</h4>
<h4 dir="rtl"> FLOAT: برای ذخیره اعداد اعشاری با دقت متوسط استفاده می‌شه.</h4>
<h4 dir="rtl"> DECIMAL: برای ذخیره اعداد اعشاری با دقت بالا و بدون گرد شدن استفاده می‌شه.</h4>


2.تاریخ و زمان:
<h4 dir="rtl"> DATE: برای ذخیره تاریخ به صورت YYYY-MM-DD استفاده می‌شه.</h4>
<h4 dir="rtl"> TIME: برای ذخیره زمان به صورت HH:MM:SS استفاده می‌شه.</h4>
<h4 dir="rtl"> DATETIME: برای ذخیره تاریخ و زمان به صورت YYYY-MM-DD HH:MM:SS استفاده می‌شه.</h4>


3.متن:
<h4 dir="rtl"> VARCHAR: برای ذخیره رشته‌های متنی با طول متغیر تا حداکثر 4000 کاراکتر استفاده می‌شه.</h4>
<h4 dir="rtl"> CHAR: برای ذخیره رشته‌های متنی با طول ثابت تا حداکثر 255 کاراکتر استفاده می‌شه.</h4>
<h4 dir="rtl"> TEXT: برای ذخیره رشته‌های متنی با طول خیلی زیاد (تا 2 گیگابایت) استفاده می‌شه.</h4>


4.دوعرضی:
<h4 dir="rtl"> BINARY: برای ذخیره داده‌های دوعرضی، مثل تصاویر یا فایل‌ها استفاده می‌شه.</h4>


5.سایر data type ها:
<h4 dir="rtl"> BOOLEAN: برای ذخیره مقادیر درست یا غلط استفاده می‌شه.</h4>
<h4 dir="rtl"> CURSOR: برای اشاره به مجموعه نتایج یه پرس و جو استفاده می‌شه.</h4>

این فقط یه خلاصه کوتاه از data type ها در پایگاه داده بود. انواع مختلفی از data type ها در سیستم‌های مختلف مدیریت پایگاه داده وجود داره و هر کدوم ویژگی‌ها و کاربردهای خاص خودشون رو دارن. برای یادگیری بیشتر در مورد data type ها، می‌تونید به مستندات سیستم مدیریت پایگاه داده که اگر ازش استفاده می‌کنید مراجعه کنید.
