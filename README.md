# Minik Dünya — Kamera Atölyesi

Genwi blogu için Türkçe, mobil uyumlu Three.js kamera etkinliği. Geniş / alt / kuş bakışı açı, sabit / fiziksel yaklaşma / yörünge hareketi, FOV ve hız, oynat-duraklat, su döngüsü zaman çizgisi ve çekim promptu.

Statik yayın: `python -m http.server 8765` ardından `http://localhost:8765`. Derleme, API anahtarı veya hesap gerektirmez. Three.js 0.160.1 yerel olarak dahil edilmiştir; MIT lisansı vendor klasöründedir. Film ve görseller kullanıcı tarafından sağlanmıştır. 3D geometri özgün ve basitleştirilmiş eğitim temsilidir.

Genwi alanları: `interactive_url=https://talent14-edu.github.io/mini-dunya-kamera/`, `interactive_title=Minik Dünya: Etkileşimli Kamera Atölyesi`, `interactive_height=800`. Gövdede ayrı bir satıra `[[etkilesim]]` eklenir. Kopyalama izni olmayan sandbox içinde prompt seçimiyle elle kopyalama desteklenir.

10 Kasım 2026: Genwi backend host izni dev ekibi tarafından güncellendi; Türkçe ve İngilizce yazıların iframe alanları API tarafından kabul edildi. Türkçe atölye kök adreste, İngilizce atölye `en.html` adresinde. İngilizce arayüz ve promptlar `../localize_en.py` ile aynı sahne kaynağından üretilir.

Web videosu: 720×1280 H.264/yuv420p, AAC, faststart; kaynak film 1080×1920 H.264/yuv444p idi. Mobil ve tarayıcı uyumluluğu için dönüştürüldü.

İngilizce film `assets/film-en.mp4`: kullanıcının İngilizce seslendirme ve altyazılı kaynağı, 1080×1920 H.264/yuv420p, faststart; çözünürlük korunur.

Gömülü görünüm `compact.css` kullanır: sahne ve temel kontroller iframe yüksekliğine sığar; büyük başlıklar, uzun açıklamalar, hız/FOV sürgüleri ve alt film bağlantısı gösterilmez. Prompt tek satır önizlenir; kopyalama düğmesi tam metni kopyalar. İframe yüksekliği Genwi'de 800 olarak korunur; içerik masaüstü/mobilde gerçek iframe yüksekliğine uyum sağlar.

GitHub Pages: main dalı / kök dizin. Yalnızca bu klasörün içeriğini yayınlayın; admin dosyaları veya oturum bilgileri dahil edilmez.
