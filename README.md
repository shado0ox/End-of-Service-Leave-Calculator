# 🧾 نموذج حساب الحقوق والإجازات
### End of Service & Leave Entitlements Calculator

> نموذج ويب تفاعلي لحساب مستحقات الموظفين والعمالة المنزلية وتوليد خطاب استلام رسمي ثنائي اللغة — وفق نظام العمل السعودي ولائحة العمالة المنزلية.
>
> Interactive web form to calculate employee & domestic worker entitlements and generate a bilingual official receipt letter — based on Saudi Labor Law and Domestic Workers Regulation.

---

## 📸 لقطة شاشة | Screenshot

> افتح الملف في المتصفح مباشرةً — لا يحتاج إلى تثبيت أي شيء.

---

## ✨ المميزات | Features

### 👔 وضع موظف نظام العمل | Labor Law Employee Mode
- حساب مكافأة نهاية الخدمة وفق **المادة 84 / 85 / 109** من نظام العمل السعودي
- دعم جميع حالات الإنهاء:
  - فصل من صاحب العمل
  - استقالة (ثلث / ثلثان / كاملة حسب سنوات الخدمة)
  - انتهاء العقد
  - إنهاء بالتراضي
  - تسوية مقدمة حتى تاريخ معين
  - اتفاق خاص — 30 يوم من تاريخ التعيين
- احتساب بدل رصيد الإجازات (أساس 21 أو 30 يوم/سنة حسب الخدمة)
- توليد **خطاب استلام رسمي** ثنائي اللغة (عربي / إنجليزي)
- إمكانية رفع شعار الشركة في الخطاب

### 🏠 وضع العمالة المنزلية | Domestic Worker Mode
- حساب المكافأة وفق **المادة 22 من لائحة العمالة المنزلية**
  - راتب شهر كامل عن كل **4 سنوات** متتالية
  - احتساب كسور السنوات بالتناسب (أشهر وأيام)
- دعم أنواع الخدمة: عاملة منزلية، سائق خاص، مربية أطفال، طاهي، حارس، بستاني
- حقل رقم عقد **مساند**
- خطاب مستقل يستند إلى المادة 22 والقرار الوزاري رقم 40676

### 🌐 ثنائية اللغة | Bilingual Interface
- تبديل فوري بين **العربية** و **English** لكامل واجهة النموذج
- تغيير اتجاه الصفحة تلقائياً (RTL / LTR)

### 🖨️ الطباعة | Print
- زر طباعة مباشر للخطاب بتنسيق A4
- إخفاء عناصر النموذج عند الطباعة تلقائياً

---

## 🚀 طريقة الاستخدام | How to Use

```bash
# 1. استنساخ المستودع | Clone the repository
git clone https://github.com/YOUR_USERNAME/entitlements-calculator.git

# 2. افتح الملف مباشرةً في المتصفح | Open directly in browser
open entitlements_final_v2.html
```

> ✅ **لا يحتاج إلى سيرفر أو تثبيت** — ملف HTML واحد يعمل بالكامل في المتصفح.
> ✅ **No server or installation required** — single HTML file, runs entirely in the browser.

---

## 📐 أسس الاحتساب | Calculation Basis

### موظفو نظام العمل | Labor Law Employees

| حالة الإنهاء | المكافأة |
|---|---|
| فصل / انتهاء عقد / تراضي | نصف الراتب لكل سنة (أولى 5)، ثم راتب كامل لكل سنة بعدها |
| استقالة 2-5 سنوات | ثلث المكافأة |
| استقالة 5-10 سنوات | ثلثا المكافأة |
| استقالة +10 سنوات | المكافأة كاملة |
| أقل من سنة | لا مكافأة |

### العمالة المنزلية | Domestic Workers

| البند | القاعدة |
|---|---|
| مكافأة نهاية الخدمة | شهر عن كل 4 سنوات (م. 22 لائحة العمالة المنزلية) |
| إجازة سنوية | 30 يوم بعد سنتين متتاليتين |
| تصفية الحقوق | خلال 7 أيام من تاريخ الإنهاء |

---

## 🗂️ هيكل المشروع | Project Structure

```
entitlements-calculator/
│
├── entitlements_final_v2.html   # الملف الرئيسي — كل شيء في ملف واحد
└── README.md                    # هذا الملف
```

---

## 🛠️ التقنيات المستخدمة | Tech Stack

| التقنية | الاستخدام |
|---|---|
| HTML5 | هيكل الصفحة |
| CSS3 | التصميم والتخطيط (Grid, Flexbox, Print Media) |
| Vanilla JavaScript | الحسابات، تبديل اللغة، توليد الخطاب، لوحة التوقيع |

> ❌ لا يوجد أي اعتماد خارجي — لا مكتبات، لا CDN، لا قواعد بيانات.

---

## 📋 المتطلبات | Requirements

- أي متصفح حديث (Chrome, Edge, Firefox, Safari)
- لا يحتاج إلى اتصال بالإنترنت

---

## 📜 المرجع القانوني | Legal Reference

- **نظام العمل السعودي** — المواد 84، 85، 109
- **لائحة العمالة المنزلية** — القرار الوزاري رقم 40676 بتاريخ 17/03/1445هـ (المادة 22)
- **وزارة الموارد البشرية والتنمية الاجتماعية** — المملكة العربية السعودية

> ⚠️ هذا النموذج للأغراض التوضيحية والتقريبية. يُنصح بمراجعة متخصص قانوني أو جهة رسمية للحصول على تسوية نهائية ملزمة.
>
> ⚠️ This tool is for reference purposes only. Consult a legal professional or official authority for binding settlements.

---

## 🤝 المساهمة | Contributing

المساهمات مرحب بها! يرجى فتح **Issue** أو **Pull Request**.

Contributions are welcome! Feel free to open an **Issue** or **Pull Request**.

---

## 👨‍💻 المطور | Developer

**Shady Nassef**

> *تم تصميم وتطوير هذا النظام بواسطة Shady Nassef*
> *Designed & Developed by Shady Nassef*

---

## 📄 الرخصة | License

هذا المشروع مفتوح المصدر تحت رخصة [MIT License](LICENSE).

This project is open source under the [MIT License](LICENSE).
