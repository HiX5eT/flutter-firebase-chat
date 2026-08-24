# 🚀 Özel Sohbet Uygulaması (Flutter Web)

Sıfırdan geliştirdiğim, anlık mesajlaşma ve medya paylaşım özelliklerine sahip web tabanlı özel sohbet uygulaması. 

## 📌 Özellikler
- **Google ile Giriş:** Güvenli bir şekilde Firebase Authentication üzerinden hızlıca oturum açma.
- **Gerçek Zamanlı Mesajlaşma:** Cloud Firestore altyapısı ile anlık mesaj alışverişi.
- **Medya Paylaşımı:** Galeri üzerinden fotoğraf seçip Base64 formatına çevirerek sohbet içinde paylaşabilme.
- **Yönetici (Admin) Kontrolleri:** Belirlenen admin yetkilisi ile istenmeyen mesajları doğrudan sohbetten sikebilme/silebilme.
- **Responsive Tasarım:** Modern ve şık kullanıcı arayüzü.

## 🛠️ Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak ve kendi Firebase projenize bağlamak için şu adımları izleyin:

1. Bu depoyu klonlayın:
   ```bash
   git clone https://github.com/HiX5eT/flutter-firebase-chat.git
   ```
2. lib/ klasörü altındaki firebase_options.dart dosyasını açın ve kendi Firebase projenize ait anahtarları (BURAYA_..._YAZIN yazan yerlere) girin.

3. Projeyi tarayıcıda çalıştırın:
   ```bash
   flutter run -d chrome
   ````
