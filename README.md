# Overload — Progressive Overload Tracker

🇹🇷 [Türkçe](#-türkçe) · 🇬🇧 [English](#-english)

---

## 🇹🇷 Türkçe

**Overload**, ağırlık antrenmanında *progresif yüklenme* (progressive overload) takibi için yapılmış tek dosyalık bir web uygulamasıdır. Antrenmanlarını günlük kaydeder, haftalık ve aylık hacmini hesaplar, geçen haftaya göre ne kadar artış yapman gerektiğini önerir.

Kurulum, hesap ya da sunucu gerekmez. Tek bir `Overload.html` dosyasıdır; tarayıcıda açman yeterlidir.

### Özellikler

- **Gün / Hafta / Ay görünümü:** Gün sekmesinde o günün antrenmanını girersin. Hafta sekmesi haftalık hacim, toplam set, antrenman günü sayısı ve günlük ortalamayı gösterir. Ay sekmesi aylık özet ve takvim sunar.
- **Hareket ve set kaydı:** Her hareket için set, kilo (kg) ve tekrar girersin. Hacim `kilo × tekrar` olarak hesaplanır.
- **Hazır program şablonları:** Push, Pull, Bacak, Üst Vücut, Alt Vücut, Tüm Vücut, Dinlenme ve Özel. Bir şablon seçip hareketleri tek seferde ekleyebilirsin.
- **Progresif artış önerisi:** Geçen haftanın aynı gün antrenmanına bakarak hedef kilo ve tekrar önerir. Varsayılan kurallar: üst vücut hareketlerinde +2,5 kg, alt vücut hareketlerinde +5 kg (hareket adındaki "squat", "leg", "deadlift" gibi ipuçlarından anlaşılır). Kilo artırılamıyorsa tekrar sayısı +1 artırılır. Bu değerleri uygulama içinden değiştirebilirsin.
- **Geçen haftadan kopyalama:** Tek bir hareketi, bir günü ya da tüm haftayı düz olarak veya artış uygulanmış hâliyle kopyalayabilirsin.
- **Rekor (PR) rozeti:** Her hareket için bugüne kadarki en yüksek kilo 🏆 ile işaretlenir.
- **Aylık hacim hedefi:** Hedefini (varsayılan 5000 kg·tekrar) kendin belirlersin, ilerleme çubuğundan takip edersin.
- **Koyu ve açık tema.**
- **Mobil uyumlu** arayüz ve yazdırma düzeni.

### Nasıl kullanılır?

1. `Overload.html` dosyasını bilgisayarına indir.
2. Dosyaya çift tıklayarak tarayıcında aç.
3. Gün sekmesinden hareket ekleyip setlerini gir.

İstersen GitHub Pages ile internette herkesin açabileceği bir bağlantıya da çevirebilirsin.

### Verilerin nerede tutulur?

Tüm veriler tarayıcının `localStorage` alanında, **yalnızca senin cihazında** saklanır. Hiçbir sunucuya gönderilmez. Bunun sonuçları:

- Farklı bir tarayıcıda ya da cihazda açarsan verilerin görünmez.
- Tarayıcı verilerini (site verileri/çerezler) temizlersen kayıtların silinir.
- Gizli sekmede kalıcı çalışmayabilir.

Uygulamada dışa aktarma ya da yedekleme özelliği yoktur.

### Notlar

- Yazı tipleri (Space Grotesk ve Inter) Google Fonts'tan yüklenir. İnternet yoksa sistem yazı tipine geçer, uygulama yine çalışır.
- Bu uygulama bir antrenör ya da sağlık danışmanı değildir. Artış önerileri basit kurallara dayanır, kendi durumuna göre ayarla.

---

## 🇬🇧 English

**Overload** is a single-file web app for tracking *progressive overload* in strength training. It logs your workouts by day, calculates weekly and monthly volume, and suggests targets for the next week based on what you did the week before.

No installation, account or server needed. It is one `Overload.html` file, so you just open it in a browser.

### Features

- **Day / Week / Month views:** Log the day's workout in the Day tab. The Week tab shows weekly volume, total sets, number of training days and the daily average. The Month tab gives a monthly summary and a calendar.
- **Exercise and set logging:** Enter sets, weight (kg) and reps for each exercise. Volume is calculated as `weight × reps`.
- **Program templates:** Push, Pull, Legs, Upper Body, Lower Body, Full Body, Rest and Custom. Pick a template to add its exercises in one go.
- **Progressive overload suggestions:** Looks at the same day last week and suggests target weight and reps. Default rules: +2.5 kg for upper body lifts, +5 kg for lower body lifts (detected from hints in the exercise name such as "squat", "leg" or "deadlift"). If weight can't be increased, reps go up by 1. You can change these values inside the app.
- **Copy from last week:** Copy a single exercise, a whole day or the entire week, either as-is or with the progression applied.
- **Personal record (PR) badge:** The highest weight you've logged for each exercise is marked with 🏆.
- **Monthly volume goal:** Set your own target (default 5000 kg·reps) and follow progress on a bar.
- **Dark and light themes.**
- **Mobile-friendly** layout and print styles.

### How to use

1. Download `Overload.html` to your computer.
2. Double-click it to open it in your browser.
3. Add exercises in the Day tab and enter your sets.

You can also publish it with GitHub Pages to get a link anyone can open.

### Where is my data stored?

All data is stored in your browser's `localStorage`, **on your device only**. Nothing is sent to a server. This means:

- Your data won't appear if you open the app in a different browser or on another device.
- Clearing browser site data will delete your logs.
- It may not persist in private/incognito windows.

The app has no export or backup feature.

### Notes

- Fonts (Space Grotesk and Inter) load from Google Fonts. Without internet the app falls back to system fonts and still works.
- This app is not a coach or medical advice. The suggestions follow simple rules, so adjust them to your own situation.
