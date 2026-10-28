# In1 — Gizlilik Politikası ve Aydınlatma Metni

Bu klasör, **In1** Android uygulamasının (`com.cctogether.in1`) gizlilik
politikası ve KVKK aydınlatma metnidir. Play mağaza kaydının istediği
gizlilik politikası adresi buraya bakar.

| Dil | Dosya | Yayındaki adres |
|---|---|---|
| Türkçe (asıl) | `index.html` | https://in1destek-star.github.io/in1-gizlilik/ |
| İngilizce (çeviri) | `en/index.html` | https://in1destek-star.github.io/in1-gizlilik/en/ |
| Kullanım Koşulları (asıl) | `kosullar.html` | https://in1destek-star.github.io/in1-gizlilik/kosullar.html |
| Terms of Use (çeviri) | `en/terms.html` | https://in1destek-star.github.io/in1-gizlilik/en/terms.html |

Uyuşmazlıkta **Türkçe metin geçerlidir**; İngilizcesi kolaylık için çeviridir
(antrenör sözleşmesindeki kalıbın aynısı).

Veri sorumlusu: **Ali Emre CİNEMRE** · in1destek@gmail.com

---

## Yayımlama (ilk kurulum)

1. GitHub'da **`in1-gizlilik`** adıyla **herkese açık (public)** bir depo aç.
   Ad değişirse yukarıdaki iki adres ve `AydinlatmaMetni.kt` birlikte değişir.
2. Bu klasörün içeriğini (`index.html`, `en/index.html`, bu README) o deponun
   **köküne** koyup gönder.
3. Depoda **Settings → Pages → Build and deployment**: kaynak *Deploy from a
   branch*, dal `main`, klasör `/ (root)`. Birkaç dakikada yayına girer.
4. Play Console → **Store listing → Privacy policy** alanına Türkçe adresi yaz.
   Hesap silme için ayrıca istenen adres: aynı sayfanın `#hesap-silme` bölümü.

## Bakım

Asıl kaynak uygulama deposundadır: `projectc/gizlilik/`. Buradaki dosyalar o
klasörden kopyalanır — **metin değişince ikisi birlikte değişir**, yoksa
yayındaki sayfa ile uygulamanın gösterdiği metin ayrışır.

Metin değiştiğinde birlikte güncellenecek üç yer:

- `gizlilik/index.html` ve `gizlilik/en/index.html` — üstteki tarih ve sürüm
- `paylasilan/.../ortak/AydinlatmaMetni.kt` — uygulama içi kısa sürüm, `AYDINLATMA_SURUMU`
- Bu depo (yayındaki kopya)

Kullanım Koşulları (28 Ekim 2026'dan beri) ayrı bir metin: `kosullar.html` + `en/terms.html`
birlikte değişir, adresleri `AydinlatmaMetni.kt`'deki `kullanimKosullariAdresi`. Antrenör
Sözleşmesi ve gizlilik politikasıyla çelişmemeli — biri değişince öbürleri okunur.

Hukuki metinlerden biri değişince Arşiv'deki PDF'ler de yenilenir (vault `hukuki_pdf.py`;
yenisi `Arşiv/In1 uygulaması/Sözleşmeler/In1 metinleri/`e, eskisi Çöp Sepeti'ne).

Verilerin kullanımını etkileyen bir değişiklikte rıza yeniden istenir
(politika bölüm 13) — **gerekiyorsa**. 28 Ekim 2026 (Sürüm 4, `AYDINLATMA_SURUMU`
2026-10-28): sürüm arttı ama yeniden rıza dalgası açılmadı, bilinçli — uygulama rızayı
sürümle tutmuyor ve yeni kalemlerin (antrenörle isteğe bağlı paylaşım) her birinin rızası
kendi anahtarı; gerekçe `AydinlatmaMetni.kt`'nin 28 Ekim notunda.

**Her değişiklik üçünü birden gerektirmez** (5 Eylül 2026, Washington bölümü):
o gün yalnız web sayfalarına 7.2 eklendi ve `AYDINLATMA_SURUMU` bilerek
**değiştirilmedi** — uygulama içi kısa metin aynı kaldı, yeni bir işleme
doğmadı, eklenen şey yalnızca Washington sakinlerine yapılan bir açıklama.
Sürümü artırmak (o günkü ölçüyle) rızayı herkese yeniden sordururdu. Ölçü: *bu değişiklik
verinin kullanımını değiştiriyor mu?* Değiştirmiyorsa sayfaların üstündeki
**tarih** ilerler, sürüm ve `AYDINLATMA_SURUMU` yerinde kalır.
