


# PowerBI – Şehirler ve Bölgeler Raporu

Bu repo, **Power BI Desktop** kullanılarak hazırlanmış örnek bir raporları içerecektir.

**Bu projenin amacı** şehir ve bölge bazındaki nüfus verilerini **Power BI veri modeli** içinde organize ederek farklı kırılımlarda analiz edebilmek, bu verileri **ölçüler (DAX measures)** ile toplulaştırmak (SUM), harita ve kart görselleriyle etkileşimli hale getirmektir.

Hazırlanan Power BI modeli:

- Şehirler ve bölgeler arasında **ilişkisel bir veri modeli (relationship)** kurar.
- Erkek, kadın ve toplam nüfus gibi sayısal alanlar üzerinden **toplam (SUM aggregation)** hesaplamaları yapar.
- Bölge seçimine göre tüm görsellerin **dinamik olarak filtrelenmesini** sağlar.
- Harita görseli üzerinde şehirlerin nüfus büyüklüklerine göre **bubble-map** gösterimi sunar.
- Kullanıcıya, veriyi şehir → bölge → ülke düzeyinde farklı **hiyerarşik kırılımlarla** inceleme imkanı verir.
- Tablo, kart, düğme (button) ve harita bileşenleri aracılığıyla **interaktif raporlama deneyimi** sağlar.

Bu yapı sayesinde, Power BI’daki veri modelleme, measure oluşturma, filtre bağlamı (filter context) ve görselleştirme prensiplerini uygulamalı olarak göstermeyi hedefler.

---
- **10102025_kaynak.pbix**  
  Tüm modelleme, ölçüler (measures), ilişkiler ve görselleştirmeler bu dosyanın içinde yer alır.

- **veri klasörü**  
  Power BI raporuna bağlı olan Excel dosyalarını içerir.

---

## 2. Gerekli Program

Bu projeyi açmak ve çalıştırmak için:

- **Power BI Desktop**

İndirme bağlantısı:  
https://powerbi.microsoft.com/

---

## 3. Rapor Dosyasını Nasıl Açarsın?

1. Bu GitHub reposunu bilgisayarına indir:
   - Yeşil **Code** butonuna → **Download ZIP**
   - Ya da Git kullanıyorsan:  
     `git clone https://github.com/<kullanıcı-adın>/PowerBI.git`

2. Klasörde yer alan **10102025_kaynak.pbix** dosyasına çift tıkla.

3. Power BI açıldığında model otomatik yüklenir.

---

## 4. Veri Klasörü ile Bağlantıyı Düzenleme 

Projeyi farklı klasöre taşıdığında Power BI veri yolunu yeniden isteyebilir.

Bu durumda:

1. Power BI’da:
   - **Home → Transform data → Data source settings**
2. **Change Source…** butonuna tıkla.
3. Veri yolu olarak repo içindeki **veri** klasörünü göster:
   - `veri/1-bolgeler.xlsx`
   - `veri/1-sehirler.xlsx`
4. Kaydet → **Refresh**

---

## 5. Veriyi Güncellemek veya Kendi Verinizi Kullanmak

1. `veri` klasöründeki Excel dosyalarını aç.
2. Sütun başlıklarını değiştirmeden verileri güncelle.
3. Power BI’da **Refresh** yap.
4. Görseller ve modeller otomatik olarak yeni veriyle güncellenir.

Yeni Excel kaynakları eklemek istersen:
- **Get data → Excel** ile yeni verileri içeri aktarabilirsin.

---

