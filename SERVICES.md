# Services — الخدمات

<div dir="rtl">

خدمات **سايبر آي كيو**، ينفّذها فريق **سايبر تيم**. لكل خدمة قائمة بالأعمال المنفّذة التي تثبت قدرة الفريق عليها، ولكل عمل مستودع مستقل.

| # | الخدمة | الجهة المستفيدة |
|---|---|---|
| 1 | [المنصة التعليمية للجامعات](#1-المنصة-التعليمية-للجامعات) | الجامعات، الطلبة |
| 2 | [خدمات الهاردوير](#2-خدمات-الهاردوير) | الجامعات، المؤسسات |
| 3 | [خدمات السوفتوير والبرمجة](#3-خدمات-السوفتوير-والبرمجة) | الجامعات، المؤسسات |
| 4 | [خدمات الأمن السيبراني](#4-خدمات-الأمن-السيبراني) | المؤسسات، الجامعات |
| 5 | [حلول الذكاء الاصطناعي](#5-حلول-الذكاء-الاصطناعي) | المؤسسات، الطلبة |
| 6 | [التدريب والورش](#6-التدريب-والورش) | الجامعات، الطلبة |

---

## 1. المنصة التعليمية للجامعات

**الخدمة الأولى التي تقدّمها سايبر آي كيو للجامعات.** منصة إلكترونية توفّر للجامعة مكاناً جاهزاً تنشر فيه كورساتها لطلبتها.

**ما تحصل عليه الجامعة:**

- نشر كورسات من إعداد الجامعة نفسها على المنصة.
- شهادات تصدر من المنصة **باسم الجامعة وشعارها** للطلبة الذين يكملون الكورس.

**ما تقدّمه سايبر آي كيو على المنصة:**

- كورسات عامة في **الأمن السيبراني**.
- **تحديات CTF** للتدريب العملي.
- كورسات **البرمجة**.
- كورسات **الذكاء الاصطناعي**.

**الحالة:** قيد التطوير — الكود في مستودع خاص. التفاصيل الكاملة في [PLATFORM.md](PLATFORM.md).

---

## 2. خدمات الهاردوير

**ما تشمله:**

- تصميم وبناء أجهزة أمنية مدمجة على Raspberry Pi و ESP32 و Raspberry Pi Pico W.
- بناء منظومات تحليل الطيف الترددي على SDR.
- تحويل أجهزة منخفضة الكلفة (مثل Android TV Box) إلى خوادم أمنية.
- تجهيز المختبرات: تركيب الحاسبات، تمديد الشبكات، تجميع السيرفرات وإعدادها، برمجة الراوترات.
- صيانة وتأهيل الحاسبات: فحص، استبدال وحدات التخزين، ترقية الذاكرة، معالجة الأعطال، إعادة التنصيب.

**الإثبات:**

| العمل | ما يثبته |
|---|---|
| [Cybersecurity-Lab-Setup](https://github.com/CYBERIQ-HQ/Cybersecurity-Lab-Setup) | مختبر كامل من الصفر: 30 حاسبة، سيرفران، شبكة LAN، راوتر |
| [Laptop-Maintenance](https://github.com/CYBERIQ-HQ/Laptop-Maintenance) | 150 حاسبة محمولة صُيّنت في 3 مختبرات خلال 3–4 أسابيع |
| [Cyber-Shield](https://github.com/CYBERIQ-HQ/Cyber-Shield) | جهاز مراقبة لاسلكي مستقل على ESP32 |
| [Evil-Twin-Detector](https://github.com/CYBERIQ-HQ/Evil-Twin-Detector) | جهاز كشف نقاط الوصول المزيفة على Pico W |
| [CSS-Cyber-Sentinel-System](https://github.com/CYBERIQ-HQ/CSS-Cyber-Sentinel-System) | مختبر أمن سيبراني محمول على Raspberry Pi 5 |
| [TV-Box-HomeSOC](https://github.com/CYBERIQ-HQ/TV-Box-HomeSOC) | خادم أمني مبني على Android TV Box |
| [TSS-Tactical-SIGINT](https://github.com/CYBERIQ-HQ/TSS-Tactical-SIGINT) | منظومة SDR محمولة لتحليل الطيف |

---

## 3. خدمات السوفتوير والبرمجة

**ما تشمله:**

- تطوير المنصات والمواقع الإلكترونية.
- برمجة الأنظمة المدمجة (Firmware) للأجهزة.
- لوحات مراقبة وتقارير (Dashboards).
- إعداد وتشغيل أنظمة Linux والخوادم والخدمات الشبكية.
- عروض تعليمية تفاعلية على الويب.

**الإثبات:**

| العمل | ما يثبته |
|---|---|
| [المنصة التعليمية](PLATFORM.md) | تطوير منصة كورسات وشهادات للجامعات |
| [TV-Box-HomeSOC](https://github.com/CYBERIQ-HQ/TV-Box-HomeSOC) | خادم Linux بخدمات أمنية ولوحة مراقبة |
| [Cyber-Shield](https://github.com/CYBERIQ-HQ/Cyber-Shield) | برمجة نظام مدمج يصنّف التهديدات وينبّه لحظياً |
| [Workshop2](https://github.com/hfsduu5-coder/Workshop2) · [Workshop3](https://github.com/hfsduu5-coder/Workshop3) | عروض ورش تفاعلية مبنية على الويب |

---

## 4. خدمات الأمن السيبراني

**ما تشمله:**

- تصميم وبناء مراكز عمليات أمنية (SOC) منخفضة الكلفة.
- مراقبة الشبكات وتحليل حركة البيانات.
- كشف التهديدات اللاسلكية: نقاط الوصول المزيفة والمارقة، هجمات فك الارتباط، إغراق القنوات.
- تقييم أمن الشبكات ضمن نطاق مصرّح به.
- التوعية الأمنية وتدريب الكوادر.

> جميع الخدمات تُنفّذ ضمن بيئات مصرّح بها وبموافقة الجهة المالكة، التزاماً بأخلاقيات وقوانين الأمن السيبراني.

**الإثبات:**

| العمل | ما يثبته |
|---|---|
| [CS-SOC](https://github.com/CYBERIQ-HQ/CS-SOC) | منصة دفاع سيبراني وإلكتروني |
| [TV-Box-HomeSOC](https://github.com/CYBERIQ-HQ/TV-Box-HomeSOC) | SOC مصغّر: فلترة DNS، جدار ناري، IDS/IPS، VPN، سجلات |
| [Evil-Twin-Detector](https://github.com/CYBERIQ-HQ/Evil-Twin-Detector) | كشف نقاط الوصول المزيفة لحظياً |
| [Cyber-Shield](https://github.com/CYBERIQ-HQ/Cyber-Shield) | رصد التهديدات في نطاق 2.4 GHz |
| [CSS-Cyber-Sentinel-System](https://github.com/CYBERIQ-HQ/CSS-Cyber-Sentinel-System) | مراقبة الشبكات واكتشاف الثغرات |
| [Wireless-Security-Tester](https://github.com/CYBERIQ-HQ/Wireless-Security-Tester) | تدريب مختبري على صمود الأجهزة اللاسلكية |

---

## 5. حلول الذكاء الاصطناعي

**ما تشمله:**

- توظيف الذكاء الاصطناعي في تحليل الإشارات ورصد التهديدات.
- الذكاء الاصطناعي على الأجهزة الطرفية (Edge AI).
- كورسات الذكاء الاصطناعي على المنصة التعليمية.

**الإثبات:**

| العمل | ما يثبته |
|---|---|
| [TSS-Tactical-SIGINT](https://github.com/CYBERIQ-HQ/TSS-Tactical-SIGINT) | تحليل الطيف الترددي بالذكاء الاصطناعي على جهاز طرفي (قيد التطوير) |
| [CS-SOC](https://github.com/CYBERIQ-HQ/CS-SOC) | منصة دفاع تعتمد على الذكاء الاصطناعي (قيد التطوير) |

---

## 6. التدريب والورش

**ما تشمله:**

- ورش تطبيقية في الأمن السيبراني والشبكات.
- تدريب على مسابقات CTF.
- إرشاد أكاديمي ومهني لطلبة الهندسة.

**الإثبات:**

| العمل | العرض المباشر |
|---|---|
| [ورشة آفاق التعليم الأكاديمي والمهني](https://github.com/CYBERIQ-HQ/Workshop-Academic-Horizons) | [Workshop2](https://github.com/hfsduu5-coder/Workshop2) |
| [ورشة CTF & Cybersecurity](https://github.com/CYBERIQ-HQ/Workshop-CTF) | [Workshop3](https://github.com/hfsduu5-coder/Workshop3) |

</div>

---

## English summary

| Service | Proof |
|---|---|
| University course platform: university-branded courses and certificates, plus Cyber IQ courses in cybersecurity, CTF, programming and AI | [PLATFORM.md](PLATFORM.md) (in development) |
| Hardware: embedded security devices, SDR systems, lab build-outs, device maintenance | Lab-Setup · Laptop-Maintenance · Cyber-Shield · Evil-Twin-Detector · CSS · TV-Box-HomeSOC · TSS |
| Software: platforms and websites, firmware, dashboards, Linux servers | Platform · TV-Box-HomeSOC · Cyber-Shield · Workshop2/3 |
| Cybersecurity: SOC builds, network monitoring, wireless threat detection, authorised assessments, awareness | CS-SOC · TV-Box-HomeSOC · Evil-Twin-Detector · Cyber-Shield · CSS · Wireless-Security-Tester |
| AI: AI-driven signal and threat analysis, edge AI, AI courses | TSS · CS-SOC (in development) |
| Training: hands-on workshops and CTF | Workshop-Academic-Horizons · Workshop-CTF |
