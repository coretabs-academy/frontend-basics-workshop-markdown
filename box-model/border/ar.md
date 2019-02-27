الخاصية `border` تتيح لنا إضافة إطار للعنصر، تعتبر هذه الخاصية إختصار لثلاث خواص كما تطرقنا إليها في الفيديو أعلاة والتي هي:

```
border-width
border-style
border-color
```

من المستحسن استخدام الخاصية  `border`  إذا كانت تريد ضبط جميع الإطارات إلى قيمة واحدة، كما في المثال التالي:

```
p{
    border: 10px solid red;
}
```

اما في حال أردت أن يكون لكل إتجاة من الإطار قيمة خاصة به فبإمكانك إستخدام الثلاث الخاصيات أو بإمكانك كذلك إستخدام الإختصار مع تحديد الإتجاة المرغوب تطبيق الإطار عليه، على سبيل المثال الكودين التاليين يحددان إطار للعنصر `p` من الجهة اليسار.

```
p{
    border-left-width: 10px;
    border-left-style: solid;
    border-left-color: red;
}
```

```
p{
    border-left: 10px solid red;
}
```

## القيم التي يمكن إسنادها للخاصية` border-style`:


<table>
   <tbody><tr>
    <td style="vertical-align: middle;"><code>none</code></td>
    <td style="vertical-align: middle;">
     <div style="margin: 0.5em; width: 3em; height: 3em; border-style: none; background-color: #fff88e;">&nbsp;</div>
    </td>
    <td style="vertical-align: middle;">عدم عرض إطار</td>
   </tr>
   <tr>
    <td style="vertical-align: middle;"><code>dotted</code></td>
    <td style="vertical-align: middle;">
     <div style="margin: 0.5em; width: 3em; height: 3em; border-width: 3px; border-style: dotted; background-color: #fff88e;">&nbsp;</div>
    </td>
    <td style="vertical-align: middle;">عرض سلسلة من النقط، والتباعد بينها ليس مُعرّفًا من المواصفة، وإنما هو تابع للمتصفح.</td>
   </tr>
   <tr>
    <td style="vertical-align: middle;"><code>dashed</code></td>
    <td style="vertical-align: middle;">
     <div style="margin: 0.5em; width: 3em; height: 3em; border-width: 3px; border-style: dashed; background-color: #fff88e;">&nbsp;</div>
    </td>
    <td style="vertical-align: middle;">عرض سلسة من الشرطات -، وطولها والتباعد بينها ليس معرّفًا من المواصفة، وإنما هو تابع للمتصفح.</td>
   </tr>
   <tr>
    <td style="vertical-align: middle;"><code>solid</code></td>
    <td style="vertical-align: middle;">
     <div style="margin: 0.5em; width: 3em; height: 3em; border-width: 3px; border-style: solid; background-color: #fff88e;">&nbsp;</div>
    </td>
    <td style="vertical-align: middle;">عرض خط مستقيم مليء.</td>
   </tr>
   <tr>
    <td style="vertical-align: middle;"><code>double</code></td>
    <td style="vertical-align: middle;">
     <div style="margin: 0.5em; width: 3em; height: 3em; border-width: 3px; border-style: double; background-color: #fff88e;">&nbsp;</div>
    </td>
    <td style="vertical-align: middle;">عرض خطين مستقيمين مليئين.</td>
   </tr>
   <tr>
    <td style="vertical-align: middle;"><code>groove</code></td>
    <td style="vertical-align: middle;">
     <div style="margin: 0.5em; width: 3em; height: 3em; border-width: 3px; border-style: groove; background-color: #fff88e;">&nbsp;</div>
    </td>
    <td style="vertical-align: middle;">عرض الإطار كأنه منحوت أو منقوش، وهذه القيمة عكس القيمة <code>ridge</code>.</td>
   </tr>
   <tr>
    <td style="vertical-align: middle;"><code>ridge</code></td>
    <td style="vertical-align: middle;">
     <div style="margin: 0.5em; width: 3em; height: 3em; border-width: 3px; border-style: ridge; background-color: #fff88e;">&nbsp;</div>
    </td>
    <td style="vertical-align: middle;">عرض الإطار كأنه منبثق، وهذه القيمة عكس القيمة <code>groove</code>.</td>
   </tr>
   <tr>
    <td style="vertical-align: middle;"><code>inset</code></td>
    <td style="vertical-align: middle;">
     <div style="margin: 0.5em; width: 3em; height: 3em; border-width: 3px; border-style: inset; background-color: #fff88e;">&nbsp;</div>
    </td>
    <td style="vertical-align: middle;">عرض الإطار بطريقة تجعل العنصر يبدو وكأنه مُضمّن في مكانه، وهي على عكس القيمة <code>outset</code>.</td>
   </tr>
   <tr>
    <td style="vertical-align: middle;"><code>outset</code></td>
    <td style="vertical-align: middle;">
     <div style="margin: 0.5em; width: 3em; height: 3em; border-width: 3px; border-style: outset; background-color: #fff88e;">&nbsp;</div>
    </td>
    <td style="vertical-align: middle;">
     <p>عرض الإطار بطريقة تجعل العنصر يبدو وكأنه بارز عن مكانه، وهي على عكس القيمة <code>inset</code>.</p>
    </td>
   </tr>
 </tbody></table>