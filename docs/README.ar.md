# HudHud AIDE: بيئة التطوير الذكية المستقلة

<p align="center">
  <b>Languages:</b> <a href="../README.md">English</a> | <a href="README.tr.md">Türkçe</a> | <b>العربية</b> | <a href="README.ja.md">日本語</a> | <a href="README.ru.md">Русский</a> | <a href="README.es.md">Español</a> | <a href="README.pt.md">Português</a> | <a href="README.zh.md">简体中文</a>
</p>

---

[![الإصدار](https://img.shields.io/badge/version-v0.4.46-orange.svg)](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46)
[![المنصة](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)](https://github.com/HudHudMind/hudhudscript)
[![حزمة الأدوات](https://img.shields.io/badge/toolchain-HudHudScript%20x86_64%20(v1..v4)-green.svg)](https://github.com/HudHudMind/hudhudscript)

**HudHud AIDE** هي بيئة تطوير متكاملة قائمة على الذكاء الاصطناعي، صُممت بشكل أساسي للغة [**HudHudScript**](https://github.com/HudHudMind/hudhudscript)، مع دعم تحرير التعليمات البرمجية وتطوير المشاريع باللغات البرمجية الحديثة مثل **Python و Rust و C/C++ و TypeScript/JavaScript** من خلال محررها المدمج ووكيل البرمجة الذكي.

تجمع البيئة بين نموذجي عمل متكاملين:
* **تحرير التعليمات البرمجية ومساعدة الوكيل الذكي:** كتابة التعليمات البرمجية متعددة اللغات وتشخيصها وإعادة هيكلتها باستخدام وكيل ذكي مدرك لمساحة العمل.
* **البرمجة المرئية (`.hudhudgraph`):** نظام برمجة مرئي قائم على العقد لتصميم وهيكلة وتوليد مسارات منطق **HudHudScript** الأصلية وسلاسل الوكلاء المتعددين.

تجمع HudHud AIDE بين **تطوير البرمجيات التقليدي والنماذج البرمجية الحديثة**:
* **البرمجة القائمة على الوكلاء (Agentic Programming):** تحديد ونشر الوكلاء المستقلين والأدوار وربط الأدوات وتنسيق الوكلاء المتعددين.
* **هندسة الحلقات وسلاسل التكرار (Loop Engineering & Loop Chains):** بناء حلقات تنفيذ مدفوعة بالتغذية الراجعة ودورات تقييم وسلاسل تحسين متكررة.
* **أنظمة الحوكمة (Governance):** فرض القيود التشغيلية وسياسات الأمان وقواعد التحقق وحدود الأذونات مباشرة داخل النماذج البرمجية والرسم البياني.
* **البرمجة الموجهة للفاعل (SOP):** هيكلة البرمجيات بناءً على الفواعل النشطة والسياقات التشغيلية والنوايا السلوكية.

يمكن للمهندسين والمطورين بناء وكلاء ذكاء اصطناعي مخصصين وهياكل برمجية مرئياً من خلال البرمجة المرئية، أو برمجياً في الكود المصدري، أو تعاونياً مع وكيل البرمجة المدمج.

---

## نظرة عامة على الإمكانات الرئيسية

```
┌─────────────────────────────────────────────────────────────┐
│                        HudHud AIDE                          │
├───────────────────┬─────────────────────┬───────────────────┤
│ البرمجة المرئية   │    وكيل البرمجة     │   HudHudScript    │
│  (.hudhudgraph    │  (ذكاء اصطناعي واعٍ  │  (بيئة تشغيل محلية│
│    نظام العقد)    │   بمساحة العمل)     │   متوافقة للعتاد) │
└───────────────────┴─────────────────────┴───────────────────┘
```

* **النمذجة المرئية للهيكل والمنطق:** نمذجة تدفقات التطبيق وسلاسل الوكلاء وهياكل الحالة باستخدام البرمجة المرئية القائمة على العقد.
* **المبرمج المساعد المستقل:** وكيل برمجة مدمج يحلل الكود البرمجي وتخطيط المشروع والرسوم البيانية المرئية مباشرة.
* **دعم لغة HudHudScript:** تكامل كامل للأطر البرمجية مثل Agentic Programming و Loop Engineering وقواعد الحوكمة (Governance) و Subject-Oriented Programming (SOP).
* **حزمة أدوات مجهزة للعتاد:** مترجم ومفسر ومحرك LSP ومدير حزم مهيأة مسبقاً لمعالجك (`x86-64-v1` to `v4`).

---

## البرمجة المرئية وملفات HudHudGraphs

توفر **البرمجة المرئية** في HudHud AIDE مساحة تفاعلية لتصميم وفحص الهياكل البرمجية وتدفقات العمل مرئياً جنباً إلى جنب مع الكود المصدري.

تُحفظ المخططات المرئية في ملفات **`.hudhudgraph`** القياسية.

```
                    ┌─────────────────────────┐
                    │       Agent Node        │
                    ├───────────┬─────────────┤
                    │ Role      │ Governance  │
                    │ Tools     │ Validation  │
                    └─────┬─────┴──────┬──────┘
                          │            │
                          ▼            ▼
                   [ Action / Loop ] [ Policy ]
```

### الإمكانات:
* **أكثر من 240 نوع عقدة متخصص:** عقد جاهزة لتغطية مسارات التطبيق، تعريفات الوكلاء، خطوط معالجة البيانات، آلات الحالة، وقواعد الحوكمة.
* **وصلات دبابيس محددة النوع:** قنوات بيانات واضحة وتدفقات تنفيذ مع تحقق آمن من الأنواع.
* **لوحة خصائص تفاعلية:** حدد أي عقدة لضبط معاملاتها وسلوكها وخصائصها في الوقت الفعلي.
* **سير عمل هجين:** استخدم ملفات `.hudhudgraph` المرئية جنباً إلى جنب مع كود `.hud` دون تعقيد إجباري لتوليد الكود.

### كيفية الاستخدام:
1. افتح أو أنشئ أي ملف `.hudhudgraph` في مساحة عملك.
2. انقر على **"Open with Visual Designer"** في شريط التبويب.
3. اسحب العقد من **لوحة العقد** اليسرى إلى مساحة العمل.
4. اربط مسارات التنفيذ ودبابيس البيانات بين العقد.
5. عدّل خصائص العقد في اللوحة اليمنى واحفظ (`Ctrl + S` / `Cmd + S`).

---

## وكيل البرمجة الذكي المدمج

تتضمن HudHud AIDE مساعد برمجة ذكي مدمج مصمم للعمل مباشرة عبر مساحة عمل مشروعك.

### المهام الأساسية:
* **تحليل مساحة العمل:** يقرأ ويفهم الملفات المصدرية وتكوينات المشروع ومخططات `.hudhudgraph`.
* **تنفيذ التعديلات متعددة الملفات:** يطور الميزات ويجري التعديلات عبر عدة ملفات في خطوة واحدة.
* **التشخيص وحل المشكلات:** يحدد تحذيرات المترجم واستثناءات التشغيل وأخطاء الأنواع ويقدم حلولاً مثبتة.
* **أتمتة المهام:** يتابع خطط العمل الهندسية متعددة الخطوات واختبارات التشغيل.

---

## دعم لغة ونماذج HudHudScript

صُممت HudHud AIDE لتفهم وتدعم المفاهيم الأساسية للغة [**HudHudScript**](https://github.com/HudHudMind/hudhudscript) بشكل أصلي:

* **البرمجة القائمة على الوكلاء (Agentic Programming):** بنى برمجية لتعريف الوكلاء المستقلين والأدوار والمسؤوليات والأدوات.
* **هندسة الحلقات (Loop Engineering):** حلقات تنفيذ منظمة تجمع بين الإجراءات والتحقق والتحسين التكراري.
* **أنظمة الحوكمة (Governance):** أدوات برمجية لتعريف القواعد والقيود ومجالس الإشراف والأذونات مباشرة.
* **البرمجة الموجهة للفاعل (SOP):** نمذجة برمجية تتمحور حول الفواعل والسياقات والمسؤوليات السلوكية.

---

## حزمة أدوات HudHudScript الأصلية

تأتي HudHud AIDE مع حزمة أدوات أصلية كاملة. يكتشف النظام أثناء التثبيت إمكانات معالجك (SSE4.2, AVX2, AVX-512) ويفعل الحزمة المطابقة (`x86-64-v1` to `v4`):

| الأداة / البرنامج | الدور |
| :--- | :--- |
| **`hudhud`** | بيئة تشغيل سطر الأوامر (CLI) ومنفذ التطبيقات |
| **`hudc`** | مترجم HudHudScript الأصلي المحسّن |
| **`hudi`** | صدفة REPL تفاعلية ومفسر مباشر |
| **`hudconv`** | أداة ترحيل شجرة القواعد المجردة (AST) والبايت كود |
| **`hudhudscript-lsp`** | محرك LSP للتلوين البرمجي والإكمال التلقائي والتوثيق المباشر |
| **`hudhud_ffi`** | واجهة تشغيل دوال C / Rust الخارجية (FFI) |

---

## سير العمل الهندسي الموحد

```
   1. البرمجة المرئية        2. التنفيذ البرمجي         3. التحقق والتشغيل
 ┌──────────────────┐      ┌──────────────────┐      ┌──────────────────┐
 │ نموذج المخطط     │ ───► │ كتابة الكود مع   │ ───► │ بناء واختبار     │
 │ (.hudhudgraph)   │      │ الوكيل الذكي     │      │ وتشغيل (hudc)    │
 └──────────────────┘      └──────────────────┘      └──────────────────┘
```

1. **النمذجة:** صمم المنطق أو سلاسل الوكلاء أو خطوط البيانات مرئياً باستخدام البرمجة المرئية.
2. **التنفيذ:** اكتب كود HudHudScript أو تعاون مع وكيل البرمجة المدمج لتنفيذ المنطق البرمجي.
3. **التشغيل واستكشاف الأخطاء:** شغّل التطبيق وافحصه مباشرة في البيئة باستخدام أدوات الفحص والتنفيذ الأصلية.

---

## متطلبات النظام والتثبيت

يمكنك تنزيل حزم التثبيت الأحدث من صفحة [GitHub Releases](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46) أو عبر الروابط المباشرة أدناه:

### Windows (x64)
* **نظام التشغيل:** Windows 10 / 11 (64-bit)
* **تنزيل:** [`hudhud-aide-v0.4.46-win-x64-setup.exe`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-win-x64-setup.exe)
* **تنبيه SmartScreen / الملفات غير الموقعة:**
  نظراً لأن ملف التثبيت غير موقع رقمياً حالياً، قد تظهر شاشة Microsoft Defender SmartScreen رسالة *"حماية Windows لجهاز الكمبيوتر الخاص بك"*:
  1. انقر على **"مزيد من المعلومات"** (*More info*).
  2. انقر على **"التشغيل على أي حال"** (*Run anyway*) لمتابعة التثبيت.
* *يقوم برنامج التثبيت تلقائياً بتهيئة مستوى المعالج المناسب (`v1` to `v4`).*

### Linux (x86_64)
* **نظام التشغيل:** Ubuntu 20.04+, Debian 11+, Fedora, Arch Linux, Kali Linux
* **تنزيل:** [`hudhud-aide-v0.4.46-linux-x64-installer.run`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-linux-x64-installer.run)
* **التثبيت:**
  ```bash
  chmod +x hudhud-aide-v0.4.46-linux-x64-installer.run
  ./hudhud-aide-v0.4.46-linux-x64-installer.run
  ```

---

## المجتمع والروابط

* **الموقع الإلكتروني:** [https://hudhudscript.com](https://hudhudscript.com)
* **GitHub (HudHudScript):** [https://github.com/HudHudMind/hudhudscript](https://github.com/HudHudMind/hudhudscript)
* **GitHub (HudHud AIDE):** [https://github.com/HudHudMind/hudhud-aide](https://github.com/HudHudMind/hudhud-aide)
* **Discord:** [https://discord.gg/UxEJ5MfH](https://discord.gg/UxEJ5MfH)
* **Reddit:** [https://www.reddit.com/r/hudhudscript/](https://www.reddit.com/r/hudhudscript/)
* **Twitter / X:** [https://x.com/hudhud_script](https://x.com/hudhud_script)
* **Instagram:** [https://www.instagram.com/hudhudscript/](https://www.instagram.com/hudhudscript/)
* **TikTok:** [https://www.tiktok.com/@hudhudscript](https://www.tiktok.com/@hudhudscript)
* **YouTube:** [https://www.youtube.com/@HudHudScripting](https://www.youtube.com/@HudHudScripting)
* **LinkedIn:** [https://www.linkedin.com/groups/27050016/](https://www.linkedin.com/groups/27050016/)
* **Patreon:** [https://www.patreon.com/cw/hudhudscript](https://www.patreon.com/cw/hudhudscript)

---

## الترخيص والاستفسارات

HudHud AIDE هي بيئة تطوير برمجية احترافية طُوّرت بواسطة **HudHud Script**.

* **المستودع:** [https://github.com/HudHudMind/hudhudscript](https://github.com/HudHudMind/hudhudscript)

---
*© 2026 HudHud Script. جميع الحقوق محفوظة.*
