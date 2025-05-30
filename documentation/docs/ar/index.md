---
title: الصفحة الرئيسية
---

<img alt="شعار المنظمة العالمية للأرصاد الجوية" src="/assets/img/wmo-logo.png" width="200">
# تدريب WIS2 في صندوق

WIS2 في صندوق ([wis2box](https://docs.wis2box.wis.wmo.int)) هو تطبيق مرجعي مجاني ومفتوح المصدر لعقدة WIS2 التابعة للمنظمة العالمية للأرصاد الجوية. يوفر المشروع مجموعة أدوات جاهزة للاستخدام لاستقبال ومعالجة ونشر بيانات الطقس/المناخ/المياه باستخدام منهجيات قائمة على المعايير بما يتماشى مع مبادئ WIS2. كما يوفر wis2box الوصول إلى جميع البيانات في شبكة WIS2. تم تصميم wis2box ليكون سهل الاستخدام لمقدمي البيانات، موفرًا البنية التحتية والخدمات اللازمة لاكتشاف البيانات والوصول إليها وتصورها.

يوفر هذا التدريب شرحًا خطوة بخطوة لجوانب مختلفة من مشروع wis2box بالإضافة إلى عدد من التمارين
لمساعدتك على نشر وتنزيل البيانات من WIS2. يتم تقديم التدريب على شكل عروض تقديمية وكذلك
تمارين عملية.

سيتمكن المشاركون من العمل مع بيانات وميتاداتا اختبارية، بالإضافة إلى دمج بياناتهم وميتاداتا الخاصة بهم.

يغطي هذا التدريب مجموعة واسعة من الموضوعات (التثبيت/الإعداد/التكوين، نشر/تنزيل البيانات، إلخ).

## الأهداف ونتائج التعلم

الأهداف من هذا التدريب هي التعرف على الآتي:

- مفاهيم ومكونات الهندسة المعمارية الأساسية لـ WIS2
- صيغ البيانات والميتاداتا المستخدمة في WIS2 للاكتشاف والوصول
- هندسة وبيئة wis2box
- الوظائف الأساسية لـ wis2box:
    - إدارة الميتاداتا
    - استقبال البيانات وتحويلها إلى صيغة BUFR
    - وسيط MQTT لنشر رسائل WIS2
    - نقطة نهاية HTTP لتنزيل البيانات
    - نقطة نهاية API للوصول البرمجي إلى البيانات

## التنقل

التنقل الأيسر يوفر جدول محتويات للتدريب بأكمله.

التنقل الأيمن يوفر جدول محتويات لصفحة محددة.

## المتطلبات الأساسية

### المعرفة

- أوامر Linux الأساسية (انظر [cheatsheet](./cheatsheets/linux.md))
- معرفة أساسية بالشبكات وبروتوكولات الإنترنت

### البرمجيات

يتطلب هذا التدريب الأدوات التالية:

- نسخة تعمل بنظام التشغيل Ubuntu (مقدمة من مدربي WMO خلال جلسات التدريب المحلية) انظر [Accessing your student VM](./practical-sessions/accessing-your-student-vm.md#introduction)
- عميل SSH للوصول إلى نسختك
- MQTT Explorer على جهازك المحلي
- عميل SCP و SFTP لنسخ الملفات من جهازك المحلي

## الاتفاقيات

!!! question

    يدعوك قسم مميز بهذه الطريقة للإجابة على سؤال.

ستلاحظ أيضًا أقسام النصائح والملاحظات ضمن النص:

!!! tip

    تشارك النصائح المساعدة حول كيفية تحقيق المهام بأفضل شكل.

!!! note

    توفر الملاحظات معلومات إضافية حول الموضوع الذي يغطيه الجلسة العملية، بالإضافة إلى كيفية تحقيق المهام بأفضل شكل.

يتم الإشارة إلى الأمثلة على النحو التالي:

Configuration
``` {.yaml linenums="1"}
my-collection-defined-in-yaml:
    type: collection
    title: my title defined as a yaml attribute named title
    description: my description as a yaml attribute named description
```

الأجزاء التي يجب كتابتها في وحدة التحكم/الطرفية مشار إليها كما يلي:

```bash
echo 'Hello world'
```

أسماء الحاويات (الصور التي يتم تشغيلها) مشار إليها بـ **bold**.

## موقع ومواد التدريب

محتويات التدريب والويكي ومتتبع القضايا يتم إدارتها على GitHub في [https://github.com/World-Meteorological-Organization/wis2box-training](https://github.com/World-Meteorological-Organization/wis2box-training).

## طباعة المواد

يمكن تصدير هذا التدريب إلى PDF. لحفظ أو طباعة مواد التدريب هذه، انتقل إلى [print page](print_page)، واختر
File > Print > Save as PDF.

## مواد التمرين

يمكن تنزيل مواد التمرين من ملف [exercise-materials.zip](/exercise-materials.zip) zipfile.

## الدعم

للمشكلات/الأخطاء/الاقتراحات أو التحسينات/المساهمات في هذا التدريب، يرجى استخدام [GitHub issue tracker](https://github.com/World-Meteorological-Organization/wis2box-training/issues).

يمكن الإبلاغ عن جميع أخطاء وتحسينات ومشكلات wis2box على [GitHub](https://github.com/World-Meteorological-Organization/wis2box/issues).

للحصول على دعم إضافي أو لطرح الأسئلة، يرجى التواصل عبر wis2-support@wmo.int.

كما هو الحال دائمًا، يمكن العثور على وثائق wis2box الأساسية دائمًا على [https://docs.wis2box.wis.wmo.int](https://docs.wis2box.wis.wmo.int).

المساهمات مشجعة دائمًا ومرحب بها!