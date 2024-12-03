Antalya Turist Memnuniyeti Analizi
Bu proje, Antalya, Belek ve Kemer bölgelerindeki 4 ve 5 yıldızlı otellere yönelik Alman ve Rus turistlerin çevrimiçi yorumlarını analiz ederek, turist memnuniyeti, hizmet algıları ve sadakat eğilimleri hakkında derinlemesine içgörüler sunmayı amaçlamaktadır.

İçindekiler
Hakkında
Veri Seti
Kullanılan Teknikler
Gereksinimler
Kurulum ve Kullanım
Sonuçlar
Ek Materyaller
Katkıda Bulunanlar
Lisans
Hakkında
Bu projede, 2014 ile 8 Mart 2024 tarihleri arasında toplanan toplam 145.518 çevrimiçi yorum analiz edilmiştir. Yorumların %80,6'sı Rusça, %19,4'ü Almanca olarak kaydedilmiştir. Doğal Dil İşleme (NLP) ve konu modelleme teknikleri kullanılarak, turistlerin memnuniyet düzeyleri, hizmet algıları ve sadakat eğilimleri incelenmiştir.

Veri Seti
Veri seti, çeşitli çevrimiçi seyahat platformlarından toplanan Alman ve Rus turistlerin Antalya bölgesindeki otellere yönelik yorumlarından oluşmaktadır. Veri seti, metin yorumları ve puanlamaları içermektedir.

Not: Veri seti, gizlilik politikaları ve veri paylaşım kısıtlamaları nedeniyle bu depoda yer almamaktadır. Veri setine erişim veya örnek veriler için lütfen bizimle iletişime geçin.

Kullanılan Teknikler
Doğal Dil İşleme (NLP): Metin verilerinin işlenmesi ve analiz edilmesi.
Konu Modelleme: Yorumlardaki ana temaları belirlemek için LDA gibi algoritmaların kullanılması.
Duygu Analizi: Yorumların olumlu, olumsuz veya nötr olarak sınıflandırılması.
Çok Dilli Analiz: Rusça ve Almanca yorumların işlenmesi için çok dilli NLP araçlarının kullanılması.
Veri Görselleştirme: Sonuçların grafiksel olarak sunulması.
Gereksinimler
Python 3.8 veya üzeri
Python Kütüphaneleri
pandas
numpy
scikit-learn
nltk
gensim
spaCy
matplotlib
seaborn
SpaCy Dil Modelleri
Almanca: de_core_news_sm
Rusça: ru_core_news_sm
Kurulum ve Kullanım
1. Depoyu Klonlayın (git clone https://github.com/ahmeteke/Tourist-Satisfaction-Antalya.git)
Sonuçlar
Analizler sonucunda:
Belek bölgesinin her iki turist grubunda da en yüksek memnuniyet puanlarına sahip olduğu (Alman turistler için 4,74; Rus turistler için 4,64),
Kemer bölgesinde özellikle Rus turistler arasında memnuniyet düzeylerinin daha düşük olduğu (4,38),
Alman turistlerin sadakat ve tekrar ziyaret niyeti sergilediği, Rus turistlerin ise eğlence, deniz ve spa deneyimlerine daha fazla önem verdiği,
Güler yüzlü personel ve yemek hizmetlerinin her iki grup için de memnuniyeti artıran temel unsurlar olduğu tespit edilmiştir.

Ek Materyaller
Bu depoda, makalemizde yer kısıtlamaları nedeniyle paylaşamadığımız 500'er adet kelime öbeği, frekans ve ortalama puan bilgilerini içeren tam listeyi bulabilirsiniz. Bu liste, analizlerimizde önemli olan ve turistlerin yorumlarında en sık geçen ifadeleri içermektedir.
Örnek:

Katkıda Bulunanlar
Ahmet Büyükeke- Araştırmacı ve Geliştirici
Lisans
Bu proje MIT Lisansı ile lisanslanmıştır - detaylar için LICENSE dosyasına bakınız.
