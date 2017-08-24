---
permalink: /series/HosseinAbedi/numerical-python-tutorial/numerical-python-tutorial-intro-0
title:    آموزش پایتون برای محاسبات عددی و آمار
author: Hossein Abedi
excerpt: آموزش پایتون برای پیاده‌سازی سریع روش‌های محاسباتی و آماری
is_cover: true
---

یکی از ویژگی‌های خوب پایتون اینه که برای خیلی از زمینه‌های تحقیقاتی براش یه عالمه کتابخونه پیدا می‌شه. تو اینجا یه سری کتابخونه برای کارهای مربوط به دیتاساینس هستن رو می خواهیم با هم بررسی کنیم و تعدادی از فانکشنالیتی های مربوط به اون‌ها رو هم با تعدادی مثال ببینیم.

# Numpy
کتابخونه‌ی نامپای یکی از کتابخونه‌های قدیمیه پایتونه که برای محاسبات عددی معرفی شده. 
برای نصبش با پیپ  بر روی لینوکس (Debian/Ubuntu)
می‌تونید از دستور زیر استفاده کنین
```sh
sudo aptitude install python3-numpy
```

این کتابخونه اصلی‌ترین قابلیتش ارائه‌ی یه ساختمان داده اس به نام 
numpy array
که با اون می‌شه به راحتی چیزای مثل بردار و ماتریس رو تعریف کرد.
برای مثال
```python
import numpy as np

vector_0 = np.array([9, 0, 5, 5])
matrix_0 = np.array([[4, 5], [50, 60]])
```
با مراجعه به 
[داشبور مثال‌های نامپای](/assets/dashboards/HosseinAbedi/numpy.ipynb)
 می‌تونین با یه سری مثال با نامپای بیشتر آشنا بشین.