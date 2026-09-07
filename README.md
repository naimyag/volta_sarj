# Volta Şarj

Elektrikli aracınızın batarya yönetim sistemine (BMS) Bluetooth ile bağlanıp bataryanın
durumunu gerçek zamanlı gösteren mobil uygulama.

**Tanıtım sayfası:** https://naimyag.github.io/volta_sarj/
**Gizlilik politikası:** https://naimyag.github.io/volta_sarj/gizlilik.html

## Neler yapıyor

- **Canlı telemetri** — paket gerilimi, akım, şarj durumu (SoC), kapasite ve sürüş sırasında
  anlık güç göstergesi
- **Öğrenen menzil tahmini** — sabit bir katsayı yerine sizin gerçek sürüş verinizden öğrenilen
  tüketime ve batarya sıcaklığına göre hesaplanır
- **Hücre bazında detay** — her hücrenin gerilimi, aralarındaki fark ve kritik eşik uyarıları
- **Şarj takibi** — duvar şarjını rejeneratif frenlemeden ayırt eder, dolum süresini ve tahmini
  bitiş saatini gösterir
- **Sıcaklık ve arıza durumları** — hücre/MOS sıcaklıkları, BMS'in bildirdiği arızalar önem
  sırasına göre
- **Çevrimdışı görünüm** — araç yakınınızda değilken son bilinen durumu, ne zaman görüldüğü
  bilgisiyle gösterir

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
