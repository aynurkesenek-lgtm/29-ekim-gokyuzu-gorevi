# Antigravity oyun geliştirme promptu
# 29 Ekim Gökyüzü Görevi — Cumhuriyet İçin Uç!

Bu dosyanın tamamını Antigravity’ye görev olarak ver. Bu metin geliştirilecek oyunun gereksinimleridir; yapılmış özellik veya test sonucu iddiası değildir.

## 1. Görevin

Deneyimli HTML5 oyun geliştiricisi, oyun tasarımcısı, çocuklara yönelik arayüz tasarımcısı ve test uzmanı olarak çalış. Aşağıda tanımlanan Türkçe 2D uçuş oyununu baştan sona geliştir, çalıştır ve doğrulayabildiğin kontrolleri test et.

Oyunun adı **“29 Ekim Gökyüzü Görevi”**, alt başlığı **“Cumhuriyet İçin Uç, Bayrakları Topla!”** olsun.

Temel fikir: Öğrenci bir gösteri uçağıyla bayram uçuşuna katılır, Türk bayrağı simgelerini toplar ve güvenli uçuş koridorlarından geçer. Oyun neşeli, akıcı, kolay anlaşılır ve tekrar oynanabilir olmalı. Yalnızca afiş görünümünde bir ekran, hareketli maket veya örnek kod teslim etme. Kazanma, uçuş sonu, yeniden başlatma, duraklatma ve bütün kontroller çalışan gerçek bir oyun teslim et.

Önce kontrol hissini ve adil oynanışı kur; ardından canlı sahneleri ve efektleri tamamla. İkisi de nihai kabul koşuludur.

## 2. Hedef kitle ve sınıf kullanımı

Kaynak taslaktaki ilkokul erişilebilirliğini koru; ortaokul öğrencilerinin de ilgisini çekecek bir görsel dil oluştur. Okul öncesi görünümden kaçın.

- Ana kullanım: sınıftaki yatay akıllı tahta.
- Destek: masaüstü tarayıcı, fare, klavye ve dokunma.
- “Rahat uçuş”: yaklaşık 3–4. sınıf veya ilk kez oynayanlar için.
- “Keşif uçuşu”: yaklaşık 5–6. sınıf ve daha deneyimli öğrenciler için.
- Her iki seçenekte de aynı 15 bayraklık hedef, aynı 3 can ve aynı 3 sahne olsun; hız ve engel yoğunluğu değişsin.
- Öğrenciye yalnızca bu iki anlaşılır seçenek göster; ayar tablosuyla başlatma.
- Bir tur yaklaşık 2–3 dakika hedeflesin. Kaçırılan bayraklar nedeniyle kesin süre garantisi verme ve zorunlu geri sayım koyma.
- Kısa turlar sayesinde öğrenciler sırayla tahtaya çıkabilsin.
- Öğrenci adı, üyelik, kişisel veri, reklam, sohbet veya çevrim içi liderlik tablosu isteme.

## 3. Tasarımın ana farkı: canlı ama okunabilir ekran

Yüksek kaliteli, renkli, hafif 2.5D hissi veren çizgi film/oyun atmosferi tasarla. Oyun bir web formu veya düğmelerle çevrili küçük bir Canvas gibi görünmesin.

Görsel hiyerarşi:

1. Büyük uçuş alanı ve kolay görülen uçak.
2. Belirgin bayrak simgeleri ve güvenli koridorlar.
3. Küçük, okunaklı üst bilgi şeridi.
4. Sahnenin önüne geçmeyen sınırlı efektler.

Renk paleti: gökyüzü mavisi, beyaz, sıcak güneş sarısı ve bayram kırmızısı. Kırmızıyı bütün engellerde kullanma; bayraklar ön planda kalsın. Koyu yazılar açık yüzeylerde, açık yazılar yeterince koyu yüzeylerde kullanılsın.

Arka plan tek renk olmasın: yumuşak ışık geçişi, güneş halesi, farklı hızlarda kayan uzak tepeler, şehir silüeti ve dekoratif bulutlar kullan. Ön plan uçağı arka plandan kontur ve hafif gölgeyle ayrılsın. Pervane, egzoz/iz, kanat eğimi ve bayrak dalgalanması ölçülü animasyonlar içersin.

Arka plan hareketi ana nesnelerden yavaş olsun; göz yormasın. Konfeti sürekli yağmasın. Ekran sarsıntısı varsayılan kapalı olsun. Yoğun flaş, hızlı yanıp sönme veya ürkütücü efekt olmasın.

## 4. 29 Ekim temasının uygulanması

Tema yalnızca başlıktaki tarihten ibaret olmasın. Açılışta bayram süslemeleri, uzak şehirde kırmızı-beyaz flamalar, seviyeler arasında anlamlı görsel geçişler ve finalde bir kutlama meydanı oluştur.

Kullanılabilecek kısa ifadeler:

- “29 Ekim Cumhuriyet Bayramı”
- “Rotanı seç, güvenle uç, bayrakları topla!”
- “Cumhuriyet Bayramımız kutlu olsun!”
- Finalde “Yaşasın Cumhuriyet!”

Tarihli bir sürüme kilitleme; yıl ve yıl dönümü sayısını ana oyuna sabitleme. 1923 kuruluş yılı dekoratif bir panoda kullanılabilir. Doğrulanmamış tarih bilgisi, uydurma Atatürk sözü veya alıntı ekleme. Bu bir refleks ve rota oyunu; yalnızca bayrak topladığı için tarih öğrettiğini veya kodlama becerisi kazandırdığını iddia etme.

Türk bayrağını doğru yön ve geometriyle, kırmızı zemin, beyaz hilal ve beyaz beş köşeli yıldızla vektörel çiz. Emojiyle geçiştirme. Bayrağın oranları ve hilal-yıldız yerleşimi için ayrı çizim fonksiyonu kullan; biçimi ekran ölçeklemesinde bozulmasın. Dalgalanma hafif olsun, sembol deforme olmasın.

Toplananlar “bayrak simgeleri” olarak küçük, ışıklı rozet/işaretler içinde sunulabilir. Kaçırılan bayrak simgesi ekranın dışına çıkar; yanma, parçalanma, yere düşüp ezilme veya çarpışma efektiyle yok edilme gösterme. Bayraklar hasar nesnesi olmasın.

Uçak bir bayram gösteri uçağı olsun. Silah, çatışma veya hedef vurma ekleme. Uçuş sonunda güvenli kutlama sahnesi göster.

## 5. Ekranlar ve başlangıç deneyimi

### Ana menü

- Büyük başlık: “29 Ekim Gökyüzü Görevi”.
- Alt başlık: “Cumhuriyet İçin Uç, Bayrakları Topla!”
- Kanca: **“15 bayrağı toplayıp bayram uçuşunu tamamlayabilir misin?”**
- Büyük “Uçuşa başla” düğmesi.
- İki zorluk seçeneği: Rahat uçuş / Keşif uçuşu.
- “Nasıl oynanır?”, “Ses”, “Tam ekran”.
- Uçak ve yavaş kayan bulutlarla canlı ön izleme; dekoratif animasyonlar menü düğmelerini hareket ettirmesin.

### Etkileşimli eğitim uçuşu

İlk başlangıçta veya kullanıcı istediğinde 15–20 saniyelik, atlanabilen alıştırma sun:

1. “Uçağı yukarıdaki halkaya götür.” Hareketi gerçekten denetle.
2. “Şimdi bayrak simgesini topla.” Gerçek toplama etkileşimi kullan.
3. Bir görünür engel ve geniş geçit göster; engelden uzak durmayı öğret.

Alıştırmada can kaybı veya başarısızlık yok. Kontrolü öğrendikten sonra “Hazırım” ile asıl uçuşa geç. Eğitim puanı ana oyuna eklenmesin. Sonraki oyunlarda isteğe bağlı atlanabilsin. Oynama sırasında uzun yönergeler çıkmasın.

### Aktif uçuş

Üstte büyük ve sade gösterge: “Bayrak 7/15”, “Puan 70”, üç can simgesi, sahne adı. Sağda erişilebilir duraklatma ve ses. Gösterge oyun nesnelerinin üzerinden geçmesin; oyun dünyasında HUD için ayrılmış alan olsun.

Dokunmatik kontrol alanı uçuş sahnesini kapatmayacak biçimde altta veya sol altta ayrı bir bant/panelde bulunsun.

### Duraklatma

Başlık ve “Devam et”, “Yeniden başlat”, “Ana menü”. Yeniden başlat ve ana menü mevcut turu bitirecekse kısa onay iste. Devam etmeden önce 3–2–1 görsel hazırlık ver; bu sürede dünya ve çarpışmalar donmuş kalsın. Hazırlık sırasını da iptal edilebilir biçimde yönet.

### Başarı

15. bayrakta oyun mantığını hemen durdur; skor 150, bayrak 15 olsun. Uçak kısa, hasarsız bir bitiş animasyonuyla kutlama meydanına süzülsün. Bu animasyon aktif engel simülasyonu olmasın.

Başlık: “Bayram uçuşu tamamlandı!”

Mesaj: “15 bayrağı topladın. Cumhuriyet Bayramımız kutlu olsun!”

Büyük, doğru çizilmiş Türk bayrağı, kısa konfeti, uçak ve şehir kutlaması. “Yeniden uç” ve “Ana menü” düğmeleri animasyon bekletmeden kullanılabilsin.

### Uçuş sonu

Üç can bittiğinde uçak patlamasın veya düşmesin. Hareket dursun; “Uçuş molası” başlığı ve “Yeni bir rota deneyebilirsin!” mesajı göster. Toplanan bayrak ve puan doğru olsun. “Tekrar dene” / “Ana menü” sun. Kaybetmeyi millî bir görevde başarısızlık gibi çerçeveleme.

## 6. Kontroller: önce akıllı tahta

Üç kontrol yöntemini aynı oyun motoruna bağla:

### A. Tahta için ana yöntem: göreli kontrol paneli

Ekranın alt bölümünde büyük bir “Parmağını burada hareket ettir” kontrol alanı olsun. Öğrencinin eli uçağı ve yaklaşan engelleri kapatmasın.

- Parmağın paneldeki hareket farkı uçağın hedef konumunu değiştirsin.
- İlk dokunmada uçak parmak noktasına ışınlanmasın.
- Duyarlılık kontrollü ve kararlı olsun; küçük parmak hareketi aşırı uçuş üretmesin.
- Parmak kaldırılınca uçak son konumunda güvenle kalsın.
- Tek işaretçi kimliği takip et; ikinci parmağın uçağı kaçırmasına izin verme.

### B. Doğrudan sürükleme

Uçağa veya etrafındaki geniş görünmez yakalama alanına dokunup sürüklemek de mümkün olsun. Yakalama alanı görselden büyük olabilir; bu büyüklüğü çarpışma alanıyla karıştırma. Dokunma ofsetini koru, basınca uçak zıplamasın.

Fareyle de aynı davranış çalışsın. Uçak dışındaki yere tıklamak aniden o noktaya taşımamalı.

### C. Büyük yön düğmeleri ve klavye

İsteğe bağlı erişilebilir dört yön düğmesi; basılı tutma sürekli hareket ettirsin. En az 64×64, tercihen 80×80 CSS px olsun. Pointer up/cancel/lost capture durumunda basılı yön temizlensin. Çapraz harekette hız normalize edilsin.

Klavye: oklar ve WASD. Oyun aktifken ilgili tuşların sayfayı kaydırmasını önle; menüde tarayıcı etkileşimlerini gereksiz engelleme. Odak kaybında basılı tuşları temizle. Aynı anda giriş yöntemleri çelişirse en son kullanılan yöntemi önceliklendir ve bunu tutarlı uygula.

## 7. Hareket hissi ve koordinat sistemi

- Mantıksal oyun dünyası için sabit bir boyut seç; örneğin 1600×900. Ekran boyutuyla dünya fiziğini değiştirme.
- HUD ve kontrol paneli için güvenli alanları ayır; uçak bunların altına girmesin.
- Canvas ekranda oranı korunarak ölçeklensin; gerekirse uyumlu arka plan çerçevesi kullan.
- Pointer koordinatlarını canvas bounding rect, ölçek ve varsa boşlukları hesaba katarak dünya koordinatına çevir.
- Uçak genişliğini oyun alanının yaklaşık %7–9’u kadar tut; görünür, kontrol edilebilir ve koridorlara sığabilir olsun.
- Uçağın başlangıç konumu sol üçte birde, güvenli yükseklikte olsun.
- Sağa-sola serbestlik kontrollü bir uçuş bölgesiyle sınırlandırılabilir; ekranın sağ kenarına gidip gelen nesnelerle aniden çarpışmasın.
- Hedefi hız sınırıyla takip et; kontrol hissini geciktiren ağır yumuşatma kullanma.
- Uçak hareketi arka planın ileri akışından bağımsız olsun. Bırakılınca otomatik düşüş ekleme; bu Flappy Bird değil.
- Kanat eğimi hareket yönüne bağlı, sınırlı bir görsel efekt olsun; hitbox’ı gereksiz değişmesin.

## 8. Üç sahne ve zorluk eğrisi

Her 5 bayrak bir sahneyi tamamlasın. Toplam puan ve can geçişte korunsun.

| Bayrak sayısı | Sahne | Atmosfer ve oynanış |
|---|---|---|
| 0–4 | Bayram Sabahı | Açık mavi gökyüzü, kırmızı-beyaz süslü uzak şehir, seyrek engel, geniş koridor |
| 5–9 | Rüzgâr Rotası | Yeni tepe/şehir katmanları, sıcak hava balonları, hafif çapraz rota; otomatik rüzgârla kontrol kaybı yok |
| 10–14 | Kutlama Meydanına Doğru | Altın ışık dokunuşu, uzakta kutlama alanı, daha hareketli ama adil düzenler |
| 15 | Bayram Finali | Hasarsız kutlama sahnesi ve sonuç ekranı |

5. ve 10. bayrakta dünya kısa süre dursun, yeni sahne adı 1 saniye kadar gösterilsin. Bu sırada hasar ve üretim olmasın. Geçişten sonra uçağın önünde en az 2 saniyelik güvenli koridor sağla. Geçiş animasyonu skoru, uçağı veya canı sıfırlamasın.

Hız bir anda sıçramasın. Örnek başlangıç ayarı olarak rahat modda yatay akış 150 → 180 → 210 dünya birimi/sn; keşif modunda 180 → 215 → 250 denenebilir. Bunlar sabit doğru değerler değildir: gerçek oyun testinden sonra ayarla. Oyuncu hareket hızı bu akıştan kaçınmaya izin verecek düzeyde olsun.

İlk 8–10 saniyede az engel ve kolay ilk bayrak ver. Oyunu başlar başlamaz çarpışmaya dönüştürme. Rahat modda hedef tur süresine yaklaşmadan bayrak üretimi çok seyrek kalmasın.

## 9. Bayrak üretimi ve toplama

- Her simge +1 bayrak ve +10 puan; başka gizli puan veya çarpan yok. Puan her zaman bayrak×10.
- 15 bayrakta hedef tamamlanır; sayaç 15’i aşmaz.
- Bayrak simgeleri ulaşılabilir, engelle çakışmayan noktalarda oluşsun.
- Kaçırmak can azaltmasın ve görevi imkânsızlaştırmasın; hedefe ulaşana kadar yenileri gelsin.
- İlk sahnede geniş, doğal bir rota; ilerleyenlerde küçük yükseklik değişimleri kullan.
- Bayrakla engel aynı kare/zamanda üst üste doğmasın.
- Toplama alanı çarpışma alanına göre biraz daha cömert olsun.
- Bir simge bir kere alınsın; iki karede tekrar puan yazmasın.
- Simge toplanınca kısa halka, hafif parçacık ve küçük “+10” göster. Metinler birikmesin; aynı anda sınırlı bildirim olsun.
- “Güzel rota!”, “Bir bayrak daha!” gibi kısa mesajlar kullan. Her toplamada büyük ekran yazısı çıkmasın.

## 10. Engeller: görsel olarak anlaşılır ve adil

Normal beyaz bulutları dekor yap; onlara değmek can azaltmasın. Dekoratif bulut ile hasar veren bulut arasındaki belirsizliği kaldır.

Hasar veren nesneler:

1. Önceden görülebilen koyu rüzgâr bulutu: ayrı silüet, ince rüzgâr çizgileri ve eğitimde tanıtım.
2. Sıcak hava balonu: yavaş ve öngörülebilir hareket; görseldeki sepet/gövde hitbox’ı tutarlı olsun.
3. Havada bakım şamandırası: yuvarlak, açık konturlu nesne; uçuş temasıyla uyumlu.

Kuşlar uzak dekor olabilir; çarpışmada kuşlara zarar verme sahnesi oluşturma. Dağları çoğunlukla arka planda tut; uçuş alanının içine aniden giren dev zirveyle çıkışı kapatma.

Görselde tehlikeli görünen ama hasar vermeyen ön plan nesneleriyle öğrenciyi yanıltma. Engeller ekrandan yeterince uzakta doğsun ve oyuncuya tepki süresi bıraksın.

## 11. Adil parkur üretimi

Tamamen bağımsız rastgele nesneler serpmek yerine **test edilmiş engel şablonları ve güvenli koridor** kullan.

- Başlangıçta 10–15 kısa, doğrulanabilir parkur parçası oluştur.
- Her parçada giriş/çıkış güvenli aralığı ve engel sınırları belli olsun.
- Parça geçişleri uçağın mevcut/olası konumundan ulaşılabilir olmalı.
- Güvenli koridor genişliği en az uçak hitbox yüksekliğinin 2,5 katı olsun; rahat modda daha geniş tut.
- Ardışık güvenli aralıklar arasındaki düşey mesafe, parçaların varış süresi ve uçağın düşey hızına göre aşılabilir olsun. Hesabı kodda doğrula; yalnızca “adil üretim” yorumu yazma.
- Bir engelin görünmesiyle uçağa varması arasında rahat modda yaklaşık en az 2,5 saniye, keşif modunda en az 2 saniye tepki süresi hedefle.
- Bayraklar güvenli rotada veya güvenli sapmayla erişilen yerde olsun.
- Bayrak aldıktan hemen sonra kaçınılmaz çarpışma olmasın.
- Aynı yükseklikte sürekli bayrak üretip oyunu hareketsiz durarak kazanılır yapma.
- Zorluk yeni can cezası yerine hız, rota çeşitliliği ve koridor değişimiyle kontrollü artsın.
- Testlerde tekrar üretilebilirlik için tohumlanabilir rastgelelik kullan.
- Geçerli şablon bulunamazsa güvenli, seyrek bir parçaya dön; hatalı rastgele parça üretme.

## 12. Can ve çarpışma sistemi

- Başlangıç 3 can. Her geçerli temas 1 can azaltır.
- Hitbox uçağın görsel sınırlarından yaklaşık %15–25 küçük olabilir; köşe temaslarında adil hissettirsin.
- Canvas üzerindeki hitbox görselle aynı ölçek ve koordinatta olsun.
- Çarpışma sonrası en az 1,5 saniye koruma uygula; saydam kalkan halkası kullan, yanıp sönme kullanma.
- Aynı engel örneği bir turda en fazla bir kez hasar verebilsin. Koruma bitti diye hâlâ temas edilen nesne yeniden can almasın.
- Can kaybından sonra yeni engelle hemen çarpışmayı önlemek için açık alan bırak veya ilgili yakın tehlikeyi güvenli biçimde uzaklaştır.
- Çarpışma uçağı kontrol dışına savurmasın. Kısa sıcak renkli uyarı ve isteğe bağlı yumuşak ses yeterli.
- Can 0 olduğunda simülasyon, üretim ve puanlama durur.
- Aynı fizik adımında ölümcül çarpışma ve 15. bayrak teması varsa deterministik kural kullan: önce hasarı işle; can sıfırsa uçuş biter ve o adımda bayrak puanı eklenmez. Can kalmışsa toplama işlenebilir. Bu sıralamayı test et.

## 13. Durum makinesi ve zaman yönetimi

Durumlar en az: menu, tutorial, playing, paused, levelTransition, resumeCountdown, won, lost. Her durumda hangi girdilerin ve güncellemelerin açık olduğunu tanımla.

- Tek requestAnimationFrame zinciri çalışsın. Yeniden başlatmada ikinci döngü açılmasın.
- Hareket saniye tabanlı olsun; 30/60/120 Hz’de benzer hız üret.
- Fizik için sabit alt adım ve accumulator veya eşdeğer güvenli yaklaşım kullan; uzun dt değerini sınırla. Yüksek hızda nesnenin hitbox’ın içinden atlamasını önle.
- Oyun zamanını gerçek duvar saatinden ayır. Koruma, üretim, bildirim ve geçişler simülasyon zamanıyla uyumlu olsun.
- Duraklatmada bütün aktif oyun sayaçları dursun. Arka planın hareketi de sakin biçimde dursun.
- visibilitychange/blur olayında güvenli duraklatma yap. Dönüşte otomatik hasar veya büyük dt sıçraması olmasın; kullanıcı “Devam et” desin.
- Pointer capture kullan; pointercancel, lostpointercapture, pencere odağı kaybı ve oyun sonu giriş durumlarını temizlesin.
- Yeni turda tüm nesneler, efektler, hasar kimlikleri, kontrol durumları, sayaçlar ve geçişler sıfırlansın.
- Menü ve oyunu her karede DOM’dan yeniden kurma. Canvas sahneyi çizsin; HUD yalnızca değeri değişince güncellensin.
- Pencere yeniden boyutlanınca koordinatlar tutarlı kalsın; uçağın konumu güvenli sınırlara alınsın. Gerekirse yeniden boyutlandırma oyunu duraklatsın.

## 14. Akıllı tahta, okunabilirlik ve erişilebilirlik

- Hedef çözünürlükler: 1920×1080, 1366×768, 1280×720.
- Sayfa bütünü kaydırma gerektirmesin; overflow:hidden kullanıp düğmeleri kırparak sorunu saklama.
- Menü ve sonuç ekranında ana düğmeler en az 64 px yüksekliğinde; temel kontroller hiçbir hedef boyutta 48 px altına düşmesin.
- Ana başlık 48–72 px, oyun göstergeleri yaklaşık 24–32 px, yardımcı açıklamalar hedef ekranlarda en az 20 px olsun.
- Yer kazanmak için yazıları sürekli küçültmek yerine düzeni sadeleştir.
- Dokunma paneli HUD veya uçakla çakışmasın.
- Tam ekran desteği yoksa hata yerine normal ekran kullanımını sürdür.
- Renk dışında şekil/metin kullan. Kalp simgelerine ek olarak erişilebilir “3 can” metni bulunsun.
- DOM menüleri klavyeyle erişilebilir, düğmeler açıklayıcı etiketli olsun. Sadece Canvas üstüne çizilmiş tıklama yazılarına bağımlı menü kurma.
- prefers-reduced-motion durumunda parallax ve parçacıkları azalt; oynanış için gerekli nesne hareketleri korunabilir.
- Sesi varsayılan kapalı başlat. Ses kapalıyken oyunun bütün bilgileri anlaşılır olsun.

## 15. Ses ve efekt tasarımı

Harici ses dosyası gerektirmeden Web Audio API ile kısa toplama, hasar, geçiş ve başarı sesleri oluştur. İlk kullanıcı etkileşiminden önce ses başlatma. Ses API’si kullanılamıyorsa oyun devam etsin.

Arka plan müziği zorunlu değil. Otomatik millî marş veya sesli alıntı ekleme. “Ses kapalı” seçildiğinde sırada bekleyen sesler de iptal edilsin. Ses düğmesi etiket ve simgeyi birlikte değiştirsin.

Parçacık havuzu ve üst sınırlar kullan. Toplama halkası, pervane ve yumuşak gölge canlılığı sağlasın; çok sayıda DOM düğümü veya her karede yeni nesne üretimiyle performansı düşürme.

## 16. Teknik altyapı ve çevrim dışı teslim

HTML5 + CSS3 + Vanilla JavaScript + Canvas API kullan. Backend, hesap, React, veritabanı ve harici API gerekli değil.

Önerilen kaynak düzeni: index.html, style.css, game.js; oyun büyürse input/render/spawn/audio gibi modüllere mantıklı ayırabilirsin. Mevcut projeyi önce incele; ilgisiz dosyaları silme.

Ek olarak **29_ekim_gokyuzu_gorevi.html** adlı tek bağımsız teslim dosyası üret. Bütün kod ve gerekli varlıklar içinde olsun. Çift tıklanıp file:// üzerinden açıldığında oyun çalışsın; fetch, dinamik import, sunucu veya service worker zorunluluğu olmasın.

- Görselleri Canvas/yerel SVG ile üret; harici görsel ve font indirmesine bağımlı olma.
- UTF-8 ve Türkçe karakterleri doğru kullan.
- devicePixelRatio desteğiyle net çizim yap; zayıf donanımda DPR değerini örneğin 2 ile sınırla.
- Performans için arka plan katmanlarını önceden çizip önbelleğe alabilirsin.
- Kaliteyi otomatik düşürmek gerekirse parçacıkları azalt; fizik veya kontrol hassasiyetini bozma.
- Kayıt zorunlu değil. Ses/zorluk/öğretici tercihi yerelde tutulabilir; depolama kapalıysa oyun çökmesin.
- Kişisel veri veya dış ağ isteği üretme.

## 17. Eğitimsel çerçeve

Gerçekçi hedefler: yön kavramı, dikkat, el-göz koordinasyonu, güvenli rota seçimi ve denemeye göre strateji değiştirme. Cumhuriyet Bayramı temasını neşeli bir ortak kutlamayla hissettir.

Bu sürüme zorunlu tarih sınavı, oyun ortasında çıkan çoktan seçmeli soru veya alakasız kodlama bloğu ekleme; uçuş akışını kesme. CodeWeek kapsamında kullanılırsa öğretmen rehberinde “Oyun tasarımında kullanılan koşul ve döngüleri konuşma” şeklinde isteğe bağlı etkinlik öner: “Bayrağa dokununca ne olur?”, “Can sıfırsa hangi ekran açılır?” Oyunu oynamanın kendisini kod yazmakla eşitleme.

## 18. Test gereksinimleri

Kodda özelliğin bulunması test edildiği anlamına gelmez. Motor/simülasyon testi, tarayıcı etkileşim testi, dokunmatik emülasyon ve gerçek akıllı tahta kontrolünü ayrı raporla.

### Oyun mantığı

1. Bayrak toplama tam bir kere +1 ve +10 verir.
2. Kaçırılan bayrak hedefe ulaşmayı engellemez.
3. 5. ve 10. bayrak doğru sahneye geçirir; puan ve can korunur.
4. 15. bayrakta kazanç ve yeni üretim durur; toplam 150 puandır.
5. Can sayısı 0’ın altına, bayrak sayısı 15’in üstüne çıkmaz.
6. Aynı engel tek kez hasar verir; hasar koruması çalışır ve duraklatmada tüketilmez.
7. Aynı adımda ölüm/son bayrak önceliği tanımlı davranır.
8. 3 can bittiğinde uçuş sonu açılır.
9. Aynı tohum aynı parkuru üretir; en az 100 farklı tohumda koridor/geçiş uygunluk kuralları sınanır. Bu kontrolün insanla oynanabilirliği tamamen kanıtlamadığını belirt.
10. Doğum noktasında bayrak/engel çakışması ve erişilemez dar koridor oluşmaz.
11. Art arda 10 yeniden başlatmada tek oyun döngüsü ve temiz durum korunur.
12. 30/60/120 Hz simülasyonda süreye göre yer değiştirme tolerans içinde aynıdır.

### Kontrol ve arayüz

13. Oklar ve WASD; zıt yönler ve çapraz hareket doğru yönetilir.
14. Yön düğmelerine basılı tutma ve bırakma çalışır; odak kaybında hareket takılı kalmaz.
15. Doğrudan sürüklemede uçak sıçramaz.
16. Göreli panelde ilk dokunma konumu uçağı değiştirmez, hareket farkı doğru aktarılır.
17. Farklı ekran ölçeklerinde pointer koordinatı doğrudur.
18. İkinci parmak ve pointercancel güvenli yönetilir.
19. Duraklatma, devam geri sayımı, ana menü ve sonuç ekranı düğmeleri çalışır.
20. Tam ekran ve yeniden boyutlandırma uçuş alanını bozmaz.

### Görsel, çevrim dışı ve performans

21. Üç hedef çözünürlükte ekranları gerçek tarayıcıda incele; temel düğmelerin görünürlük ve ölçülerini kontrol et.
22. Dekoratif bulutlar ile hasar nesneleri açıkça ayırt edilir.
23. Türk bayrağı farklı boyutlarda doğru görünür, aynalanmaz veya ters dönmez.
24. Göstergeler ve kontrol paneli uçuş alanını örtmez.
25. Uçak ve engeller hareketli arka planda seçilebilir.
26. Sesi kapatma bütün sesleri susturur; ses API’si yoksa oyun sürer.
27. Bağımsız dosya file:// ve ağ kapalı ortamda çalışır; uzak istek yoktur.
28. Tarayıcı konsolunda hata yoktur.
29. Nesne ve parçacık sayıları sınırlıdır; uzun tur ve yeniden başlatma gereksiz birikim yaratmaz.
30. Gerçek cihaz varsa performansı ölç; yoksa “akıllı tahtada 60 FPS garantili” gibi iddia kurma. Test edilen cihaz/ortamı ve gözlemi yaz.

En az bir tam kazanma akışını ve bir uçuş sonu akışını tarayıcıda doğrula. Geliştirici araçlarıyla durum atlanarak yapılan kontrolü doğal oynayarak tamamlanmış tur gibi raporlama. İnsan gözüyle kontrol hissi ve zorluk değerlendirmesini ayrıca yapabildiğin ölçüde belirt.

## 19. Geliştirme sırası

1. Mevcut klasörü incele, kısa plan oluştur.
2. Canvas, koordinat sistemi ve üç giriş yöntemini kur; boş sahnede hareket hissini doğrula.
3. Bayrak toplama, göstergeler ve hedefi tamamla.
4. Engelleri, hitbox’ları, korumayı ve adil parkur şablonlarını ekle.
5. Üç sahne, geçiş, başarı ve uçuş sonu akışını tamamla.
6. Menü, etkileşimli alıştırma, duraklatma ve devam geri sayımını bağla.
7. 29 Ekim sahne tasarımlarını, katmanları, uçak ayrıntılarını ve kutlama finalini tamamla.
8. Ses, azaltılmış hareket ve farklı çözünürlükleri düzenle.
9. Testleri çalıştır, gerçek sorunları düzelt; kaynak ve bağımsız dosyayı ayrı doğrula.

Her aşamada kısa ilerleme bildir. Kullanıcıya plan verip durma. Rutin görsel kararlar için yeniden onay isteme; bu gereksinimleri uygulanabilir biçimde tamamla.

## 20. Son teslim

- Düzenlenebilir kaynak proje.
- **29_ekim_gokyuzu_gorevi.html**: USB ile akıllı tahtaya taşınabilen bağımsız oyun.
- **KULLANIM.md**: dosyayı açma, tam ekran, üç kontrol yöntemi, zorluk seçimi, eğitim uçuşu, ses ve yeniden başlatma.
- **TEST_SONUCLARI.md**: gerçekten çalıştırılan testler, sonucu, kullanılan ortamlar ve doğrulanamayanlar.
- Kısa öğretmen notu: bir öğrencinin uçtuğu sırada sınıfın rotayı sözlü önermesi ve sonrasında güvenli rota kararının konuşulması.

Son yanıtında hangi dosyayı açacağımı ve gerçek test sonuçlarını kısa biçimde belirt. Eksik veya test edilemeyen özellikleri gizleme.

## 21. Nihai kabul ölçütü

Oyun, yalnızca hareket eden bir uçak değil; dokunmatik kontrolü rahat, parkuru adil, 29 Ekim atmosferi güçlü ve bütün akışları tamamlanmış bir bayram uçuşu olmalı. Öğrenci birkaç saniyede nasıl oynayacağını anlamalı, tur boyunca neyi topladığını ve neden can kaybettiğini açıkça görmeli; tekrar oynamak istediğinde yeni tur sorunsuz başlamalı.
