# Unity 3 Boyutlu Tic Tac Toe Oyunu Ödevi

 Bu ödevde tic tac toe oyununu 3 boyutlu ortamda iki insanın
 sırayla oynayabileceği bir oyun tasarlanmalıdır. Oyunun içinde 
 temel tasarımlar tamamlanmış ve oyun motorunun önemli kısımları 
 boş bırakılmıştır.
 Ödevi tamamlamak için TicTacToeGame.zip dosyası açılıp klasör UnityHub
 ile proje aç kısmından açılacaktır. Klasör içerisinde kütüphane eklentileri
 yer kaplamaması için eklenmemiştir. Proje açılırken eksik kütüphaneleri 
 UnityHub tamamlayacaktır. Bir diğer ayrıntı da proje açıldığında boş bir sahne
 açacaktır. Assets klasöründen Scenes klasörüne girerek oradadaki AnaSahne seçilerek
 oyunun sahnesine ulaşılabilinir.
 
 Projede, Ana Sahne içinde 3 boyutlu gerekli tüm nesneler eklenmiştir.
 Oyun Mantığı boş 3 boyutlu nesnesi içerisine ana kamera ve ışık eklenmiştir. 
 Sahnede kamera bakış açısını düzeltmek için Oyun Mantığı nesnesi seçildikten 
 sonra Ctrl+Shift+F tuşları ile sahneyi tekrardan kamera ile eşleştirebilirsiniz.
 Oyun içinde zemin nesnesi altında 
	9 adet kare: x ve o çizilecek kareler
	4 adet çizgi: 9 kareyi görsel olarak ayrıştırmak için
 eklenmiştir.
 
 x şekilleri x1, x2, x3, x4 ve x5 olarak tanımlanmış,
 o şekilleride o1, o2, o3, o4 ve o5 olarak tanımlanmıştır.
 
 hareket etmesi gereken x ve o şekillerine Rigidbody componentleri görsel ekranda eklenmiş ve 
 hareket ettirmek için Rigidbody.MovePosition() fonksiyonu ile kullanıma hazırdır.
 oyunKodu.cs içinde bulunan fonksiyonlar incelenerek örnek kullanımını görebilirsiniz.
 
 Kod içindeki eksiklikler:
 1. oyunKodu.cs scripti içinde Update fonksiyonu içerisindeki oyun mantığı eksiktir.
 2. oyun oynanırken oyuncuların kazananını kontrol eden checkBoardState() fonksiyonu eksiktir.
 
 Yukarıdaki eksik kodlar için oyunKodu.cs ve cubeScript.cs kodları incelenip eksikler tamamlanmalıdır.
 1. x oyuncusu için x nesnelerin yerleştirilmesi: 30 puan
 2. o oyuncusu için o nesnelerin yerleştirilmesi: 30 puan
 3. oyunun kazananının kontrol edilmesi: 40 puan
 
 şeklinde punlanacaktır.
 
 Ek olarak;
 
 1. Oyun çizimleri içerisindeki nesnelerin oyunKodu.cs scripti içinde 
	Start() fonksiyonunda kod olarak tanımlanması: 25 puan
 2. Oyun çizimlerine dışarıdan 3 boyutlu (.obj formatlı) nesneler 
	eklenerek tamamlanması: 25 puan
	
 fazladan puan kazanabilirsiniz. 
 
 Ödevden en fazla 100 puan alabilirsiniz. Oyunun en az hata ile çalışıyor olması 
 puanlandırmada öncelikli durumdur. Lütfen önce oyun mantığı için gereken kodu tamamlayınız.
 Sonrasında ek puanlar için devam ediniz.
 
 Oyunda renklendirme kuralları mevcuttur:
 Bir kare üzreinde gezinirken kare mavi renkte olacaktır.
 Bir kare boşken oyuncular tıklarsa kare sarı renkte olacaktır.
 Bir kare dolu iken oyuncular tıklarsa kare kırmızı renkte olacaktır.
 
 Bu kurallar cubeScript.cs ve oyunKodu.cs scriptlerinde tanımlanmıştır. Ek bir işleme gerek yoktur.
 
 Önemli uyarı: nesneleri Rigidbody kullanarak hareket ettirirken görememe durumları oluşabilir. 
 Nesneler yer çekiminden dolayı zemin altında kalıp boşlukta aşağı düşebilirler. Bu durumu engellemek 
 için zemin ve karelerin üstünde y koordinatları ile MovePosition fonksiyonu kullanılmalıdır.

 Oyunun teslimatı internet üzerinden yapılacaktır. Proje klasörü boyutu büyük olacağı için 
 (tahmini en az 300 mb civarı) tamamen gönderilmemelidir. Sadece Projenin bulunduğu klasördeki
 Assets, Packages ve ProjectSettings klasörleri zip formatı ile sıkıştırılı gönderilmelidir. 
 Ek bir açıklama gerekiyorsa Açıklama.txt benzeri bir dosya ile açıklamalar eklenmelidir.
 Dışardan eklenen nesneler büyük boyutlarda olabilir. zip dosyasının 5 mb boyutu geçmemesine 
 özen gösterelim.
 
 ## Ödevin son teslim tarihi 27 Haziran 2022 saat 17:00'a kadardır. 
 Daha geç gelen projeler kabul edilmeyecektir.
 
 Ödevi teslim ederken kendinizi tanıtan (isim, soyisim, numara) bir txt dosyasını bu repo içerisine koymayı unutmayın. 
 
