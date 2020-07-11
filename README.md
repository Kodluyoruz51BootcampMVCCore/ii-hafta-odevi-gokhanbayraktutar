# II Hafta (6-7 Haziran) Ödevleri 

## 6 Haziran Ödevleri:
- [ ] Github'ın Gitflow'u ile diğer yaklaşımları arasındaki fark nedir? ( gitflow vs ..)
- [ ] [Git and GitHub with Briana Swift](https://www.youtube.com/playlist?list=PLg7s6cbtAD17Gw5u8644bgKhgRLiJXdX4) Youtube Listesi incelensin. (11 Video)
- [ ] Merge pull request
    - [ ] Create a merge commit
    - [ ] Squash and merge 
    - [ ] Rebase and merge altında ne fark var (Ödev)
- [ ] issue ve #pull request de id ler neden artıyor farklı sekmeler olmasına rağmen?
- [ ] [Ramp up on Git and GitHub](https://lab.github.com/githubtraining/paths/ramp-up-on-git-and-github) (ödev)
- [ ] Aspnetboilerplate ve yan ürünler araştırması. [AspNet Boilerplate - Web Application Framework](https://aspnetboilerplate.com/)
- [ ] hackerRank.com --> [30 Days Of Code](https://www.hackerrank.com/domains/tutorials/30-days-of-code)

## 7 Haziran Ödevleri:
- [ ] Razor Pages Nedir?
- [ ] 4 Farklı Projede Yapılacak *Change Authentication* :
  - [ ] No Authentication
  - [ ] Individual User Account
  - [ ] Work or School Accounts
  - [ ] Windows Authentication seçili projeler oluşturulmalı
- [ ] Ayarlardaki Output kısmındaki Console Application nedir? diğerleri arasında fark nedir? [Ders Akışındaki 6. Madde'yi inceleyin.] ( araştırma ödev verildi ).
- [ ] c# json serialize / deserialize
- [ ] MVC vs MVVM
   - [ ] MVP vs MVW vs MVU Pattern arasındaki farkı araştır
   - [ ] Model-View-Update (MVU) nedir?
   
 
 
 
 
   ## 6 Haziran Ödevleri:
- [ ] Github'ın Gitflow'u ile diğer yaklaşımları arasındaki fark nedir? ( gitflow vs ..)


 **Gitflow (Branch modeli)

Temelde yazılım geliştirme yaşam döngüsü boyunca bir repositorye iki ana branch ile çalışılır. Bunlar Master ve Developer branchleridir.
 
Master branch (ana branch), genellikle projenin yayınlanmaya hazır haldeki kısımlarını tutar.
 Developer branch ise, geliştirme evresinde olan ve yeni sürümde yayınlanacak olan projenin son halinin kaynak kodlarını barındırır.
 Developer branchinde her şey yolunda gidiyorsa ve proje testlerden geçmişse master branchi ile birleştirilir. Bu birleştirme işlemleri _merge etmek_ olarak anılır.

Master ve Developer branch haricinde kullanılan paralel branchler de mevcuttur. Bunlardan biri Feature branchtir.
 
Feature Branch: Bir proje için oluşturduğunuz her task (proje için oluşturulmuş görev) ve bu tasklarda geliştirmeyi planladığınız her feature için ayrı bir feature branch açabilirsiniz.
 Feature branchleri, developer branchinin altında olmak zorundadır.
 Proje ekibinden herkes farklı feature branchlerinde çalışabilir. Ancak geliştirmenin sonunda feature branchlerin her biri developer branchine merge edilmelidir.


Feature branchleri ile çalışmanın en büyük avantajı, o branchte çalışılan özelliğin fail etmesi, bekleneni vermemesi durumunda masterın developerın ve diğer feature branchlerinin hiç bir şekilde etkilenmemiş olmasıdır.

Akılda kalıcılığını arttırmak amacıyla ufak bir senaryo oluşturalım; Ayşe ismindeki geliştirici bir e-ticaret sitesinin ödeme sayfasındaki, kartlı ödeme alanını geliştiriyor olsun. Bu feature in adı, _K123 Kartli Odeme Secenegi_ şeklinde olsun.

Ayşe, _K123 Kartli Odeme Secenegi_ isminde bir feature branch oluşturur. İlgili geliştirmeyi gerçekleştirir. Bu geliştirmenin çalıştığından emin olduktan sonra developer branchine gönderir. Developer branchindeki tüm geliştirmeler yeniden test edildikten ve emin olunduktan sonra master branchine mergelenir.

Diğer paralel branchlerin isimleri ise Release branchler, Hotfix branchlerdir.

Release Branch:  Yeni bir versiyon güncelleme yapacağınız zaman versiyonadki son değişiklikler bu brach üzerinden yapılır, sürüm numarası bu brachte güncellenir ve değişiklikler bittiğinde hem developer hem de master branchlerine merge edilir. Ardından release branchi silinir.

Hotfix Branch: Yayınladığınız yeni versiyonda önemli bir hata keşfettiniz ve bu hatanın acilen çözülmesi gerekiyor. Bu gibi durumlarda bir hotfix branch açılır. Ardından hata bu branchte giderilir ve developer ile master branchlerine merge edilir. Daha sonra hotfix branchi silinir.


- [ ] [Git and GitHub with Briana Swift](https://www.youtube.com/playlist?list=PLg7s6cbtAD17Gw5u8644bgKhgRLiJXdX4) Youtube Listesi incelensin. (11 Video) ---İncelendi.
 
- [ ] Merge pull request
    - [ ] Create a merge commit
    - [ ] Squash and merge 
    - [ ] Rebase and merge altında ne fark var (Ödev)

**Merge etmek:** Merging en basit anlamda herhangi bir brachde yaptığımız değişiklikleri master branchimiz ile birleştirme veya master branche entegre etme işlemidir.

**Merge Commit:** Tüm commitleri feature branchin geçmişinde (history) tutar ve master branchin içerisine taşır.son işlemde ekstra commit ekleyecektir.

**Squash and Merge:** Feature Brachin tüm commitlerini tek bir committe gruplandıracak sonra ana dalın önüne ekleyecektir.Son işlemde ekstra commit ekleyecektir.

**Rebase and Merge:** Feature brachin geçmişinde ki (history) tüm commitleri master branchin önüne ekler.Son işlemde ekstra commit eklenmez.


[**Ramp up on Git and GitHub**](https://lab.github.com/githubtraining/paths/ramp-up-on-git-and-github) **: Çalışmaya başlandı.**

**Aspnetboilerplate ve yan ürünler araştırması. ** [**AspNet Boilerplate - Web Application Framework**](https://aspnetboilerplate.com/)

**hackerRank.com  ** [**30 Days Of Code**](https://www.hackerrank.com/domains/tutorials/30-days-of-code) **: Başlandı.**

## 7 Haziran Ödevleri:
- [ ] Razor Pages Nedir?

**Razor Pages**

Razor Pages, WebForms gibi hızlı ve kolay uygulama geliştirmek için kullanılan yeni bir web uygulama geliştirme yöntemidir. Razor Pages işlemler yapmak için Model yapısını kullanır. Model yapısını kullanmak için @model ile razor sayfasına dahil edilir. Bu model genellikle razor sayfası ile aynı ada sahip.cshtml.cs dosyalarında yer alır. Model içerisine eklenen özellikler daha sonra razor sayfalarında kullanılabilir. İsteklerin yönetimi;

- Sayfaya yapılan istekleri (GET, POST) yönetmek için handler yapısı kullanılır.
 Örneğin GET istekleri için OnGet veya OnGetAsync metodu çalışır. Diğer istekler için de aynı şekilde çağrılmaktadır.

Örnek için;

([https://medium.com/abisteknoloji/net-frameworkten-net-core-a-g%C3%B6%C3%A7-abe9c76e450](https://medium.com/abisteknoloji/net-frameworkten-net-core-a-g%C3%B6%C3%A7-abe9c76e450))


- [ ] c# json serialize / deserialize

**Serialization:** Bir nesnenin saklanacak / transfer edilecek forma dönüştürülme işlemidir. Serileşmenin tersi olarak Deserialization ifadesi kullanılır ve bu da Streamin (Akış) nesne modeline dönüştürülme işlemidir.

Net Framework içerisinde bulunan System.Runtime.Serialization namespacei bu işlemler için kullanılmaktadır. İçerisinde bulunan sınıflar ve araçlar sayesinde, kendi nesnelerimizi istenilen/ihtiyaç duyulan formatta saklama imkanı sunar.

Serialization bize iki temel metot sunar;

XML eXtensiple Markup Language ve SOAP Simple Object Access Protokol

**Serileştirme işlemleri**

**Binar Serialization:** Tür bağımlılığı açısından önemlidir. İkili serileştirme işlemi, daha çok birbirinden bağımsız iki uygulama arasında, nesne modellerini taşımak için kullanılır. İkili serileştirme işlemi; bir nesnenin durumunun saklama ortamına uygun hale getirilip yazılması süreci olarak tanımlanabilir. İşlem süresince, nesnenin public ve private öğeleri, sınıfın adı, sınıfı barındıran Assembly nin adı saklama ortamına yazılmak üzere byte lar akışına çevirilir. Nesne, Deserialize edildiğinde ise nesnenin tam bir kopyası oluşturulur ve kullanıma sunulur. Binary serialization ile .Net Remoting kullanarak farklı domain içinde bulunan bir bilgisayardaki uygulamalara bile taşınabilir. Bazen Binary Serialization ile bir nesneyi serialize etmek, sürücüde gereğinden çok fazla yer işgal etmeye neden olabilir, çünkü nesnemiz kendi ve içinde bulunan her yapı ve nesne için sürücüde binary header ile fazladan yer işgal eder. Hatta eğer nesnelerden oluşmuş bir array veya collection (IList, ObservableCollection vb.) varsa bunun içinde bulunan her nesne içinde (foreach) bir binary header (o classın yapısı) dosyamıza eklenerek dosyanın boyutunu şişirebilir.

XML ve SOAP Serileştirme: Tür esnekliği ile ön plana çıkan bu yapı, çok sık tercih edilmektedir. XML Serileştirme işleminde sadece ortak tipler ve metotlar serileştirilebilir. Bu yapıda verilerinizi kullanacak olan uygulamayı kısıtlamadan saklayabiliriz. XML ve SOAP açık bir standart yapı olduğundan, aynı zaman da her türlü uygulama ile rahatlıkla okunabildiğinden veri paylaşımı oldukça hızlıdır.

([http://www.cihanozhan.com/csharp-ile-binary-serialization/](http://www.cihanozhan.com/csharp-ile-binary-serialization/))

- [ ] MVC vs MVVM
   - [ ] MVP vs MVW vs MVU Pattern arasındaki farkı araştır
   - [ ] Model-View-Update (MVU) nedir?
   
   **MVC (MODEL-VİEW-CONTROLLER)**

**1-Model: ** Model, proje içerisinde kullanılacak olan nesnelerin oluşturulduğu kısımdır. Günlük hayattaki somut nesnelerin, bilgisayar ortamında modellenmesi anlamına gelir. Örneğin bir kütüphane otomasyonu yapmak istediğimizde kitap bilgilerinin tutulacağı bir modele ihtiyaç duyulacaktır. Bu modelde kitabın seri numarası, adı, yazarı, yayınevi gibi bilgileri yer alacaktır.

**2-View:**  Proje tamamlandığında kullanıcının gördüğü arayüzdür. Bu bir web sayfası, masaüstü uygulaması arayüzü veya mobil bir tasarım olabilir. Projenin yapısına göre bu tasarım farklı şekillerde oluşturulabilir.

**3-Controller:**  Projedeki tüm işlemlerin (veritabanı işlemleri, hesaplamalar, veri aktarımı vb.) yapıldığı kontrol bölümüdür. Controller ayrıca model ve view arasındaki veri akışını da kontrol eder.

**MVVM (Model – View – View Model**)kalıbı modern bir kalıptır. Yapısal olarak [**MVC**  ](https://kenanatmaca.com/mvc-pattern/)yapısına benzemektedir. Model ile View arasında bulunan View Model ikili arasında köprü görevi görür. Bu modelde View içerisinde Model yapısı ile bağlantı kurulmaz. Tüm işlem View Model aracılığı ile gerçekleştirilir.

Bunun gibi yapılar eski tasarım kalıplarında görülen ihtiyaç ve eksiklikler sonucu tasarlanmıştır. Halen günümüzde yazılımın ve teknolojinin gelişimine bağlı olarak yeni tasarım kalıpları ortaya çıkmaktadır.

**View:** Uygulamanın tüm tasarım olaylarının bulunduğu taraftır. (UIViewController içerisinde yazdığınız elementlere eriştiğiniz durum)

**Model:**  Modellenen verinin bulunduğu, fetch işlemlerinin yapıldığı bölüm (MVCdeki Model ile aynı işlev)

**View Model** : View ile Model arasındaki iletişimi sağlar. View Model yapısı Viewe erişemez ancak View VMe erişebilir. Aynı mantıkla VM Model yapısına erişebilir ancak Model VM yapısına erişemez.

**MVP (Model View Presenter)**

**Model:** Presenterın ihtiyaç duyduğu bilgileri sağlar. İş mantığı bu kısımda ele alınır. View: Verilerin görüntülendiği ve işlem yapmak için kullanıcı ile etkileşime geçilen kısımdır. **Presenter** : Model ile View arasındaki bağlantıyı sağlayan kısımdır. Verileri modelden alır ve UI mantığını uygular.

MVP kendi arasında Supervising Controller ve Passive View diye ikiye ayrılıyor

**MVW(Model-View-Whatever)**

Burada W(Whatever) herhangi bir şey(C-Controller, VM-ViewModel ya da P-Presenter) olabilir.

**Model-View-Update (MVU) nedir?**

Modeldeki tüm değişiklikler, View tarafından gönderilen mesajları alan ve değişiklikleri buna göre uygulayan saf bir Update işlevi tarafından uygulanır.


