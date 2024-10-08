# apt

> أداة إدارة الحزم للتوزيعات القائمة على ديبيان.
> بديل لـ `apt-get` عند الاستخدام الفعال في إصدارات أوبونتو 16.04 وما بعده.
> لمزيد من التفاصيل: <https://manned.org/apt.8>.

- تحديث قائمة الحزم الموجودة وإصداراتها (يوصى بتشغيله قبل أي أمر `apt` آخر):

`sudo apt update`

- البحث عن حزمة معينة:

`apt search {{package}}`

- إظهار معلومات حول حزمة معينة:

`apt show {{package}}`

- تثبيت حزمة معينة، أو تحديثها إلى آخر إصدار متوفر:

`sudo apt install {{package}}`

- إزالة حزمة معينة (استخدام `purge` لحذف ملفات الإعدادات الخاصة بالحزمة):

`sudo apt remove {{package}}`

- تطوير جميع الحزم المثبتة إلى أجدد الإصدارات المتوفرة:

`sudo apt upgrade`

- إظهار قائمة جميع الحزم:

`apt list`

- إظهار قائمة جميع الحزم المثبتة:

`apt list --installed`
