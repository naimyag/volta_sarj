# Volta Şarj

Elektrikli aracınızın batarya yönetim sistemine (BMS) Bluetooth ile bağlanıp bataryanın
durumunu gerçek zamanlı gösteren mobil uygulama.

**Tanıtım sayfası:** https://naimyag.github.io/volta_sarj/
**Gizlilik politikası:** https://naimyag.github.io/volta_sarj/gizlilik.html

## Neler yapıyor

- **Canlı batarya durumu** — doluluk, gerilim, akım ve kapasite; sürüşte güç göstergesi, şarjda
  dolum bilgisi
- **Şarj takibi ve alarm** — %80/%90/%100 için alarm; ne zaman biteceği şarj akımına göre
  hesaplanır, uygulama kapalıyken de çalar
- **Öğrenen menzil tahmini** — sürüşlerinizden öğrenilen tüketim ve batarya sıcaklığına göre;
  aracın kilometresiyle kalibre edilebilir
- **Hücre bazında detay** — her hücrenin gerilimi, aralarındaki fark, geride kalan hücre uyarısı
- **Sıcaklık ve arıza durumları** — hücre/MOS sıcaklıkları, BMS arızaları önem sırasına göre
- **Rejenerasyon ayrımı** — inişte üretilen enerji duvar şarjından ayırt edilir
- **Sürüş penceresi (Android)** — doluluk, menzil ve akım diğer uygulamaların üstünde
- **Çevrimdışı görünüm** — araç yakında değilken son bilinen durum ve ne zaman görüldüğü
- **Gizlilik** — internete bağlanmaz, internet izni bile yok; veriler telefondan çıkmaz

## Platformlar

| Platform | Minimum sürüm |
|---|---|
| Android | 7.0 (API 24) |
| iOS | 15.0 |

Kotlin Multiplatform ve Compose Multiplatform ile yazıldı; iki platform da aynı iş mantığını
ve arayüzü paylaşıyor.

## Gizlilik

Uygulama **hiçbir veri toplamıyor ve internete hiçbir şey göndermiyor.** Sunucusu yok, hesap
açmanız gerekmiyor, analitik ve reklam içermiyor. Batarya verisi ve sürüş mesafesi yalnızca
telefonunuzda kalıyor; uygulamayı sildiğinizde tamamen siliniyor.

Ayrıntılar için [gizlilik politikası](https://naimyag.github.io/volta_sarj/gizlilik.html).

## Bu depo hakkında

Burası uygulamanın **tanıtım sayfası ve gizlilik politikasını** barındırır. Uygulamanın kaynak
kodu ayrı bir depoda tutuluyor.
