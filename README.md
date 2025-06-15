# 🚀 مشروع أتمتة يونيش (UNICH Project Automation)

أداة متكاملة لتوليد إيميلات Gmail (Dot Trick) وتنفيذ عمليات الإحالة بشكل تلقائي واحترافي على منصة Unich، مع دعم كامل للأتمتة وحل الكابتشا وإدارة الحسابات.

## ⭐️ المميزات

- توليد عدد غير محدود من إيميلات Gmail بطريقة dot trick
- أتمتة تسجيل الإحالات على Unich بشكل كامل
- دعم حل الكابتشا اليدوي وقراءة OTP من Gmail
- إدارة تلقائية للحسابات المجربة والناجحة والفاشلة
- سجلات مفصلة لكل العمليات والأخطاء
- واجهة تفاعلية ملونة وسهلة الاستخدام
- دعم كامل لأنظمة Windows و Linux

## 🛠️ المتطلبات

### نظام Windows
- Python 3.8 أو أعلى
- متصفح Google Chrome أو Chromium
- Git (اختياري)

### نظام Linux (Ubuntu/Debian)
- Python 3.8 أو أعلى
- متصفح Google Chrome أو Chromium
- Git (اختياري)

## ⚙️ خطوات التثبيت والتشغيل

### نظام Windows

1. **استنساخ المشروع:**
```bash
git clone https://github.com/phoenixcrypto/UNICH-REF.git
cd UNICH-REF
```

2. **إنشاء وتفعيل البيئة الافتراضية:**
```bash
python -m venv venv
.\venv\Scripts\activate
```

3. **تثبيت المكتبات المطلوبة:**
```bash
pip install -r requirements.txt
```

4. **تثبيت متصفح Chrome/Chromium:**
- تحميل Chrome من: https://www.google.com/chrome/
- أو تحميل Chromium من: https://www.chromium.org/getting-involved/download-chromium/

### نظام Linux (Ubuntu/Debian)

1. **تثبيت المتطلبات الأساسية:**
```bash
sudo apt update
sudo apt upgrade
sudo apt install python3 python3-pip python3-venv wget unzip
```

2. **استنساخ المشروع:**
```bash
git clone https://github.com/phoenixcrypto/UNICH-REF.git
cd UNICH-REF
```

3. **إنشاء وتفعيل البيئة الافتراضية:**
```bash
python3 -m venv venv
source venv/bin/activate
```

4. **تثبيت المكتبات المطلوبة:**
```bash
pip install -r requirements.txt
```

5. **تثبيت متصفح Chrome/Chromium:**
```bash
# لتثبيت Chrome
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
sudo apt --fix-broken install

# أو لتثبيت Chromium
sudo apt install chromium-browser
```

## 📱 طريقة الاستخدام

1. **تفعيل البيئة الافتراضية:**
```bash
# على نظام Windows
.\venv\Scripts\activate

# على نظام Linux
source venv/bin/activate
```

2. **تشغيل السكربت:**
```bash
python main.py
```

3. **اختيار من القائمة:**
- الخيار 1: توليد إيميلات Gmail dot trick
- الخيار 2: تشغيل أتمتة الإحالات
- الخيار 0: الخروج

## ⚙️ الإعدادات

يمكنك تعديل ملف `config.py` لتخصيص:
- رابط الإحالة والكود
- إعدادات البريد الإلكتروني
- إعدادات المتصفح
- التأخير والوقت المستغرق
- إعدادات الأمان
- تفضيلات التسجيل

## 📁 هيكل المشروع

```
UNICH-REF/
├── data/
│   ├── accounts.txt         # الحسابات المراد تجربتها
│   ├── done.txt            # الحسابات الناجحة
│   └── errors.txt          # الحسابات الفاشلة
├── logs/
│   └── logs.txt            # سجل العمليات
├── modules/
│   ├── automation.py       # منطق الأتمتة
│   ├── gmail_dot_generator.py # توليد الإيميلات
│   ├── system_utils.py     # أدوات النظام
│   └── utils.py            # أدوات مساعدة
├── drivers/                # ملفات المتصفح
├── backups/                # النسخ الاحتياطية
├── config.py              # ملف الإعدادات
├── main.py                # الملف الرئيسي
└── requirements.txt       # المكتبات المطلوبة
```

## 🔧 استكشاف الأخطاء وإصلاحها

### المشاكل الشائعة

1. **عدم العثور على Chrome/Chromium:**
- تأكد من تثبيت المتصفح
- تحقق من المسار في ملف config.py
- جرب استخدام Chromium بدلاً من Chrome

2. **خطأ ModuleNotFoundError:**
- تأكد من تفعيل البيئة الافتراضية
- قم بتشغيل `pip install -r requirements.txt` مرة أخرى

3. **مشاكل الصلاحيات (Linux):**
```bash
chmod -R 755 .
```

4. **خطأ UnicodeEncodeError:**
```bash
# على نظام Windows
set PYTHONIOENCODING=utf-8

# على نظام Linux
export PYTHONIOENCODING=utf-8
```

## 🤝 المساهمة

1. قم بعمل Fork للمشروع
2. أنشئ فرع جديد للميزة
3. قم بعمل Commit للتغييرات
4. ادفع التغييرات إلى الفرع
5. قم بإنشاء Pull Request

## 📄 الترخيص

هذا المشروع مرخص تحت رخصة MIT - راجع ملف LICENSE للمزيد من التفاصيل.

## 📞 الدعم الفني

للحصول على الدعم، انضم إلى قناة التليجرام: [@PhoenixCrypto_PC](https://t.me/PhoenixCrypto_PC)

## 📦 المستودع

مستودع GitHub: [https://github.com/phoenixcrypto/UNICH-REF](https://github.com/phoenixcrypto/UNICH-REF)

## ⚠️ ملاحظات مهمة

- السكربت تعليمي ويُستخدم على مسؤوليتك الشخصية
- لا تشارك بياناتك مع أي جهة غير موثوقة
- تابع القناة على التليجرام لأحدث التحديثات والشروحات