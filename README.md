# sstool
Multipurpose Tool to catch cheaters during screenshares.
# 🛡️ Minecraft Advanced SS (ScreenShare) Tool

> Sunucunuzdaki şüpheli oyuncuları profesyonel bir şekilde denetlemenizi ve hile (cheat) kalıntılarını tespit etmenizi sağlayan gelişmiş kontrol aracı.

<p align="center">
  <img src="https://img.shields.io/badge/C%23-.NET%208.0-blue?style=for-the-badge&logo=dotnet" alt=".NET Version">
  <img src="https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge&logo=windows" alt="Platform">
  <img src="https://img.shields.io/github/license/kullaniciadi/proje-adi?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/github/v/release/kullaniciadi/proje-adi?style=for-the-badge" alt="Release">
</p>

---

## 📋 İçindekiler
- [Özellikler](#-özellikler)
- [Nasıl Çalışır?](#-nasıl-çalışır)
- [Kurulum & Kullanım](#-kurulum--kullanım)
- [Ekran Görüntüleri](#-ekran-görüntüleri)
- [Katkıda Bulunma](#-katkıda-bulunma)
- [Yasal Uyarı](#-yasal-uyarı)

---

## ✨ Özellikler

*   🔍 **Prefetch ve Log Analizi:** Son çalıştırılan zararlı yazılımların izlerini ve zaman damgalarını listeler.
*   🗑️ **Çöp Kutusu (Recycle Bin) Taraması:** Oyuncunun silmeye çalıştığı ancak çöp kutusunda kalan şüpheli dosyaları tespit eder.
*   📂 **Son Açılan Dosyalar (Recent Files):** Windows `Recent` ve `JumpLists` kayıtlarını tarayarak yakın zamanda açılan dosya ve klasörleri gösterir.
*   🌐 **Tarayıcı ve İndirme Geçmişi:** Tarayıcılardan indirilen hile dosyalarının izlerini kontrol eder.
*   ⚡ **Hızlı ve Hafif:** Sistemi yormayan optimize edilmiş arayüz ve hızlı tarama motoru.
*   🔒 **Güvenli Raporlama:** Kontrol sonuçlarını yetkililer için düzenli bir formatta sunar.

---

## ⚙️ Nasıl Çalışır?

Araç, hedef bilgisayarda herhangi bir kalıcı arka plan servisi çalıştırmaz. Sadece yetkili eşliğinde çalıştırılarak Windows'un yerel kayıt defteri (`Registry`), `Prefetch`, `ShimCache` ve log dosyalarını okur; bu sayede silinmiş veya gizlenmiş hile kalıntılarını gün yüzüne çıkarır.

---

## 🚀 Kurulum & Kullanım

1. **[Releases](https://github.com/kullaniciadi/proje-adi/releases)** sayfasından en son sürümü indirin.
2. Aracı kontrol edilecek oyuncunun ekran paylaşımı (Discord vb.) açmasıyla birlikte bilgisayarında çalıştırın.
3. Sekmeler arası geçiş yaparak taranmasını istediğiniz alanları inceleyin.

> [!NOTE]
> Bu araç, tam işlevsellik ve sistem günlüklerine erişim için **Yönetici Yetkisi (Run as Administrator)** gerektirir.

---

## 📸 Ekran Görüntüleri

*(Buraya uygulamanızın arayüzünü gösteren görseller ekleyebilirsiniz)*
| Ana Ekran | Prefetch Analizi |
| :---: | :---: |
| ![Ana Ekran](https://via.placeholder.com/400x250?text=Main+UI) | ![Prefetch](https://via.placeholder.com/400x250?text=Prefetch+Scan) |

---

## 🤝 Katkıda Bulunma

Projeye katkıda bulunmak istiyorsanız:
1. Bu repository'yi **Fork** edin.
2. Yeni bir dal (`git checkout -b feature/YeniOzellik`) oluşturun.
3. Değişikliklerinizi commit edin (`git commit -m 'Eklendi: Yeni özellik'`).
4. Dalınızı uzak sunucuya gönderin (`git push origin feature/YeniOzellik`).
5. Bir **Pull Request** açın.

---

## ⚠️ Yasal Uyarı / Disclaimer

Bu yazılım yalnızca Minecraft sunucularındaki yetkililerin **adil oyun ortamını koruması** amacıyla geliştirilmiştir. Hiçbir şekilde kişisel verilerin izinsiz ele geçirilmesi veya kötü niyetli kullanımı amaçlanmaz. Kullanımdan doğabilecek sorumluluk tamamen kullanıcıya aittir.

---

<p align="center">Made with ❤️ for Minecraft Community</p>
