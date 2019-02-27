تستخدم الخاصية `line-height` لضبط المسافة بين الأسطر في النصوص

---

## حل التحدي 

قمت منك بطلب إعطاء الـ `header` إرتفاع بمقدار `200px` كالتالي: 

```
 header{
       background-color: #4268b3;
       color: #ffffff;
       width: 100%;
       height: 200px; //هنا التغييرات تمت
       line-height: 50px;
       font-size: 30px;
       letter-spacing: -1px;
  }
```

من ثم سنقوم بمحاذة كلمة facebook في منتصف ال `header` بإستخدام الخاصية `text-align` بالشكل التالي: 

```
 header{
       background-color: #4268b3;
       color: #ffffff;
       width: 100%;
       height: 200px; 
       line-height: 50px;
       font-size: 30px;
       letter-spacing: -1px;
       text-align: center; //تم إضافة هذه الخاصية
  }
```

أخيراً سنقوم بتوسيط الكلمة عمودياً بإستخدام الخاصية `line-height` كالتالي:

```
 header{
       background-color: #4268b3;
       color: #ffffff;
       width: 100%;
       height: 200px; 
       line-height: 200px; //هنا التغييرات تمت
       font-size: 30px;
       letter-spacing: -1px;
       text-align: center; 
  }
```