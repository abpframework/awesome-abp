[English](README.md)｜[简体中文](README.zh-Hans.md) | Türkçe

# Awesome ABP!

[ABP](https://github.com/abpframework/abp) ile ilgili kaynakların kategorize edilmiş bir listesi.

## İçindekiler

- [Resmi Bağlantılar](#resmi-bağlantılar)
- [Diğer Listeler](#diğer-listeler)
- [Öğreticiler / Makaleler](#öğreticiler--makaleler)
- [Etkinlikler](#etkinlikler)
- [UI Frameworkleri](#ui-frameworkleri)
- [Temalar](#temalar)
- [Uygulama Modülleri](#uygulama-modülleri)
- [Araçlar](#araçlar)
- [NuGet / NPM Paketleri](#nuget--npm-paketleri)
- [Video Eğitimler](#video-eğitimler)

## Resmi Bağlantılar

### Resmi web-siteleri

* **[abp.io](https://abp.io/)** (ABP Platform'u için anasayfa - ücretli başlangıç şablonları, özellikleri, modülleri, araçları ve desteği içerir -)
* **[abp.io/docs](https://abp.io/docs/latest/)** (dökümantasyon)
* **[abp.io/community](https://abp.io/community/)** (ABP ve .NET ile ilgili gönderiler ve etkinlikler)
* **[abp.io/blog](https://abp.io/blog/)** (en son haberler ve sürümler için resmi blog)

### Diğer resmi bağlantılar

* [**twitter**.com/abpframework](https://twitter.com/abpframework)
* [**discord**.gg/abp](https://discord.gg/abp)
* [**stackoverflow**.com/questions/tagged/abp](https://stackoverflow.com/questions/tagged/abp)
* [**github**.com/abpframework](https://github.com/abpframework)

## Diğer Listeler

* [Awesome ABP](https://github.com/EasyAbp/awesome-abp) (EasyAbp Topluluğu tarafından): ABP ile ilgili kaynakların listelendiği bir repository.

## Öğreticiler / Makaleler

### Resmi Öğreticiler

* [Başlarken](https://abp.io/docs/latest/get-started/layered-web-application): ABP ile bir uygulama oluşturun ve geliştirmeye başlayın.
* [Hızlı Başlangıç](https://abp.io/docs/latest/tutorials/todo): ABP kullanmaya başlayın ve basit bir TODO uygulaması oluşturun.
* [Web Uygulama Geliştirme](https://abp.io/docs/latest/tutorials/book-store/part-01): Tam özellikli bir web uygulaması oluşturmak için 10 bölümlük bir eğitim serisi.
* [Modüler CRM Uygulaması](https://abp.io/docs/latest/tutorials/modular-crm): ABP ile modüler bir CRM uygulaması oluşturun.
* [Microservice Çözümü](https://abp.io/docs/latest/tutorials/microservice): ABP microservice çözümü oluşturmayı ve çalıştırmayı öğrenin.
* [Mobil Uygulama Geliştirme](https://abp.io/docs/latest/tutorials/mobile): ABP ile mobil uygulamalar geliştirin.

### Topluluk Gönderileri

ABP takımı ve ABP topluluğu tarafından yayınlanan en son makaleleri görmek için [abp.io/community/articles](https://abp.io/community/articles) adresini ziyaret edin.

## Etkinlikler

ABP ekibi tarafından düzenlenen çevrimiçi etkinlikler, demolar ve soruc-cevap oturumları için aşağıdaki listeye göz atabilirsiniz:

* [ABP Community Talks](https://www.youtube.com/playlist?list=PLsNclT2aHJcOsPustEkzG6DywiO8eh0lB)
* [ABP .NET Conference 2023](https://www.youtube.com/playlist?list=PLsNclT2aHJcPTA3D4fIF10fsbhbckEbBC)
* [ABP Dotnet Conference 2024](https://www.youtube.com/playlist?list=PLsNclT2aHJcNbSrRbO4K36Pm0Pa8MDC-A)

> ABP'deki yeniliklerden haberdar olmak için [YouTube kanalımıza](https://www.youtube.com/c/Volosoft) abone olmayı unutmayın!

## UI Frameworkleri

> ABP, web ve mobil uygulamalar için birden fazla resmi UI seçeneğini destekler. React en yeni eklenen UI seçeneğidir ve ABP Studio v3.0+ Modern Wizard veya `abp new --modern` ile modern template sistemi üzerinden kullanılabilir.

* [MVC / Razor Pages](https://abp.io/docs/latest/framework/ui/mvc-razor-pages/overall): Modüler navigation, theming, tag helper'lar, dynamic JavaScript proxy'ler ve UI customization gibi ABP özellikleriyle server-rendered ASP.NET Core UI.
* [Blazor](https://abp.io/docs/latest/framework/ui/blazor/overall): WebAssembly, Server, Blazor WebApp ve MAUI Blazor desteğine sahip .NET tabanlı SPA UI.
* [Angular](https://abp.io/docs/latest/framework/ui/angular/overview): ABP backend entegrasyonu, service proxy'ler, authorization, localization, theming ve customization özellikleri sunan TypeScript tabanlı SPA UI.
* [React](https://abp.io/docs/latest/framework/ui/react): Vite, React, TanStack Router, TanStack Query, shadcn/ui ve ABP Admin Console entegrasyonunu kullanan modern template UI.
* [React Native](https://abp.io/docs/latest/framework/ui/react-native/index?LanguageCode=en): ABP tabanlı backend'lerle entegre mobil başlangıç template'i.
* [MAUI](https://abp.io/docs/latest/framework/ui/maui/index): ABP tabanlı backend'lerle entegre .NET MAUI mobil template'i.

## Temalar

### Resmi Temalar

* [Basic Theme](https://abp.io/docs/latest/framework/ui/mvc-razor-pages/basic-theme): Bootstrap ile oluşturulmuş minimalist bir tema. Basic Theme üzerine kendi temanızı ve stilinizi oluşturabilirsiniz.
* [Lepton Theme](https://abp.io/docs/latest/ui-themes/lepton): Birden çok renk ve stil seçeneğine sahip profesyonel bir UI teması.
* [LeptonX Theme](https://x.leptontheme.com/): Modern, responsive ve esnek bir UI teması. Yeni uygulamalar için önerilen temadır. İki versiyonu vardı:
  * [LeptonX Lite](https://abp.io/docs/latest/ui-themes/lepton-x-lite/asp-net-core): Daha az özellik ve seçeneğe sahip ücretsiz sürüm.
  * [LeptonX](https://abp.io/docs/latest/ui-themes/lepton-x/mvc): Tüm özellikler ve seçeneklerle birlikte tam sürüm.

## Uygulama Modülleri

Bir uygulama modülü, genellikle kendi entityleri, servisleri, API'leri ve UI bileşenleri ile tam olarak uygulanmış bir uygulama/iş işlevselliği sağlar.

### Açık Kaynak / Ücretsiz Modüller

#### Resmi Açık Kaynak / Ücretsiz Modüller

Bu uygulama modülleri, ABP ekibi tarafından oluşturulur ve sürdülür.

* [Account](https://abp.io/docs/latest/Modules/Account): Hesap yönetimi için kullanıcı arabirimi sağlar ve kullanıcının uygulamada oturum açmasına/kayıt olmasına izin verir.
* [Audit Logging](https://abp.io/docs/latest/Modules/Audit-Logging): Denetim günlüklerini (audit-logs) bir veritabanında saklar.
* [Background Jobs](https://abp.io/docs/latest/Modules/Background-Jobs): Arka planda işlemler gerçekleştirirken, bunları veritabanında saklayın ve yönetin.
* [Blogging](https://abp.io/modules/Volo.Blogging): Kendi bloglarınızı oluşturun ve yönetin (Artık geliştirilmiyor, bunun yerine [CMS Kit modülünün](https://abp.io/docs/latest/Modules/Cms-Kit/Index) [blogging özelliğini](https://abp.io/docs/latest/Modules/Cms-Kit/Blogging) kullanın).
* [CMS Kit](https://abp.io/docs/latest/Modules/Cms-Kit/Index): Yeniden kullanılabilir *İçerik Yönetim Sistemi* özellikleri sağlar.
* [Docs](https://abp.io/docs/latest/Modules/Docs): Teknik dokümantasyon web sitesi oluşturmak için kullanılır. Şuan ABP'nin [kendi dökümanları](https://abp.io/docs) bu modülü kullanmaktadır. 
* [Feature Management](https://abp.io/docs/latest/Modules/Feature-Management): [Özellikleri](https://abp.io/docs/latest/framework/infrastructure/features) sürdürmek ve yönetmek için kullanılır.
* [Identity](https://abp.io/docs/latest/Modules/Identity): Organizasyon birimlerini, rolleri, kullanıcıları ve bunların izinlerini Microsoft Identity kütüphanesine dayanarak yönetir.
* [IdentityServer](https://abp.io/docs/latest/Modules/IdentityServer): IdentityServer4 ile entegre olur.
* [OpenIddict](https://abp.io/docs/latest/Modules/OpenIddict): OpenIddict ile entegre olur.
* [Permission Management](https://abp.io/docs/latest/Modules/Permission-Management): İzinleri sürdürmek için kullanılır.
* [Setting Management](https://abp.io/docs/latest/Modules/Setting-Management): [Ayarları](https://abp.io/docs/latest/framework/infrastructure/Settings) sürdürmek ve yönetmek için kullanılır.
* [Tenant Management](https://abp.io/docs/latest/Modules/Tenant-Management): [Multi-tenant](https://abp.io/docs/latest/framework/architecture/multi-tenancy) bir uygulamadaki tenantları yönetmeyi sağlar.

### Commercial Modüller

#### Resmi Commercial Modüller

* [Account](https://abp.io/modules/Volo.Account.Pro): Giriş, kayıt, şifremi unuttum, e-posta aktivasyonu, sosyal girişler ve hesapla ilgili diğer işlevleri sağlar.
* [Audit Logging](https://abp.io/modules/Volo.AuditLogging.Ui): Kullanıcı denetleme günlüklerinin ve varlık geçmişlerinin ayrıntılı olarak raporlanması.
* [Chat](https://abp.io/modules/Volo.Chat): Kullanıcılar arasında gerçek zamanlı mesajlaşma.
* [CMS Kit](https://abp.io/modules/Volo.CmsKit.Pro): Kendi *İçerik Yönetim Sisteminizi* oluşturmak için yardımcı olur.
* [File Management](https://abp.io/modules/Volo.FileManagement): Dosyaları hiyerarşik bir klasör yapısında yükleyin, indirin ve düzenleyin.
* [Forms](https://abp.io/modules/Volo.Forms): Kullanıcılarınız için formlar ve anketler oluşturun.
* [GDPR](https://abp.io/modules/Volo.Gdpr): Kullanıcıların, uygulama tarafından toplanan kişisel verilerini indirmelerine ve silmelerine izin verir.
* [Identity](https://abp.io/modules/Volo.Identity.Pro): Kullanıcı, rol, organizasyon birimi ve izin yönetimi.
* [Identity Server UI](https://abp.io/modules/Volo.Identityserver.Ui): İstemciler, API kaynakları, kimlik kaynakları, sırlar, uygulama URL'leri, talepler ve daha fazlası gibi kimlik sunucusu nesnelerini yönetme.
* [Language Management](https://abp.io/modules/Volo.LanguageManagement): Dilleri ekleyin veya kaldırın ve uygulama kullanıcı arabirimini anında yerelleştirin.
* [Payment](https://abp.io/modules/Volo.Payment): Çeşitli ödeme ağ geçitleri için entegrasyon sağlar.
* [SaaS](https://abp.io/modules/Volo.Saas): Multi-tenant / SaaS uygulamanızı oluşturmak için kiracıları, sürümleri ve özellikleri yönetin.
* [Text Template Management](https://abp.io/modules/Volo.TextTemplateManagement): UI üzerinden metin/e-posta şablonlarını düzenleyin.
* [Twilio SMS](https://abp.io/modules/Volo.Abp.Sms.Twilio): Twilio Cloud hizmeti üzerinden SMS gönderir.

## Araçlar

* [ABP CLI](https://abp.io/docs/latest/CLI): ABP için resmi CLI; `--modern` ile modern template oluşturmayı ve React UI desteğini içerir.
* [ABP Suite](https://abp.io/suite): Tam katmanlı CRUD sayfalarını otomatik olarak oluşturmak, uygulama modüllerinin kaynağını yüklemek ve indirmek için kullanılan bir araçtır. Bu aracı sadece aktif lisans sahipleri kullanabilir.
* [ABP Studio](https://abp.io/studio): ABP Studio, çözüm oluşturma, geliştirme, çalıştırma, izleme, Git/GitHub iş akışları, dağıtım yardımcıları ve ABP-aware içgörüleri tek bir geliştirme ortamında birleştiren cross-platform bir masaüstü uygulamasıdır.
  * [Modern Wizard / Modern Templates](https://abp.io/docs/latest/framework/ui/react): Vite, TanStack Router, TanStack Query, shadcn/ui, Tailwind CSS, Zod ve React Hook Form gibi popüler React-first teknolojilerle AI-assisted geliştirmeye uygun ABP çözümleri oluşturun; authentication, authorization, localization, multi-tenancy ve Admin Console gibi temel ABP kavramları ve modülleriyle hazır entegrasyonu koruyun.
  * [ABP Studio AI Coding Agent](https://abp.io/studio/ai-agent): ABP Studio içinde yer alan Ask, Plan ve Agent modlarına sahip ABP-aware kodlama ajanı. ABP solution yapısını anlar; solution analysis, scoped build'ler, run profile'lar, runtime monitoring, loglar, HTTP request'leri, distributed event'ler, custom workflow'lar ve Git/GitHub özellikleriyle ABP uygulamalarını geliştirme, debug etme ve review etme süreçlerine yardımcı olur.
* [AbpDevTools](https://github.com/enisn/AbpDevTools): ABP ile geliştirmeyi kolaylaştırmak için bir dizi araç içeren bir CLI uygulaması.

## NuGet / NPM Paketleri

* [Tüm resmi NuGet ve NPM paketleri](https://abp.io/packages)

## Video Eğitimler

ABP ve .NET ile ilgili en son video gönderileri için **[abp.io/community](https://abp.io/community/)** web sitesini ziyaret edin. Bu websitesinde, ilgili websitesinde ve diğer kaynaklarda yayınlanan gönderileri görebilirsiniz.

### İngilizce

* [.NET Microservices with ABP - Full Series](https://abp.io/community/videos/.net-microservice-with-abp-full-series-m6opqjb1)

### İngilizce Dışındaki Eğitimler

#### Türkçe (Turkish)

* [ABP & Blazor ile kapsamlı bir eğitim seti](https://www.udemy.com/course/web-tabanli-on-muhasebe-1-5/) (Udemy, toplam 100 saat)
* [ABP Framework Eğitim Serisi](https://www.youtube.com/watch?v=JvwPpSTEAvg&list=PLBEMB-Eql15s3kaMvQ6pIobVk492a7s9j&index=1)  (YouTube, ücretsiz)