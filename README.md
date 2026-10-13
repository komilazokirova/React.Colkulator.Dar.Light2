# 🧮 Oddiy Kalkulyator (Smart Modern Calculator)

React 19, TypeScript va Tailwind CSS yordamida yaratilgan zamonaviy, qulay va chiroyli interfeysga ega interaktiv kalkulyator web-ilovasi.

![Kalkulyator](https://img.shields.io/badge/React-19-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)
![TailwindCSS](https://img.shields.io/badge/Tailwind-CSS-38bdf8?logo=tailwindcss)
![Vite](https://img.shields.io/badge/Vite-6-646cff?logo=vite)

---

## ✨ Asosiy imkoniyatlar (Features)

- **Asosiy arifmetik amallar**:
  - Qo'shish (`+`), Ayrish (`-`), Ko'paytirish (`×`), Bo'lish (`÷`), Foiz hisoblash (`%`).
- **Qo'shimcha ilmiy funksiyalar**:
  - Kvadrat darajaga ko'tarish (\(x^2\))
  - Kvadrat ildiz chiqarish (\(\sqrt{x}\))
  - Teskari qiymatni topish (\(1/x\))
  - Ishorani o'zgartirish (\(\pm\))
- **Amallar tarixi (Calculation History)**:
  - Barcha bajarilgan hisob-kitoblar avtomatik saqlanadi (`localStorage`).
  - Istalgan tarix elementini bosib, natijani qayta displeyga yuklash mumkin.
  - Tarixni bir tugma bilan tozalash imkoniyati.
- **Mavzular (Light / Dark Mode)**:
  - Tungi (Dark) va kunduzgi (Light) rejimlar. Tizim tanloviga moslashish va foydalanuvchi tanlovini saqlab qolish.
- **Audio effektlar (Sound Feedback)**:
  - Web Audio API orqali tugmalarni bosganda yoqimli chertish tovushi (istalgan vaqtda o'chirib/yoqish mumkin).
- **Natijani nusxalash (Copy to Clipboard)**:
  - Chiqqan natijani birgina bosish orqali nusxalab olish.
- **To'liq klaviatura boshqaruvi (Keyboard Shortcuts)**:
  - Sichqonchasiz faqat klaviaturadan foydalanib barcha amallarni tezkor bajarish.

---

## ⌨️ Klaviatura tugmalari (Shortcuts)

| Tugma | Vazifasi |
| :--- | :--- |
| `0` - `9` | Raqamlar kiritish |
| `+` `-` `*` `/` | Arifmetik amallar |
| `Enter` yoki `=` | Natijani hisoblash |
| `Backspace` | Oxirgi kiritilgan raqamni o'chirish |
| `Escape` yoki `C` | Displeyni tozalash (AC) |
| `%` | Foiz amali |
| `H` | Tarix panelini ochish / yopish |
| `T` | Mavzuni almashtirish (Dark / Light) |

---

## 🚀 O'rnatish va ishga tushirish (Getting Started)

1. **Repozitoriyani yuklab oling yoki klon qiling**:
   ```bash
   git clone https://github.com/komilazokirova/loyixa.00.git
   cd simple-calculator
   ```

2. **Kutubxonalarni o'rnating**:
   ```bash
   npm install
   ```

3. **Lokal serverda ishga tushiring**:
   ```bash
   npm run dev
   ```

4. **Production uchun build olish**:
   ```bash
   npm run build
   ```

---

## 📁 Loyiha tuzilmasi (Project Structure)

```
simple-calculator/
├── src/
│   ├── components/
│   │   ├── Display.tsx                # Katta displey va nusxalash
│   │   ├── Header.tsx                 # Logo, mavzu, audio va modallar
│   │   ├── Keypad.tsx                 # Raqamlar va amallar tugmalari
│   │   ├── HistoryDrawer.tsx          # Hisob-kitoblar tarixi
│   │   └── KeyboardShortcutsModal.tsx # Klaviatura yordami
│   ├── hooks/
│   │   └── useCalculator.ts           # Kalkulyator state va operatsiyalari
│   ├── types/
│   │   └── calculator.ts              # TypeScript tiplari
│   ├── utils/
│   │   └── calculatorEngine.ts        # Arifmetik mantiq va Web Audio
│   ├── App.tsx                        # Asosiy sahifa
│   ├── main.tsx                       # Entry point
│   └── index.css                      # Tailwind va maxsus stillar
├── index.html
├── package.json
├── tsconfig.json
└── vite.config.ts
```

---

Dasturchi: **Komila Zokirova**
