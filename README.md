# iView

iView, önceliği iPad olan; belgeleri tek bir çalışma alanında görüntülemeyi ve ileride düzenlemeyi hedefleyen yerel belge uygulamasıdır.

## Geliştirme durumu

- iPad odaklı temel çalışma alanı hazır: Ana, Tablo, Belge, Sunu, PDF ve Eklenti bölümleri soldaki dock üzerinden erişilebilir.
- iView uygulama ikonu iOS ve macOS uygulama varlıklarına eklendi.
- Dosyalar üzerinden seçilen yerel PDF dosyaları iView içinde açılıp görüntülenebiliyor.
- Dosyalar üzerinden seçilen yerel Word (`.doc` ve `.docx`) dosyaları iView içinde açılıp görüntülenebiliyor.
- Dosyalar üzerinden seçilen yerel PowerPoint (`.ppt` ve `.pptx`) dosyaları iView içinde açılıp görüntülenebiliyor.
- Dosyalar üzerinden seçilen yerel Excel (`.xls` ve `.xlsx`) dosyaları iView içinde açılıp görüntülenebiliyor.
- iPad'de Dosyalar uygulamasından "iView ile Aç" akışıyla gönderilen desteklenen belgeler, iView içindeki uygun bölüme yönlendiriliyor; bu akış PDF ile iPad Simulator'da doğrulandı.
- Açık PDF, Word, PowerPoint ve Excel belgeleri için **Dosyalara Kaydet** denetimi; özgün belgeyi ezmeden güvenli bir kopya hazırlayıp iPadOS'un sistem dosya seçicisini açıyor. iPad Simulator otomatik testleri belge verisini, dosya adını, türünü ve kaynak belgenin değişmediğini doğruluyor. Sistem seçicide hedef klasör belirlenip dosyanın oluşması ayrıca uçtan uca doğrulanacak.
- Açık PDF, Word, PowerPoint ve Excel belgeleri için **Paylaş** denetimi; iView'in yönettiği kısa ömürlü bir kopyayı iPadOS'un sistem paylaşım arayüzüne veriyor. iPad Simulator otomatik testleri kopyanın veri içeriğini, adını, türünü ve güvenli temizliğini doğruluyor. Hedef uygulamaya gerçek teslim işlemi ayrıca uçtan uca doğrulanacak.
- PDF, Excel, Word ve PowerPoint dışındaki belge türlerini açma; belge düzenleme ve yazdırma özellikleri henüz geliştirme aşamasındadır.

Ayrıntılı geliştirme sırası için [Yol Haritası](ROADMAP.md) dosyasına bakın.
