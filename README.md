


# PowerBI – Şehirler ve Bölgeler Raporu

Bu repo, **Power BI Desktop** kullanılarak hazırlanmış örnek bir raporları içerecektir , bu raporda kullanılan Excel veri dosyalarını içerir.
Amaç; şehir ve bölge bazında verileri Power BI ile nasıl modele dönüştürebileceğini, görselleştirebileceğini ve yeniden kullanabileceğini göstermektir.

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

## 4. Veri Klasörü ile Bağlantıyı Düzenleme (Gerekirse)

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

