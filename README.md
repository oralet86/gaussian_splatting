# gaussian_splatting
Konu - Telefon Videosundan 3D Gaussian Splatting ile Sahne Yeniden Oluşturma	

Kapsam ve Araştırma Sorusu - Görüntü sayısı, poz hatası ve bulanıklığın yeni görüş sentezi kalitesine etkisi; NeRF ile karşılaştırma.

Öğrenme bileşeni:	En az bir derin öğrenme modeli projenin verisinde eğitilir veya ince ayar yapılır (tam ince ayar, LoRA/adaptör, istem öğrenme ya da gerekçeli sıfırdan eğitim). Hazır modeli yalnızca çalıştırmak (inference) yeterli değildir.
  
Temel yöntemler: En az iki alternatifle karşılaştırma: bir klasik/basit yöntem ve bir hazır modelin ince ayarsız sonucu.

Ablasyon:	En az bir tasarım kararının etkisi en az 3 deney koşuluyla ölçülür (ör. veri artırma, dondurulan katman, LoRA rankı, veri miktarı).

Değerlendirme: Ayrı eğitim/doğrulama/test kümeleri; göreve uygun en az iki metrik; mümkünse 3 tohumla ortalama ± std; veri sızıntısı kontrolü.

Veri: Kaynağı ve lisansı belli veri; bölme yöntemi raporlanır; küçük test kümesi gerekçelendirilir.

Hata analizi: Başarısız örnekler görsel olarak gösterilir ve nedenleri tartışılır.

Tekrarlanabilirlik: GitHub deposu README ile baştan sona çalışır; requirements.txt, sabit tohum (seed), donanım ve eğitim süresi raporlanır.

Kabul edilmeyenler: Kaggle/GitHub not defterinin yeniden çalıştırılması; yalnızca hazır model çıkarımı; ticari API çağrısı; MNIST/CIFAR-10/PlantVillage'da standart CNN; yalnızca klasik OpenCV boru hattı.

Bildiri: IEEE konferans şablonu, iki sütun, kaynaklar dahil en fazla 6 sayfa; Özetçe/Abstract, Giriş, İlgili Çalışmalar, Yöntem, Veri Seti ve Deney Düzeneği, Deneysel Sonuçlar, Tartışma, Sonuç, Kod ve Veri Erişilebilirliği, Yapay Zekâ Beyanı, Kaynaklar (en az 10, IEEE stili).

Hesaplama sınırı	Deneyler Colab/Kaggle ücretsiz GPU'suyla yapılabilecek ölçekte; tek eğitim koşusu 4 saati aşmamalı.
