# Mobile Development Assessment

## Merhaba

Bu değerlendirme işe başvuru sürecindeki adaylar için hazırlanmış olup, katılacak kimselerin yaklaşım ve yetkinliklerini değerlendirmede bizlere yardımcı olmak için tasarlanmıştır.

Değerlendirme dahilinde; belirtilen süre içerisinde aşağıda kapsamı ve detayları belirlenmiş projeyi tamamlamanızı beklemekteyiz. Dikkat edebileceğiniz bir diğer husus ise, bizlerin doğru bir değerlendirme yapmamıza yardımcı olacak şekilde iletebileceğiniz en iyi çalışmayı bizlere teslim ediyor olmanız.


### Teknik Beklentiler

- Kullanılacak Teknolojiler:
  - JavaScript ve/veya TypeScript
  - React Native
  - Git

- Kısıtlamalar ve Gereksinimler:
  - Görseller için vektörel dosya formatları kullanmak
  - React'da yalnızca Functional componentler kullanmak
  - Form değerlerini state yönetimi ile saklamak
  - Atomic design prensipleri uygulamak
  - Projenin sık commitlerle Git üzerinde geliştirilmesi
  - Git üzerinde master, development branchleri ve sürüm taglemelerinin kullanımı
  - Minimum %60 unit testing code coverage
  - Projenin nasıl çalıştırılacağına dair README.md dokümantasyonu


### Ürün Beklentileri

- Splash screen ile açılan uygulama 2 saniye sonra ana ekrana geçiş yapacak.
- Ana ekranda bir navigation yapısı kurulacak ve uygulamanın iki tab'dan oluşması sağlanacak.
- İlk tab üzerindeki bir webview ile setur.com.tr'i açacak
- İkinci tab ise [data/controls.json](data/controls.json) dosyasını referans alarak;
  - Dinamik bir biçimde tab içeriğini oluşturacak,
  - Tab içeriği kaydırılabilir olacak,
  - Tab içindeki kontroller json dosyasından okunarak ekrana çizilecek,
  - "input" tipindeki kontroller kullanıcının klavye ile giriş yapabileceği metin kutuları oluşturacak,
  - "input" tipindeki kontroller için "validator" değeri ilgili alanın kodda client taraflı bir doğrulama yapmasını sağlayacak,
  - "choice" tipindeki kontroller kullanıcının "items" altındaki key/value eşleniklerinden oluşan değerleri seçmelerini sağlayan bir liste oluşturacak,
  - "choice" tipindeki bir kontrol için "multiple" değeri `true` olarak belirlendiyse kullanıcı formda bu alan için birden fazla seçim yapabilecek,
  - Kontroller çizildikten sonra tab içeriğinin en altında bir "Gönder" button'u yer alacak,
  - "Gönder" button'una tıklandığında form değerleri firebase, telegram, e-mail v.b. bir noktaya form değerlerini gönderecek,


### Nasıl başlanabilir?

Bir react native proje tabanı oluşturarak başlayabilirsiniz.

Ardından bu codebase'i bir git repository'sine aktarmanız, çalışma bitiminde de bu repository adresiyle paylaşmanız gerekecek.


## Sorularınız

Değerlendirmelerle ilgili sorularınızı [github@setur.com.tr](mailto:github@setur.com.tr) adresine iletebilirsiniz.


### Lisans

[Apache 2.0](LICENSE) ile lisanslanmıştır.
