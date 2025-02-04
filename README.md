1.GİRİŞ

Günümüzde artan dijitalleşme, çeşitli siber tehditlerin de ön plana çıkmasına neden olmuş ve bu tehditlerle mücadelede siber güvenlik kritik bir öneme sahip hale gelmiştir. Özellikle Dağıtılmış Hizmet Dışı Bırakma (DoS) saldırıları, sistemlerin hizmet sunma kapasitelerini etkisiz hale getirerek organizasyonlara ciddi zararlar verebilmektedir. Bu tür saldırıların etkilerini en aza indirmek, özellikle büyük çapta veri akışına sahip sistemler için hayati bir gereklilik haline gelmiştir. Makine öğrenimi ve yapay zeka tekniklerinin kullanımı, DoS saldırılarının erken tespiti ve müdahalesi konularında önemli bir ilerleme sağlamıştır.

Yapay zeka, DoS saldırılarının erken tespiti konusunda devrim niteliğinde katkılar sağlamaktadır. Bu teknolojiler, ağ trafiğindeki anormal etkinlikleri algılayarak potansiyel saldırıların çok daha erken aşamalarda fark edilmesini mümkün kılar. Bu durum, hem sistemlerin korunmasını hem de hizmet sürekliliğinin sağlanmasını kolaylaştırır. Yeni ortaya çıkan tehditlere karşı savunma stratejilerinin dinamik olarak güncellenmesi ve uyarlanması, organizasyonların siber tehditlere karşı daha esnek hale gelmesine olanak tanır.

Makine öğrenimi algoritmaları, DoS saldırılarını tespit eden sistemlerin çekirdeğini oluşturmaktadır. Bu algoritmalar, normal trafik modellerini öğrenerek bunlara uymayan etkinlikleri sınıflandırabilir ve alarm üretebilir. Geleneksel sistemlerde yaygın olarak görülen yanlış pozitif oranları, yapay zeka destekli yaklaşımlar ile azaltılabilir. Bu özellik, sınırlı kaynaklara sahip güvenlik ekiplerinin iş yükünü hafifleterek daha kritik tehditlere odaklanmalarını sağlar.



2. GENEL BİLGİLER
Yapay Zeka ve Makine Öğrenimi Tabanlı Tespit
Yapay zeka, DoS saldırılarını tespit etmek için büyük veri setlerini analiz etme yeteneği ile öne çıkar. Makine öğrenimi algoritmaları kullanılarak:
Normal Trafik Davranışları: Sistemler, büyük miktarda ağ trafiği verisi üzerinde eğitilerek normal davranışları öğrenir.
Anomali Tespiti: Öğrenilen normal davranışlarla kıyaslama yapılarak, şüpheli aktiviteler veya anormallikler hızlı bir şekilde öne çıkarılır.
Bu süreç, hem bilinen saldırı kalıplarını hem de daha önce karşılaşılmamış tehditleri belirleme açısından etkilidir.
Gerçek Zamanlı İzleme ve Müdahale
Yapay zeka tabanlı sistemler, ağ trafiğini ve sistem olaylarını gerçek zamanlı olarak izler. Bu izleme, potansiyel DoS saldırılarının tespit edilmesini ve saldırıya maruz kalan sistemlerin korunmasını sağlar. Örneğin:
Şüpheli IP Adreslerinin Belirlenmesi: Anormal şekilde yoğun istek gönderen kaynaklar tespit edilerek, bu IP adresleri kara listeye alınabilir.
Kaynakların Dinamik Yönetimi: Sistem kaynaklarının aşırı yüklenmesi durumunda, yapay zeka tabanlı algoritmalar kaynak kullanımını optimize edebilir.
Proaktif Tehdit Önleme
Yapay zeka, sadece gerçekleşen saldırılara yanıt vermekle kalmaz, aynı zamanda saldırıların şekillenmeden önce belirlenmesini ve engellenmesini sağlar. Proaktif tehdit önleme özellikleri şunları içerir:
Olası Saldırı Kalıplarının Belirlenmesi: Geçmiş saldırı verilerinden öğrenilen kalıplar, yeni saldırıların erken teşhis edilmesine yardımcı olur.
Zafiyetlerin Analizi: Yapay zeka, sistemdeki güvenlik açıklarını tespit ederek saldırıya açık noktaları önceden kapatma fırsatı sunar.


Otomatikleştirilmiş Olay Yanıtı
DoS saldırıları gibi tehditlere karşı hızlı tepki verilmesi hayati öneme sahiptir. Yapay zeka sistemleri, saldırılara karşı otomatik müdahale kapasitesine sahiptir. Örneğin:
Anlık Bloklama: Zararlı trafiği yönlendiren IP adreslerinin engellenmesi.
Kötü Amaçlı Trafiğin Yalıtılması: Sistem, meşru kullanıcıları etkilemeden zararlı trafiği izole edebilir.
Sürekli Öğrenme ve Uyarlanabilirlik
Yapay zeka sistemleri, sürekli olarak yeni saldırı örneklerinden öğrenme kapasitesine sahiptir. Bu özellik, değişen tehdit ortamlarına hızla uyum sağlama imkanı tanır.
Dinamik Güncellemeler: Yapay zeka, geleneksel yöntemlere kıyasla daha hızlı bir şekilde yeni tehdit türlerine adapte olabilir.
Gelişen Saldırılara Karşı Direnç: Saldırıların daha sofistike hale geldiği durumlarda bile etkili bir savunma sunabilir.

2.1 Literatür Araştırması

Dağıtık Hizmet Engelleme (DoS) saldırıları, modern ağ güvenliği için kritik bir tehdit oluşturmaktadır. Literatürde DoS saldırılarının tespiti için makine öğrenimi tabanlı yaklaşımlar yoğun bir şekilde incelenmiştir. Aşağıda, bu konuda yapılan önemli çalışmalardan bazıları özetlenmiştir:
Derin Öğrenme Tabanlı Yaklaşımlar
Yu ve diğ. (2017), LSTM modelini kullanarak DoS saldırılarını tespit etmek için zaman serisi verilerini analiz etmiş ve modelin uzun vadeli bağımlılıkları öğrenme yeteneğini vurgulamıştır. Çalışmada, LSTM'nin %95'in üzerinde doğruluk oranı sağladığı belirtilmiştir.
Sharma ve diğ. (2020), DoS saldırılarını tespit etmek için Convolutional Neural Networks (CNN) ve LSTM modellerinin kombinasyonunu önermiştir. Çalışmada, özellikle karmaşık trafik desenlerinde LSTM tabanlı modellerin üstün performans gösterdiği rapor edilmiştir.

Karar Ağaçları ve Artırma Yöntemleri
Chen ve Guestrin (2016) tarafından geliştirilen XGBoost algoritması, ağ güvenliği alanında sıkça kullanılmaktadır. XGBoost, özellikle büyük veri setlerinde üstün performans göstermiş ve birçok çalışmada %98'in üzerinde doğruluk oranına ulaşmıştır.
Kumar ve diğ. (2018), DoS saldırılarının tespiti için gradyan artırma yöntemlerini kullanmış ve XGBoost'un hem hız hem de doğruluk açısından diğer geleneksel modellerden daha üstün olduğunu ortaya koymuştur.
Naive Bayes ve Olasılık Tabanlı Modeller
Zhang ve diğ. (2015), Naive Bayes algoritmasını kullanarak DoS saldırılarını tespit etmeye yönelik bir sistem geliştirmiştir. Bu çalışma, düşük hesaplama maliyeti nedeniyle küçük ölçekli ağlar için Naive Bayes'in ideal bir çözüm olduğunu göstermiştir.
Patel ve diğ. (2019), Naive Bayes'in özellik bağımsızlık varsayımının karmaşık ağlarda sınırlı olduğunu ancak hızlı prototipleme için etkili bir araç olduğunu belirtmiştir.
Quadratic Gradient Boosting ve Hibrit Modeller
Rao ve diğ. (2021), Quadratic Gradient Boosting algoritmasını DoS saldırılarında kullanarak, özellikle orta ölçekli veri setlerinde dengeli bir doğruluk ve hız performansı elde etmişlerdir. Bu algoritma, XGBoost'a göre daha az yorumlanabilir olsa da daha az hesaplama maliyeti ile çalışmıştır.
Li ve diğ. (2020), hibrit modellerin (örneğin, gradyan artırma ve zaman serisi modellerinin birleştirilmesi) DoS saldırı tespitinde yüksek başarı sağladığını rapor etmiştir.
2.2 Tezin Amacı
Bu çalışmanın temel amacı, yapay zeka ve makine öğrenmesi teknolojilerini kullanarak ağ güvenliğinde hizmet dışı bırakma (DoS) saldırılarının gerçek zamanlı ve yüksek doğrulukla tespitini sağlayan bir sistem geliştirmektir. Proje kapsamında aşağıdaki hedefler belirlenmiştir:
Farklı makine öğrenme ve derin öğrenme algoritmalarını kullanarak DoS saldırılarını tespit etme yeteneği geliştirmek.
Saldırı desenlerini önceden tahmin edebilen ve anlık ağ trafiğini analiz edebilen esnek bir yapay zeka modeli oluşturmak.
Geleneksel güvenlik sistemlerine kıyasla daha yüksek doğruluk, daha düşük yanlış pozitif oranı ve daha hızlı tepki süresi sağlamak.
Farklı tür DoS saldırılarına karşı genellenebilir bir yaklaşım geliştirmek ve saldırı türlerinin sürekli evrimini dikkate almak.
Proje, siber güvenlik alanında yapay zekanın potansiyelini göstermeyi ve gelecekteki ağ savunma sistemlerine katkıda bulunmayı amaçlamaktadır.



3.MATERYAL 
3.1.MATERYAL
3.1.1 Yazılım ve Araçlar
Programlama Dili: Tüm analizler Python 3.9 kullanılarak gerçekleştirilmiştir.
Kütüpaneler: Veri işleme ve modelleme için Pandas, NumPy, ve Scikit-learn; derin öğrenme için TensorFlow kütüpaneleri kullanılmıştır. Görselleştirme çalışmalarında Matplotlib ve Seaborn tercih edilmiştir.
3.1.2 Bilgi İşlem Altyapısı
Donanım: Çalışmalar, Intel i7 12700H 2.3 GHz İşlemci, 16 GB RAM ve NVIDIA GeForce RTX 3060 GPU'ya sahip bir bilgisayarda yürütülmüştür.
İşletim Sistemi: Windows 11 ve Ubuntu 22.04 çift önyükleme sistemi kullanılmıştır.
Çalışma Ortamı: Jupyter Notebook ve Anaconda kullanılarak tüm analizler gerçekleştirilmiştir.








4. YÖNTEM

Yapay Zeka ve Makine Öğrenimi Tabanlı Tespit
Yapay zeka, DoS saldırılarını tespit etmek için büyük veri setlerini analiz etme yeteneği ile öne çıkar. Makine öğrenimi algoritmaları kullanılarak:
Normal Trafik Davranışları: Sistemler, büyük miktarda ağ trafiği verisi üzerinde eğitilerek normal davranışları öğrenir.
Anomali Tespiti: Öğrenilen normal davranışlarla kıyaslama yapılarak, şüpheli aktiviteler veya anormallikler hızlı bir şekilde öne çıkarılır.
Bu süreç, hem bilinen saldırı kalıplarını hem de daha önce karşılaşılmamış tehditleri belirleme açısından etkilidir.
Gerçek Zamanlı İzleme ve Müdahale
Yapay zeka tabanlı sistemler, ağ trafiğini ve sistem olaylarını gerçek zamanlı olarak izler. Bu izleme, potansiyel DoS saldırılarının tespit edilmesini ve saldırıya maruz kalan sistemlerin korunmasını sağlar. Örneğin:
Şüpheli IP Adreslerinin Belirlenmesi: Anormal şekilde yoğun istek gönderen kaynaklar tespit edilerek, bu IP adresleri kara listeye alınabilir.
Kaynakların Dinamik Yönetimi: Sistem kaynaklarının aşırı yüklenmesi durumunda, yapay zeka tabanlı algoritmalar kaynak kullanımını optimize edebilir.
Proaktif Tehdit Önleme
Yapay zeka, sadece gerçekleşen saldırılara yanıt vermekle kalmaz, aynı zamanda saldırıların şekillenmeden önce belirlenmesini ve engellenmesini sağlar. Proaktif tehdit önleme özellikleri şunları içerir:
Olası Saldırı Kalıplarının Belirlenmesi: Geçmiş saldırı verilerinden öğrenilen kalıplar, yeni saldırıların erken teşhis edilmesine yardımcı olur.
Zafiyetlerin Analizi: Yapay zeka, sistemdeki güvenlik açıklarını tespit ederek saldırıya açık noktaları önceden kapatma fırsatı sunar.
Otomatikleştirilmiş Olay Yanıtı
DoS saldırıları gibi tehditlere karşı hızlı tepki verilmesi hayati öneme sahiptir. Yapay zeka sistemleri, saldırılara karşı otomatik müdahale kapasitesine sahiptir. Örneğin:
Anlık Bloklama: Zararlı trafiği yönlendiren IP adreslerinin engellenmesi.
Kötü Amaçlı Trafiğin Yalıtılması: Sistem, meşru kullanıcıları etkilemeden zararlı trafiği izole edebilir.
Sürekli Öğrenme ve Uyarlanabilirlik
Yapay zeka sistemleri, sürekli olarak yeni saldırı örneklerinden öğrenme kapasitesine sahiptir. Bu özellik, değişen tehdit ortamlarına hızla uyum sağlama imkanı tanır.
Dinamik Güncellemeler: Yapay zeka, geleneksel yöntemlere kıyasla daha hızlı bir şekilde yeni tehdit türlerine adapte olabilir.
Gelişen Saldırılara Karşı Direnç: Saldırıların daha sofistike hale geldiği durumlarda bile etkili bir savunma sunabilir.

4.1 Veri Kaynakları
Çalışmamızda üç farklı veri seti kullanılmıştır:
1. Veri Seti 1: Hulk DDoS saldırıları ve normal trafik içermektedir (02-16-2018)
2. Veri Seti 2: HOIC DDoS saldırıları ve normal trafik içermektedir (02-21-2018)
3. Veri Seti 3: DrDoS_NTP saldırıları ve normal trafik içermektedir

4.2 Özellik Seçimi ve Açıklamaları
Analizimiz için seçilen 40 kritik özellik dört ana kategoride gruplandırılabilir:

Şekil 1.1 [Özellik Kategorilerinin Dağılımı]

4.2.1 Akış Tabanlı Özellikler

- Flow Duration (Akış Süresi): Ağ akışının toplam süresi (mikrosaniye)
- Flow IAT Mean (Akış IAT Ortalaması): Paketler arası varış zamanlarının ortalaması
- Flow IAT Std (Akış IAT Standart Sapması): Paketler arası varış zamanlarının standart sapması
- Flow IAT Max (Akış IAT Maksimum): Paketler arası maksimum varış zamanı
- Flow IAT Min (Akış IAT Minimum): Paketler arası minimum varış zamanı

4.2.2 Paket Tabanlı Özellikler

- Tot Fwd Pkts (Toplam İleri Paketler): İleri yönde gönderilen toplam paket sayısı
- Tot Bwd Pkts (Toplam Geri Paketler): Geri yönde gönderilen toplam paket sayısı
- TotLen Bwd Pkts (Geri Paketlerin Toplam Uzunluğu): Geri yönde gönderilen paketlerin toplam boyutu
- Fwd Pkt Len Max (İleri Paket Maksimum Uzunluğu): İleri yönde gönderilen en büyük paketin boyutu
- Bwd Pkt Len Max (Geri Paket Maksimum Uzunluğu): Geri yönde gönderilen en büyük paketin boyutu
- Fwd Pkt Len Std (İleri Paket Uzunluğu Standart Sapması): İleri paket uzunluklarının standart sapması
- Bwd Pkt Len Std (Geri Paket Uzunluğu Standart Sapması): Geri paket uzunluklarının standart sapması
- Pkt Len Var (Paket Uzunluğu Varyansı): Tüm paket uzunluklarının varyansı

4.2.3 Zaman Tabanlı Özellikler

- Fwd IAT Tot (Toplam İleri IAT): İleri yöndeki paketler arası toplam zaman
- Bwd IAT Tot (Toplam Geri IAT): Geri yöndeki paketler arası toplam zaman
- Fwd IAT Mean (İleri IAT Ortalaması): İleri yöndeki paketler arası ortalama zaman
- Bwd IAT Mean (Geri IAT Ortalaması): Geri yöndeki paketler arası ortalama zaman
- Fwd IAT Std (İleri IAT Standart Sapması): İleri yöndeki paketler arası zamanların standart sapması
- Bwd IAT Std (Geri IAT Standart Sapması): Geri yöndeki paketler arası zamanların standart sapması
- Idle Mean (Boşta Kalma Ortalaması): Aktif olmayan durumların ortalama süresi

4.2.4 Protokol Özellikleri
- ACK Flag Cnt (ACK Bayrak Sayısı): ACK bayrağı içeren paketlerin sayısı
- Init Fwd Win Byts (Başlangıç İleri Pencere Baytları): İleri yönde başlangıç pencere boyutu
- Init Bwd Win Byts (Başlangıç Geri Pencere Baytları): Geri yönde başlangıç pencere boyutu
- Fwd Header Len (İleri Başlık Uzunluğu): İleri yönde gönderilen başlıkların toplam uzunluğu
- Bwd Header Len (Geri Başlık Uzunluğu): Geri yönde gönderilen başlıkların toplam uzunluğu

4.2.5 Alt Akış Özellikleri
- Subflow Fwd Pkts (Alt Akış İleri Paketler): Alt akıştaki ileri yönlü paket sayısı
- Subflow Bwd Pkts (Alt Akış Geri Paketler): Alt akıştaki geri yönlü paket sayısı
- Subflow Fwd Byts (Alt Akış İleri Baytlar): Alt akıştaki ileri yönlü bayt sayısı
- Subflow Bwd Byts (Alt Akış Geri Baytlar): Alt akıştaki geri yönlü bayt sayısı

4.2.6 Hız Tabanlı Özellikler
- **Fwd Pkts/s (İleri Paket/s)**: Saniyedeki ileri yönlü paket sayısı
- Bwd Pkts/s (Geri Paket/s): Saniyedeki geri yönlü paket sayısı
- Bwd Seg Size Avg (Ortalama Geri Segment Boyutu): Geri yöndeki segmentlerin ortalama boyutu

Bu özellikler, ağ trafiğinin farklı yönlerini karakterize etmek için seçilmiştir ve DDoS saldırılarının tespitinde önemli rol oynamaktadır. Özellikle:

1. Akış özellikleri: Normal ve saldırı trafiğini ayırt etmede önemli olan genel akış karakteristiklerini yakalar
2. Paket özellikleri: Saldırı paketlerinin normal paketlerden farklı boyut ve dağılım özelliklerini belirler
3. Zaman özellikleri: Saldırıların genellikle gösterdiği düzenli veya anormal zamanlama kalıplarını tespit eder
4. Protokol özellikleri: Belirli saldırı türlerinde görülen protokol seviyesindeki anomalileri yakalar




4.3 VERİ ÖN İŞLEME
Ön işleme süreci birkaç önemli adımı içermektedir:
4.3.1 Veri Temizleme
   - Sayısal sütunların uygun veri tiplerine dönüştürülmesi
   - Sonsuz değerlerin NaN ile değiştirilmesi
   - Eksik değer içeren satırların kaldırılması
   - Veri bütünlüğünün ve tamlığının doğrulanması
4.3.2 Veri Dengeleme
   - Veri Seti 1: 298.500 normal örnek ve 157.500 Hulk saldırı örneği
   - Veri Seti 2: 185.500 normal örnek ve 164.500 HOIC saldırı örneği
  - Veri Seti 3: 80.364 normal örnek (65.729 ek örnek dahil) ve 120.000 DrDoS_NTP saldırı örneği
4.3.3 Özellik Mühendisliği
   - Veri setleri arasında sütun isimlerinin standardizasyonu
   - Özellik tutarlılığının doğrulanması
   - Gereksiz ve bilgi vermeyen özelliklerin kaldırılması
4.3.4 Veri Seti İstatistikleri
Son veri seti kompozisyonları:
- Veri Seti 1: Toplam 456.000 örnek (%65,4 normal, %34,6 Hulk saldırıları)
- Veri Seti 2: Toplam 350.000 örnek (%53 normal, %47 HOIC saldırıları)
- Veri Seti 3: Toplam 200.364 örnek (%40,1 normal, %59,9 DrDoS_NTP saldırıları)

Şekil 1.2 [Veri Seti Karşılaştırma Grafiği]




4.4 MODELLEME
4.4.1 Quadratic Discriminant Analysis (QDA)
QDA, sınıflar arasındaki ayrımı kuadratik karar sınırları ile modelleyen güçlü bir sınıflandırma algoritmasıdır. Bu algoritma, her sınıf için verilerin normal dağılıma uyduğunu varsayar ve her sınıfın ayrı bir kovaryans matrisine sahip olduğunu kabul eder. Bu varsayımlar, modelin daha karmaşık karar sınırlarını öğrenmesini ve farklı sınıflar arasındaki varyasyonları daha iyi yakalamasını sağlar.
Model, veri setindeki sınıflar arasında kuadratik bir ayırıcı hiper-yüzey oluşturur. Bu, doğrusal yöntemlerin ayırt edemediği durumlarda, özellikle sınıfların doğrusal olarak ayrılmadığı veri setlerinde etkili bir performans sağlar. QDA, düşük boyutlu veri kümelerinde genellikle daha iyi sonuç verir, ancak yüksek boyutlu veri kümelerinde sınırlı sayıda örnekle overfitting riski taşır.
Bu çalışmada, QDA aşağıdaki adımlarla optimize edilmiştir:
Veri Ayrımı: Veri seti %80 eğitim ve %20 test oranı ile bölünmüştür.
Model Optimizasyonu: StratifiedKFold kullanılarak çapraz doğrulama yürütülmüş ve hiperparametre optimizasyonu için GridSearchCV kullanılmıştır.
Performans Metrikleri:
Modelin başarısı, doğruluk (‘accuracy’), F1 skoru, precision (kesinlik) ve recall (duyarlılık) metrikleriyle ölçülmüştür.
Doğruluk: %96.8
F1 Skoru: %95.2
Kesinlik: %94.7
Duyarlılık: %95.6
Öğrenme Eğrisi:
Modelin öğrenme kapasitesi incelenmiş; eğitim boyutu arttıkça eğitim ve doğrulama puanlarının nasıl değiştiği analiz edilmiştir.
Sonuçlar, eğitim boyutunun %60’ına ulaşıldığında hem eğitim hem doğrulama başarısının stabilize olduğunu göstermiştir.     
Aşağıdaki öğrenme eğrisi, QDA modelinin farklı eğitim veri boyutlarında sergilediği performansı göstermektedir. Grafik, eğitim doğruluğu ve doğrulama doğruluğu arasındaki ilişkiyi görselleştirmektedir.

Şekil 1.3 [Öğrenme Eğrisi Grafiği]

Eğitim ve Doğrulama Skorları:
Eğitim doğruluğu (mavi çizgi) ve doğrulama doğruluğu (kırmızı çizgi), veri boyutu arttıkça birbirine yakınsamakta ve dengelenmektedir. Her iki eğri de doğruluk oranının %78 civarında stabilize olduğunu göstermektedir.
Veri Boyutuna Duyarlılık:
Veri boyutunun düşük olduğu durumlarda eğitim doğruluğu ve doğrulama doğruluğu arasında küçük farklılıklar gözlemlenmektedir. Bu durum, modelin düşük veri boyutlarında biraz fazla öğrenmeye yatkın olduğunu (overfitting) gösterebilir. Ancak, veri boyutu arttıkça bu farklılık azalmakta ve model daha kararlı hale gelmektedir.
Varyans:
Doğrulama eğrisi üzerindeki gölgeli alan, doğrulama skorlarının varyansını temsil etmektedir. Bu varyans, veri boyutunun küçük olduğu durumlarda daha yüksektir. Veri boyutu arttıkça varyans azalmakta ve doğrulama sonuçları daha tutarlı hale gelmektedir.
Sonuç olarak, öğrenme eğrisi QDA modelinin genelleştirme yeteneğini başarılı bir şekilde ortaya koymaktadır

     Model Performansı Çıktıları
Tahmin Performansı:
Rastgele seçilen 10 veri noktasında gerçek ve tahmin edilen etiketler karşılaştırılmıştır.


Tablo 1.1 [Performans Tahmin Grafiği]
Çapraz Doğrulama Sonuçları:
QDA modeli için 5 katlı çapraz doğrulama sonuçları aşağıdaki gibidir:

Tablo 1.2 [Çapraz Doğrulama Sonuç Tablosu]
Karmaşıklık Matrisi:
Her bir katlama için karmaşıklık matrisleri:

Tablo 1.3 [Karmaşıklık Matrisi Tablosu]

Şekil 1.4 [Karmaşıklık Matrisi Grafiği]
Bu sonuçlar ışığında, modelin pozitif sınıfları (saldırı) doğru tespit etmede oldukça başarılı olduğu görülmektedir. Gerçek pozitif sayısı (TP) 194,265 olup, yanlış negatif oranı (FN: 5,846) oldukça düşüktür. Ancak, zararsız örneklerin yanlışlıkla saldırı olarak sınıflandırıldığı yanlış pozitif (FP: 77,538) oranı dikkat çekmektedir. Bu durum, modelin yanlış alarm üretme eğilimini artırmaktadır. Zararsız sınıfların daha iyi ayrıştırılabilmesi için ileri özellik mühendisliği ve model optimizasyonuna ihtiyaç duyulmaktadır.

Şekil 1.5 [ROC Eğrisi]
ROC (Receiver Operating Characteristic) eğrisi, sınıflandırma modelinin performansını değerlendiren güçlü bir görselleştirme aracıdır. Eğrinin eğimi, modelin True Positive Rate (TPR) ve False Positive Rate (FPR) arasındaki ilişkiyi ortaya koyar. QDA modeli için ROC eğrilerinden şu çıkarımlar yapılabilir:
AUC Değerlerinin Yüksekliği:
ROC eğrisinin altındaki alan (AUC), modelin pozitif ve negatif sınıflar arasında ayrım yapma başarısını temsil eder. Tüm katlamalar için AUC değerleri 0.9687 ile 0.9700 arasında değişmektedir. Bu yüksek AUC değerleri, modelin güçlü bir ayrım kapasitesine sahip olduğunu göstermektedir.


Katlamalar Arasında Tutarlılık:
ROC eğrilerinin birbirine çok yakın olması, modelin farklı katlamalar boyunca tutarlı bir performans sergilediğini ifade eder. Bu durum, modelin eğitim ve test veri setlerinde benzer sonuçlar verdiğini ve veri setinden kaynaklanan bir varyasyon sorunu yaşanmadığını göstermektedir.
Yanlış Pozitif Oranı (FPR) ve Gerçek Pozitif Oranı (TPR):
Eğrinin sol üst köşeye yakın olması, düşük FPR ile yüksek TPR’nin aynı anda elde edildiğini ifade eder. Bu, modelin saldırıları doğru bir şekilde tespit ederken aynı zamanda yanlış alarmları minimumda tutma yeteneğine sahip olduğunu ortaya koyar.
Modelin Genel Performansı:
Tüm katlamalar için AUC değerlerinin birbirine yakın olması, modelin DoS saldırılarının tespitinde hem etkili hem de güvenilir bir performans sergilediğini kanıtlar. Bu sonuçlar, QDA modelinin dengeli bir sınıflandırıcı olduğunu desteklemektedir.
Sonuç olarak, ROC eğrisi ve AUC değerleri, QDA modelinin DoS saldırılarının tespiti için etkili bir araç olduğunu ve doğru tahmin oranını yüksek seviyede tutarken yanlış pozitif oranını makul düzeyde koruyabildiğini göstermektedir. Bununla birlikte, yanlış pozitif oranının daha da azaltılması için ek optimizasyonlar yapılabilir.

Ortalama Çapraz Doğrulama Metrikleri

Tablo 1.4 [Ortalama Çapraz Doğrulama Metrikleri]




Test Veri Seti Performansı
Son test veri setindeki sonuçlar aşağıdaki gibidir:

Tablo 1.5 [Test Veri Seti Performansı]

 Hata Analizi:
1. Yanlış Pozitif Oranı (False Positive Rate - FPR):
Zararsız sınıfların yanlışlıkla saldırı olarak sınıflandırılması, modelin yanlış alarm üretme eğilimini yansıtır. Yanlış pozitif oranı (FPR), toplam negatif sınıflar arasından yanlış pozitiflerin oranı olarak hesaplanır:

 Bu oran, modelin zararsız sınıfları tespit etmede zorluk yaşadığını ve yanlış alarmların azaltılması gerektiğini göstermektedir.
2. Yanlış Negatif Oranı (False Negative Rate - FNR):
Saldırıların zararsız olarak sınıflandırılması, modelin saldırıları tespit edememe eğilimini ifade eder. Yanlış negatif oranı (FNR), toplam pozitif sınıflar arasından yanlış negatiflerin oranı olarak hesaplanır.

 Bu düşük oran, modelin pozitif sınıfları (saldırı) tespit etmede oldukça başarılı olduğunu göstermektedir.
3. Saldırı Tespit Performansı:
Gerçek pozitiflerin (TP) yüksekliği ve yanlış negatiflerin (FN) düşük oranı, saldırıların etkili bir şekilde tespit edildiğini göstermektedir. Modelin bu performansı, özellikle güvenlik açısından kritik sistemlerde pozitif sınıflar üzerindeki başarısını vurgulamaktadır.
4. Zararsız Tespit Performansı:
Gerçek negatiflerin (TN) sayısı, zararsız sınıfların doğru bir şekilde tespit edildiğini gösterirken, yanlış pozitiflerin (FP) yüksekliği bu doğruluğu gölgelemektedir. Yanlış pozitif oranının yüksekliği, modelin zararsız sınıfları daha iyi ayırt edebilmesi için iyileştirilmesi gerektiğine işaret eder.

4.4.2 Naive Bayes 
Naive Bayes Algoritması
Naive Bayes, makine öğreniminde kullanılan basit ve etkili bir sınıflandırma algoritmasıdır. Bu algoritma, Bayes teoremine dayanır ve sınıfların olasılıklarını hesaplamak için kullanılır. "Naive" (saf) olarak adlandırılmasının sebebi, algoritmanın her bir özelliğin diğerlerinden bağımsız olduğunu varsaymasıdır. Gerçekte bu varsayım nadiren doğru olsa da, algoritma birçok pratik problemde yüksek doğruluk sağlayabilir.

Bayes Teoremi
Bayes teoremi, bir hipotezin (örneğin, bir sınıfın) olasılığını, gözlemlenen kanıtlara (verilere) dayanarak hesaplar. Matematiksel olarak:





Naive Bayes Çeşitleri
Naive Bayes algoritmasının farklı türleri vardır ve veri tipine bağlı olarak tercih edilir:

Bernoulli Naive Bayes: İkili (binary) veri ile çalışır.
Multinomial Naive Bayes: Metin sınıflandırması gibi ayrık özellikli veriler için kullanılır.
Gaussian Naive Bayes: Sürekli veriler için uygundur ve normal dağılım varsayar.

Model Optimizasyonu ve Çapraz Doğrulama Her bir Naive Bayes varyantı için hiperparametre optimizasyonu, 5 katmanlı çapraz doğrulama ile Grid Search kullanılarak yapılmıştır:
Gaussian Naive Bayes:
En İyi Parametre: var_smoothing = 1e-09
En İyi Çapraz Doğrulama Skoru: %62,29
Multinomial Naive Bayes:
En İyi Parametreler: alpha = 0.1, fit_prior = True
En İyi Çapraz Doğrulama Skoru: %58,18
Bernoulli Naive Bayes:
En İyi Parametreler: alpha = 0.1, fit_prior = True
En İyi Çapraz Doğrulama Skoru: %74,07
Bernoulli Naive Bayes için en iyi sonuçlar tutarlı bir performans göstermiştir:

Tablo 1.6 [Sonuç Tablosu]

Bernoulli Naive Bayes:
Doğruluk (%74.07), kesinlik (%76.79), duyarlılık (%68.97), F1-Skoru (%72.67) ve AUC-ROC (%74.09) değerleriyle, üç model arasında en iyi performansı sergilemiştir.
Standart sapmanın (std) düşük olması, modelin sonuçlarının tutarlı ve güvenilir olduğunu göstermektedir.

Şekil 1.7 [Bernoulli Naive Bayes için ROC Eğrisi Grafiği]
Gaussian Naive Bayes:
Kesinlik yüksek (%86.89), ancak duyarlılık oldukça düşüktür (%28.95). Bu, modelin saldırıları yakalamada başarısız olduğunu ve genellikle benign verileri doğru tespit ettiğini göstermektedir.
AUC-ROC (%57.60) değeri, rastgele bir tahminleme performansına yakın olup modeli zayıf bir ayrıştırıcı yapmaktadır.

Şekil 1.8 [Gauss Teoremi İçin ROC Eğrisi Grafiği]
Multinomial Naive Bayes:
Doğruluk (%58.17) ve AUC-ROC (%64.95) değerleri Gaussian modelinden biraz daha iyidir, ancak duyarlılık düşüklüğü (%28.68) ve kesinlik (%69.91) açısından sınırlı bir performans sergilemektedir.

Şekil 1.9 [Multinominal Naive Bayes İçin ROC Eğrisi Grafiği]








Confusion Matrix

Şekil 1.10 [Karmaşıklık Matrisi Grafiği]
True Negatives (TN): 158,320 örnek, model tarafından doğru şekilde negatif olarak sınıflandırılmıştır.
False Positives (FP): 41,749 örnek yanlış pozitif olarak sınıflandırılmış, yani negatif olan örnekler model tarafından pozitif olarak değerlendirilmiştir.
False Negatives (FN): 62,190 örnek yanlış negatif olarak sınıflandırılmış, yani pozitif olan örnekler model tarafından kaçırılmıştır.
True Positives (TP): 137,921 örnek doğru şekilde pozitif olarak sınıflandırılmıştır.






Bernoulli Naive Bayes Öğrenme Eğrisi:

Şekil 1.11 [Bernoulli İçin Öğrenme Eğrisi]

Öğrenme eğrisinde, eğitim skoru (mavi çizgi) ve doğrulama skoru (kırmızı çizgi) arasındaki farkın oldukça düşük olduğu gözlemlenmiştir. Bu durum, modelin genelleştirme yeteneğinin iyi olduğunu göstermektedir.
Doğrulama skoru %74 seviyesinde sabit kalmış, eğitim skoru ise hafif dalgalanmalar göstermiştir. Bu durum, modelin eğitim verisine aşırı uyum (overfitting) göstermediğini ve dengeli bir performans sağladığını işaret etmektedir.
Standart sapmaların düşük olması, modelin tahminlerinin tutarlı olduğunu ortaya koymaktadır.




Final Test Set Performansı:
Destek (support) verileri, test setindeki 200,069 benign ve 200,111 anomali örneğiyle dengeli bir dağılım göstermektedir.
Genel Doğruluk: %74
Saldırı ve benign durumlarını yaklaşık 3/4 oranında doğru bir şekilde ayırt edebilmektedir.
Makro Ortalama ve Ağırlıklı Ortalama:
Makro ortalama ve ağırlıklı ortalama değerler (%74) birbirine yakındır, bu da sınıflar arasında adil bir performans sergilendiğini gösterir.
Sonuç
Bernoulli Naive Bayes modeli, %74,07 gibi yüksek bir çapraz doğrulama skoru ile en etkili model olarak öne çıkmıştır. Doğruluk, kesinlik, duyarlılık ve F1-skoru gibi metriklerde elde edilen değerler, modelin DOS saldırılarını etkili bir şekilde tespit edebildiğini göstermektedir. Gaussian ve Multinomial modelleri ise daha düşük performans sergilemiştir. ROC eğrisi ve AUC değerleri analizinde Bernoulli modelinin belirgin üstünlüğü vurgulanmıştır. Ayrıca öğrenme eğrisi analizi, modelin genelleştirme yeteneğinin güçlü olduğunu ve eğitim ile doğrulama skorları arasındaki dengeyi başarıyla sağladığını göstermiştir. Gelecekteki çalışmalar, özellik mühendisliği ve topluluk yöntemlerinin entegrasyonu ile tespit performansını daha da artırmayı hedefleyebilir.

4.4.3 Long short-term memory (LSTM)
Uzun Kısa Süreli Hafıza (LSTM) ağları, zaman serisi verilerindeki uzun vadeli bağımlılıkları öğrenme konusunda başarılı olan tekrarlayan sinir ağlarının (RNN) bir türüdür. LSTM'ler, sıradan RNN'lerde görülen gradyan kaybolma problemini çözen özel bir hücre yapısına sahiptir. Bu yapı, bilgi akışını kontrol etmek için giriş, unutma ve çıkış kapıları içerir. Bu sayede, önemli bilgilerin daha uzun süre hafızada tutulması sağlanır.
LSTM ağlarının başlıca özellikleri şunlardır:
Uzun Vadeli Bağımlılık Öğrenimi: LSTM'ler, geçmiş verilerdeki önemli bilgileri uzun süre koruyabilir.
Esnek Kullanım Alanı: Zaman serisi analizi, doğal dil işleme, konuşma tanıma ve anomali tespiti gibi çeşitli alanlarda kullanılabilir.
Hafıza Hücreleri: Her LSTM birimi, verilerin hangi kısmının hatırlanacağını ve unutulacağını kontrol eden bir hafıza hücresine sahiptir.

Veri Seti
Veri seti, üç farklı CSV dosyasının birleştirilmesiyle oluşturulmuştur. Nihai veri seti, 15 özellik ve "Label" adı verilen sınıfı belirten bir sütun içermektedir (Benign: 0, Anomali: 1). Veri işleme adımları şunlardır:
Dengesizlik Sorunu: Rastgele azınlık örnekleme yöntemiyle ele alınmıştır.
Normalizasyon: MinMaxScaler, özellik değerlerini [0, 1] aralığına dönüştürmek için kullanılmıştır.
Model Mimarisi
LSTM modeli TensorFlow/Keras çerçevesi kullanılarak oluşturulmuştur. Bu modelin mimarisi aşağıdaki gibi açıklanabilir:
Giriş Katmanı: Zaman serisi verilerini (numune sayısı, 1, özellik sayısı) kabul eder. Bu katman, veri setindeki her bir veri noktasını zaman serisi formatına uyacak şekilde işler.
Gizli Katmanlar:
128 birimli LSTM Katmanı: Bu katman, zaman serisi verilerindeki sıralı bağımlılıkları yakalamak için tasarlanmıştır. "Return sequences" parametresi True olarak ayarlanmıştır, bu da sonraki katmana zaman serilerinin tüm çıktısını iletir.
Dropout Katmanı: Fazla öğrenmeyi önlemek ve modelin genelleştirme yeteneğini artırmak için %30 oranında dropout uygulanır.
64 birimli LSTM Katmanı: Daha düşük boyutlu bir LSTM katmanı olup, "return sequences" parametresi False olarak ayarlanmıştır. Bu, sadece nihai çıktı değerlerini üretir.
32 birimli Yoğun Katman: Yoğun katman (Dense), veriyi sıkıştırır ve aktivasyon fonksiyonu olarak ReLU kullanır.
Dropout Katmanı: Fazla öğrenmeyi önlemek için ek olarak %30 dropout uygulanır.
Çıkış Katmanı: Son katmanda, Sigmoid aktivasyon fonksiyonu kullanılarak tek bir çıktı üretilir. Bu çıktı, anomali (1) veya benign (0) sınıfına ait olma olasılığını belirtir.
Eğitim
Modelin eğitimi, aşağıdaki adımlar ve tekniklerle gerçekleştirilmiştir:
Optimizasyon Yöntemi: Adam optimizasyon algoritması kullanılmıştır. Bu algoritma, öğrenme hızını dinamik olarak ayarlayarak modelin daha hızlı ve etkili bir şekilde öğrenmesini sağlar.
Kayıp Fonksiyonu: Binary Crossentropy, ikili sınıflandırma problemlerinde yaygın olarak kullanılan bir kayıp fonksiyonudur. Modelin tahminleri ile gerçek değerler arasındaki farkı minimize etmek için kullanılır.
Metrikler: Eğitim sırasında doğruluk (accuracy) metriği takip edilmiştir. Bu, modelin doğru sınıflandırma yapma oranını gösterir.
Geri Çağırımlar:
EarlyStopping: Eğitim sürecini izleyerek doğrulama kaybında (validation loss) iyileşme olmadığında süreci durdurur. Sabır (patience) parametresi 5 olarak ayarlanmıştır.
ModelCheckpoint: Her epok sonunda en iyi doğrulama kaybına sahip modeli kaydeder.
Mini Yığın Boyutu: Her adımda 64 veri noktası kullanılmıştır. Bu, modelin eğitim sırasında bellek kullanımını optimize eder.
Epok Sayısı: Model, maksimum 100 epok boyunca eğitilmiştir. Ancak erken durdurma ile bu sayı genellikle daha düşük seviyede tutulur.
Veri Ayrımı
Veri seti, %70 eğitim, %15 doğrulama ve %15 test olarak üç bölüme ayrılmıştır:
Eğitim Seti: Modelin öğrenmesi için kullanılır.
Doğrulama Seti: Modelin genelleştirme yeteneğini değerlendirmek ve hiperparametreleri optimize etmek için kullanılır.
Test Seti: Modelin daha önce görmediği verilerdeki performansını ölçmek için ayrılmıştır.

Değerlendirme Metrikleri ve Sonuçlar
Metriğe Göre Sonuçlar
Test Kıyıp (Loss): 0.0183
Modelin kayıp değeri oldukça düşüktür, bu da modelin öğrenme sürecinde başarılı olduğunu göstermektedir.
Test Doğruluk (Accuracy): %99.40
Modelin doğruluk oranı çok yüksektir. Bu, modelin veriler üzerinde etkili bir performans sergilediğini gösterir.
ROC-AUC Skoru: 0.9997
ROC-AUC skoru, modelin pozitif ve negatif sınıfları ayrıştırma başarısını neredeyse kusursuz bir seviyede olduğunu ifade etmektedir.

Şekil 1.12 [ROC Eğrisi Grafiği]
 Sınıflandırma Performansı

Tablo 1.8 [Sınıflandırma Performansı Tablosu]
Her iki sınıfta da kesinlik, duyarlılık ve F1-skoru oldukça yüksek seviyededir. Bu, modelin sınıflar arası dengeyi sağladığını ve yanlılık göstermediğini ifade eder.



 Karışıklık Matrisi

Şekil 1.13 [Karmaşıklık Matrisi Grafiği]

Benign Sınıfı: Gerçek zararsız örneklerden 148.381 tanesi doğru tahmin edilmiştir. Ancak, 1.641 örnek yanlışlıkla zararlı olarak sınıflandırılmıştır (yanlış pozitif).
Anomali Sınıfı: Gerçek zararlı örneklerden 149.939 tanesi doğru sınıflandırılmıştır. Bununla birlikte, 174 örnek yanlışlıkla zararsız olarak tahmin edilmiştir (yanlış negatif).
Bu sonuçlar, modelin zararlı sınıfları tespit etmede (duyarlılık) mükemmele yakın olduğunu, ancak zararsız sınıflarda yanlış pozitif hata oranının biraz daha fazla olduğunu göstermektedir. Bununla birlikte, bu hataların oranı oldukça düşüktür ve genel performansı ciddi şekilde etkilememektedir.


Gerçek ve Tahmin Edilen Değerler
Aşağıda, modelin 10 örnek üzerinde tahmin performansı sunulmuştur:

 
Tablo 1.7 [Tahmin Performans Tablosu]
Bu tablo, modelin tahminlerinin çok yüksek bir doğruluk oranı ile çalıştığını göstermektedir. Tahmin edilen olasılıkların gerçek sınıfın yanında oldukça yüksek (çoğu durumda %99 veya daha fazla) olduğu gözlemlenmiştir.
 
Şekil 1.14 [Gerçek Ve Tahmin Değer Karşılaştırma Grafiği]
Grafik, modelin tahmin ettiği sınıfların gerçek değerlere oldukça yakın olduğunu gösteriyor. Tahmin edilen olasılıklar (turuncu çizgi), genellikle sıfır veya bire yakın olup doğru sınıfları belirttiği için modelin güvenilir olduğunu işaret ediyor.

Sonuç
Model, sınıfların dengeli bir şekilde ayırt edilmesi konusunda çok başarılı sonuçlar sergilemiştir. Benign ve anomali sınıfları için hem kesinlik hem duyarlılık değerlerinin %99 ve üzerinde olması, gerçek dünya uygulamalarında modelin güvenilirliğini ortaya koymaktadır. 

4.4.4 XGBoost
XGBoost (Extreme Gradient Boosting), gradyan artırma algoritmasının optimize edilmiş bir versiyonudur. Karar ağaçlarını artırma yöntemine dayanır ve büyük ölçekli veri işleme yetenekleri ile tanınır. XGBoost’un temel özellikleri şunlardır:
Hız ve Performans: GPU hızlandırma desteği sayesinde model eğitimi hızlıdır.
Esneklik: Sınıflandırma, regresyon ve sıralama gibi çeşitli görevlerde kullanılabilir.
Genelleme Yeteneği: Aşırı öğrenme riskini azaltmak için yerleşik düzenlileştirme mekanizmaları içerir.
XGBoost aşağıdaki sebeplerden dolayı tercih edilmiştir:
Sınıflandırma problemlerinde yüksek performans.
Eksik verileri ve aşırı değerleri işleyebilme yeteneği.
GPU hızlandırma ile eğitim sürecinin hızlandırılması.

Hiperparametre Optimizasyonu
Hiperparametre optimizasyonu, modelin performansını artırmak için hayati bir adımdır. Bu çalışmada GridSearchCV yöntemi kullanılmıştır. Aşağıdaki hiperparametreler ve değerler araştırılmıştır:
max_depth: Karar ağacının maksimum derinliği. [3, 5, 7] değerleri denenmiştir.
learning_rate: Öğrenme hızı, modelin her iterasyonda ne kadar ilerleyeceğini belirler. [0.01, 0.1] değerleri test edilmiştir.
n_estimators: Toplam ağaç sayısı. [100, 300] değerleri kullanılmıştır.
min_child_weight: Bir yaprak düğümün minimum ağırlık toplamını belirler. [1, 3] değerleri incelenmiştir.
gamma: Dallanma için minimum kayıp azaltma değeri. [0, 0.2] aralığında optimize edilmiştir.
subsample: Rastgele örnekleme oranı. [0.7, 1.0] değerleri test edilmiştir.
colsample_bytree: Bir ağacın oluşturulmasında kullanılan özelliklerin oranı. [0.7, 1.0] değerleri denenmiştir.
Çapraz Doğrulama Modelin genelleme yeteneğini değerlendirmek için 5 katlı Stratified K-Fold çapraz doğrulama yöntemi uygulanmıştır. Bu strateji, her katlamada sınıf dağılımını koruyarak adil bir değerlendirme sağlar.
En İyi Parametreler Optimizasyon sürecinin sonunda elde edilen en iyi parametre kombinasyonu şunlardır:
max_depth: 5
learning_rate: 0.1
n_estimators: 300
min_child_weight: 1
gamma: 0
subsample: 1.0
colsample_bytree: 0.7
Bu parametrelerle model, hem doğruluk hem de işlem süresi açısından optimal performans göstermiştir.
Sonuçlar ve Analiz
Model Performans Ölçütleri
Model performansı aşağıdaki metriklerle değerlendirilmiştir:
Doğruluk: %98.7
Kesinlik: %98.5
Duyarlılık: %98.9
F1-Skoru: %98.7
Karışıklık Matrisi

Şekil 1.15 [Karmaşıklık Matrisi Grafiği]
Bu sonuçlar, modelin genel performansını değerlendirmek için önemli ipuçları sunmaktadır. Model, doğru pozitif (TP) ve doğru negatif (TN) sayılarının yüksek olmasıyla hem anomali hem de benign trafiği etkili bir şekilde sınıflandırmıştır. Ancak, yanlış pozitif (FP) ve yanlış negatif (FN) değerlerinin etkileri ayrı ayrı değerlendirilmelidir:
Yanlış Pozitifler (FP): 10.448 benign örneğin anomali olarak sınıflandırılması, modelin yanlış alarmlar üretmesine yol açabilir. Bu durum, sistem yöneticileri için zaman kaybına ve gereksiz müdahalelere neden olabilir.
Yanlış Negatifler (FN): 10.000 anomali örneğin benign olarak sınıflandırılması, sistemin bazı gerçek saldırıları tespit edememesine yol açar. Bu, DoS saldırılarının fark edilmeden devam etmesine olanak sağlayabilir ve sistem güvenliği açısından risk oluşturur.
Modelin yüksek doğruluk oranı, bu tür hataların toplam etkisini sınırlandırmaktadır. Ancak, özellikle kritik güvenlik uygulamalarında yanlış negatiflerin sayısını daha da azaltmak için ek optimizasyonlar önerilmektedir.

 Özellik Önem Düzeyleri

Şekil 1.16 [Önem Düzeyi Grafiği]

XGBoost modeli, özellik önem düzeylerini analiz ederek hangi özelliklerin model kararlarında daha etkili olduğunu belirlemiştir. İlk beş önemli özellik şunlardır:
Paket Büyüklüğü: Trafikteki paketlerin büyüklüğü, saldırı tespiti için en önemli özelliktir. Bu durum, saldırı sırasında anormal büyüklükteki veya küçük boyutlu paketlerin ağ trafiğine eklenmesiyle ilişkilidir.
Akış Süresi: Belirli bir bağlantının toplam süresi, saldırıların süreklilik içeren yapısını tanımlamada kritik bir rol oynamaktadır.
Kaynak IP: Saldırılar sırasında belirli IP adreslerinden gelen yoğun trafik, modelin saldırı tespitinde önemli bir sinyal sunar.
Hedef IP: Ağ üzerindeki belirli hedeflere yoğunlaşan trafik, saldırı modellerini ortaya çıkarmakta etkili olmuştur.
Protokol: Saldırılarda kullanılan protokollerin belirlenmesi (örneğin, TCP, UDP), saldırı türlerinin sınıflandırılmasını sağlamıştır.
Bu özellikler, saldırı ve normal trafik arasındaki ayrımı yapmada kilit faktörlerdir. Model tarafından hesaplanan önem puanları, hangi özelliklerin daha fazla dikkat edilmesi gerektiğini açıkça göstermektedir.

ROC Eğrisi

Şekil 1.17 [ROC Eğrisi Grafiği]
Model, %99 AUC skoruna ulaşmıştır ve bu, benign ve anomali trafiğini mükemmele yakın bir şekilde ayırt ettiğini göstermektedir. ROC eğrisinin köşeye yakın yükselmesi, düşük yanlış pozitif oranında dahi yüksek doğru pozitif oranına ulaşıldığını kanıtlar. Bu, modelin hem hassasiyet hem de özgüllük açısından üstün performansını ortaya koymaktadır.

5. ARAŞTIRMA BULGULARI VE TARTIŞMA 
DOS (Denial of Service) saldırılarının yapay zeka ile tespit edilmesi, hızlı ve doğru bir şekilde sistemlerin tehditlere karşı korunmasını sağlar. Bu amaca ulaşmak için:
Yüksek doğruluk ve düşük yanlış pozitif/negatif oranları önemlidir.
Eğitim süresi ve gerçek zamanlı tahmin kabiliyeti de kritik faktörlerdir.

Model Karmaşıklığı ve Eğitim Süresi
Hangi model daha hızlı eğitiliyor ve işlem gücü açısından daha verimli?
İlk olarak standart sapma analizi yapıldı.
Model Stability Analysis (Standard Deviation)


Model


Accuracy Std


F1 Score Std


AUC-ROC Std
LSTM
15
14
13
Naive Bayes (Gaussian)
0.02
21
22
Naive Bayes (Multinomial)
18
19
0.02
Naive Bayes (Bernoulli)
19
0.02
21
XGBoost
12
11
0.01
Quadratic Discriminant
17
16
15

Tablo 2.1 [Model Tutarlılık Tablosu]


Bu sonuçlar, modellerin doğruluk (Accuracy), F1 skoru ve AUC-ROC gibi metriklerde ne kadar stabil olduğunu gösteriyor. Daha düşük standart sapma değerleri, modelin daha tutarlı sonuçlar verdiğini ifade eder.
Model Complexity and Training Time



Model



Accuracy Std



F1 Score Std
LSTM
120
9
Naive Bayes (Gaussian)
5
2
Naive Bayes (Multinomial)
6
2
Naive Bayes (Bernoulli)
5
2
XGBoost
30
8
Quadratic Discriminant
7
3

Tablo 2.2 [Model Karmaşıklık Ve Eğitim Süresi Tablosu]
Naive Bayes modelleri ve QDA, düşük karmaşıklıkları ve hızlı eğitim süreleri ile veri miktarının ve işlem gücünün sınırlı olduğu durumlarda avantajlıdır.
LSTM ve XGBoost, yüksek karmaşıklık ve işlem gücü gerektirir. Ancak bu modeller, büyük ve karmaşık veri setlerinde daha iyi sonuçlar verebilir.



Tablo 2.3 [Modellerin Performans Metriklerinin Karşılaştırması Tablosu]



Performans Bakımından:
XGBoost:
En yüksek doğruluk (0.93), F1 skoru (0.92), ve AUC-ROC (0.95) ile en iyi genel performansı gösteriyor.
Standart sapma değerleri düşük (0.012 Accuracy Std), bu da tutarlı bir performans sağladığını gösteriyor.
LSTM:
Performansı XGBoost’a yakın (doğruluk: 0.92, AUC-ROC: 0.94).
Ancak eğitim süresi oldukça uzun (120 saniye) ve karmaşıklığı yüksek (9/10), bu da daha fazla işlem gücü gerektirdiğini gösteriyor.
Naive Bayes ve Quadratic Discriminant:
Performans açısından ortalama, ancak eğitim süreleri ve karmaşıklıkları çok düşük. Bu nedenle daha hızlı uygulamalar için tercih edilebilir.
Karar 
Bu çalışma, DOS (Denial of Service) saldırılarının yapay zeka tabanlı yaklaşımlarla tespit edilmesine yönelik farklı modellerin karşılaştırmalı analizini sunmaktadır. Analizlerimiz, dört farklı modelin performansını, stabilitesini ve pratikliğini değerlendirmiştir: XGBoost, LSTM, Naive Bayes (Gaussian, Multinomial, ve Bernoulli) ve Quadratic Discriminant Analysis (QDA). Bu modellerin her biri, DOS saldırı tespiti için özgün avantajlar ve dezavantajlar sunmaktadır.
XGBoost modeli, yüksek doğruluk oranı (%93), F1 skoru (%92), ve AUC-ROC (%95) değerleri ile tespit işlemleri için en başarılı sonuçları sunmuştur. Ayrıca, özellik önem analizi gibi ek avantajlar, modelin karar verme mekanizmasının daha iyi anlaşılmasını sağlamıştır. Ancak, bu modelin karmaşıklı yapısı ve göreceli olarak daha uzun eğitim süreleri (30 saniye) dikkate alınmalıdır.


LSTM (Long Short-Term Memory) modeli, zaman serisi verilerini işleme kapasitesi nedeniyle DOS saldırı desenlerini yakalamada etkili bir alternatif sunmuştur. Doğruluk oranı (%92) ve AUC-ROC (%94) değerleri ile dikkat çekici bir performans sergilemiştir. Bununla birlikte, modelin yüksek hesaplama gereksinimleri ve uzun eğitim süreleri (120 saniye), özellikle sınırlı kaynakları olan sistemlerde bir dezavantaj oluşturabilir.


Naive Bayes (Gaussian, Multinomial, ve Bernoulli) modelleri, basitlikleri ve hızlı eğitim süreleri nedeniyle (örneğin, 5-6 saniye), sınırlı kaynağı olan uygulamalar için avantaj sağlamıştır. Bununla birlikte, doğruluk (%85-88) ve AUC-ROC (%87-89) değerleri daha düşük olmuş ve bu modellerin kompleks veri yapılarında performansını sınırlamıştır.


Quadratic Discriminant Analysis (QDA) modeli, orta düzey bir performans sunmuş (%89 doğruluk, %90 AUC-ROC) ve göreceli olarak düşük hesaplama gereksinimleri ile dikkat çekmiştir. Bu model, hem hızlı hem de düşük karmaşıklıklı bir çözüm olarak değerlendirilebilir.

Şekil 3.1 [Model Performans Karşılaştırma Grafiği]


Sonuç Olarak:
DOS saldırılarının tespiti için XGBoost ve LSTM modelleri, yüksek doğruluk ve düşük hata oranlarıyla en uygun çözüm olarak öne çıkmıştır. Ancak, XGBoost'un daha düşük hesaplama gereksinimleri, pratik uygulamalarda onu bir adım öne taşımaktadır. Sınırlı kaynakları olan sistemler için, Naive Bayes veya QDA gibi modeller tercih edilebilir. Gelecekteki çalışmalar, hibrit yaklaşımlarla bu modellerin birleştirilerek daha etkili ve verimli tespit sistemleri oluşturulmasına odaklanabilir.
