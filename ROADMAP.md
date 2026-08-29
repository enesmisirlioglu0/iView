# iView Yol Haritası

> **Öncelik:** iView, ilk olarak iPad'de rahat ve doğal bir belge görüntüleme deneyimi sunmak için geliştirilecek.
>
> **Çalışma sırası:** Aşamalar, temel dosya akışından başlayıp daha karmaşık belge düzenleme ve güvenlik işlemlerine ilerleyecek şekilde kolaydan zora düzenlenmiştir.

## 1. Aşama — Belgeyi Alma ve Görüntüleme Temeli

- [x] İndirilen PDF dosyalarını iView içinde görüntüleme.
- [x] İndirilen Word dosyalarını iView içinde görüntüleme.
- [x] İndirilen PowerPoint dosyalarını iView içinde görüntüleme.
- [x] İndirilen Excel dosyalarını iView içinde görüntüleme.
- [x] Diğer uygulamalardan "iView ile Aç" seçeneğiyle belge alma.
- [ ] Dosyalar uygulamasından sürükleyip bırakarak belge açma.
  - Durum notu: Belge sağlayıcısından alma, tür saptama ve güvenli geçici kopyalama hattı iPad Simulator'da otomatik test edildi. Dosyalar uygulamasından iView ekranına yapılan fiziksel sürükleme jesti henüz ayrıca doğrulanmadı.
- [x] Erişilebilirlik desteği — VoiceOver, büyük metin ve daha okunabilir arayüz.
  - Doğrulama: iPad Simulator UI testleri, VoiceOver denetimlerini, dock geçişlerini, dokunma alanlarını, metin kırpılmasını ve en büyük Dynamic Type boyutunu denetledi. PDFKit ve Quick Look'un belge içi sistem denetimleri sonraki belge-odaklı kontrolde ayrıca sınanacak.

## 2. Aşama — Günlük Dosya Akışı ve iPad Deneyimi

- [ ] Açılan belgeleri **Dosyalar** uygulamasına kaydetme.
  - Durum notu: Açık PDF, Word, Excel ve PowerPoint belgeleri için özgün içeriği değiştirmeden kopya hazırlayan ve iPadOS'un sistem **Dosyalara Kaydet** ekranını açan akış eklendi. iPad Simulator otomatik testleri veri içeriğini, dosya adını, dosya türünü ve kaynak belgenin değişmediğini doğruladı. Sistem ekranında hedef klasörün seçilip dosyanın oluştuğu uçtan uca jest testi ayrıca doğrulanacak.
- [ ] Açılan belgeleri sistem paylaşım seçenekleriyle paylaşma.
  - Durum notu: Açık PDF, Word, Excel ve PowerPoint belgeleri için uygulamanın denetiminde, aynı dosya adı ve türünü koruyan kısa ömürlü bir kopya hazırlanıp iPadOS'un sistem paylaşım arayüzüne veriliyor. iPad Simulator otomatik testleri belge verisini, adı ve türünü; benzersiz geçici kopyalama ile güvenli temizliği doğruladı. Hedef uygulamanın belgeyi gerçekten teslim alması ayrı uçtan uca kontrolde doğrulanacak.
- [ ] Açılan belgeleri iView'in desteklediği tüm platformlarda sistem yazdırma seçenekleriyle yazdırma.
- [ ] iPad çoklu görev ekranlarında rahat kullanım.
- [ ] Harici klavye kısayolları desteği.

## 3. Aşama — Yeni PDF Oluşturma

- [ ] Görselleri tek bir PDF belgesine dönüştürme.
- [ ] Kamera ile kağıt belge tarayıp PDF oluşturma.

## 4. Aşama — Güvenli Düzenleme Altyapısı

- [ ] Düzenleme yapmadan önce özgün dosyayı koruyan ayrı bir kopya oluşturma.
- [ ] Açılan belgeler üzerinde belge düzenleme işlemleri sunma.
- [ ] Düzenlemelerde geri al ve yinele.
- [ ] Belge bilgilerini düzenleme — başlık, yazar veya tarih gibi.

## 5. Aşama — İleri Belge İşlemleri ve Güvenlik

- [ ] Açılan belgelerdeki doldurulabilir form alanlarını tamamlama.
- [ ] Açılan belgelere imza ekleme işlemleri sunma.
- [ ] Düzenlenebilir belge metinlerinde bul ve değiştir işlemi.
- [ ] Parolalı belgeleri açma ve belgeleri parola ile koruma.

## Not

Bu yol haritası şimdilik yalnızca ilk kullanım hedefini tanımlar. Yeni özellikler ve ayrıntılar, uygulama geliştikçe eklenecek ve uygun aşamaya kolaydan zora yerleştirilecektir.
