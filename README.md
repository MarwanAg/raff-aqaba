# رف العقبة — Raff Aqaba (Demo)

نسخة تجريبية (MVP) لمنصة تجمع محلات الألبسة في العقبة، لكل محل معرض منفصل باسمه ولونه، والزبون يتنقّل بين المعارض باسم كل محل.

A demo platform where every clothing shop in Aqaba gets its own showroom, and customers move between showrooms by shop name.

## المميزات / Features

- دليل المحلات مع بحث بالاسم أو المنطقة — Shop directory with search by name or area
- معرض منفصل لكل محل: فلاتر حسب القسم والمقاس، بحث داخل المعرض، ترتيب حسب السعر — Separate showroom per shop with category, size, search and sort
- تفاصيل القطعة: المقاسات المتوفرة، زر واتساب برسالة جاهزة، حجز القطعة واستلامها من المحل — Item sheet with sizes, WhatsApp inquiry and in-store reservation
- لوحة المحل: إضافة وتعديل وحذف القطع، رفع صور، تبديل توفر المقاسات، إدارة الحجوزات، بيانات ولون المعرض، تسجيل محل جديد — Shop dashboard for items, photos, sizes, reservations and showroom details
- صفحة الاشتراك (50 د.أ شهرياً، سعر مقترح) — Subscription page (50 JD/month, proposed)
- عربي وإنجليزي مع اتجاه RTL/LTR — Arabic and English with RTL/LTR

## التقنيات / Stack

- React 18 (UMD + Babel standalone، بدون build)
- Tailwind CSS (Play CDN)
- GSAP 3.13 (SplitText, ScrollTrigger)
- Lenis (smooth scroll)
- مكوّنات حركة بنمط React Bits: SplitText, BlurText, Magnet, SpotlightCard, DotGrid, ScrollVelocity, CountUp
- localStorage لتخزين البيانات الوهمية في متصفح الزائر

## التشغيل / Run

افتح `index.html` مباشرة في المتصفح، أو فعّل GitHub Pages من إعدادات المستودع:
Settings → Pages → Branch: `main` / root.

Open `index.html` in a browser, or enable GitHub Pages (Settings → Pages → `main`, root).

## رابط الاستبيان / Survey link

ضع رابط Google Form في المتغير `SURVEY_URL` في أول السكربت داخل `index.html`.

Set `SURVEY_URL` at the top of the script in `index.html`.

## ملاحظة / Note

المحلات والقطع والأرقام أمثلة وهمية لعرض الفكرة. البيانات تُحفظ في متصفح الزائر فقط.

Shops, items and numbers are fictional. Data is stored only in the visitor's browser.
