# مستودع ضوابط الأمن السيبراني CIS باللغة العربية
## Arabic CIS Controls Repository

### نظرة عامة | Overview

يهدف هذا المستودع إلى توفير ترجمة شاملة وتطبيق عملي لضوابط الأمن السيبراني الحرجة من مركز أمان الإنترنت (CIS) باللغة العربية، لمساعدة المؤسسات في الوطن العربي على تبني وتطبيق أفضل الممارسات في الأمن السيبراني.

This repository aims to provide an Arabic translation and practical implementation guide for the CIS Critical Security Controls to help organizations in the Arab world adopt and implement cybersecurity best practices.

### الضوابط الـ18 لـ CIS v8.1 | CIS v8.1 Controls

| رقم الضابط | اسم الضابط | Implementation Groups |
|------------|-------------|----------------------|
| 1 | جرد والتحكم في أصول المؤسسة | IG1, IG2, IG3 |
| 2 | جرد والتحكم في أصول البرمجيات | IG1, IG2, IG3 |
| 3 | حماية البيانات | IG1, IG2, IG3 |
| 4 | التكوين الآمن لأصول وبرمجيات المؤسسة | IG1, IG2, IG3 |
| 5 | إدارة الحسابات | IG1, IG2, IG3 |
| 6 | إدارة التحكم في الوصول | IG1, IG2, IG3 |
| 7 | إدارة الثغرات المستمرة | IG1, IG2, IG3 |
| 8 | إدارة سجلات التدقيق | IG1, IG2, IG3 |
| 9 | حماية البريد الإلكتروني ومتصفحات الويب | IG1, IG2, IG3 |
| 10 | دفاعات البرمجيات الخبيثة | IG1, IG2, IG3 |
| 11 | استعادة البيانات | IG1, IG2, IG3 |
| 12 | إدارة البنية التحتية للشبكة | IG2, IG3 |
| 13 | مراقبة ودفاع الشبكة | IG2, IG3 |
| 14 | التوعية الأمنية والتدريب المهني | IG1, IG2, IG3 |
| 15 | إدارة مزودي الخدمة | IG2, IG3 |
| 16 | أمن برمجيات التطبيقات | IG2, IG3 |
| 17 | إدارة الاستجابة للحوادث | IG2, IG3 |
| 18 | اختبارات الاختراق | IG3 |

### هيكل المستودع | Repository Structure

```
arabic-cis-controls/
├── README.md
├── docs/
│   ├── introduction.md              # مقدمة عامة
│   ├── implementation-groups.md     # مجموعات التطبيق
│   ├── arab-world-context.md       # السياق في الوطن العربي
│   └── glossary.md                 # مسرد المصطلحات
├── controls/
│   ├── control-01.md               # الضابط الأول
│   ├── control-02.md               # الضابط الثاني
│   └── ...                        # باقي الضوابط
├── implementation-guides/
│   ├── ig1-guide.md                # دليل المجموعة الأولى
│   ├── ig2-guide.md                # دليل المجموعة الثانية
│   ├── ig3-guide.md                # دليل المجموعة الثالثة
│   └── sector-specific/            # أدلة قطاعية
├── templates/
│   ├── assessment-templates/       # قوالب التقييم
│   ├── policy-templates/          # قوالب السياسات
│   └── checklists/                # قوائم المراجعة
├── frameworks/
│   ├── kuwait-mapping.md          # ربط مع الاستراتيجية الكويتية
│   ├── uae-mapping.md             # ربط مع ضوابط الإمارات
│   ├── saudi-mapping.md           # ربط مع ضوابط السعودية
│   └── banking-sector.md          # القطاع المصرفي
├── resources/
│   ├── tools.md                   # أدوات مساعدة
│   ├── references.md              # مراجع إضافية
│   └── training-materials.md      # مواد تدريبية
└── examples/
    ├── small-organization.md      # مثال منظمة صغيرة
    ├── medium-enterprise.md       # مثال مؤسسة متوسطة
    └── large-corporation.md       # مثال شركة كبيرة
```

### مجموعات التطبيق | Implementation Groups

#### المجموعة الأولى IG1 - الوقاية السيبرانية الأساسية
- **الهدف**: الحماية من الهجمات الشائعة غير المستهدفة
- **المؤسسات المستهدفة**: الشركات الصغيرة والمتوسطة
- **عدد الضوابط**: 56 إجراء وقائي عبر 15 ضابط

#### المجموعة الثانية IG2 - الأمان المعزز  
- **الهدف**: الدفاع ضد مجموعة أوسع من التهديدات
- **المؤسسات المستهدفة**: المؤسسات ذات التعقيد التشغيلي المتزايد
- **عدد الضوابط**: 130 إجراء وقائي عبر 18 ضابط

#### المجموعة الثالثة IG3 - الدفاع المتقدم
- **الهدف**: التخفيف من الهجمات المتقدمة والمستمرة
- **المؤسسات المستهدفة**: المؤسسات عالية المخاطر والبنية التحتية الحيوية
- **عدد الضوابط**: جميع الـ153 إجراء وقائي

### الربط مع الأطر الوطنية العربية | Mapping to Arab National Frameworks

هذا المستودع يربط ضوابط CIS مع الأطر الوطنية التالية:

- **الكويت**: الاستراتيجية الوطنية للأمن السيبراني وإطار البنك المركزي الكويتي
- **الإمارات**: لائحة ضمان المعلومات (IA) والاستراتيجية الوطنية للأمن السيبراني  
- **السعودية**: الضوابط الأساسية للأمن السيبراني (ECC) وإطار مؤسسة النقد
- **قطر**: الاستراتيجية الوطنية للأمن السيبراني (NCSS)
- **عمان**: سياسات وزارة النقل والاتصالات وتقنية المعلومات

### كيفية الاستخدام | How to Use

1. **ابدأ بالمقدمة**: اقرأ [docs/introduction.md](docs/introduction.md)
2. **حدد مجموعة التطبيق**: راجع [docs/implementation-groups.md](docs/implementation-groups.md)
3. **اختر الضوابط المناسبة**: من مجلد [controls/](controls/)
4. **استخدم القوالب**: من مجلد [templates/](templates/)
5. **راجع الأمثلة العملية**: من مجلد [examples/](examples/)

### المساهمة | Contributing

نرحب بالمساهمات من المجتمع العربي لتحسين هذا المستودع:

- ترجمة وتحسين المحتوى الموجود
- إضافة أمثلة عملية من البيئة العربية
- تطوير قوالب وأدوات جديدة
- ربط مع أطر وطنية إضافية

### الترخيص | License

هذا المشروع مرخص تحت [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

### التواصل | Contact

للاستفسارات والمساهمات، يرجى فتح قضية (Issue) جديدة أو التواصل عبر البريد الإلكتروني.

---

**ملاحظة**: هذا المستودع مستقل وغير رسمي من مركز أمان الإنترنت (CIS). الهدف هو تسهيل تطبيق ضوابط CIS في البيئة العربية.

*Note: This repository is independent and not officially affiliated with the Center for Internet Security (CIS). The goal is to facilitate the implementation of CIS Controls in Arabic environments.*
