# Zihin Pusulası (deneme sürümü)

İlkokul 1-4. sınıf öğrencileri için dikkat, hafıza ve BİLSEM'e hazırlık uygulaması. Sözel, görsel ve matris bölümleri vardır; uygulama veliler için tasarlanmıştır, çocuk soruları veli gözetiminde çözer.

Bu depo yalnızca deneme sürümünü içerir: her sınıf için 36 test sorusu (her bölümde 12) ve alıştırma soruları. Tam sürümün soruları burada yoktur.

- **Uygulamayı açmak için:** depo sayfasının sağındaki GitHub Pages bağlantısı (iPhone, Android, tablet ve bilgisayarda tarayıcıda çalışır, ana ekrana eklenebilir).
- **Android APK:** Releases → "Zihin Pusulası - deneme sürümü" → `Zihin-Pusulasi.apk`

Geliştirici: Mustafa Erman Akçakmak, Uzman Psikolojik Danışman · ermanak87@hotmail.com · Instagram ve X: @mermanak

## Dosyalar

- `kaynak.zip`: uygulama kodu (`lib/`, `pubspec.yaml`), derleme araçları (`arac/`) ve açılış sayfası (`site/`)
- `paket1.zip`, `paket2.zip`: deneme soruları (`assets/bilsem-sorular.json`), soru görselleri, yazı tipleri, uygulama simgeleri
- `.github/workflows/yayin.yml`: her güncellemede web sürümünü GitHub Pages'e yayınlar ve Android APK'sını derler

`arac/deneme.keystore` yalnızca bu deneme sürümünün APK'sını hep aynı imzayla derlemek içindir. Mağaza sürümü ayrı ve gizli bir anahtarla imzalanacak.
