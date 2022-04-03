# BTK-Akademi-Datathon
![foto](https://user-images.githubusercontent.com/63146261/161426084-a86656e8-eee0-44f2-bc0a-56fd8471acf2.jpg)
# Özet
Bu çalışma, **BTK Akademi** tarafından yapılan Datathon yarışması için hazırlanmıştır. Yarışmada istenilenler doğrultusunda **01.01.2016 - 01.01.2020** yılları arasında üretim yeri, besin değeri, fiyatı, kategorisi gibi farklı değişkenleri paylaşılan ürünlerin **01.01.2020 - 01.01.2021 tarihleri arasında fiyat tahminlemesi** yapılmıştır. 

Çalışma süresince, ürün fiyatı değişkeninde etkili olan tüm parametreler veri seti ve ek veri setleri çerçevesinde ele alınmış olup, anlamlılıkları incelenmiştir. Çalışma sonunda elde edilen model sayesinde, belirli parametreleri verilen bir ürünün ilgili tarihlerdeki fiyat tahmini **SMAPE(Symmetric Mean Absolute Percentage Error)** hata metriğinde **train veri seti için 1.07, validasyon veri seti için 1.24 validasyon değeri** elde edilmiştir. Model öncesinde, veri setinin doğru bir şekilde yorumlanabilmesi ve işlenebilmesi için izlenen işlem basamakları sırasıyla şu şekildedir;
 * Exploratory Data Analysis (Keşifçi Veri Analizi)
 * Feature Engineering (Özellik Mühendisliği)
 * Feature Extraction (Değişken Türetme)
 * Korelasyon Analizi
 * Encoding (Kodlama)
 * Model Oluşturma 
 * Tahminleme
 * Tahminleme Başarı Testi
# Veri Seti
https://www.kaggle.com/competitions/datathon2022

Bu veri seti BTK Akademi tarafından sentetik olarak üretilmiştir. Bu sebeple, değişkenler arasında beklenildiği gibi gerçeğe yakın korelasyon bulunmamıştır. Bu durum, kodun ilgili kısımında (EDA) görselleştirilerek açıklanmıştır. 

Toplamda 8 Değişken, 272+ binden fazla gözlemden oluşmakta olup 16.99 MB boyutundadır.

Veri seti üzerindeki değişkenler sırasıyla şöyledir;

**tarih:** Ürünün özelliklerinin belirlendiği tarih

**ürün:** Ürünün ismi

**ürün besin değeri:** Ürünün sahip olduğu besin değeri

**ürün kategorisi:** Ürünün ait olduğu kategori

**ürün fiyatı:** Ürünün fiyatı

**ürün üretim yeri:** Ürünün üretim yeri

**market:** Ürünün satıldığı market

**şehir:** Ürünün satıldığı şehir

