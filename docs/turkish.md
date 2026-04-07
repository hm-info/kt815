# KT815 Manual

 Otomatik ispanyolet vidalama makinesi.

 İlk proje, ASAŞ 34158  

 Ağdan JSon dosya çekerek çalışıyor. 

## Monitoring Process Page
<img src="_media/monitoringprocess.png" width="700">

**Monitoring Process Page :** Json dosyasından okunan dataların  listelendiği ve çerçeve üzerindeki vidalama işlem pozisyonlarının görsel olarak simüle edildiği çalışma sayfasıdır.


## Log Page

<img src="_media/alarmlog.png" width="700">

**Log Page:**  Alarm kayıtlarının ve HMI kayıtlarının olduğu sayfadır.

**Alarm Logs:** Geçmişe yönelik arıza kayıtları bulunur.

<img src="_media/hmilog.png" width="700">

**HMI Logs:** Geçmişe yönelik HMI arızaları ile ilgili kayıtlar bulunur.


## Jog Page

<img src="_media/jog.png" width="700">

**Jog:** Sayfanın en altında bulunan, Activate butonuna, basıldıktan sonra ilgili eksen butonuna basılarak, istenilen pozisyon gitmesi için JOG- ve JOG+ butonları kullanılır veya Set Position ve Set Velocity değerleri girilerek Move butonuna basılarak hareket ettirilir. Stop butonuna basılarak durdurulur.

## Region Settings Page
<img src="_media/dilayarlari.png" width="700">

- İstenilen dil veya ölçü birimi seçildikten sonra **Save** butonuna basılır. Değişiklikler yapılmış olur.

## Manual Control Page

<img src="_media/man_genel.png " width="700">

- Manual Control General Page

<img src="_media/man_yukleme.png" width="700">

- Manual Control Load Station Page

<img src="_media/man_vidalama.png" width="700">

- Manual Control Screwing Station Page

- Sayfanın en altında bulunan , **Activate** butonuna basılır. İlgili istasyon seçilir ve ardından hareket ettirmek istediğimiz çıkışın, üzerine basarak o çıkışı çalıştırırız. Ardından tekrar basarak o çıkışı eski konumuna alırız.


## Input Page
<img src="_media/in_genel.png" width="700">

- Inputs General Page

<img src="_media/in_yukleme.png" width="700">

- Inputs Load Station Page

<img src="_media/in_vidalama.png" width="700">

- Inputs Screwing Station Page

- Makinede bulunan butonların, sensörlerin ve switchlerin bulunduğu sayfadır.

## Parameters Page
- Makinenin tüm istasyonlarının ,parametrelerinin bulunduğu sayfadır.

<img src="_media/par_genel.png" width="700">

## General Parameters

**Y1 Ekseni Açılma Offset:** Çerçeve yükleme ve boşaltma işlemleri için gerekli olan eksen açılma offseti.
**X1A Ekseni Açılma Offset:** Çerçeve yükleme ve boşaltma işlemleri için gerekli olan eksen açılma offseti.
**Y1 Ekseni Maksimum Tork:** Y1 ekseni maksimum tork değeri.
**Y1 Ekseni Tork Limiti:** Y1 eksen çerçeve boy ölçme tork limit değeri.
**Y1 Ekseni Tork Ölçüm Hızı:** Y1 ekseni çerçeve boy ölçüm hızı.
**Çerçeve Ölçüm Toleransı:** Ölçüm yapılan çerçeve boyunun kabul edilebilecek aralıktaki değeri belirtir.

### Parameters Page Buttons
- Parametre sayfasında, değer kısmına, bir parametre veya parametrelerde değişiklik yapıldıktan sonra ,**Save** butonu ile kaydetmemiz gerekir. **Refresh** butonu ile değişiklik yaptığımız sayfayı yenileyebiliriz.
- **Export Params**: Makinenin, mevcut parametrelerini , Csv uzantısı ile dışarı aktarırız.
- **Import Params**: Haricen, makinede kullanılmak üzere parametreleri alırız.
- **Load Default Params**: Fabrika ayarlarını geri yükler.

## Axis Settings

<img src="_media/eksenparametreleri.png" width="700">

### Axis X1A Parameters
<img src="_media/eksenparametreleri.png" width="700">

- **Loading Axis (X1A) minimum limit position** : Yükleme X1A eksenin, minimum gidebileceği noktadır.
- **Loading Axis (X1A) minimum limit enabled** : Yükleme X1A eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (X1A) maximum limit position** : Yükleme X1A eksenin, maximum gidebileceği noktadır.
- **Loading Axis (X1A) maximum limit enabled** : Yükleme X1A eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (X1A) moving velocity** : Yükleme X1A eksenin, minimum hız değeridir.

### Axis X1B Parameters
<img src="_media/X1B_Axset.png" width="700">

- **Loading Axis (X1B) minimum limit position** : Yükleme X1B eksenin, minimum gidebileceği noktadır.
- **Loading Axis (X1B) minimum limit enabled** : Yükleme X1B eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (X1B) maximum limit position** : Yükleme X1B eksenin, maximum gidebileceği noktadır.
- **Loading Axis (X1B) maximum limit enabled** : Yükleme X1B eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (X1B) moving velocity** : Yükleme X1B eksenin, minimum hız değeridir.

### Axis Y1 Parameters
<img src="_media/sY1_Axset.png" width="700">

- **Loading Axis (Y1) minimum limit position** : Yükleme Y1 eksenin, minimum gidebileceği noktadır.
- **Loading Axis (Y1) minimum limit enabled** : Yükleme Y1 eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (Y1) maximum limit position** : Yükleme Y1 eksenin, maximum gidebileceği noktadır.
- **Loading Axis (Y1) maximum limit enabled** : Yükleme Y1 eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (Y1) moving velocity** : Yükleme Y1 eksenin, minimum hız değeridir.

### Axis SX1 Parameters
<img src="_media/sX1_Axset.png" width="700">

- **Loading Axis (SX1) minimum limit position** : Vidalama sX1 eksenin, minimum gidebileceği noktadır.
- **Loading Axis (SX1) minimum limit enabled** : Vidalama sX1 eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SX1) maximum limit position** : Vidalama sX1 eksenin, maximum gidebileceği noktadır.
- **Loading Axis (SX1) maximum limit enabled** : Vidalama sX1 eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SX1) moving velocity** : Vidalama sX1 eksenin, minimum hız değeridir.

### Axis SZ1 Parameters
<img src="_media/sZ1_Axset.png" width="700">

- **Loading Axis (SZ1) minimum limit position** : Vidalama sZ1 eksenin, minimum gidebileceği noktadır.
- **Loading Axis (SZ1) minimum limit enabled** : Vidalama sZ1 eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SZ1) maximum limit position** : Vidalama sZ1 eksenin, maximum gidebileceği noktadır.
- **Loading Axis (SZ1) maximum limit enabled** : Vidalama sZ1 eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SZ1) moving velocity** : Vidalama sZ1 eksenin, minimum hız değeridir.

### Axis SX2 Parameters
<img src="_media/sX2_Axset.png" width="700">

- **Loading Axis (SX2) minimum limit position** : Vidalama sX2 eksenin, minimum gidebileceği noktadır.
- **Loading Axis (SX2) minimum limit enabled** : Vidalama sX2 eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SX2) maximum limit position** : Vidalama sX2 eksenin, maximum gidebileceği noktadır.
- **Loading Axis (SX2) maximum limit enabled** : Vidalama sX2 eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SX2) moving velocity** : Vidalama sX2 eksenin, minimum hız değeridir.

### Axis SZ2 Parameters
<img src="_media/SZ2_AxSeT.png" width="700">

- **Loading Axis (SZ2) minimum limit position** : Vidalama sZ2 eksenin, minimum gidebileceği noktadır.
- **Loading Axis (SZ2) minimum limit enabled** : Vidalama sZ2 eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SZ2) maximum limit position** : Vidalama sZ2 eksenin, maximum gidebileceği noktadır.
- **Loading Axis (SZ2) maximum limit enabled** : Vidalama sZ2 eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SZ2) moving velocity** : Vidalama sZ2 eksenin, minimum hız değeridir.

### Axis SY1 Parameters
<img src="_media/sY1_Axset.png" width="700">

- **Loading Axis (SY1) minimum limit position** : Vidalama sY1 eksenin, minimum gidebileceği noktadır.
- **Loading Axis (SY1) minimum limit enabled** : Vidalama sY1 eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SY1) maximum limit position** : Vidalama sY1 eksenin, maximum gidebileceği noktadır.
- **Loading Axis (SY1) maximum limit enabled** : Vidalama sY1 eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SY1) moving velocity** : Vidalama sY1 eksenin, minimum hız değeridir.

### Axis SZ3 Parameters
<img src="_media/sZ3_Axset.png" width="700">

- **Loading Axis (SZ3) minimum limit position** : Vidalama sZ3 eksenin, minimum gidebileceği noktadır.
- **Loading Axis (SZ3) minimum limit enabled** : Vidalama sZ3 eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SZ3) maximum limit position** : Vidalama sZ3 eksenin, maximum gidebileceği noktadır.
- **Loading Axis (SZ3) maximum limit enabled** : Vidalama sZ3 eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SZ3) moving velocity** : Vidalama sZ3 eksenin, minimum hız değeridir.

### Axis SY2 Parameters
<img src="_media/sY2_Axset.png" width="700">

- **Loading Axis (SY2) minimum limit position** : Vidalama sY2 eksenin, minimum gidebileceği noktadır.
- **Loading Axis (SY2) minimum limit enabled** : Vidalama sY2 eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SY2) maximum limit position** : Vidalama sY2 eksenin, maximum gidebileceği noktadır.
- **Loading Axis (SY2) maximum limit enabled** : Vidalama sY2 eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SY2) moving velocity** : Vidalama sY2 eksenin, minimum hız değeridir.

### AxisZ4 Parameters
<img src="_media/sZ4_Axset.png" width="700">

- **Loading Axis (SZ4) minimum limit position** : Vidalama sZ4 eksenin, minimum gidebileceği noktadır.
- **Loading Axis (SZ4) minimum limit enabled** : Vidalama sZ4 eksenin, minimum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SZ4) maximum limit position** : Vidalama sZ4 eksenin, maximum gidebileceği noktadır.
- **Loading Axis (SZ4) maximum limit enabled** : Vidalama sZ4 eksenin, maximum gidebileceği noktayı etkinleştiririz.
- **Loading Axis (SZ4) moving velocity** : Vidalama sZ4 eksenin, minimum hız değeridir.

### Axis Calibration
<img src="_media/eksenkalibrasyon.png" width="700">

- İlgili eksen, sayfada seçildikten sonra **Calibration Value** değerine ekseni kalibre etmek istediğimiz değeri gireriz. Sayfanın altında bulunan **Calibrate** butonuna bastığımızda ekseni istediğimiz değer kalibre edecektir ve kalibre edilen değer **Axis Actual Value** tarafında gelecektir.

## User Settings

<img src="_media/KullaniciAyar.png" width="700">

### Page Access Settings
- Bu sayfada ,**Operatör** ,**Maintenance** ve **Service** modlarında , giriş yapılmasını istediğimiz sayfaları seçebiliriz. İlgili mod seçildikten sonra ,o mod da, kullanmak istediğimiz sayfa veya sayfaları seçeriz. Ardından **Save** butonuna bastığımızda ,değişiklikleri yapmış oluruz. 

### Password Settings
-  Bu sayfada ,**Operatör** ,**Maintenance** ve **Service** modlarına, girebilmek için şifre ayarı yapabiliriz.
İlgili mod seçildikten sonra kendi belirlediğimiz şifreyi gireriz ve ardından **Save** butonu ile şifremizi değiştirmiş oluruz.
