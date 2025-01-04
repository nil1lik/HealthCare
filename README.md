![Kayt2025-01-04134019-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/0381ded3-7ffa-4276-bec9-872a12297f5b)

# Laboratuvar Yönetim Sistemi - ABP Framework & Blazor

Bu proje, ABP Framework ile geliştirilmiş bir laboratuvar yönetim sistemi uygulamasıdır. Blazor tabanlı bir arayüze sahiptir ve ABP’nin güçlü modüler yapısını kullanır.

---

## 🚀 Kurulum

Projenizi yerel ortamda çalıştırmak için aşağıdaki adımları izleyin:

### 📋 Gerekli Araçlar
Projenin çalışması için şu araçların yüklü olduğundan emin olun:
- [.NET SDK 7.0 veya üzeri](https://dotnet.microsoft.com/download)
- [Redis](https://redis.io/) (Cache için)

### 🛠️ Adımlar

#### 1. Projeyi Klonlayın
```bash
git clone https://github.com/nil1lik/HealthCare.git
cd Pusula.Training.HealthCare
```

#### 2. Gereksinimleri Yükleyin
**Backend** için gerekli bağımlılıkları yüklemek:
```bash
dotnet restore
```
**Frontend** için gerekli bağımlılıkları yüklemek:
```bash
cd src/Pusula.Training.HealthCare.Blazor
npm install
install-libs
```

#### 3. Veritabanını Güncelleyin
Veritabanını oluşturmak ve güncellemek için migration komutlarını çalıştırın:
```bash
dotnet run --project src/Pusula.Training.HealthCare.DbMigrator
```

#### 4. Redis Çalıştırın
Redis’in çalıştığından emin olun. Redis’i Docker ile çalıştırabilirsiniz:
```bash
docker run -d -p 6379:6379 redis
```

#### 5. Projeyi Çalıştırın
**Backend API**'yi çalıştırmak için:
```bash
dotnet run --project src/Pusula.Training.HealthCare.Tooling.Aspire
```
**Blazor UI**'yi çalıştırmak için:
```bash
dotnet run --project src/Pusula.Training.HealthCare.Blazor
```

#### 6. Uygulamayı Açın
Tarayıcınızda aşağıdaki URL'lere giderek projeyi görüntüleyebilirsiniz:
- **API**: `https://localhost:44301`
- **Blazor UI**: `https://localhost:44302`

---

## 🔧 Kullanılan Teknolojiler

- **ABP Framework**  
- **Blazor**  
- **Syncfusion** bileşenleri  
- **Entity Framework Core**  
- **Redis**  
- **MERNIS Entegrasyonu**  

---

## 🤝 Katkıda Bulunma

Proje hakkında geri bildirim veya katkı sağlamak için bir **Pull Request** gönderebilirsiniz.

---

**Not:** Herhangi bir sorunla karşılaşırsanız lütfen bir **Issue** açın. 😊
