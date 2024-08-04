# Netflix Show Analysis

Bu proje, Netflix içeriklerinin analizi için bir veri bilimi çalışmasıdır. Projede kullanılan veri seti, Netflix'teki film ve dizilerin özelliklerini içermektedir. Analiz, veri temizliği, veri görselleştirme ve çeşitli veri analizi tekniklerini içermektedir.

## Veri Seti

Analizde kullanılan veri seti [Kaggle'dan](https://www.kaggle.com/datasets/shivamb/netflix-shows) alınmıştır. Veri seti, Netflix'teki film ve dizilerin başlıkları, türleri, rating'leri ve yayın yılları gibi bilgileri içermektedir.

## Kütüphaneler

Proje aşağıdaki Python kütüphanelerini kullanmaktadır:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## Veri Analizi

Proje aşağıdaki adımları içermektedir:

1. **Veri Yükleme ve İlk İnceleme**
   - Veri, `netflix_titles.csv` dosyasından yüklenir.
   - İlk beş satır, veri türleri, sütun isimleri ve veri şekli görüntülenir.

2. **Eksik Veri Analizi**
   - Eksik verilerin sayısı belirlenir ve eksik veri ısı haritası görselleştirilir.

3. **Veri Dağılımı Analizi**
   - Türlere göre dağılım bar grafiği
   - Yıllara göre boxplot ve histogram
   - Türlerin ve rating'lerin dağılımı pie chart ve countplot

4. **Eksik Verilerin Temizlenmesi**
   - Eksik veriler temizlenir ve temizlenmiş veri setinin ilk beş satırı görüntülenir.

5. **Türlerin ve Rating'lerin Analizi**
   - Türler ve ratingler için countplot ve pie chart
   - Türlere göre yıllık yayın sayısının görselleştirilmesi

6. **Popüler Türlerin Analizi**
   - En popüler türlerin bar grafiği

## Sonuçlar

Projede elde edilen bulgular, Netflix'teki içeriklerin dağılımı, rating'ler ve yıllık yayın trendleri hakkında bilgiler sunar. Bu analiz, içeriklerin nasıl dağıldığını ve hangi türlerin daha popüler olduğunu anlamak için kullanılabilir.

## Kullanım
  1. Veri setini netflix_titles.csv olarak indirin ve proje dizinine ekleyin.
  2. Python dosyasını çalıştırarak analizleri görüntüleyin.
