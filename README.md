# Hastane Acil Servis Yönetim Sistemi

## 📌 Proje Açıklaması
Bu proje, hastane acil servisinde hasta kayıtlarını yönetmek için geliştirilmiş bir C programıdır. Sistem, hastaların öncelik sırasına göre kayıt edilmesini sağlar, her hastaya benzersiz bir reçete numarası atar ve hasta bilgilerini listeleyebilir.

## 📂 İçerik
- **Hasta Ekleme:** Yeni hastalar eklenirken öncelik sırasına göre kayıt edilir.
- **Hasta Listesi Görüntüleme:** Kayıtlı hastalar öncelik sırasına göre listelenir.
- **Reçete Detaylarını Yazdırma:** Tüm hastaların reçete numaraları ile bilgileri görüntülenir.

## 🚀 Kurulum
Bu projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### 1️⃣ Gereksinimler
- GCC derleyicisi
- Linux veya Windows işletim sistemi

### 2️⃣ Derleme ve Çalıştırma
```bash
# Kodu derleme
gcc hospital_er.c -o hospital_er

# Programı çalıştırma
./hospital_er
```

## ⚙️ Kullanım
1. Hasta ekleme işlemi gerçekleştirilir.
2. Hasta bilgileri ekrana yazdırılır.
3. Reçete detayları listelenir.

## 📜 Örnek Çıktı
```
Acil Servis Hasta Listesi:

ID: P001
Ad: Ali Yilmaz
Yas: 45
Cinsiyet: M
Durum: Kalp Krizi
Oncelik: 1
Recete No: 1000

ID: P003
Ad: Mehmet Can
Yas: 65
Cinsiyet: M
Durum: Solunum Yetmezligi
Oncelik: 2
Recete No: 1001
```

