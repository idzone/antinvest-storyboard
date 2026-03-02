# antinvest-storyboard

ANT Invest Club аппын **гол storyboard** — бүх дэлгэцийн скриншот ба хавтасны газрын зураг. Хэрэглэгч болон backend хөгжүүлэгчид лавлагаа болгон ашиглана.

## Холбоос

- **Storyboard (зурагтай):** [https://idzone.github.io/antinvest-storyboard/](https://idzone.github.io/antinvest-storyboard/)

## Агуулга

- `index.html` — гол storyboard хуудас (Splash, Onboard, ДАН, Register, Login, Home, Loan, Savings, Profile)
- `screenshots/01_auth/` — бүх дэлгэцийн скриншотууд (splash, onboard, dan_not_connected, register, biometric, resetpass, home, loan, savings, profile)
- **Идэвхтэй зээл (22→1–6):** Дэлгэц 22 «Идэвхтэй зээл байхгүй»-аас идэвхтэй зээлтэй flow холбогдсон. Зургууд: `screenshots/01_auth/loan/loan_22_active_1.png` … `loan_22_active_6.png` (жагсаалт → дэлгэрэнгүй → эргэн төлөлт → үндсэн данс/банк/QPAY). Эдгээр 6 зураг байхгүй бол картууд хоосон харагдана; Cursor-ийн assets-аас хуулж тавина.

## GitHub Pages идэвхжүүлэх

1. Энэ репог GitHub дээр push хийсний дараа: **Settings** → **Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main` (эсвэл `master`), folder: **/ (root)** → Save
4. Хэдэн минутын дараа сайт нээгдэнэ: `https://idzone.github.io/antinvest-storyboard/`
..