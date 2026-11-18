# Altyazı Çevirmen (Gemini)

Kamerayı ekrandaki İngilizce altyazıya tut → Gemini okur ve Türkçeye çevirir.

## APK'yı almak (Android Studio gerekmez)
1. github.com'da yeni bir repo aç (private olabilir).
2. Bu klasördeki TÜM dosyaları yükle (`.github` klasörü dahil).
3. Repo'da **Actions** sekmesi → "APK Derle" otomatik çalışır (~4-6 dk).
4. Biten çalıştırmaya gir → en altta **AltyaziCevirmen-apk** → indir, zip'i aç, `app-debug.apk`'yı telefona kur.

## Android Studio ile
Klasörü aç → Build > Build APK(s).

## Kullanım
Ayarlar → Gemini API anahtarı (aistudio.google.com/apikey) → Kaydet → Başlat.
Sarı kesikli kutu taranan alandır. Görüntü değişmezse API çağrılmaz.
