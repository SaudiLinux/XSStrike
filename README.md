# طريقة استخدام أداة Saudi Linux XSStrike

أداة Saudi Linux XSStrike هي أداة متقدمة للكشف عن ثغرات XSS (Cross-Site Scripting) في تطبيقات الويب. تم تطويرها بواسطة Saudi Linux 

## متطلبات النظام

- بايثون 3.6 أو أعلى
- نظام تشغيل متوافق (Windows، Linux، أو macOS)
- اتصال بالإنترنت لجلب التبعيات

## تثبيت المكتبات المطلوبة

قبل استخدام الأداة، يجب تثبيت المكتبات المطلوبة باستخدام الأمر التالي:



## طريقة الاستخدام الأساسية

git clone https://github.com/SaudiLinux/XSStrike.git
cd XSStrike

python saudi_xsstrike.py -u " http://example.com/page.php?param=test "

```

## خيارات الاستخدام المتقدمة

1. تخطي فحص DOM XSS:
```
python saudi_xsstrike.py -u " http://example.com/page.php?param=test " --skip-dom

```

2. تفعيل اكتشاف وتجاوز جدار 
حماية التطبيقات (WAF):
```
python saudi_xsstrike.py -u " http://example.com/page.php?param=test " --waf

```

3. فحص مكتبات JavaScript 
القديمة:
```
python saudi_xsstrike.py -u " http://example.com/page.php?param=test " --js-libs

```

4. تفعيل الزاحف لاستكشاف 
الموقع:
```
python saudi_xsstrike.py -u " http://example.com/page.php?param=test " --crawl

```

5. فحص Blind XSS:
```
python saudi_xsstrike.py -u " http://example.com/page.php?param=test " --blind

```

## ميزات الأداة

- تحليل استجابة الموقع 
باستخدام محللات متعددة
- مولد ذكي للـpayload مضمون 
العمل
- محرك تشويش قوي لاختبار 
الثغرات بشكل منهجي
- محللات HTML وJavaScript 
يدوية لنتائج دقيقة وموثوقة
- القدرة على اكتشاف وتجاوز 
جدار حماية التطبيقات (WAF)
- فحص مكتبات JavaScript 
القديمة
- دعم للـBlind XSS للكشف عن 
نقاط الضعف المخفية
- زاحف متعدد المسارات 
لاستكشاف المواقع بكفاءة

## ملاحظات هامة

- هذه الأداة مخصصة للاختبار 
الأمني الأخلاقي فقط.
- يجب استخدامها فقط على 
المواقع التي لديك إذن قانوني 
لاختبارها.
- المطور غير مسؤول عن أي 
استخدام غير قانوني للأداة.

## المطور

تم تطوير هذه الأداة بواسطة 
Saudi Linux استنادًا إلى 
XSStrike الأصلي، مع إضافة 
ميزات مخصصة وتحسينات للكشف 
عن ثغرات XSS بشكل فعال.
```
