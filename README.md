# Ödev 3 A) AWS Crud

kullanılan paketleri yüklemek için
```
npm install
```
projeyi ayağa kaldırmak için aşağıdakilerden her hangi birini kullanabilirsiniz.
```
npx nodemon index
```

# Ödev 3 B)

## SQL ve NoSQL Arasındaki Fark

| SQL             | NoSQL                                                                |
| ----------------- | ------------------------------------------------------------------ |
|SQL veritabanları dikey olarak ölçeklenebilir. Tek bir sunucu üzerinde donanım kapasitesini (CPU, RAM, SSD vb.) Artırarak ölçeklenebilirler.|NoSQL veritabanları yatay olarak ölçeklenebilir. Büyük yükü yönetmek ve yığını azaltmak için altyapıya daha fazla sunucu eklenerek ölçeklenebilirler.|
|SQL veritabanları esas olarak ilişkisel veritabanıdır (RDBMS).|NoSQL veritabanları esas olarak ilişkisel olmayan veya dağıtılmış veritabanlarıdır.|
|Eski bir teknoloji.|Nispeten genç teknoloji.|
|SQL veritabanları satır ve sütunlar biçiminde tablo tabanlıdır ve standart şema tanımlarına kesinlikle uymalıdır.Çok sıralı işlemlere ihtiyaç duyan uygulamalar için daha iyi bir seçenektir.|NoSQL veritabanları belgelere, anahtar / değer çiftlerine, grafiklere veya sütunlara dayalı olabilir ve standart şema tanımlarına bağlı kalmaları gerekmez.|
|Yapılandırılmış veriler için iyi tasarlanmış önceden tanımlanmış bir şemaya sahiptirler.|Yapılandırılmamış veriler için dinamik şemaya sahiptirler. Veriler, önceden tanımlanmış bir yapıya sahip olmadan esnek bir şekilde saklanabilir.|
|SQL veritabanları normalleştirilmiş şemayı destekler.|NoSQL veritabanları, normalleştirilmiş şemayı tercih eder.|
|Ölçeklendirme maliyeti yüksektir.|İlişkisel veritabanlarına kıyasla ölçeklendirmek daha ucuzdur.|
|SQL, sorguları işlemek için standart bir arayüze sahip olduğundan karmaşık sorgular için iyi bir seçimdir.SQL sorgularının sözdizimi düzeltildi.|NoSQL'de sorguları işlemek için standart bir arayüz olmadığından karmaşık sorgular için uygun değildir.NoSQL'deki sorgular SQL sorguları kadar güçlü değildir.UnQL olarak adlandırılır ve Yapılandırılmamış sorgu dilini kullanma sözdizimi sözdiziminden sözdizimine değişiklik gösterir.|
|SQL veritabanları hiyerarşik veri depolamaya pek uygun değildir.|NoSQL veritabanları, verileri depolamak için anahtar-değer çifti yöntemini izlediği için hiyerarşik veri depolamaya en uygun olanıdır.|
|Ticari açıdan bakıldığında, SQL veritabanları genellikle açık kaynak veya kapalı kaynak olarak sınıflandırılır.|Anahtar-değer deposu, belge deposu, grafik deposu, sütun deposu ve XML deposu olarak verileri saklama şekillerine göre sınıflandırılırlar.|
|SQL veritabanları, ACID özelliklerini (Atomiklik, Tutarlılık, İzolasyon ve Dayanıklılık) doğru şekilde takip eder.|NoSQL veritabanları, Brewers CAP teoremini (Tutarlılık, Kullanılabilirlik ve Bölme toleransı) doğru şekilde takip eder.|
|SQL veritabanına yeni veri eklemek, verileri doldurmak, şemaları değiştirmek gibi bazı değişikliklerin yapılmasını gerektirir.|Yeni veriler, önceden herhangi bir adım gerektirmediğinden, NoSQL veritabanlarına kolayca eklenebilir.|
|Tüm SQL veritabanları için mükemmel satıcı desteği ve topluluk desteği mevcuttur.|NoSQL veritabanları için yalnızca sınırlı topluluk desteği mevcuttur.|
|Yüksek işlem tabanlı uygulamalar için en uygun çözüm.|NoSQL'i yoğun işlem amaçlı kullanabilirsiniz. Ancak bunun için en uygun seçenek değil.|
|Hiyerarşik veri depolamaya uygun değildir.|Hiyerarşik veri depolamak ve büyük veri kümelerini depolamak için uygundur (Örn.Büyük Veri).|
|SQL veritabanları örneği: MySQL, Oracle, MS-SQL, SQLite.|NoSQL veritabanı örnekleri: MongoDB, Apache CouchDB, Redis, HBase.|

## Kaynak
https://tr.myservername.com/sql-vs-nosql-exact-differences
