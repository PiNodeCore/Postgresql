# PostgreSQL Persian Date Functions
A repository of custom PostgreSQL functions and extensions. To convert date from Gregorian to Hijri and also Hijri  to Gregorian ,


# توابع تبدیل تاریخ میلادی به شمسی در دیتابیس پستگرس
جهت ساخت یک تقویم شمسی در دیتا بیس پستگرس ابتدا شما تابع تبدیل تاریخ میلادی به شمسی را که با دو الگوریتم مختلف در این مخزن موجود میباشد را با اجرای یکی از آنها ایجاد نمایید. سپس در ادامه کار با اجرا کوئری ساخت تقویم شما یک جدول به صورت یک تقویم در دیتا بیس خود خواهید داشت که در آینده با استفاده از جوینت به این جدول از محاسبه دوباره تبدیل تاریخ بی نیاز میشود و سرعت پردازش های کوئری شما نیز بالاتر خواهد رفت .


### در این مخزن از توابع تبدیل تاریخ میلادی به شمسی در آدرس و مخزن زیر استفاده شده است
 تابع تبدیل تاریخ در مخزن موجود در این آدرس   https://github.com/mehdipourfar/pg_jalali_format/blob/master/format_jalali.sql  برگرفته شده است


# The conversion date is adapted from this address
Convert Date to Persian and Create Calendar Hijri


## Creating a Custom Solar Calendar Hijri by Sql 
Using this script, you can store an Hijri solar calendar and a Gregorian calendar in a table so that you can use the connection with this table to convert dates in your queries.








