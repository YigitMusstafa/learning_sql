# 🎓 SQL Öğren

Tarayıcıda çalışan, kurulum gerektirmeyen interaktif SQL öğrenme uygulaması. Gerçek bir veritabanı üzerinde sorgu yazıp anında sonuç görebilirsin.

## 🚀 Nasıl Kullanılır

`sql_ogren.html` dosyasını tarayıcıda aç — başka bir şey gerekmez.  
İnternet bağlantısı olması yeterli (sql.js CDN'den yükleniyor).

## 📦 İçerik

### İki veritabanı var:

**📚 vt_ders** — Bir üniversitenin öğrenci sistemi  
`fakulteler` → `bolumler` → `ogrenciler` → `notlar` ↔ `dersler`

**🛒 alisveris** — Bir online alışveriş sitesinin satış sistemi  
`kategoriler` → `urunler` ↔ `satis_detay` ↔ `satis` ↔ `musteriler`

### İki mod var:

**📖 Ders Modu** — Konu anlatımı + tıkla-çalıştır örnekler  
DDL, DML, SELECT, WHERE, LIKE, Aggregate fonksiyonlar, GROUP BY, JOIN, Subquery

**🎯 Sınav Modu** — Rastgele soru üretici  
- 3 zorluk seviyesi: 🟢 Kolay / 🟡 Orta / 🔴 Zor  
- 4 yardım seviyesi: Boşluk Doldur → Anahtar Kelimeler → İpucu → Bağımsız  
- Her soruda veritabanından gerçek veri çekilerek sonsuz çeşitlilik  
- Cevabını yaz, "Kontrol Et" — anında doğru/yanlış

## ⚙️ Teknik

- Saf HTML + CSS + JavaScript, sıfır bağımlılık
- [sql.js](https://github.com/sql-js/sql.js) ile tarayıcı içi SQLite
- Veriler uygulama içinde tanımlı, sayfa yenilenince sıfırlanır
- `Ctrl+Enter` ile sorgu çalıştır


