🗣️ Speech to Text (C#)

Bu proje, C# ve System.Speech kütüphanesi kullanılarak geliştirilen bir sesli konuşmayı yazıya dönüştürme (Speech-to-Text) uygulamasıdır.
Uygulama, kullanıcının mikrofon aracılığıyla söylediği kelimeleri tanır ve metin olarak ekrana yazar.

⚙️ Özellikler

🎤 Gerçek zamanlı ses tanıma

📝 Tanınan metnin anlık olarak yazıya dökülmesi

🌍 Türkçe ve İngilizce dil desteği (sistemde yüklü tanıyıcıya bağlı)

💾 Yazıya dökülen metni kaydetme özelliği (isteğe bağlı eklenebilir)

🧩 Kullanılan Teknolojiler

.NET Framework / .NET 6+

C# (Windows Forms veya Console)

System.Speech.Recognition kütüphanesi

🚀 Kurulum ve Çalıştırma

Proje dosyalarını indir veya klonla:

git clone https://github.com/kullaniciAdin/speech-to-text.git


Visual Studio ile projeyi aç.

System.Speech kütüphanesini ekle:

Solution Explorer > References > Add Reference > Assemblies > Framework

System.Speech kutusunu işaretle ve ekle.

Programı çalıştır (F5 tuşu).

⚠️ Sık Karşılaşılan Hatalar

Hata:

System.ArgumentException: Gerekli kimliğe sahip tanıyıcı bulunamadı.
Parametre adı: culture


Çözüm:

Bilgisayarında Türkçe veya İngilizce dil tanıyıcı (speech recognizer) yüklü değil.

Windows Ayarları → Dil ve Bölge → Konuşma Dili kısmından bir dil tanıyıcı yükle.

🧠 Geliştirici Notu

Bu proje, sesli komut sistemleri, asistan uygulamaları veya dikte yazılımları için temel bir yapı sağlar.
Dilersen OpenAI API veya Azure Speech API ile daha gelişmiş bir model entegre edebilirsin.
