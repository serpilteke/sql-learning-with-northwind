# sql-learning-with-northwind
**Northwind ile SQL pratiği**

Merhaba!  
Bu repo, SQL Server üzerinde gerçek bir veritabanı olan **Northwind** ile adım adım SQL sorgularını anlamak ve örneklerle öğrenmek için oluşturulmuştur.  
Gerçek veriye dayalı uygulamalarla, sorguların nasıl çalıştığını pratikle pekiştirmek amaçlanır.

---

## 📚 Neden Northwind?

Northwind, küçük bir ticaret firmasını temsil eden örnek bir veritabanıdır. İçinde:
- Ürünler 🛍️  
- Siparişler 📦  
- Kategoriler 🗂️  
- Müşteriler 👥  
- Çalışanlar 👩‍💼
gibi pek çok gerçek hayat verisi barındırır.  Bu sayede sadece teori değil, uygulamaya dönük düşünmeyi de sağlar.

---

## 🎯 Amaç

- SQL’in temel yapı taşlarını örneklerle öğrenmek  
- Her sorgunun mantığını kavramak  
- Gerçek iş senaryolarına dayalı örnekler ile pratik yapmak
- Her konunun altına kendi notlarımı ekleyerek kişiselleştirmek

---

## 🔧 Kurulum ve Başlama

Projeyi kullanabilmek için Microsoft SQL Server üzerinde **Northwind** veritabanının yüklü olması gerekir.

> Eğer SQL Server Management Studio (SSMS) yüklü değilse [bu bağlantıdan indirebilirsin.](https://learn.microsoft.com/tr-tr/ssms/download-sql-server-management-studio-ssms)

### 📜 Script ile Kurulum

`.bak` dosyası olmadan, doğrudan SQL komutlarıyla Northwind veritabanını kurmak için:

1. Aşağıdaki bağlantıya tıklayarak kurulum scriptini aç:  
   🔗 [instnwnd.sql – Northwind Kurulum Scripti](https://raw.githubusercontent.com/microsoft/sql-server-samples/master/samples/databases/northwind-pubs/instnwnd.sql)

2. Script içeriğini kopyalayarak SSMS’te yeni bir sorgu penceresine yapıştır.

3. Üstte `USE master;` satırı bulunduğundan emin ol (zaten scriptin içinde yer alır).

4. **F5** tuşuna basarak veya **Execute** butonuna tıklayarak scripti çalıştır.

5. Kurulum tamamlandığında, sol menüde `Northwind` adında bir veritabanı oluşacaktır.

> Bu script; tablo yapıları, veriler ve ilişkiler dahil olmak üzere temel Northwind veritabanını oluşturur.

---

## 🗺️ Veritabanı Diyagramı

Northwind veritabanının tablo yapısı ve ilişkilerini incelemek için Microsoft tarafından hazırlanan resmi diyagramı kullanabilirsiniz:

🔗 [Northwind Database Diagram – Microsoft Support](https://support.microsoft.com/en-us/office/northwind-database-diagram-cd422d47-e4e3-4819-8100-cdae6aaa0857)

> Bu şema, tablo ilişkilerini anlamak ve SQL sorgularınızı doğru tablolara yönlendirebilmek için oldukça faydalıdır.

---


## 📩 İletişim

Her türlü görüş, katkı ya da destek için:  
📎 [LinkedIn - Serpil Teke](https://linkedin.com/in/serpilteke)
