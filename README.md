Power BI – Şehirler ve Bölgeler Raporu

Bu repo, Power BI Desktop kullanılarak hazırlanmış örnek raporları içermektedir.

Bu projenin amacı, şehir ve bölge bazındaki nüfus verilerini Power BI veri modeli içinde organize ederek farklı kırılımlarda analiz edebilmek; bu verileri ölçüler (DAX measures) ile toplulaştırmak (SUM) ve harita ile kart görselleriyle etkileşimli hale getirmektir.

Hazırlanan Power BI modeli:

Şehirler ve bölgeler arasında ilişkisel bir veri modeli (relationship) kurar.
Erkek, kadın ve toplam nüfus gibi sayısal alanlar üzerinden toplam (SUM aggregation) hesaplamaları yapar.
Bölge seçimine göre tüm görsellerin dinamik olarak filtrelenmesini sağlar.
Harita görseli üzerinde şehirlerin nüfus büyüklüklerine göre bubble map gösterimi sunar.
Kullanıcıya, veriyi şehir → bölge → ülke düzeyinde farklı hiyerarşik kırılımlarla inceleme imkânı verir.
Tablo, kart, düğme (button) ve harita bileşenleri aracılığıyla interaktif raporlama deneyimi sağlar.

Bu yapı sayesinde Power BI’daki veri modelleme, measure oluşturma, filtre bağlamı (filter context) ve görselleştirme prensiplerinin uygulamalı olarak gösterilmesi hedeflenir.
10102025_kaynak.pbix
Tüm modelleme, ölçüler (measures), ilişkiler ve görselleştirmeler bu dosyanın içinde yer alır.
veri klasörü
Power BI raporuna bağlı olan Excel dosyalarını içerir.
2. Gerekli Program

Bu projeyi açmak ve çalıştırmak için:

Power BI Desktop

İndirme bağlantısı:
https://powerbi.microsoft.com/

3. Rapor Dosyasını Nasıl Açarsın?
Bu GitHub reposunu bilgisayarına indir:
Yeşil Code butonuna → Download ZIP
Ya da Git kullanıyorsan:
git clone https://github.com/<kullanıcı-adın>/PowerBI.git
Klasörde yer alan 10102025_kaynak.pbix dosyasına çift tıkla.
Power BI açıldığında model otomatik olarak yüklenir.
4. Veri Klasörü ile Bağlantıyı Düzenleme

Projeyi farklı bir klasöre taşıdığında Power BI veri yolunu yeniden isteyebilir.

Bu durumda:

Power BI’da:
Home → Transform data → Data source settings
Change Source… butonuna tıkla.
Veri yolu olarak repo içindeki veri klasörünü göster:
veri/1-bolgeler.xlsx
veri/1-sehirler.xlsx
Kaydet → Refresh
5. Veriyi Güncellemek veya Kendi Verinizi Kullanmak
veri klasöründeki Excel dosyalarını aç.
Sütun başlıklarını değiştirmeden verileri güncelle.
Power BI’da Refresh yap.
Görseller ve model otomatik olarak yeni veriyle güncellenir.

Yeni Excel kaynakları eklemek istersen:

Get Data → Excel ile yeni verileri içeri aktarabilirsin.
