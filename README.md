# MongoDB Tabanlı Müşteri Yönetim Sistemi

## Proje Hakkında

Bu proje, MongoDB kullanarak geliştirilen basit bir **Müşteri Yönetim Sistemi** uygulamasıdır. Uygulama, kullanıcıların müşteri bilgilerini kolayca ekleyip, silebileceği, güncelleyebileceği ve listeleyebileceği bir ortam sunuyor. Windows Forms üzerinde geliştirilmiş olan bu sistem, MongoDB ile veri yönetimini hem hızlı hem de pratik hale getiriyor. 

Veritabanı tarafında MongoDB kullanarak esnek bir yapı sağladık ve kullanıcıların temel veritabanı işlemlerini rahatça yapmalarını hedefledik.

## Özellikler

- **Müşteri Bilgileri Yönetimi**:
  - Yeni bir müşteri ekleyebilir, mevcut müşterileri silebilir, güncelleyebilir ve listeleyebilirsiniz.
  - Müşteri bilgilerini ID ile arayarak kolayca sorgulayabilirsiniz.

- **Veritabanı Yönetimi**:
  - MongoDB ile verilerin hızlı ve esnek bir şekilde yönetilmesini sağladık. 
  - C# üzerinden MongoDB'ye kolayca bağlanarak veriler üzerinde işlemler yaptık.

- **Kullanıcı Dostu Arayüz**:
  - Windows Forms ile basit ama işlevsel bir kullanıcı arayüzü tasarladık. Kullanıcılar tüm işlemleri birkaç tıklama ile yapabiliyor.

## Kullanılan Teknolojiler

- **MongoDB**: Veritabanı olarak MongoDB kullanıldı.
- **C# & Windows Forms**: Uygulama Windows Forms üzerinde geliştirilmiş olup, C# ile kodlanmıştır.
- **MongoDB C# Driver**: MongoDB ile etkileşime geçmek için C# sürücüsü kullanıldı.

## Teknik Detaylar

1. **MongoDB ve Veri İşlemleri**: 
   - MongoDB, esnek ve ölçeklenebilir yapısıyla veri yönetimi sağladı. C# ile MongoDB arasındaki bağlantıyı `MongoDbConnection.cs` dosyası üzerinden yönettik.
   
2. **CRUD İşlemleri**:
   - Uygulamada temel CRUD (Create, Read, Update, Delete) işlemleri gerçekleştirilmiştir. 
   - Müşteri ID’sine göre veri sorgulama ve listeleme işlemleri de eklenmiştir.

3. **Arayüz Tasarımı**:
   - Windows Forms kullanarak kolay anlaşılır bir arayüz tasarlandı. Tüm işlemler, kullanıcıların rahatça erişebileceği butonlarla yapıldı.

## Neler Öğrendim?

MongoDB ile çalışmak gerçekten heyecan vericiydi. Veritabanı işlemlerinde MongoDB’nin esneklik ve hız sağlama avantajlarını keşfettim. Özellikle, MongoDB ile veri eklemek, silmek, güncellemek ve sorgulamak işlemlerini nasıl daha verimli yapabileceğimi öğrendim. Ayrıca, C# ile MongoDB'ye bağlanmayı ve Windows Forms üzerinde basit bir kullanıcı arayüzü oluşturmayı deneyimledim.



## **Uygulama İle Yapılabilecekler**:
   - **Müşteri Ekleme**: `Add` butonunu kullanarak yeni müşteri bilgilerini ekleyebilirsiniz.
   - **Listeleme**: `List` butonunu kullanarak tüm müşterileri listeleyebilirsiniz.
   - **Müşteri Güncelleme**: Mevcut bir müşteri bilgisini güncellemek için `Update` butonunu kullanabilirsiniz.
   - **Müşteri Silme**: `Delete` butonuyla müşteri bilgilerini silebilirsiniz.
   - **ID ile Arama**: Bir müşteriyi ID’siyle aramak için `Get by ID` butonunu kullanabilirsiniz.

## Arayüz Görseli

![image](https://github.com/user-attachments/assets/9bc012e0-19f6-48a5-bc2b-957d20c77460)


