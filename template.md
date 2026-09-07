---
title: ""
series: ""
part: 0
youtube_url: "https://www.youtube.com/watch?v=VIDEO_ID"
duration: "nn:nn:nn"
published_date: "nnnn-nn-nn"
status: ""
verified_by: null
tags: []
---

### Alanların Anlamları

* **`title`**: Videonun YouTube'daki tam veya düzenlenmiş başlığı.
* **`series`**: Videonun bağlı olduğu serinin adı (*Şeytan Üçgeni*, *Taht Oyunları* vb.). Tekil videolar için `null`.
* **`part`**: Serinin kaçıncı bölümü olduğu. Tekil videolarda `null`.
* **`youtube_url`**: Okuyucuların veya doğrulama yapmak isteyenlerin doğrudan ulaşabileceği orijinal link.
* **`duration`**: Videonun toplam süresi (`SS:DD:SN` formatında).
* **`published_date`**: Videonun yayımlandığı tarih (`YYYY-AA-GG` formatında).
* **`status`**: Metnin güvenilirlik ve denetim aşaması:
  * `draft`: Ham veri veya LLM çıktısı alınmış hali.
  * `in-review`: Dinleme ve doğrulama aşamasında.
  * `verified`: Dinlenerek teyit edilmiş, kesinleşmiş metin.
* **`verified_by`**: Metni baştan sona dinleyip onaylayan kişinin GitHub kullanıcı adı. Henüz doğrulanmadıysa `null`.
* **`tags`**: Repo içindeki aramalarda veya filtrelemelerde kullanılan anahtar kelimeler.

...
