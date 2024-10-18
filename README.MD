# Word2Vec loyihasi

Ushbu repositoryda Word2Vec modeli va so'z embeddinglarini tushunish uchun olib borilgan tajribalar kiritilgan. Word2Vec — so'zlarni uzluksiz vektor fazosida ifodalaydigan kuchli model bo'lib, so'zlar orasidagi semantik o'xshashlikni aniqlashda ishlatiladi.

## Umumiy ma'lumot

Word2Vec modeli bir-biriga bog'liq bo'lgan ikkita asosiy modelni o'z ichiga oladi:

- **CBOW (Continuous Bag of Words):** Ma'lum bir so'zni uning kontekstdagi so'zlariga asoslanib bashorat qiladi.
- **Skip-gram:** Berilgan so'z asosida uning kontekstdagi so'zlarini bashorat qiladi.

Har ikki model so'zlarni yuqori o'lchamli vektor fazosida joylashtiradi, bunda semantik jihatdan o'xshash so'zlar bir-biriga yaqin bo'ladi.

## Asosiy tushunchalar

- **So'z embeddinglari:** So'zlarning zich vektorli ifodalari, bunda ma'nosi o'xshash so'zlar yaqin vektorlar sifatida ifodalanadi.
- **Kontekst derazasi:** Berilgan so'z atrofidagi qancha so'zlarni kontekst sifatida olish kerakligi.
- **Mashq qilish maqsadi:** O'xshash so'zlar orasidagi masofani minimallashtirish va o'xshash bo'lmagan so'zlarni maksimal darajada uzoqlashtirish.

## Fayllar va tuzilma

- `word2vec_model.py`: CBOW va Skip-gram usullari yordamida Word2Vec modelini amalga oshiruvchi kod.
- `data_preprocessing.py`: Matnni model uchun tayyorlash, tozalash va tokenizatsiya qilish funksiyalarini o'z ichiga oladi.
- `train.py`: Word2Vec modelini berilgan datasetda o'qitish uchun ishlatiladigan skript.
- `README.md`: Ushbu hujjat.

## Ishlatish yo'riqnomasi

1. Repositoryni klonlash:

```bash
git clone https://github.com/nurbekdev/word2vec.git
