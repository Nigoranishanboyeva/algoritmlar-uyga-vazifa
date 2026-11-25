# algoritmlar-uyga-vazifa
# Algoritmlar — uyga vazifa

## 1-topshiriq. Qaysi xossa buzilgan? — 15 ball

| Algoritm | Buzilgan xossa | Sabab | Tuzatilgan variant |
|---|---|---|---|
| a) «Kompotga shakarni ko‘nglingizcha soling». | Aniqlik | «Ko‘nglingizcha» iborasi shakar miqdorini aniq belgilamaydi. | «1 litr kompotga 2 osh qoshiq shakar soling». |
| b) «1. Eshikni yop. 2. Xonadan chiq». | Diskretlik (qadamlarning ketma-ketligi) | Yopilgan eshikdan chiqish uchun uni avval ochish kerak. | «1. Agar eshik yopiq bo‘lsa, uni och. 2. Xonadan chiq. 3. Eshikni yop». |
| c) «1. Bir qadam tashla. 2. 1-qadamga qayt». | Natijaviylik (chekli qadamlarda tugash) | To‘xtash sharti yo‘q, shuning uchun qadamlar cheksiz takrorlanadi. | «Bir qadam oldinga yur» buyrug‘ini 5 marta bajar va to‘xta. |
| d) Robot-changyutgichga «Xonani chiroyli qilib qo‘y». | Tushunarlilik | Robot «chiroyli qilib qo‘y» degan iborani buyruq sifatida bajara olmaydi. | Robotga o‘zi taniydigan «Tozalashni boshlash» buyrug‘ini ber. |
| e) «Ikki sonni qo‘shish» algoritmi faqat 5 va 7 uchun ishlaydi. | Ommaviylik | Algoritm faqat bitta sonlar juftligiga moslangan. | «1. `a` va `b` sonlarini kirit. 2. `a + b` ni hisobla. 3. Yig‘indini chiqar». |

## 2-topshiriq. Bankomat algoritmi — 15 ball

**a) To‘g‘ri tartib** — **8 → 2 → 6 → 4 → 5 → 1 → 3 → 7**.

Avval bankomatni ko‘zdan kechiraman. Kartani qo‘yib, tilni tanlayman va PIN kodni qo‘lim bilan to‘sib kiritaman. «Naqd pul yechish» xizmatini, keyin 100 000 so‘mni tanlayman. Pul va kartani olib, chekni tekshiraman.

**b) O‘rni almashishi mumkin bo‘lgan qadamlar** — **6 va 4**, agar bankomat tilni PIN koddan keyin ham tanlashga imkon bersa. Amalda bankomat ekranida ko‘rsatilgan tartibga amal qilaman.

**c) Shartli qadam.** Agar karta teshigida begona qurilma ko‘rinsa, kartani qo‘ymayman va boshqa bankomatdan foydalanaman. Bu karta ma’lumotlarini himoya qilishga yordam beradi.

## 3-topshiriq. Ijrochi bo‘ling — 15 ball

| 2-qadam necha marta bajarildi | Son qiymati | 20 dan kattami? |
|---:|---:|---|
| 0 | 2 | Yo‘q |
| 1 | 5 | Yo‘q |
| 2 | 8 | Yo‘q |
| 3 | 11 | Yo‘q |
| 4 | 14 | Yo‘q |
| 5 | 17 | Yo‘q |
| 6 | 20 | Yo‘q |
| 7 | 23 | Ha |

**a)** Algoritm **23** sonini yozdi. 20 ga yetganda shart bajarilmadi, chunki son 20 dan katta bo‘lishi kerak.

**b)** 2-qadam **7 marta** bajarildi. Yettinchi qo‘shishdan keyin son 23 bo‘ldi va algoritm to‘xtadi.

**c)** Son 1 dan boshlansa va shart «20 ga teng bo‘lsa» deb o‘zgartirilsa, algoritm **to‘xtamaydi**. Sonlar `1, 4, 7, 10, 13, 16, 19, 22, …` tarzida o‘zgaradi. 19 dan keyin 22 keladi va keyingi qiymatlar yana ortib boradi, shuning uchun 20 hosil bo‘lmaydi.

## 4-topshiriq. Robot labirinti — 20 ball

**a) Eng qisqa yo‘l** — `→ ↓ → ↓ → ↓ → ↓ → ↓`

**Sababi.** Bu yo‘l devorlarga tegmaydi. Bayroq boshlang‘ich katakdan 5 katak o‘ngda va 5 katak pastda joylashgan. Shuning uchun 10 qadamdan qisqa yo‘l bo‘lishi mumkin emas.

**b) Takrorlash bilan** — `→ ↓` buyruqlar juftligini **5 marta** takrorla.

**c) 50 pog‘ona uchun** — `→ ↓` buyruqlar juftligini **50 marta** takrorla. Jami 100 ta buyruq bajariladi. Bu **ommaviylik** xossasiga misol, chunki shu zinapoya shakli davom etsa, algoritm istalgan `N` pog‘ona uchun ishlaydi: `→ ↓` juftligini `N` marta takrorlash kifoya.

## 5-topshiriq. Katta masalani bo‘laklarga ajrating — 15 ball

### a) Mini-futbol turnirini bo‘laklarga ajratish

1. Oltita sinf jamoasini ro‘yxatga olish.
2. O‘yin formatini va musobaqa qoidalarini belgilash.
3. Maydon, o‘yin vaqtlari, jihozlar va hakamlarni belgilash.
4. O‘yin jadvalini tuzish va jamoalarga yuborish.
5. O‘yinlarni o‘tkazish va natijalarni qayd etish.
6. G‘oliblarni aniqlash va taqdirlash.

### b) Birinchi bo‘lak va sababi

Avval jamoalarni ro‘yxatga olaman. O‘yin juftliklarini tuzish uchun qaysi jamoalar qatnashishi ma’lum bo‘lishi kerak.

### c) O‘yin jadvalini tuzish algoritmi

Har bir jamoa qolgan jamoalar bilan bir martadan o‘ynaydi.

1. Oltita jamoani 1 dan 6 gacha raqamla.
2. Barcha o‘yin juftliklarini yoz. Har bir juftlikni bir marta yoz.
3. Maydonning bo‘sh vaqtlarini tartib bilan yoz.
4. Birinchi belgilanmagan juftlikni va birinchi bo‘sh vaqtni ol.
5. Agar bo‘sh vaqt qolmagan bo‘lsa, maydon uchun qo‘shimcha vaqt ajrat va uni ro‘yxatga qo‘sh.
6. Juftlikni jadvalga yoz va tanlangan vaqtni band deb belgilab qo‘y.
7. Barcha juftliklar jadvalga kiritilguncha 4–6-qadamlarni takrorla.
8. Jadvalda 15 ta o‘yin borligini tekshir va uni jamoalarga yubor.

Olti jamoaning har biriga beshtadan raqib to‘g‘ri keladi. Har bir o‘yin ikki jamoa hisobida uchragani uchun jami `6 × 5 ÷ 2 = 15` ta o‘yin bo‘ladi.

## 6-topshiriq. Uyda «odam-robot» sinovi — 20 ball

**Tanlangan ish** — ertangi darsga sumka yig‘ish.

1. Sumkani stol ustiga qo‘y.
2. Sumkaning asosiy bo‘limi fermuarini och.
3. Ertangi dars jadvalini och.
4. Jadvaldagi birinchi fanning nomini o‘qi.
5. Shu fan uchun kerakli darslikni sumkaga sol.
6. Shu fan uchun ajratilgan daftarni sumkaga sol.
7. Agar jadvalda keyingi fan bo‘lsa, uning nomini o‘qi va 5–6-qadamlarni takrorla. Barcha fanlar tugagach, 8-qadamga o‘t.
8. Qalamdonni sumkaning old cho‘ntagiga sol.
9. Sumkaning asosiy bo‘limi va old cho‘ntagi fermuarlarini yop.
10. Sumkani stol yoniga qo‘y.

Quyidagi misolda 8-qadamni bajarish uchun cho‘ntakni ochish ham yozilishi kerak. Bo‘sh qatorga uyda o‘tkazgan sinovingizning natijasini yozing.

| Robot qoqilgan joy | Qaysi xossa buzilgan va nima uchun? | Tuzatilgan qadam |
|---|---|---|
| Namuna — 8-qadamda old cho‘ntak yopiq edi. | Diskretlik. Cho‘ntakni ochish qadami tushib qolgan. | «Old cho‘ntak fermuarini och va qalamdonni cho‘ntakka sol». |
| … | … | … |

## O‘zimni tekshiraman

- [ ] Algoritm nima ekanini bir jumla bilan ayta olaman.
- [ ] Beshta xossani misol bilan tushuntira olaman.
- [ ] Algoritmni qog‘ozda ijrochi kabi bajara olaman.
- [ ] Katta masalani bo‘laklarga ajrata olaman.

**Jami — 100 ball.**
