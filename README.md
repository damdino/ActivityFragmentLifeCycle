12-> Program Run edildiğinde ekrana gelen loglara bakıldığında, Activity içerisinde, ID kullanarak, çalışma zamanında (run time) programmatically olarak eklenen C Faragmentinin işlem önceliği olduğu görülmektedir. Run time programmatically olarak eklenen fragmentler, XML içerisinden eklenen fragmentlere göre işlem önceliğine sahiptir. Run Time Programmatically olarak eklenen fragmentlerde aktivite çalışırken herhangi bir zaman da etkinliğe ekleme veya kaldırma yapabilirz. Fakat XML üzerinden eklenen fragmentler de böyle bir durum söz konusu değildir
//////////////////////////////**************************************************************************////////////////////////////////
13-> Aktiviteler,Android platformundaki uygulamaların temel yapı taşlarından biridir. Bir kullanıcının bir uygulamanın etkileşimine giriş noktası olarak kullanılırlar ve ayrıca bir kullanıcının bir uygulamada veya uygulamalar arasında nasıl gezindiğinin merkezinde yer alırlar.
//////////////////////////////**************************************************************************////////////////////////////////
Bir Fragmanent, bir aktivite aktivite veya kullanıcı arabiriminin bir bölümünü temsil eder. Çok bölmeli bir UI oluşturmak ve birden fazla aktvivitede bir fragmenti yeniden kullanmak için birden çok fragmenti tek bir aktivitede birleştirebilirsiniz. Bir fragment, kendi yaşam döngüsü olan, kendi girdi olaylarını alan ve aktivite çalışırken eklenebilen veya kaldırılabilen bir aktivitenin modüler bir bölümü olarak düşünülebilir.Avantajı, aktivite ile ilişkili birden çok etkinlik tarafından kullanılabilmesidir.
Eğer Frame'i sabit içeriği değişen sayfalar oluşturulacaksa, Fragment kullanımı uygulamanın -tasarımın- verimliliğini arttıracaktır. Fakat değişken Frame kullanılacaksa Activity kullanımı daha uygun olacaktır. 
//////////////////////////////**************************************************************************////////////////////////////////
14->Eğer basit, çok fazla değişim gerektirmeyecek, birden fazla sekmeli uygulama-tasarım- gerçekleştirmek istiyorsak kodumuzu XML içerisine ekleyerek kullanabilir. Çünkü XML içerisinden eklenen fragmentler üzerinde değişikliğe izin verilmiyor. Ayrıca ekran boyutu veya farklı ekran yönlendirmesi gibi farklı bir cihaz konfigürasyonunun kullanımı için XML içerisinden eklemek sunum için basit bir çözümdür.
Bunun dışında değişime uğrayan, önceliği yüksek olan uygulamalar-tasarımlar-gerçekleştirilecek ise Run time programmatically olarak eklemek daha kullanışlı olacaktır.
//////////////////////////////**************************************************************************////////////////////////////////
15-> Programmatically yüklemek ile XML içerisinde eklemek arasındaki farklar :
Uyumluluk: yaklaşık olarak her ikisi de her yerde geliştiriciler tarafından kullanılır.
Sürdürülebilirlik: aynı şey hakkında, kullanılmak istenilen fragment sınıfını tanımlamak için android: name özniteliği kullanılır.
Performans: Run Time ın , bir defalık çalışma süreci biraz daha hızlı olabilir ancak aslında eşittirler.XML'de eklenene parçacıklar değiştirilemez ve kaldıralamaz; bu sınırlandırma dışında istenilen ekleme yöntemi kullanılabilir. 





