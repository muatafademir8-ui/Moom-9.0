MOOM 9.0 - HARITA PAKETI

Bu paket MOOM 8.6 kaynaklarindan gelistirilmistir.

MEVCUT ICERIK
- Onceki 12 bolum korunmustur.
- 24 yeni bolum eklendi; toplam 36 bolum:
  VBN 10: Internet Cafe, Terk Hastane, Metro 2, AVM, Askeri Havaalani,
  Terk Okul, Sisli Orman, Gizli Lab, Liman 2, Dev Fabrika.
  Ek 14: Havaalani, Sehir Merkezi, Askeri Us, Otel, Eglence Parki,
  Benzin Istasyonu, Koy, Hapishane, Baraj, Yeraltı Tesisi, Yolcu Gemisi,
  Yeraltı Otoparki, TV Studyosu, Karli Dag Ussu.
- Yeni haritalar mevcut 2D grid / raycasting harita sistemini kullanir.
- Her yeni haritada oyuncu baslangici, dusmanlar ve esya noktalar bulunur.
- Harita secim listesi NLEV uzerinden otomatik olarak 36 bolumu destekler.
- Makefile EBOOT basligini MOOM 9.0 yapar.

ONEMLI SINIRLAMALAR
- Yolcu gemisi su an tek katli bir harita prototipidir. Merdivenle birbirine
  bagli gercek cok katli geometri henuz eklenmemistir.
- Godzilla'nin cam disindan gecmesi, animasyonu, ses ve kamera titremesi
  henuz eklenmemistir.
- Kargo ucagi, CORD, dort ayakli yaratik, Colossus, NPC dostlar ve analog
  horror yayin sistemi bu pakette yeni olarak uygulanmamistir.
- Haritalar isim ve yerlesim olarak eklendi; her biri icin ozel sanat
  varliklari, gorev senaryolari ve benzersiz cevresel olaylar henuz yoktur.

DERLEME / TEST
- main.c ve Makefile dosyalarini PSP SDK projesine koyup PSPSDK ile derleyin.
- Bu ortamda PSP SDK bulunmadigindan EBOOT.PBP derlemesi ve PPSSPP testi
  yapilamadi. Calisma garantisi verilmez.
