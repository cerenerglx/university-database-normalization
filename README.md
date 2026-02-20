# university-database-normalization,
ENGLISH

Project Overview
This project demonstrates how mixed and repetitive data originally stored in a single Excel table can be decomposed in accordance with Relational Database Management System (RDBMS) principles. To eliminate data complexity, normalization processes were applied, and the dataset was translated into English and standardized.

Processes Applied
Data Translation & Standardization
Raw data originally in Turkish was translated into English to comply with global standards. Consistent naming conventions (PascalCase / Snake_Case) were applied across all entities and attributes.

Data Decomposition
Data stored on a single sheet was logically decomposed into three distinct relational entities:

Students Table: Stores student identity information and academic program details.
Departments Table: Represents faculty structures and academic advisor mappings.
Courses Table: Manages the student–course relationship.

Normalization Goals
The primary objectives were to eliminate data redundancy, minimize data entry anomalies, and transform the dataset into a query-efficient relational architecture.

TURKCE

Proje Özeti
Bu proje, başlangıçta tek bir Excel tablosu içinde yer alan karmaşık ve tekrarlayan verilerin, İlişkisel Veritabanı Yönetim Sistemi (RDBMS) mantığına uygun şekilde nasıl ayrıştırılabileceğini göstermektedir. Veri setindeki karmaşayı ortadan kaldırmak amacıyla normalizasyon süreçleri uygulanmış; veriler standart bir yapı oluşturmak için düzenlenmiş ve isimlendirme kuralları belirlenmiştir.

Uygulanan Süreçler
Veri Çevirisi ve Standartlaştırma
Türkçe olan ham veriler, uluslararası kullanım ve tutarlılık sağlamak amacıyla İngilizceye çevrilmiştir. Tüm tablo ve alan adlarında PascalCase ve Snake_Case isimlendirme kuralları uygulanmıştır.

Veri Ayrıştırma
Tek bir sayfa üzerinde bulunan veriler, mantıksal ilişkilerine göre üç ayrı tabloya ayrıştırılmıştır:

Öğrenciler Tablosu: Öğrenci kimlik bilgileri ve öğrenim programı bilgilerini içerir.
Bölümler Tablosu: Fakülteler ile akademik danışman eşleşmelerini tutar.
Dersler Tablosu: Öğrenci–ders ilişkisini yöneten yapıyı temsil eder.

Normalizasyon Amaçları
Bu çalışmada veri tekrarını (redundancy) önlemek, veri girişinden kaynaklanan hataları azaltmak ve veriyi sorgulanabilir, sürdürülebilir ve ölçeklenebilir bir veritabanı mimarisine dönüştürmek hedeflenmiştir.
