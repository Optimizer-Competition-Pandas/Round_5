<p align="center">
  <a href="" rel="noopener">
</p>
<h3 align="center">Panda</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mtefagh/demos/HEAD)
  [![License](https://img.shields.io/badge/license-GPL-blue.svg)](https://github.com/mtefagh/demos/blob/master/LICENSE)

</div>

---

<p align="center"> 
    <br> 
</p>

## 📝 فهرست مطالب
- [صورت‌بندی سوال](#problem_statement)
- [الگوریتم بهینه‌سازی](#idea)
- [محدودیت‌ها](#limitations)
- [ایده‌های گسترش](#future_scope)
- [روند اجرا](#getting_started)
- [نحوه استفاده](#usage)
- [وابستگی‌ها](#tech_stack)
- [نویسندگان](#authors)
- [قدردانی](#acknowledgments)

## 🧐 صورت‌بندی سوال <a name = "problem_statement"></a>
<a href="https://ibb.co/RjncsSx"><img src="https://i.ibb.co/NThKJ38/5.png" alt="5" border="0"></a>
## 💡 الگوریتم بهینه‌سازی <a name = "idea"></a>

بازهم از جداسازی استفاده می‌کنیم. برای هر ستون یکبار مسأله بهینه‌سازی را با در نظر گرفتن قید

Sv=0

و یکبار هم بدون در نظر گرفتن این قید حل می‌کنیم و برای

K

ستونی که بهبود نرم یکشان از همه بیشتر بود این قید را درنظرنگرفته و برای بقیه ستون‌ها در نظر می‌گیریم. بقیه کار دقیقا مثل  مرحله سوم است
## ⛓️ محدودیت‌ها <a name = "limitations"></a>
روش ما محدودیت خاصی ندارد
## 🚀 ایده‌های گسترش <a name = "future_scope"></a>
یک ایده این بود از مرحله چهار استفاده کنیم. لاندا دا تصادفی قرار می‌دادیم و مرحله چهار رو حل می‌کردیم که ببینیم 

SV 

چه تعداد ستون ناصفر دارد. اگر کمتر از 

K

بود لاندا را کم می‌کردیم و در غیر این صورت زیاد می‌کردیم و این کار را آنقدر ادامه می‌دادیم تا تعداد ستون‌های ناصفر آن بزگترین مقدار کمتر از 

K 

شود. اما جوابی بهتر از روش اصلیمان نداد اما بنظر می‌رسد بتوان آن را به جایی رساند
## 🏁 روند اجرا <a name = "getting_started"></a>
اگر ریپازیتوری را کلون کنید دیتاهای سه سوال در سه فایل مجزا آمده است و کد برای خواندن  دیتای بخش اول و ذخیره کردن پاسخ آن آورده شده است و با تغییر نام فایل ورودی در اولین خط کد و همچنین در آخر کد (بخش سیو) می‌توان از آن برای سوال‌های دو و سه نیز استفاده کرد 
### پیش‌نیازها

نیاز به نصب کامپایلر جولیا و جوپیتر نوتبوک داریم.
برای نصب کامپایلر جولیا می‌توان از لینک زیر استفاده کرد

https://julialang.org/downloads/

برای نصب ژوپیتر نوتبوک نیز کافیست در کامپایلر نصب شده دو خط کد زیر را بنویسیم

```
Pkg using
Pkg.add(”IJulia”)
```
پکیج‌های آورده شده در بخش وابستگی‌ها را هم می‌توان به سادگی با کد زیر نصب کرد

`Pkg.add("package name")`
### نصب
کد نیاز به نصب ندارد
## 🎈 نحوه استفاده <a name="usage"></a>
همه چیز به طور مرتب در نوتبوک آمده است و فقط کافیست از اول تا اخر سلول‌های آن را به ترتیب اجرا کنیم و اگر بخواهیم مجددا کد را اجرا کنیم لازم نیست همه سلول‌ها از ابتدا اجرا شوند و کافیست سلولی که الگوریتم این بخش را پیاده‌سازی کرده است اجرا شود
## ⛏️ وابستگی‌ها <a name = "tech_stack"></a>
زبان برنامه‌نویسی

[julia](https://julialang.org/)

پکیج‌های استفاده شده 
```
MathOptInterface
GLPK
Random
LinearAlgebra
```
## ✍️ نویسندگان <a name = "authors"></a>
علی فتحی
## 🎉 قدردانی <a name = "acknowledgments"></a>
تشکر از هر کسی که به نحوی در برگزاری این مسابقه سهیم بوده است
