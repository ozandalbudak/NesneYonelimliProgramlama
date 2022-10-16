OOP C# Eğitimi ve örnekler
Nesne yönelimli programlama (OOP), alanlar (genellikle nitelikler veya özellikler olarak bilinir) biçiminde veri ve prosedürler biçiminde (genellikle bilinen) kod içerebilen "nesneler" kavramına dayanan bir programlama paradigmasıdır. yöntemler olarak). Nesnelerin bir özelliği, ilişkili oldukları nesnenin veri alanlarına erişebilen ve genellikle bunları değiştirebilen bir nesnenin prosedürleridir (nesnelerin "bu" veya "kendi" kavramı vardır). OOP'de bilgisayar programları, birbirleriyle etkileşime giren nesnelerden oluşturularak tasarlanır. OOP dilleri çeşitlidir, ancak en popüler olanları sınıf tabanlıdır, yani nesneler, türlerini de belirleyen sınıf örnekleridir.

Tanımlar
Sınıf
Sınıf, nesneler (belirli bir veri yapısı), durum (üye değişkenler veya nitelikler) için başlangıç ​​değerleri ve davranış uygulamaları (üye işlevler veya yöntemler) oluşturmak için bir plandır. Kullanıcı tanımlı nesneler, class anahtar sözcüğü kullanılarak oluşturulur. Sınıf, gelecekteki bir nesnenin doğasını tanımlayan bir plandır. Örnek, belirli bir sınıftan oluşturulan belirli bir nesnedir. Sınıflar, yeni nesneler oluşturmak ve yönetmek ve nesne yönelimli programlamada önemli bir bileşen ve kodu yeniden kullanma mekanizması olan kalıtımı desteklemek için kullanılır.

soyut sınıf
Bir Soyut sınıfın hiçbir zaman doğrudan somutlaştırılması amaçlanmamıştır. Bu sınıf, sınıf tanımında anahtar sözcük veya değiştirici özet ile işaretlenmiş en az bir soyut yöntem içermelidir. Soyut sınıflar tipik olarak sınıf hiyerarşisinde bir temel sınıf tanımlamak için kullanılır. Genellikle, kalıtım sırasında soyut sınıf kullanırız. Bir kullanıcı, alt sınıfta soyut olarak bildirilen yöntemden önce override anahtar sözcüğünü kullanmalıdır, soyut sınıf, alt sınıfta miras almak için kullanılır.

Soyut bir sınıf yapılar tarafından miras alınamaz.
Yapıcılar veya yıkıcılar içerebilir.
Soyut olmayan yöntemlerle işlevleri gerçekleştirebilir.
Çoklu kalıtımı destekleyemez.
Statik olamaz.
Arayüzler
Bir arabirim, bir sınıfın veya yapının uygulayabileceği bir grup ilgili işlevsellik için tanımları içerir. Arabirimleri kullanarak, örneğin, bir sınıfa birden çok kaynaktan gelen davranışı dahil edebilirsiniz. Bu yetenek, C#'ta önemlidir çünkü dil, sınıfların çoklu mirasını desteklemez. Ek olarak, yapılar için kalıtımı simüle etmek istiyorsanız bir arabirim kullanmanız gerekir, çünkü bunlar aslında başka bir yapı veya sınıftan miras alamazlar.

Miras
Nesne yönelimli programlamanın temel özelliklerinden biridir. Bir üst sınıfın davranışını yeniden kullanan (miras alan), genişleten veya değiştiren bir alt sınıf tanımlamanıza olanak tanır. Üyeleri miras alınan sınıfa temel sınıf denir. Temel sınıfın üyelerini miras alan sınıfa türetilmiş sınıf denir.

polimorfizm
Polimorfizm, birden fazla form alma yeteneği sağlamak anlamına gelir ve kapsülleme ve kalıtımdan sonra nesne yönelimli programlamanın temel dayanaklarından biridir. Genel olarak, polimorfizm, biri poli, diğeri morf olmak üzere iki kelimenin birleşimidir. Burada poli "çoklu" anlamına gelir ve morflar "biçimler" anlamına gelir, dolayısıyla polimorfizm birçok biçim anlamına gelir. Polimorfizm, sınıflara aynı adla çağrılan farklı yöntemleri uygulama yeteneği sağlar ve aynı zamanda gereksinimlerimize göre çalışma zamanı sırasında temel sınıf referansı aracılığıyla türetilmiş sınıf yöntemlerini çağırma yeteneği sağlar.

kapsülleme
'Fiziksel veya mantıksal bir paket içine bir veya daha fazla öğeyi kapatma süreci' olarak tanımlanır. Kapsülleme, nesne yönelimli programlama metodolojisinde, uygulama detaylarına erişimi engeller. Soyutlama ve kapsülleme, nesne yönelimli programlamada ilgili özelliklerdir. Soyutlama, ilgili bilgilerin görünür olmasına izin verir ve kapsülleme, bir programcının istenen soyutlama seviyesini uygulamasını sağlar.

Genel Erişim Belirteci
Bir sınıfın, üye değişkenlerini ve üye işlevlerini diğer işlevlere ve nesnelere göstermesine izin verir. Herhangi bir genel üyeye sınıf dışından erişilebilir.

Özel Erişim Belirteci
Bir sınıfın üye değişkenlerini ve üye işlevlerini diğer işlevlerden ve nesnelerden gizlemesine izin verir. Yalnızca aynı sınıfın işlevleri, özel üyelerine erişebilir. Bir sınıfın bir örneği bile onun özel üyelerine erişemez.

Korumalı Erişim Belirteci
Bir alt sınıfın, temel sınıfının üye değişkenlerine ve üye işlevlerine erişmesine izin verir. Bu şekilde mirasın uygulanmasına yardımcı olur.

Soyutlama
Veri Soyutlama, kullanıcıya yalnızca temel ayrıntıların gösterildiği özelliktir. Önemsiz veya gerekli olmayan birimler kullanıcıya gösterilmez. Veri Soyutlama, bir nesnenin sadece gerekli olan özelliklerini, alakasız detayları göz ardı ederek tanımlama süreci olarak da tanımlanabilir. Bir nesnenin özellikleri ve davranışları, onu benzer türdeki diğer nesnelerden ayırır ve ayrıca nesnelerin sınıflandırılmasına/gruplandırılmasına yardımcı olur.
