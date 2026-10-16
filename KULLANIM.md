# 29 Ekim Gökyüzü Görevi — Kullanım ve Öğretmen Rehberi

**Alt Başlık:** *Cumhuriyet İçin Uç, Bayrakları Topla!*

Bu kılavuz, **29 Ekim Gökyüzü Görevi** oyununun sınıftaki akıllı tahtada veya masaüstü/dizüstü bilgisayarlarda nasıl açılacağını, kontrol yöntemlerini, oyun akışını ve sınıf içi etkinlik önerilerini açıklar.

---

## 1. Oyunu Açma ve Çalıştırma

Proje klasöründe iki farklı kullanım seçeneği sunulmuştur:

1. **Tek Dosya (Akıllı Tahta / USB Bellek İçin Önerilen):**
   - [`29_ekim_gokyuzu_gorevi.html`](file:///Users/aynur/Desktop/u%C3%A7ak/29_ekim_gokyuzu_gorevi.html) dosyasını doğrudan bir USB belleğe kopyalayabilir veya bilgisayara indirebilirsiniz.
   - İnternet bağlantısı, sunucu kurulumu veya ek dosya gerektirmeden **çift tıklayarak** herhangi bir güncel tarayıcıda (Chrome, Edge, Firefox, Safari) `file://` üzerinden doğrudan açılır.
2. **Düzenlenebilir Kaynak Proje:**
   - Geliştirme veya inceleme için [`index.html`](file:///Users/aynur/Desktop/u%C3%A7ak/index.html), [`style.css`](file:///Users/aynur/Desktop/u%C3%A7ak/style.css) ve [`game.js`](file:///Users/aynur/Desktop/u%C3%A7ak/game.js) dosyaları bir arada bulunur. [`index.html`](file:///Users/aynur/Desktop/u%C3%A7ak/index.html) dosyasına çift tıklayarak da oyunu doğrudan başlatabilirsiniz.

---

## 2. Tam Ekran Kullanımı

- Ana menüde veya uçuş sırasında sağ üst bilgi şeridinde bulunan **“⛶ Tam Ekran”** düğmesine dokunarak oyunu akıllı tahtada tam ekran yapabilirsiniz.
- Tam ekrandan çıkmak için aynı düğmeye tekrar dokunabilir veya klavyeden `Esc` tuşuna basabilirsiniz.
- Cihaz veya tarayıcı tam ekran özelliğini desteklemiyorsa oyun hata vermeden pencere içinde 16:9 oranını koruyarak çalışmaya devam eder.

---

## 3. Üç Kontrol Yöntemi (Akıllı Tahta Öncelikli)

Üç kontrol yöntemi de aynı anda aktif olup en son dokunulan veya kullanılan yöntem öncelik alır:

### A. Göreli Kontrol Paneli (Akıllı Tahta İçin Ana Yöntem)
- Ekranın alt bandında yer alan geniş **“Parmağını burada hareket ettir”** alanı, öğrencinin eli uçağı ve yaklaşan engelleri kapatmasın diye özel olarak ayrılmıştır.
- Öğrenci parmağını bu panele koyduğunda uçak parmak noktasına **ışınlanmaz**; parmağın paneldeki kaydırma hareketi kadar uçağın rotası yumuşak ve kararlı biçimde değişir.
- Parmak kaldırıldığında uçak düşmez; son konumunda güvenle uçmaya devam eder.
- Aynı anda ikinci bir parmak panele değerse uçağın kontrolünü kaçırmaz (tek işaretçi kilidi).

### B. Doğrudan Sürükleme (Dokunmatik veya Fare)
- Uçağın üzerine veya yakın çevresine parmakla ya da fareyle dokunup sürükleyerek uçağı doğrudan yönlendirebilirsiniz.
- İlk dokunma ofseti korunur; uçağa dokunulduğunda sıçrama yapmaz. Uçak dışındaki uzak bir noktaya tıklamak uçağı o noktaya ışınlamaz.

### C. Büyük Yön Düğmeleri ve Klavye
- Sağ alt köşedeki büyük yön düğmelerine (**◀ ▲ ▼ ▶**) basılı tutarak uçağı sürekli hareket ettirebilirsiniz.
- Klavyede **Ok Tuşları** (`↑`, `↓`, `←`, `→`) veya **WASD** tuşları ile uçabilirsiniz. Çapraz hareketlerde hız dengelenir.

---

## 4. Zorluk Seçimi

Ana menüde öğrenciye karmaşık ayar tabloları yerine iki anlaşılır seçenek sunulur:

- **🌤️ Rahat Uçuş:** 3–4. sınıf öğrencileri veya oyunu ilk kez deneyimleyenler için uygundur. Yatay akış hızı daha sakin, güvenli uçuş koridorları daha geniştir.
- **🦅 Keşif Uçuşu:** 5–6. sınıf öğrencileri ve daha deneyimli oyuncular için uygundur. Akış biraz daha canlıdır ve rota geçişleri daha dinamik dikkat gerektirir.

Her iki seçenekte de hedef **15 Türk bayrağı simgesi** (150 puan), **3 can** ve **3 sahne** (*1. Sahne: Bayram Sabahı*, *2. Sahne: Rüzgâr Rotası*, *3. Sahne: Kutlama Meydanına Doğru*) aynıdır. Bir tur yaklaşık 2–3 dakika sürer; böylece sınıfta öğrenciler sırayla tahtaya kalkabilir.

---

## 5. Etkileşimli Eğitim Uçuşu

- Oyuna ilk kez başlandığında veya ana menüdeki **“🎯 Eğitim Uçuşu (15 sn)”** düğmesine basıldığında 3 kısa adımlı uygulamalı alıştırma başlar:
  1. Uçağı yukarıdaki parlak hedef halkaya götürme.
  2. Türk bayrağı simgesini toplama.
  3. Koyu rüzgâr bulutu engelinden uzak durarak altındaki geniş güvenli geçitten uçma.
- Eğitim uçuşunda can kaybı veya başarısızlık yoktur ve eğitim puanı ana oyuna eklenmez.
- Öğrenci dilerse **“Alıştırmayı Atla”** düğmesiyle doğrudan bayram uçuşuna geçebilir.

---

## 6. Ses, Duraklatma ve Yeniden Başlatma

- **Ses:** Sınıf ortamında ani ses oluşmaması için oyun **varsayılan olarak ses kapalı (`🔇 Ses Kapalı`)** başlar. Menüden veya sağ üstteki ses düğmesinden (`🔊 Ses Açık`) Web Audio API tabanlı efekt sesleri açılıp kapatılabilir. Ses kapatıldığında çalmakta olan tüm sesler anında susturulur.
- **Duraklatma ve Geri Sayım:** Sağ üstteki **“⏸ Duraklat”** düğmesi (veya klavyede `P` / `Esc`) oyunu durdurur. **“▶️ Devam Et”** seçildiğinde dünya ve çarpışmalar donmuş haldeyken **3–2–1** görsel hazırlık geri sayımı yapılır.
- **Yeniden Başlatma:** Duraklatma menüsünden mevcut turu sıfırlamak veya ana menüye dönmek istendiğinde yanlışlıkla basılmaları önlemek için kısa bir onay sorulur. Uçuş sonunda veya başarı ekranında ise **“✈️ Yeniden Uç”** / **“🔄 Tekrar Dene”** düğmeleriyle yeni tur anında başlar.

---

## 7. Öğretmen Notu ve Sınıf İçi Etkinlik Önerileri

### A. Ortak Rota ve Güvenli Karar Konuşması (Sınıf Etkinliği)
Sınıfta bir öğrenci akıllı tahtada uçağı yönlendirirken diğer öğrencilerin sürece aktif katılması için şu grup etkinliği uygulanabilir:
- **Uçuş Sırasında Sözlü Rehberlik:** Tahtadaki öğrenci **“Pilot”**, sınıftaki arkadaşları ise **“Hava Trafik Gözlemcileri”** olur. Yaklaşan koyu rüzgâr bulutlarını, sıcak hava balonlarını ve bayrak simgelerini gören öğrenciler *“Üst koridor açık!”*, *“Balonun altından yüksel!”* gibi kısa ve sakin yönlendirmelerle pilota destek verir.
- **Uçuş Sonrası Değerlendirme:** Tur tamamlandığında öğretmen sınıfa şu soruları yönelterek güvenli rota kararını konuşur:
  - *“Hangi noktalarda bayrağa doğrudan gitmek yerine önce engelin geçmesini beklemek veya geniş koridoru seçmek daha güvenliydi?”*
  - *“İkinci denemede rotamızı nasıl değiştirdik?”*

### B. CodeWeek / Bilişimsel Düşünme Sohbeti (İsteğe Bağlı)
Bu oyun bir refleks ve rota oyunudur; oyunu oynamak tek başına kod yazmak değildir. Ancak **CodeWeek** veya bilişim derslerinde oyun sonrasında **“Oyun tasarımında kullanılan koşul (eğer/ise) ve döngüleri konuşma”** etkinliği yapılabilir:
- **Koşul (If / Else) Soruları:**
  - *“Uçak bayrak simgesine dokununca oyunun içinde hangi kural çalışır?”* (`Eğer bayrak toplanırsa -> Bayrak sayısını 1 artır, puana 10 ekle.`)
  - *“Toplam bayrak sayısı 5 veya 10 olduğunda ne değişir?”* (`Eğer bayrak == 5 ise -> 2. Sahne: Rüzgâr Rotası'na geç.`)
  - *“Can sayısı sıfır olursa hangi ekran açılır?”* (`Eğer can == 0 ise -> Uçuş Molası ekranını göster.`)
- **Döngü (Loop) Soruları:**
  - *“Arka plandaki şehir ve bulutlar neden hiç bitmeden akmaya devam ediyor?”* (Oyun döngüsü ve sahne tekrarı kavramı).
