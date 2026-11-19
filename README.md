# Davlatlar: tuzilish va boshqaruv shakli

Davlatlarning **davlat tuzilishi** (federativ / unitar) va **boshqaruv shaklini** (monarxiya va respublika turlari) yodlash uchun oddiy veb-ilova.

## Imkoniyatlar

- **Flashkart**: davlat nomi, bossangiz javob ochiladi. Bo'lim bo'yicha filtr, "Bilaman / Bilmadim" belgilari.
- **Test**: 10 savollik variantli test.
- **Bo'lim**: bo'limlar bo'yicha yodlash (yashirish, aralashtirish, mashq).
- **Moslash**: davlatlarni boshqaruv shakliga moslashtirish.
- **Ro'yxat**: qidiruv bilan to'liq ro'yxat.

## Ishga tushirish

Bitta fayl (`index.html`), hech qanday o'rnatish yoki tashqi kutubxona kerak emas. Faylni brauzerda oching.

## GitHub Pages orqali joylash

1. GitHub'da yangi repozitoriy oching (masalan, `davlatlar-app`).
2. `index.html` va `README.md` fayllarini yuklang.
3. **Settings → Pages** bo'limiga kiring.
4. **Source:** `Deploy from a branch`, **Branch:** `main`, papka `/ (root)` ni tanlang va saqlang.
5. Bir-ikki daqiqadan so'ng sayt `https://<foydalanuvchi>.github.io/davlatlar-app/` manzilida ochiladi.

## Ma'lumot haqida

Ma'lumotlar o'quv qo'llanmadagi jadvallarga asoslangan: monarxiyalar (41), respublikalar (152, qo'llanmadagi guruhlash bo'yicha). Venesuela jadvallarda yo'q edi, shuning uchun prezidentlik respublikasi sifatida qo'shilgan. "Bilaman" belgilari brauzerda (`localStorage`) saqlanadi.
