# TCRT5000-sensor-kullanarak-Labview-ile-alarm-haberlesme-sistemi-projesi

## Marmara Üniversitesi Ölçme ve Enstrümantasyon Dersi TCRT5000 IR sensörü LabView Dönem Projesi

### Projenin Amacı:
Projede daha önce stajımda projelerde kullanmış olduğum sensörlerden biri olan TCRT5000 IR sensörünü seçtim. Daha önce stajımda bir Amerikalı reklam şirketi için projenin prototipinde kullanmış olduğum bu sensörü o projede avm vb topluma açık olarak kullanılan musluklara ekran eklenerek IR sensörü sayesinde hareketliliği tespit edip ekran üzerinde reklamı oynatmaya başlatmaktaydı. Dönem projem olarak LabView programında hazırlamış olduğum projede TCRT5000 sensörünün analog çıkışı Arduinonun A0 pinine, dijital çıkışı 2. pinine bağlanmıştır ve alınan datalar seri haberleşme ile LabView programına akatarılmıştır. Labview programında tasarlanan proje sensörün dijital çıkışından gelen dataya göre hareket tespit işlemini ve bunun ne kadar tespit edildiğini front panelde bize göstermektedir. Dijital çıkışdan gelen dataya göre her tespit işleminde programda belirtilen mail adresine haber göndermektedir. Analog çıkışı ile tespitin ne kadar yakın mesafede olduğu yani sensörün önündeki hareketliliğin yakınlık seviyesini front panelde bulunan grafikteki voltaj değişimi ile bize göstermektedir. Ayrıca Front panel üzerinde bulunan seri haberleşmenin yapılacağı portu kullanıcının belirleyebileceği, sensör pinlerinin hangi pinlere bağlandığını yine kullanıcının front panel üzerinde ayarlayabileceği bir tasarım gerçekleştirilmiştir. Bu proje alarm sistemi olarak, bir işletmeye kaç kişi girmiş hesaplama veya bir yerdeki hareketliliğin bildirimi gibi gündelik hayatta kullanılabilir. Alarm sistemi olarak evimize habersiz giren kişi veya hareketliliğin tespiti için kapının üzerine yerleştirilen sensör kapı açılış hareketi veya kapı önünde gerçekleşen hareket tespiti sonucunda sistemde bildirilen mail adresine giden mail ile kulanıcı bilgilendirilebilir. Bir işletmeye giren müşteri sayısı tespitinde yine aynı şekilde kapıya yerleştirilen sistem sayesinde giren müşteri sayısındaki datayı sistem üzerinde ve mail ile kayıt edebilmektedir.

### Kullanılan Malzemeler:
- Arduino UNO
- TCRT5000
- LabView
- Jumper kablolar

### TCRT5000 Sensörü:
Temel olarak bir kontrast sensörü olan TCRT5000 Kızılötesi Yansıma Sensör Modülü - Optik Sensör bir kızılötesi LED ve foto dirençten oluşur. Herhangi bir yüzeye kızılötesi ışık yansıtıp geri yansıyan ışın parlaklığı ölçülerek çalışan bu sensör ölçümleri foto direnç üzerinden yapar. Devre haline getirilen bu sensör ile dijital ve analog çıkış alabilirsiniz. Çizgi izleyen robotlarda, mini sumo, sumo ve çeşitli birçok robotta kolayca kullanılabilinir. Dijital çıkış kullanmanız durumunda üzerinde bulunan potansiyometre ile kalibrasyon yapmanız mümkündür.

