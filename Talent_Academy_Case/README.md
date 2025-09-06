Pusula_Zeynep_Cengiz

Ad Soyad: Zeynep Cengiz
E-posta: zeyneppcengiz14@gmail.com

 Proje Özeti

Bu proje, Fiziksel Tıp ve Rehabilitasyon alanına ait 2235 gözlem ve 13 değişkenden oluşan bir veri seti üzerinde Exploratory Data Analysis (EDA) ve veri ön işleme (data preprocessing) adımlarını içermektedir.

Amaç, hedef değişken olan TedaviSuresi ile ilgili olarak veri setini modellemeye hazır hale getirmektir. Bu süreçte eksik değerler işlenmiş, aykırı değerler incelenmiş, kategorik değişkenler düzenlenmiş ve sayısal değişkenler standartlaştırılmıştır.

Model kurulması bu çalışmanın kapsamı dışında tutulmuştur.

 Veri Seti

Gözlem Sayısı: 2235
Değişken Sayısı: 13

Değişkenler:

HastaNo: Anonim hasta ID

Yas: Hastanın yaşı

Cinsiyet: Kadın/Erkek

KanGrubu: Hastanın kan grubu

Uyruk: Hastanın uyruğu

KronikHastalik: Kronik hastalık bilgisi

Bolum: Tedavi alınan bölüm

Alerji: Alerji bilgisi

Tanilar: Hastalık tanıları

TedaviAdi: Uygulanan tedavi

TedaviSuresi: Tedavi süresi (Hedef değişken)

UygulamaYerleri: Uygulama yapılan bölgeler

UygulamaSuresi: Uygulama süresi

 Yapılan Çalışmalar
1. EDA (Exploratory Data Analysis)

Değişken tipleri incelendi.

Eksik değerler analiz edildi ve yüzdeleri hesaplandı.

Sayısal değişkenler için dağılımlar (histogram, boxplot) görselleştirildi.

Kategorik değişkenler için frekans dağılımları incelendi.

Korelasyon matrisi çıkarıldı ve heatmap ile görselleştirildi.

Aykırı değerler IQR yöntemi ile tespit edildi.

2. Veri Ön İşleme (Preprocessing)

Eksik değerler:

Sayısal değişkenler → ortalama ile dolduruldu.

Kategorik değişkenler → mod (en sık görülen değer) ile dolduruldu.

Aykırı değerler: Analiz edilip işaretlendi.

Kategorik değişkenler: Temizlendi ve gerekli yerlerde encode edildi.

Sayısal değişkenler: StandardScaler ile standartlaştırıldı.

Tanilar kolonunda benzer değerler birleştirilip düzenlendi.


3.Dosya Yapısı
 Pusula_Zeynep_Cengiz
│
├── data                     # Veri setlerin
│   ├── Talent_Academy_Case_DT_2025.xlsx   # Orijinal verilen veri
│   └── temiz_veri.xlsx                     # Senin temizlediğin veri
│
├── notebooks                # Kodların (Jupyter Notebook veya script)
│   └── eda_preprocessing.ipynb             # EDA + preprocessing adımları
│
├── README.md                 # Açıklama dosyası


Kullanım

Gerekli kütüphaneleri yükleyin:
pandas
numpy
matplotlib
seaborn
scikit-learn

Notebook dosyasını çalıştırın:

jupyter notebook notebooks/eda_preprocessing.ipynb



 İletişim
Zeynep Cengiz – zeyneppcengiz14@gmail.com