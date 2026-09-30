# Leoton Hotel

Live site: https://leoton.chernivtsi.space

## About
Leoton Hotel — готель у Чернівцях. Односторінковий лендинг. Фото закладу немає (`photos_source: null`), тому hero типографічний (CSS/SVG), а єдині фото — міста Чернівців з Pexels (див. Photos).

## Hero concept
Злітна смуга в перспективі: темне нічне тло, розмітка й бурштинові вогні, що біжать до горизонту. Концепт виходить із підтвердженого безкоштовного трансферу до аеропорту.

## Amenities (verified, list.json)
- Безкоштовний Wi‑Fi
- Безкоштовна парковка
- Кондиціонер
- Сімейні номери
- Цілодобова рецепція
- Обслуговування номерів
- Бар
- Безкоштовний трансфер з аеропорту

## Check-in / check-out
не встановлено

## Reviews
Booking.com 8.3/10 (145), Google 3.8/5 (147). Знімок на 30.09.2026, платформи окремо, без aggregateRating.

## Contact
- Phone: +380 66 363 3201
- Booking.com: https://www.booking.com/hotel/ua/leoton.html
- Google Maps: https://maps.google.com/?cid=10247185743084967943
- Address: вул. Чкалова, 30В, Чернівці

## Not published
Час заїзду/виїзду, кількість номерів, зірковість (Google Hotels показує 3★ без офіційного джерела), email, сайт, Instagram, графік і умови трансферу, «біля аеропорту». Телефон — з Google Hotels (інший довідник мав інший номер).

## Forms
HotelOS (`ch-leoton`): `stay-request` (проживання). Документ `hotels/ch-leoton` у Firestore треба створити вручну, інакше правила відхилять заявки.

## Photos
Лише фото міста (не готелю), з Pexels, підключені за прямими посиланнями images.pexels.com (без копій у репо), з підписами та авторами на сторінці:

- Резиденція буковинських митрополитів, нині Чернівецький університет: pexels.com/photo/12961411 (Valeriia Harbuz)
- Вулиця в Чернівцях: pexels.com/photo/17268858 (Андрій Копічевський)
- Цегляні арки: pexels.com/photo/38163642 (Natalia Sevruk)

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hotel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
