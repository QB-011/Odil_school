# Odil School — Zamonaviy Gamifikatsiyalashgan LMS Platformasi

"Odil School" o'quv markazi uchun to'liq funksional, zamonaviy, gamifikatsiya (Coin, Poin, Do'kon, Reyting), ko'p tilli (O'zbek / Rus) va Dark/Light rejimli ta'lim boshqaruv tizimi (LMS).

---

## Asosiy Imkoniyatlar va Bo'limlar

### 🌟 1. O'quvchilar Paneli (Student Portal - Mobile First)
- **Shaxsiy Profil:** Ism-familiya, rasm, o'qiydigan sinfi, kuratori (ustozi) haqida ma'lumot, parolni o'zgartirish.
- **Gamifikatsiya (Coin & Poin):**
  - **Odil Coin:** Uy vazifalarini topshirish, testlarni a'lo yechish va faollik uchun beriladigan asosiy valyuta.
  - **Dars Poini:** Darsdagi faol ishtirok uchun kunlik ballar.
- **Odil Coin Do'koni (Coin Shop):**
  - Yig'ilgan tangalarni kiyimlar (brendli xudi, kepka), texnik gadjetlar (fleshka, simsiz sichqoncha), sertifikatlar va mentorlik darslariga almashtirish.
- **Avtomatlashtirilgan Darslar & Testlar:**
  - Ustoz mavzu kiritishi bilan avtomatik 10 talik test shakllanadi.
  - Har bir to'g'ri javob uchun darhol Coin va Poin beriladi.
- **Qoldirilgan Darslar Bo'limi (Missed Lessons):**
  - Darsga kelmagan o'quvchilar uchun maxsus o'zlashtirish portali: dars videosi, konspekti va mustaqil test topshirish orqali darsni o'zlashtirish.
- **Reyting (Leaderboard):**
  - Sinfdoshlar va umumiy maktab bo'yicha oltin, kumush va bronza shohsupasi bilan jonli reyting.
- **Dars Jadvali:** Haftalik vaqt, xona va o'qituvchi ma'lumotlari.

### 🎓 2. Ustozlar Paneli (Teacher Portal)
- **Bitta Sinfga Diqqat Jamlash (Focus Mode):** Ustoz chalg'ib ketmasligi uchun bir vaqtning o'zida faqat tanlangan bitta sinf boshqariladi.
- **Davomat (Attendance):**
  - Har bir sanadagi davomatni "Kelgan", "Kelmagan", "Kechikkan" deb belgilash.
  - Darsga kelmagan o'quvchilarga avtomatik tarzda "Qoldirilgan darslar" portalida vazifa shakllanadi.
- **Mavzu Kiritish:**
  - O'tilgan mavzu nomi, video havolasi va tavsif kiritiladi.
  - Tizim o'quvchilar uchun avtomatik 10 talik test savollarini shakllantiradi.
- **Qo'lda Coin & Poin Mukofotlash:**
  - Doskada faol qatnashgan yoki to'g'ri fikr bildirgan o'quvchiga darhol tangalar berish imkoniyati.
- **Sinf O'quvchilari Ro'yxati va Statistikasi.**

### 🛡️ 3. Administrator Paneli (Admin Portal)
- **Yashirin / Maxsus Kirish:** Login sahifasi ostidagi maxfiy havola orqali boshqaruv markaziga o'tish.
- **Boshqaruv Metrikalari (Dashboard):**
  - Jami o'quvchilar, ustozlar, faol sinflar soni, umumiy aylanmadagi tangalar va haftalik davomat foizi.
- **O'quvchilar Boshqaruvi (CRUD):** Yangi o'quvchi qo'shish, sinfga biriktirish, o'chirish.
- **Ustozlar va Sinflar Boshqaruvi:** Yangi sinf ochish, ustoz biriktirish, dars jadvalini kiritish.
- **Umumiy Davomat Monitoringi:** Barcha sinflar bo'yicha davomat natijalarini markazlashgan holda kuzatish.
- **Coin Shop Boshqaruvi:** Do'konga yangi sovg'alar qo'shish, narxini belgilash, buyurtmalarni tasdiqlash.
- **E'lonlar & Bildirishnomalar:** Barcha maktab yoki ma'lum bir sinf uchun rasmiy e'lonlar chiqarish.

---

## 🎨 Dizayn & Texnologiyalar
- **Frontend:** React 19 + TypeScript + Vite
- **Uslublash:** Tailwind CSS v4 (Mobile-First responsive dizayn)
- **Ko'p tillilik (i18n):** O'zbek tili (UZ) va Rus tili (RU)
- **Dark / Light Mode:** `ThemeContext` orqali saqlanuvchi qorong'i va yorug' rejim
- **Gamifikatsiya:** Canvas Confetti va animatsiyalar
- **Ikonkalar:** Lucide React

---

## 🚀 Ishga Tushirish (Local Run)

1. Kutubxonalarni o'rnatish:
   ```bash
   npm install
   ```

2. Loyihani ishga tushirish (Dev server):
   ```bash
   npm run dev
   ```

3. Production build qilish:
   ```bash
   npm run build
   ```

---

## 🔑 Sinov Uchun Demo Hisoblar (1-bosishda kirish mumkin):
- **O'quvchi:** Jasur Aliyev (`+998901234567`)
- **Ustoz:** Sherzod Odilov (`+998909876543`)
- **Admin:** Odil Rahimov (`+998900000000`)
