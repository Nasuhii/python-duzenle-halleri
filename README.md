# 🐍 VBA207 - Python Programlama: Master Ders Notları & Vize Hazırlık Deposu

![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Academic](https://img.shields.io/badge/Sakarya_Üniversitesi-Veri_Bilimi_ve_Analitiği-crimson)
![Status](https://img.shields.io/badge/Durum-Tamamlandı_&_Vizeye_Hazır-brightgreen)
![Deck](https://img.shields.io/badge/Anki_Deck-data-orange)

Bu depo, **Sakarya Üniversitesi Veri Bilimi ve Analitiği Bölümü (2. Sınıf Güz Dönemi)** kapsamında yürütülen **VBA207 Python Programlama** dersinin tüm haftalık ders notlarını, kod izleme analizlerini, laboratuvar/test soru çözümlerini ve Anki flashcard entegrasyonlarını içermektedir.

---

## 📅 Ders & Sınav Bilgileri

- **Ders Kodu & Adı:** VBA207 - Python Programlama
- **Öğretim Üyesi:** Dr. Özkan CANAY
- **Dönem:** 2026 - 2027 Güz Yarıyılı (2. Sınıf)
- **Ara Sınav (Vize) Tarihi:** 11 Kasım 2026 Çarşamba — **Saat: 16:00** (Derslik: D1201, Etki Oranı: %25)
- **Sınav Formatı:** Çoktan Seçmeli (Test) / Kod İzleme (Code Tracing) / Uç Durum (Edge-Case) Analizi

---

## 📚 Depo İçerik Haritası ve Ders Notları

| Dosya Adı | Hafta / Konu | Ağırlık / Önem | Temel Başlıklar |
| :--- | :--- | :---: | :--- |
| [`H01_Kurulum_ve_Temel_Sozdizimi.md`](./H01_Kurulum_ve_Temel_Sozdizimi.md) | Hafta 01: Kurulum & Sözdizim | %5 | Anaconda, Spyder, Jupyter (.py vs .ipynb), `print(sep, end)`, `input()`, PEP 8, Traceback |
| [`H02_Degiskenler_ve_Temel_Veri_Tipleri.md`](./H02_Degiskenler_ve_Temel_Veri_Tipleri.md) | Hafta 02: Tipler & Bellek | %15 | Dinamik tiplilik, `type()`, int/float/str/bool, Tip dönüşümleri, String formatlama (f-string) |
| [`H03_Operatorler_ve_Karar_Yapilari.md`](./H03_Operatorler_ve_Karar_Yapilari.md) | Hafta 03: Operatörler & Karar | %20 | Aritmetik/Mantık operatörleri, `pow(x,y,z)`, Short-Circuit (`and`/`or` koruma), `in` (set vs list), `is` vs `==`, Ternary If |
| [`H04_Donguler_While_For_ve_Karakter_Dizileri.md`](./H04_Donguler_While_For_ve_Karakter_Dizileri.md) | Hafta 04: Döngüler & Strings | **%35 (Kritik)** | `while`, Gauss toplamı, `while-else` / `for-else` (break tuzağı), `range()`, `enumerate()`, `zip()`, String dilimleme `[::-1]`, `split()`, `count()` |
| [`H05_Fonksiyonlar_ve_Scope.md`](./H05_Fonksiyonlar_ve_Scope.md) | Hafta 05: Fonksiyonlar & Scope | %25 | `def`, Parametre vs Argüman, Varsayılan değerler, `*args`, `**kwargs`, LEGB kuralı, `global`/`nonlocal`, `lambda` |
| [`H06_Moduller_Paketler_ve_Kutuphaneler.md`](./H06_Moduller_Paketler_ve_Kutuphaneler.md) | Hafta 06: Modüller & Standart Lib | %15 | `import`, `pip`, `__version__`, `__file__`, `math` (sqrt, pow, ceil, floor), `random` (randint vs randrange, choice vs sample vs choices) |
| [`VBA207_Vize_Kod_Izleme_ve_Soru_Bankasi.md`](./VBA207_Vize_Kod_Izleme_ve_Soru_Bankasi.md) | Sınav Bankası & Soru Çözümleri | 🔥 **Tüm Konular** | 10 Çözümlü Test Sorusu, Adım adım kod izleme tabloları (Trace Tables), Acemi hataları ve hoca tuzakları |

---

## ⚡ Vize Sınavı İçin Altın Hızlı Başvuru Kartı (Cheat Sheet)

1. **`while-else` / `for-else` Tuzağı:** Döngüden `break` ile çıkılırsa `else` bloğu **ASLA ÇALIŞMAZ**.
2. **String Dilimleme Bitiş İndeksi:** `s[1:5]` işleminde 1. indeks dahildir; ancak 5. indeks **HARİÇTİR**.
3. **`pow()` 3 Parametreli Mantık:** `pow(25, 2, 5)` ifadesi `(25 ** 2) % 5` demektir ve sonuç doğrudan `0` çıkar.
4. **`randint()` vs `randrange()`:**
   - `random.randint(1, 10)` ➔ 10 DAHİLDİR.
   - `random.randrange(1, 10)` ➔ 10 HARİÇTİR (en fazla 9 üretilir).
5. **`sample()` vs `choices()`:**
   - `random.sample()` ➔ TEKRARSIZ seçim (without replacement).
   - `random.choices()` ➔ TEKRARLI seçim (with replacement).
6. **Sözlüklerde `in` Operatörü:** `in sozluk` ifadesi sadece **anahtarları (keys)** sorgular; değerleri sorgulamaz.
7. **Kısa Devre (Short-Circuit):** `sayi != 0 and 10/sayi > 1` ifadesinde `sayi = 0` ise sağ taraf hiç işletilmez, `ZeroDivisionError` engellenir.

---

## 🃏 Anki Entegrasyonu
Tüm dosyalarda otomatik **Obsidian to Anki** formatında flashcard'lar yer almaktadır:
- Teknik Konular: `TARGET DECK: data`
- B2+ İngilizce Terimler: `TARGET DECK: ing kelimeler`

---
*Hazırlayan: Nasuhi — Sakarya Üniversitesi Veri Bilimi ve Analitiği*
