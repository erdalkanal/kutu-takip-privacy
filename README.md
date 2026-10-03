# Privacy Policy for Stock & Box Tracker (Kutu Takip)

**Effective Date:** October 3, 2026  
**Last Updated:** October 3, 2026  
**Application Name:** Stock & Box Tracker / Kutu Takip  
**Package Name:** `com.kututakip.market`  
**Developer:** Erdal Kanal  

---

## 1. Overview & Core Philosophy

**Stock & Box Tracker** ("the App", "we", "our", or "us") is developed with a strict **Privacy-First** and **Offline-First** architecture. We believe that your workshop, home, and warehouse inventory data belongs solely to you. 

- We do **NOT** require any user account, registration, login, or email address.
- We do **NOT** operate any central cloud database or server that collects, stores, or analyzes your inventory items, photos, or personal records.
- All inventory data, box names, parts, QR codes, and settings remain stored **exclusively on your local device**.

---

## 2. Information We Collect (or Do Not Collect)

### 2.1 Personal Data
The App does **not** collect, store, sell, or transmit any personally identifiable information (PII) such as your name, email address, phone number, physical address, or financial details.

### 2.2 Inventory and Box Data
Any text, numbers, categories, prices, or descriptions you enter regarding your boxes, shelves, components, and tools are stored strictly within the local application sandbox database (SQLite / AsyncStorage) on your mobile device.

### 2.3 Camera and Photos
- **QR Code Scanning:** The App requests access to your device camera solely to allow you to scan QR codes and barcodes attached to your physical storage boxes. Live camera frames are processed in real-time on your device; no video or image feeds are recorded, streamed, or uploaded to any external server.
- **Item Photos:** If you choose to attach photos to your boxes or components, those images are saved locally on your device's internal storage and are never uploaded to any remote server.

---

## 3. Device Permissions and Why We Need Them

The App requests only the minimum permissions necessary to deliver its core features:

| Permission | Android Name | Purpose |
| :--- | :--- | :--- |
| **Camera** | `android.permission.CAMERA` | Used exclusively for scanning box QR codes and capturing optional item pictures locally. |
| **Storage / Media** | `READ_EXTERNAL_STORAGE` / `WRITE_EXTERNAL_STORAGE` | Used strictly when you choose to export your inventory as a local `.json` backup file or import a backup file from your storage. |
| **Notifications** | `android.permission.POST_NOTIFICATIONS` | Used optionally for local reminders or low-stock alerts. No remote push notifications are sent from external servers. |

You can review or revoke these permissions at any time through your device's system settings.

---

## 4. Third-Party Services & Analytics

To support the free version and maintain the application, the App may include Google Play Services and Google AdMob SDK. These third-party services may collect device identifiers and usage telemetry in accordance with their respective privacy policies:

- **Google Play Services:** https://policies.google.com/privacy
- **Google AdMob:** https://support.google.com/admob/answer/6128543

These SDKs handle advertising requests independently. The App does not share your internal inventory data or box contents with Google or advertising partners.

---

## 5. Data Security, Retention, and User Control

- **Complete Data Control:** You own 100% of your data. You can back up your inventory at any time using the built-in JSON export feature, or wipe everything using the database reset function in the App settings.
- **Data Deletion:** Uninstalling the application or clearing the App's storage via your device's Android settings will immediately and permanently delete all your local inventory records and settings.

---

## 6. Children's Privacy

The App is intended for general audiences, makers, hobbyists, and business users. It is not directed at children under the age of 13. We do not knowingly collect any personal information from children under 13.

---

## 7. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last Updated" date. We encourage you to review this policy periodically.

---

## 8. Contact Us

If you have any questions, suggestions, or concerns regarding this Privacy Policy, please contact us:

- **Developer GitHub:** https://github.com/erdalkanal
- **Email:** Contact via Google Play Console developer contact form / email

---
---

# Gizlilik Politikası (Kutu Takip / Stock & Box Tracker)

**Yürürlük Tarihi:** 3 Ekim 2026  
**Son Güncelleme:** 3 Ekim 2026  
**Uygulama Adı:** Kutu Takip / Stock & Box Tracker  
**Paket Adı:** `com.kututakip.market`  
**Geliştirici:** Erdal Kanal  

---

## 1. Genel Bakış ve Temel Gizlilik İlkesi

**Kutu Takip** uygulaması, kullanıcı gizliliğini en üst düzeyde korumak amacıyla **%100 Çevrimdışı (Offline-First)** ve **Gizlilik Odaklı** bir mimari ile geliştirilmiştir. Atölyeniz, deponuz ve çekmecelerinizdeki envanter verilerinin yalnızca size ait olduğuna inanıyoruz.

- Uygulama herhangi bir **üyelik, kayıt, e-posta veya kullanıcı girişi gerektirmez**.
- Kullanıcı verilerini toplayan, saklayan veya işleyen **merkezi bir bulut sunucumuz veya veritabanımız bulunmamaktadır**.
- Girdiğiniz tüm kutu bilgileri, komponentler, adetler, fiyatlar ve ayarlar **yalnızca kendi telefonunuzda/cihazınızda** yerel olarak saklanır.

---

## 2. Toplanan veya Toplanmayan Veriler

### 2.1 Kişisel Veriler
Uygulamamız adınız, soyadınız, telefon numaranız, e-posta adresiniz veya konumunuz gibi hiçbir kişisel kimlik bilgisini (PII) **toplamaz, kaydetmez ve üçüncü şahıslara satmaz**.

### 2.2 Kutu ve Envanter Verileri
Uygulamaya eklediğiniz tüm kutular, raflar, komponentler, açıklamalar ve fiyatlar cihazınızın güvenli yerel depolama alanında (SQLite / AsyncStorage) tutulur. İnternet üzerinden harici hiçbir sunucuya aktarılmaz.

### 2.3 Kamera ve Fotoğraf Erişimi
- **QR Kod Tarama:** Uygulama, fiziksel kutularınızın üzerine yapıştırdığınız QR etiketleri ve barkodları okumak için kamera izni talep eder. Kamera görüntüsü cihazınızda anlık olarak taranır; hiçbir kamera görüntüsü veya video kaydı harici bir yere gönderilmez veya saklanmaz.
- **Fotoğraflar:** Kutulara fotoğraf eklemeyi tercih ederseniz bu fotoğraflar yalnızca cihazınızın kendi hafızasında saklanır.

---

## 3. Uygulama İzinleri ve Kullanım Amaçları

Uygulama yalnızca temel işlevleri yerine getirebilmek için gerekli minimum izinleri ister:

| İzin | İzin Tanımı | Amaç |
| :--- | :--- | :--- |
| **Kamera** | `android.permission.CAMERA` | Yalnızca kutu QR kodlarını okutmak ve isteğe bağlı parça fotoğrafı çekmek için kullanılır. |
| **Depolama** | `READ_EXTERNAL_STORAGE` / `WRITE_EXTERNAL_STORAGE` | Yalnızca envanterinizi `.json` dosyası olarak yedeklemek veya mevcut bir yedeği geri yüklemek istediğinizde kullanılır. |
| **Bildirimler** | `android.permission.POST_NOTIFICATIONS` | Yalnızca yerel kritik stok veya hatırlatıcı bildirimleri için kullanılır. |

İstediğiniz zaman cihazınızın *Ayarlar > Uygulamalar* menüsünden bu izinleri değiştirebilirsiniz.

---

## 4. Üçüncü Taraf Servisler ve Reklamlar

Uygulamanın sürdürülebilirliğini sağlamak adına Google Play Hizmetleri ve Google AdMob kütüphanesi yer alabilir. Bu kütüphaneler Google'ın kendi gizlilik standartlarına uygun olarak reklam sunumu ve teknik kararlılık amacıyla anonim cihaz tanımlayıcıları kullanabilir:

- **Google Play Hizmetleri:** https://policies.google.com/privacy
- **Google AdMob:** https://support.google.com/admob/answer/6128543

Bu servislerin hiçbiri envanter verilerinize veya kutu detaylarınıza erişemez.

---

## 5. Veri Güvenliği ve Silme

- **Tam Veri Hakimiyeti:** Verilerinizin tek sahibi sizsiniz. Dilediğiniz an JSON formatında yedek alabilir veya ayarlar menüsünden tüm veritabanını sıfırlayabilirsiniz.
- **Verilerin Silinmesi:** Uygulamayı telefonunuzdan sildiğinizde veya uygulama verilerini temizlediğinizde, yerel olarak kaydedilmiş tüm envanter verileriniz kalıcı olarak cihazınızdan silinir.

---

## 6. Çocukların Gizliliği

Uygulamamız 13 yaşın altındaki çocuklara yönelik değildir ve çocuklardan bilerek herhangi bir kişisel veri toplanmamaktadır.

---

## 7. İletişim

Bu Gizlilik Politikası ile ilgili herhangi bir sorunuz, öneriniz veya geri bildiriminiz olursa bizimle iletişime geçebilirsiniz:

- **GitHub:** https://github.com/erdalkanal
- **E-posta:** Google Play Console üzerinde kayıtlı geliştirici iletişim e-postanız
