# Simple-To-do-Project
## Bu kod, Motoko dilinde yazılmış bir akıllı sözleşme örneğini içerir. 
### Akıllı sözleşme, blok zinciri tabanlı bir uygulamada özerk olarak çalışabilen ve belirli koşullar altında işlemleri gerçekleştirebilen bir program parçasıdır.

Bu örnekte, "Telefon_Defterim" adında bir aktör (actor) tanımlanır. Aktörler, Motoko dilinde eşzamanlı işlemleri yönetmek ve paralel hesaplamalar gerçekleştirmek için kullanılan bir yapıdır.

Bu aktör, bir telefon defteri uygulamasını temsil eder. Telefon defterindeki her giriş, kişinin adı ve telefon numarası ile ilişkilendirilmiş bir açıklamadan oluşan bir yapı içinde tutulur. 

Bu kodun işlevleri şunlardır:

1. `insert` fonksiyonu: Bir kişinin adı ve telefon numarası ile rehberde bir giriş ekler. `name` parametresi, kişinin adını, `entry` parametresi ise kişinin telefon numarasını ve açıklamasını içeren bir veri yapısını temsil eder.

2. `lookup` fonksiyonu: Bir kişinin adını alır ve bu kişinin rehberdeki girişini bulur. Bu fonksiyon, rehberdeki bir girişi sorgulamak için kullanılır. Eğer kişinin adı rehberde bulunursa, ilgili girişin bilgilerini döndürür. Eğer kişi rehberde bulunmazsa, null değeri döndürür.

Bu kod, blok zinciri tabanlı bir uygulamada bir telefon defteri işlevselliğini sağlamak için kullanılabilir. Örneğin, bir kişinin telefon numarasını aramak veya yeni bir kişi eklemek gibi işlemleri gerçekleştirmek için kullanılabilir.
