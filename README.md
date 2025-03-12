🎯 k-Means Kümeleme: Seramik Örneklerinin Kimyasal Bileşimi
Bu proje, k-Means (k-Ortalamalar) kümeleme algoritmasını kullanarak Chemical Composition of Ceramic Samples veri seti üzerinde analiz yapmaktadır. Kullanıcı, k parametresini ayarlayarak farklı kümeleme sonuçlarını inceleyebilir.

📂 Veri Seti
Veri seti, seramik örneklerinin çeşitli kimyasal bileşenlerini içermektedir ve aşağıdaki bağlantıdan erişilebilir:
🔗 Chemical Composition of Ceramic Samples - UCI

🔹 Önemli Not: Modeli oluştururken ilk dört sütun kullanılmayacaktır.

🛠️ Özellikler
✅ k-Means algoritması ile kümeleme
✅ k parametresi kullanıcı tarafından ayarlanabilir
✅ Veri setinin ön işlenmesi (İlk dört sütunun çıkarılması)
✅ Grafiksel görselleştirme (İki boyutlu gösterim)

🚀 Nasıl Kullanılır?
1️⃣ Depoyu klonlayın:

bash
Kopyala
Düzenle
git clone https://github.com/kullaniciadi/kmeans-ceramic.git
cd kmeans-ceramic
2️⃣ Gerekli kütüphaneleri yükleyin:

bash
Kopyala
Düzenle
pip install -r requirements.txt
3️⃣ Programı çalıştırın:

bash
Kopyala
Düzenle
python kmeans.py --k 3  # k değerini değiştirerek test edebilirsiniz
