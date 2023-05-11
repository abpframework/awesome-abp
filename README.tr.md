[English](README.md)｜[简体中文](README.zh-Hans.md) | Türkçe

# Awesome ABP!

[ABP Framework](https://github.com/abpframework/abp) ile ilgili kaynakların kategorize edilmiş bir listesi.

## İçindekiler

- [Resmi Bağlantılar](#resmi-bağlantılar)
- [Diğer Listeler](#diğer-listeler)
- [Öğreticiler / Makaleler](#öğreticiler--makaleler)
- [Etkinlikler](#etkinlikler)
- [Temalar](#temalar)
- [Uygulama Modülleri](#uygulama-modülleri)
- [Araçlar](#araçlar)
- [NuGet / NPM Paketleri](#nuget--npm-paketleri)
- [Video Eğitimler](#video-eğitimler)

## Resmi Bağlantılar

### Resmi web-siteleri

* **[abp.io](https://abp.io/)** (anasayfa)
* **[docs.abp.io](https://docs.abp.io/)** (dökümantasyon)
* **[community.abp.io](https://community.abp.io/)** (ABP ve .NET ile ilgili gönderiler ve etkinlikler)
* **[blog.abp.io](https://blog.abp.io/)** (en son haberler ve sürümler için resmi blog)
* **[commercial.abp.io](https://commercial.abp.io/)** (ABP Commercial başlangıç şablonları (startup templates), UI temaları, uygulama modülleri, araçlar ve destek)

### Diğer resmi bağlantılar

* [**twitter**.com/abpframework](https://twitter.com/abpframework)
* [**discord**.gg/abp](https://discord.gg/abp)
* [**stackoverflow**.com/questions/tagged/abp](https://stackoverflow.com/questions/tagged/abp)
* [**github**.com/abpframework](https://github.com/abpframework)

## Diğer Listeler

* [Awesome ABP](https://github.com/EasyAbp/awesome-abp) (EasyAbp Topluluğu tarafından): ABP ile ilgili kaynakların listelendiği bir repository.

## Öğreticiler / Makaleler

### Resmi Öğreticiler

* [Başlarken](https://docs.abp.io/en/abp/latest/Getting-Started): ABP Framework ile bir uygulama oluşturun ve geliştirmeye başlayın.
* [Hızlı Başlangıç](https://docs.abp.io/en/abp/latest/Tutorials/Todo/Overall): ABP Framework kullanmaya başlayın ve basit bir TODO uygulaması oluşturun.
* [Web Uygulama Geliştirme](https://docs.abp.io/en/abp/latest/Tutorials/Part-1): Tam özellikli bir web uygulaması oluşturmak için 10 bölümlük bir eğitim serisi.

### Topluluk Gönderileri

ABP Framework takımı ve ABP topluluğu tarafından yayınlanan en son makaleleri görmek için [community.abp.io/posts](https://community.abp.io/posts) adresini ziyaret edin.

## Etkinlikler

ABP ekibi tarafından düzenlenen çevrimiçi etkinlikler, demolar ve soruc-cevap oturumları için aşağıdaki listeye göz atabilirsiniz:

* [ABP Community Talks](https://www.youtube.com/playlist?list=PLsNclT2aHJcOsPustEkzG6DywiO8eh0lB)
* [ABP .NET Conference 2023](https://www.youtube.com/playlist?list=PLsNclT2aHJcPTA3D4fIF10fsbhbckEbBC)

> ABP'deki yeniliklerden haberdar olmak için [YouTube kanalımıza](https://www.youtube.com/c/Volosoft) abone olmayı unutmayın!

## Temalar

### Resmi Temalar

* [Basic Theme](https://docs.abp.io/en/abp/latest/UI/AspNetCore/Basic-Theme): Bootstrap ile oluşturulmuş minimalist bir tema. Basic Theme üzerine kendi temanızı ve stilinizi oluşturabilirsiniz.
* [Lepton Theme](https://docs.abp.io/en/commercial/latest/themes/lepton): Birden çok renk ve stil seçeneğine sahip profesyonel bir UI teması.
* [LeptonX Theme](https://x.leptontheme.com/): Modern, responsive ve esnek bir UI teması. Yeni uygulamalar için önerilen temadır. İki versiyonu vardı:
  * [LeptonX Lite](https://docs.abp.io/en/abp/latest/Themes/LeptonXLite/AspNetCore): Daha az özellik ve seçeneğe sahip ücretsiz sürüm.
  * [LeptonX](https://docs.abp.io/en/commercial/latest/themes/lepton-x/mvc): Tüm özellikler ve seçeneklerle birlikte tam sürüm.

## Uygulama Modülleri

Bir uygulama modülü, genellikle kendi entityleri, servisleri, API'leri ve UI bileşenleri ile tam olarak uygulanmış bir uygulama/iş işlevselliği sağlar.

### Açık Kaynak / Ücretsiz Modüller

#### Resmi Açık Kaynak / Ücretsiz Modüller

Bu uygulama modülleri, ABP ekibi tarafından oluşturulur ve sürdülür.

* [Account](https://docs.abp.io/en/abp/latest/Modules/Account): Hesap yönetimi için kullanıcı arabirimi sağlar ve kullanıcının uygulamada oturum açmasına/kayıt olmasına izin verir.
* [Audit Logging](https://docs.abp.io/en/abp/latest/Modules/Audit-Logging): Denetim günlüklerini (audit-logs) bir veritabanında saklar.
* [Background Jobs](https://docs.abp.io/en/abp/latest/Modules/Background-Jobs): Arka planda işlemler gerçekleştirirken, bunları veritabanında saklayın ve yönetin.
* [Blogging](https://commercial.abp.io/modules/Volo.Blogging): Kendi bloglarınızı oluşturun ve yönetin (Artık geliştirilmiyor, bunun yerine [CMS Kit modülünün](https://docs.abp.io/en/abp/latest/Modules/Cms-Kit/Index) [blogging özelliğini](https://docs.abp.io/en/abp/latest/Modules/Cms-Kit/Blogging) kullanın).
* [CMS Kit](https://docs.abp.io/en/abp/latest/Modules/Cms-Kit/Index): Yeniden kullanılabilir *İçerik Yönetim Sistemi* özellikleri sağlar.
* [Docs](https://docs.abp.io/en/abp/latest/Modules/Docs): Teknik dokümantasyon web sitesi oluşturmak için kullanılır. Şuan ABP'nin [kendi dökümanları](https://docs.abp.io/) bu modülü kullanmaktadır. 
* [Feature Management](https://docs.abp.io/en/abp/latest/Modules/Feature-Management): [Özellikleri](https://docs.abp.io/en/abp/latest/Features) sürdürmek ve yönetmek için kullanılır.
* [Identity](https://docs.abp.io/en/abp/latest/Modules/Identity): Organizasyon birimlerini, rolleri, kullanıcıları ve bunların izinlerini Microsoft Identity kütüphanesine dayanarak yönetir.
* [IdentityServer](https://docs.abp.io/en/abp/latest/Modules/IdentityServer): IdentityServer4 ile entegre olur.
* [OpenIddict](https://docs.abp.io/en/abp/latest/Modules/OpenIddict): OpenIddict ile entegre olur.
* [Permission Management](https://docs.abp.io/en/abp/latest/Modules/Permission-Management): İzinleri sürdürmek için kullanılır.
* [Setting Management](https://docs.abp.io/en/abp/latest/Modules/Setting-Management): [Ayarları](https://docs.abp.io/en/abp/latest/Settings) sürdürmek ve yönetmek için kullanılır.
* [Tenant Management](https://docs.abp.io/en/abp/latest/Modules/Tenant-Management): [Multi-tenant](https://docs.abp.io/en/abp/latest/Multi-Tenancy) bir uygulamadaki tenantları yönetmeyi sağlar.

### Commercial Modülleri

#### Resmi Commercial Modülleri

* [Account](https://commercial.abp.io/modules/Volo.Account.Pro): Giriş, kayıt, şifremi unuttum, e-posta aktivasyonu, sosyal girişler ve hesapla ilgili diğer işlevleri sağlar.
* [Audit Logging](https://commercial.abp.io/modules/Volo.AuditLogging.Ui): Kullanıcı denetleme günlüklerinin ve varlık geçmişlerinin ayrıntılı olarak raporlanması.
* [Chat](https://commercial.abp.io/modules/Volo.Chat): Kullanıcılar arasında gerçek zamanlı mesajlaşma.
* [CMS Kit](https://commercial.abp.io/modules/Volo.CmsKit.Pro): Kendi *İçerik Yönetim Sisteminizi* oluşturmak için yardımcı olur.
* [File Management](https://commercial.abp.io/modules/Volo.FileManagement): Dosyaları hiyerarşik bir klasör yapısında yükleyin, indirin ve düzenleyin.
* [Forms](https://commercial.abp.io/modules/Volo.Forms): Kullanıcılarınız için formlar ve anketler oluşturun.
* [GDPR](https://commercial.abp.io/modules/Volo.Gdpr): Kullanıcıların, uygulama tarafından toplanan kişisel verilerini indirmelerine ve silmelerine izin verir.
* [Identity](https://commercial.abp.io/modules/Volo.Identity.Pro): Kullanıcı, rol, organizasyon birimi ve izin yönetimi.
* [Identity Server UI](https://commercial.abp.io/modules/Volo.Identityserver.Ui): İstemciler, API kaynakları, kimlik kaynakları, sırlar, uygulama URL'leri, talepler ve daha fazlası gibi kimlik sunucusu nesnelerini yönetme.
* [Language Management](https://commercial.abp.io/modules/Volo.LanguageManagement): Dilleri ekleyin veya kaldırın ve uygulama kullanıcı arabirimini anında yerelleştirin.
* [Payment](https://commercial.abp.io/modules/Volo.Payment): Çeşitli ödeme ağ geçitleri için entegrasyon sağlar.
* [SaaS](https://commercial.abp.io/modules/Volo.Saas): Multi-tenant / SaaS uygulamanızı oluşturmak için kiracıları, sürümleri ve özellikleri yönetin.
* [Text Template Management](https://commercial.abp.io/modules/Volo.TextTemplateManagement): UI üzerinden metin/e-posta şablonlarını düzenleyin.
* [Twilio SMS](https://commercial.abp.io/modules/Volo.Abp.Sms.Twilio): Twilio Cloud hizmeti üzerinden SMS gönderir.

## Araçlar

* [ABP CLI](https://docs.abp.io/en/abp/latest/CLI): ABP Framework için resmi CLI.
* [ABP Suite](https://commercial.abp.io/tools/suite): Tam katmanlı CRUD sayfalarını otomatik olarak oluşturmak, uygulama modüllerinin kaynağını yüklemek ve indirmek için kullanılan bir araçtır. Bu araç, [ABP Commercial'ın](https://commercial.abp.io/) bir parçasıdır.

## NuGet / NPM Paketleri

* [Tüm resmi NuGet ve NPM paketleri](https://abp.io/packages)

## Video Eğitimler

ABP ve .NET ile ilgili en son video gönderileri için **[community.abp.io](https://community.abp.io/)** web sitesini ziyaret edin. Bu websitesinde, ilgili websitesinde ve diğer kaynaklarda yayınlanan gönderileri görebilirsiniz.

### İngilizce

* [.NET Microservices with ABP - Full Series](https://community.abp.io/posts/.net-microservice-with-abp-full-series-m6opqjb1)

### İngilizce Dışındaki Eğitimler

#### Türkçe (Turkish)

* [ABP & Blazor ile kapsamlı bir eğitim seti](https://www.udemy.com/course/web-tabanli-on-muhasebe-1-5/) (Udemy, toplam 100 saat)
* [ABP Framework Eğitim Serisi](https://www.youtube.com/watch?v=JvwPpSTEAvg&list=PLBEMB-Eql15s3kaMvQ6pIobVk492a7s9j&index=1)  (YouTube, ücretsiz)