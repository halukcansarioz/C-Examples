# 🧠 C-Examples
### (C Programlama Dili Öğrenirken Yazdığım Temel Algoritma ve Örnek Kodlar)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)](#)
[![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)](#)
[![Made with Learning](https://img.shields.io/badge/Made%20with-Learning-1f425f.svg)](#)

Programlama öğrenme sürecimde C ve C++ dilleri ile yazdığım basit algoritma ve örneklerden oluşan bir çalışma deposudur. Karar yapılarından işaretçilere, dizilerden dosyalamaya kadar birçok konuyu kapsar.

## 📚 İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Özellikler](#özellikler)
- [İçerik ve Kapsam](#içerik-ve-kapsam)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Kurulum ve Kullanım](#kurulum-ve-kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Geliştirme Süreci](#geliştirme-süreci)
- [Katkıda Bulunma](#katkıda-bulunma)
- [İletişim](#iletisim)
- [Lisans](#lisans)

---

## Proje Hakkında
Bu depo, programlama temellerini pekiştirmek amacıyla C/C++ dillerinde yazılmış küçük ve anlaşılır örnek kodları içermektedir. Her dosya, belirli bir konuyu veya algoritmayı ele alarak öğrenme sürecini adım adım belgelemektedir.

* **Geliştirici:** Haluk Can SARIÖZ
* **Amaç:** Algoritma ve programlama pratiği
* **Hedef Kitle:** Programlamaya yeni başlayanlar ve C dilini pekiştirmek isteyenler

---

## Özellikler
* **Geniş Konu Yelpazesi:** Temel girdi/çıktı işlemlerinden ileri veri yapılarına kadar birçok konu.
* **Türkçe Açıklamalar:** Kod içi yorumlar ve dosya isimleri Türkçedir, böylece konuların anlaşılması kolaylaşır.
* **Çalıştırılmaya Hazır:** Her bir `.c` veya `.cpp` dosyası bağımsız olarak derlenip çalıştırılabilir.

---

## İçerik ve Kapsam
Depoda yer alan bazı başlıca konu ve örnekler:

| Konu | Örnek Kodlar |
|------|-------------|
| **Karar Yapıları** | Sayının tek mi çift mi olduğunu anlama, Sayının asal olup olmadığını kontrol etme, 2 sayı arasında olup olmadığını kontrol etme |
| **Döngüler** | 1 ile 100 arası sayıların toplamı, Basamak sayısı bulma, Yıldızlardan piramit çizme, Fibonacci serisi |
| **Diziler ve Sıralama** | 10 Elemanlı bir diziyi sıralama, En büyük ve en küçük sayıyı bulma, Selection sort uygulaması |
| **Fonksiyonlar** | Faktöriyel hesaplama, Altın oran hesaplama, Faiz hesaplama |
| **Karakter ve String İşlemleri** | Girilen metnin uzunluğunu bulma, Kelimedeki karakter sayılarını hesaplama, Metni tersten yazma, Baş harfleri bulan program |
| **Matematiksel İşlemler** | Asal çarpan bulma, 2. dereceden denklemin köklerini hesaplama, Mükemmel sayı kontrolü, Kardeş sayı kontrolü |
| **Matris İşlemleri** | Matris uygulaması, Matris köşegen çarpımı, Sihirli matris olup olmadığını anlama |
| **İşaretçiler (Pointer)** | 10 Elemanlı dinamik dizide en büyük elemanın bulunması |
| **Dosyalama** | Örnek dosyalama işlemleri |
| **Yapılar (Struct)** | Öğrenci uygulaması, Muhtarlık uygulaması, Basit eczane uygulaması |

---

## Kullanılan Teknolojiler
* **C:** Projenin temel programlama dili.
* **C++:** Bazı örneklerde kullanılan ek özellikler.
* **GCC / G++:** Derleme işlemleri için kullanılan araçlar.
* **VS Code / Dev-C++:** Geliştirme ortamı olarak kullanılan editörler.

---

## Kurulum ve Kullanım

### 1. Depoyu Klonlayın
```bash
git clone https://github.com/halukcansarioz/C-Examples.git
```

### 2. Proje Dizinine Gidin
```bash
cd C-Examples
```

### 3. Herhangi Bir Kodu Derleyin ve Çalıştırın
Her bir dosya bağımsız bir örnektir. Örneğin:

* **Linux / macOS için:**
```bash
gcc "Faktoriyel hesaplama.c" -o faktoriyel
./faktoriyel
```

* **Windows için (MinGW / GCC kurulu olmalı):**
```bash
gcc "Faktoriyel hesaplama.c" -o faktoriyel.exe
faktoriyel.exe
```

> **Not:** Dosya isimleri Türkçe karakterler ve boşluklar içerdiği için komut satırında tırnak (`""`) içinde yazılması önerilir. Alternatif olarak, bir IDE (VS Code, Code::Blocks, Dev-C++) kullanarak da dosyaları açıp doğrudan çalıştırabilirsiniz.

---

## Proje Yapısı
Depo, düz bir dosya yapısına sahiptir. Her bir `.c` ve `.cpp` dosyası bağımsız bir algoritma veya örneği temsil eder:

```text
C-Examples/
├── .gitattributes                # Git yapılandırma dosyası
├── 1 ile 100 arası 10 sayının en büyüğü.c
├── 1 ile 100 arası sayıların toplamı.c
├── 1 ile 1000 arasındaki asal sayıların toplamı.c
├── 10 Elemanlı bir diziyi sıralama.c
├── 10 Elemanlı dinamik dizinin içerisindeki en buyuk elemanın bulunması.c
├── 10 Elemanlı dizinin en büyük ve en küçük sayılarını bulan program.c
├── 2 kökü olan denklemin köklerini hesaplayan program.c
├── 3 sayıyı küçükten büyüğe sıralama.cpp
├── Altın oran hesaplama.cpp
├── Asal çarpan bulma.cpp
├── Basamak sayısı bulma.cpp
├── Basit dizi örneği.c
├── Basit eczane uygulaması.cpp
├── En büyük iki sayıyı bulma uygulaması.c
├── En büyük sayi bulma.cpp
├── En büyük ve en küçük sayı bulma algoritması.c
├── Faiz hesaplama.cpp
├── Faktoriyel hesaplama.cpp
├── Faktoriyel.c
├── Fibonacci örneği.c
├── Girilen 3 sayının sıralanması.c
├── Gün bulma uygulaması.c
├── Harf sayısı hesaplama.c
├── Hesap makinasi.c
├── Kardeş sayı olup olmadığını kontrol etme.cpp
├── Kelimedeki karakter sayılarını hesaplama.cpp
├── Matematiksel işlem hesaplama uygulaması.c
├── Matris köşegen çarpım uygulaması.c
├── Matris uygulaması.c
├── Maximum sayi bulma.cpp
├── Muhtarlık uygulaması.cpp
├── Mükemmel sayı.c
├── N tane sayinin teklerini ve ciftlerini toplayan program.c
├── Ortalama hesaplama.cpp
├── Sayı tablosu oluşturma.cpp
├── Sayının asal olup olmadığını kontrol etme.cpp
├── Sayının bölenlerini bulma.cpp
├── Sayının tek mi çift mi olduğunu anlama.cpp
├── Sayıyla tersten piramit.cpp
├── Sayıyı kelimeye çevirme.c
├── Selecting sort uygulaması.c
├── Sihirli matris olup olmadığını anlama.cpp
├── Yıldızlardan Piramit.cpp
├── Yıldızlardan şekil çizme uygulaması.c
├── Yıldızlarla tersten piramit.cpp
├── Çember alan ve çevre hesaplama.cpp
├── Ödev.cpp
├── Örnek dosyalama.cpp
├── Örnek gets kullanımı.cpp
├── Öğrenci uygulaması.cpp
├── Üçgen hesaplama.c
└── README.md
```

---

## Geliştirme Süreci

### 1. Forklama
Kendi kod örneklerinizi eklemek veya mevcut kodları geliştirmek için depoyu fork'layabilirsiniz.

### 2. Yeni Dal (Branch) Oluşturma
```bash
git checkout -b ozellik/yeni-ornek
```

### 3. Kodları Gönderme (Push)
```bash
git push origin ozellik/yeni-ornek
```

---

## Katkıda Bulunma
1. Bu depoyu **Fork**'layın.
2. Bir **Branch** oluşturun (`git checkout -b feature/YeniOrnek`).
3. Yeni bir `.c` veya `.cpp` dosyası ekleyin ya da mevcut kodları iyileştirin.
4. Değişikliklerinizi **Commit** edin (`git commit -m 'Ekleme: Yeni örnek'`).
5. Kodlarınızı **Push**'layın (`git push origin feature/YeniOrnek`).
6. Bir **Pull Request** açın.

> **Not:** Eklenen her örnek kodun başına konuyu açıklayan kısa bir yorum satırı eklenmesi önerilir.

---

<a name="iletisim"></a>
## İletişim
**Haluk Can Sarıöz** - [GitHub Profilim](https://github.com/halukcansarioz)  
**Proje Linki:** [https://github.com/halukcansarioz/C-Examples](https://github.com/halukcansarioz/C-Examples)

---

## Lisans
Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
