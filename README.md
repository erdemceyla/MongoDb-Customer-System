Customer Management System (MongoDB & C#)Bu proje, C# ve MongoDB kullanılarak geliştirilmiş, müşteri verilerini NoSQL veritabanı üzerinde esnek ve hızlı bir şekilde yönetmeyi sağlayan bir masaüstü/konsol uygulamasıdır.  🚀 ÖzelliklerMüşteri Ekleme: Yeni müşteri bilgilerini MongoDB koleksiyonuna kaydetme.Müşteri Listeleme & Arama: Kayıtlı müşterileri çekme ve filtreleme.Müşteri Güncelleme: Var olan müşteri verilerini dinamik olarak güncelleme.Müşteri Silme: Belirtilen müşteri kaydını veritabanından kaldırma.NoSQL Entegrasyonu: Esnek veri yapısı ve hızlı CRUD işlemleri.🛠️ Teknolojiler & AraçlarDil: C# (.NET Core / .NET Framework)  Veritabanı: MongoDB  IDE: Visual Studio 2022 / 2025  Kütüphaneler: MongoDB.Driver📁 Proje YapısıPlaintext├── MongoDb/                 # Proje kaynak kodları ve C# dosyaları
│   ├── MongoDb.csproj       # C# Proje yapılandırması
│   └── ...                  # Modeller, Servisler ve UI/Form kodları
├── MongoDb.sln              # Visual Studio Solution dosyası
└── README.md                # Proje dokümantasyonu
⚙️ Kurulum ve ÇalıştırmaRepoyu klonlayın:Bashgit clone https://github.com/kullanici-adiniz/proje-adi.git
MongoDB Bağlantısını Yapılandırın:appsettings.json veya ilgili bağlantı sınıfı içerisindeki MongoDB bağlantı dizesini (ConnectionString) kendi yerel (mongodb://localhost:27017) veya Cloud (MongoDB Atlas) bilgilerinize göre güncelleyin.Bağımlılıkları Yükleyin:Visual Studio üzerinde projeyi açın ve NuGet paketlerinin yüklenmesi için projeyi Build edin:PlaintextNuGet Package Manager -> Restore Packages
Uygulamayı Çalıştırın:
Visual Studio üzerinden F5 tuşuna basarak projeyi başlatın.  
