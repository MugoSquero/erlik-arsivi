
# Erlik Belgesel & Video Transkript Arşivi

Bu depoda, [@ERLİK61](https://www.youtube.com/@ERLİK61) YouTube kanalında yayınlanan belgesel ve inceleme videolarının metin tabanlı, yapılandırılmış ve aranabilir transkript arşivini bulabilirsiniz.

Bu çalışmanın temel amacı, videoları metne dökerek hem içerikleri kolayca aranabilir kılmak hem de izlemek yerine okumayı tercih edenler için uygun bir alternatif sunmaktır.

---

### 📌 Transkript Süreci ve Etiketler

Metinler üç aşamada hazırlanır:
1. **Veri Çekme:** Ham altyazılar ve videodaki kaynakça toplanır.
2. **Yeniden İnşa (LLM):** Konuşma metni; noktalama, paragraf yapısı ve konuşmacı ayrımları yapılarak düzenlenir. Anlaşılamayan veya ASR hatası içeren kısımlar `[UNVERIFIED: ...]` olarak işaretlenir.
3. **Manuel Teyit:** Video dinlenerek `[UNVERIFIED]` etiketleri kontrol edilir ve düzeltilir.

Dosya başındaki `status` değerleri şu anlama gelir:
- `draft`: Ham veri veya LLM çıktısı alınmış hali.
- `in-review`: Dinleme ve doğrulama aşamasında.
- `verified`: Dinlenerek teyit edilmiş, kesinleşmiş metin.

---

### 📂 Dizin Yapısı

- `seriler/`: Çok bölümlü çalışmalar (*Şeytan Üçgeni*, *Taht Oyunları* vb.)
- `tekil-videolar/`: Bağımsız belgeseller ve inceleme videoları
- `scripts/`: Altyazı çekme ve temizleme otomasyonları

---

### 🔗 İlgili Bağlantılar ve Harici Kaynaklar

* Resmi Erlik hesapları, topluluk projeleri, yedek arşivler ve harici kaynaklar için [`docs/resources.md`](docs/resources.md) dosyasına bakabilirsiniz.

---

### ⚖️ Telif ve Yasal Uyarı

Bu depo tamamen gayriticari olup eğitim ve arşivleme amaçlı bir topluluk çalışmasıdır. Anlatı, senaryo ve içeriğin tüm hakları [@ERLİK61](https://www.youtube.com/@ERLİK61) kanalına aittir.

Orijinal içerik üreticisini desteklemek için lütfen [resmi YouTube kanalını](https://www.youtube.com/@ERLİK61) ziyaret edin.
