# 🚀 Nexity — Next‑Generation Adaptive Trading Intelligence

Nexity یک سیستم **هوشمند، ماژولار و خودتوسعه‌گر** برای تحلیل، شکار فرصت، مدیریت ریسک و اجرای تصمیمات در بازارهای مالی است.  
این پروژه بر پایه‌ی معماری **Behavior‑Driven Engine** ساخته می‌شود؛ یعنی Nexity مثل یک موجود زنده رفتار می‌کند، یاد می‌گیرد و تکامل پیدا می‌کند.

---

## 🧠 Vision — چرا Nexity وجود دارد؟

بازار همیشه در حال تغییر است.  
سیستم‌های معمولی فقط واکنش نشان می‌دهند.  
اما Nexity:

- **رفتار بازار را می‌فهمد**
- **خودش را با شرایط جدید وفق می‌دهد**
- **از اشتباهات یاد می‌گیرد**
- **به مرور زمان بهتر می‌شود**

Nexity یک ابزار نیست.  
یک **موجود زندهٔ تحلیلی** است.

---

## 🧱 Architecture — معماری Nexity

```
nexity/
│
├── core/                     # هسته‌ی رفتار و منطق
│   ├── behavior/             # رفتارها (Hunt, Silent, Alert, Precision, Escape)
│   ├── risk/                 # موتور مدیریت ریسک
│   ├── scanner/              # اسکنر فرصت‌ها
│   └── infinity/             # حلقه‌ی یادگیری بی‌نهایت
│
├── data/                     # داده‌ها، کش، ورودی API
│
├── engine/                   # موتور اجرای Nexity
│
├── ui/                       # داشبورد یا نسخه موبایل
│
└── config/                   # تنظیمات، کلیدها، پارامترها
```

---

## 🎮 Behavior Core — DNA رفتاری Nexity

Behavior Core شامل ۵ رفتار اصلی است:

- **[Hunt Mode](ca://s?q=Nexity_Hunt_Mode)** — شکار فرصت
- **[Silent Mode](ca://s?q=Nexity_Silent_Mode)** — انتظار هوشمند
- **[Alert Mode](ca://s?q=Nexity_Alert_Mode)** — هشدار
- **[Precision Mode](ca://s?q=Nexity_Precision_Mode)** — ورود دقیق
- **[Escape Mode](ca://s?q=Nexity_Escape_Mode)** — خروج از خطر

هر رفتار یک ماژول مستقل است و Engine آن‌ها را فعال/غیرفعال می‌کند.

---

## ⚙️ Engine — مغز اجرایی Nexity

Engine مسئول:

- اجرای رفتارها
- دریافت داده از API
- فعال‌سازی اسکنر
- مدیریت ریسک
- تولید خروجی نهایی

Engine مثل CPU سیستم عمل می‌کند.

---

## 🔍 Opportunity Scanner — اسکنر فرصت‌ها

Scanner بازار را در چند لایه بررسی می‌کند:

- ساختار قیمت
- حجم
- مومنتوم
- رفتار کندل‌ها
- الگوهای رفتاری
- شرایط ریسک

خروجی Scanner → ورودی Hunt Mode

---

## 🛡 Risk Engine — موتور مدیریت ریسک

Risk Engine:

- حد ضرر پویا
- اندازه پوزیشن
- ریسک لحظه‌ای
- شرایط خروج اضطراری
- محدودیت‌های رفتاری

را کنترل می‌کند.

---

## ♾ Infinity Loop — حلقه یادگیری بی‌نهایت

Nexity از داده‌های گذشته و رفتار خودش یاد می‌گیرد:

- چه زمانی اشتباه کرده
- چه زمانی درست عمل کرده
- چه الگویی تکرار شده
- چه رفتاری باید تقویت شود

این بخش Nexity را **خودتوسعه‌گر** می‌کند.

---

## 🛠 Installation — نصب

```
git clone https://github.com/klg2m/nexity.git
cd nexity
npm install
```

(بعداً با توجه به زبان پروژه کامل می‌شود)

---

## ▶️ Run — اجرا

```
npm start
```

یا هر اسکریپتی که بعداً تعریف می‌شود.

---

## 🗺 Roadmap — نقشه راه نسخه ۱

- [ ] ساخت Behavior Core
- [ ] ساخت Engine
- [ ] ساخت Scanner
- [ ] ساخت Risk Engine
- [ ] ساخت Infinity Loop
- [ ] ساخت داشبورد
- [ ] اتصال به API واقعی
- [ ] تست نسخه ۱
- [ ] انتشار نسخه پایدار روی main

---

## 👤 Developer

**Mehdi (klg2m)**  
Creator of Nexity
