# HTML 1-Dars: HTML ga Kirish

Ushbu hujjat 1-dars (`lesson1.html`) da o'rganilgan asosiy tushunchalarni o'z ichiga oladi.

## Darsning Maqsadi
HTML (HyperText Markup Language) ning asosiy tuzilishi, sarlavhlar va matn bilan ishlashni o'rganish.

## 1. HTML Hujjatining Tuzilishi
Har bir HTML hujjat ma'lum bir standart tuzilishga ega bo'lishi kerak.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sahifa Sarlavhasi</title>
</head>
<body>
  <!-- Asosiy tarkib shu yerda bo'ladi -->
</body>
</html>
```

### Tuzilish Elementlari:
- **`<!DOCTYPE html>`**: Brauzerga ushbu hujjat HTML5 standarti asosida yozilganligini bildiradi.
- **`<html>`**: Hujjatning ildiz elementi. `lang="en"` atributi sahifa tili ingliz tilida ekanligini ko'rsatadi.
- **`<head>`**: Hujjat haqidagi meta-ma'lumotlarni o'z ichiga oladi (foydalanuvchiga ko'rinmaydi).
- **`<body>`**: Veb-sahifaning asosiy ko'rinadigan qismini o'z ichiga oladi.

## 2. Head Qismi (`<head>`)
Bu qismda sahifa sozlamalari joylashadi.

- **`<meta charset="UTF-8">`**: Belgilar kodirovkasini (UTF-8) belgilaydi. Bu orqali har xil tillardagi harflar to'g'ri ko'rsatiladi.
- **`<meta name="viewport" ...>`**: Mobil qurilmalarda sahifaning to'g'ri ko'rinishini ta'minlaydi (moslashuvchanlik uchun).
- **`<title>`**: Brauzer tabida ko'rinadigan sahifa nomini belgilaydi. 1-darsda bu "1-Dars" deb nomlangan.

## 3. Matn Elementlari (`<body>` ichida)
1-darsda quyidagi matn formatlash teglari ishlatilgan:

### Sarlavhalar (`<h1>` - `<h6>`)
HTML da sarlavhalar `h1` dan `h6` gacha bo'ladi. `h1` eng katta va asosiy sarlavha hisoblanadi.

Misol:
```html
<h1>Introduction...?</h1>
<h2>Introduction????</h2>
```

### Paragraflar (`<p>`)
Oddiy matnni yozish uchun `<p>` (paragraph) tegi ishlatiladi. Har bir `<p>` yangi qatordan boshlanadi va matnlar orasida bo'shliq qoldiradi.

Misol:
```html
<p>Bu yerda siz HTML, CSS va JavaScript asoslarini o'rganasiz.</p>
```

## Xulosa
Bu darsda siz oddiy veb-sahifa yaratishni, unga sarlavha va matn qo'shishni o'rgandingiz. Keyingi darslarda ushbu bilimlar kengaytirib boriladi.
