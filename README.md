# breakandpass
 * JacaScript, CSS, HTML kullanılarak hazırlanmış iki boyutlu(2d) oyun projesi. <br />
 * Oyun projesine göz atmak için : http://breakandpass.eu5.org/  <br />
# Oyun Hakkında
 * Bir atari oyunu olan Breakout' dan esinlenilmiştir. <br />
 * Oyunda belirli bir düzende dizili olan dikdörtgen şeklindeki hedeflerin yuvarlak bir karakter ile yokedilerek puan kazanılması ve bu işlemi gerçekleştirirken yuvarlak karakterin, oyuncu tarafından kontrol edilen bir yapı ile yakalanıp düşmemesi anlatılır. <br />
# Oyun Kurulumu
 * Herhangi bir ön kurulum gerektirmez. Proje dosyalarına erişmek için; <br />
   * Deponun sağ üst köşesindeki Kod yazan yeşil butona tıklayarak oyunun kaynak kodlarını bilgisayaranıza aktarabilirsiniz. <br />
   * Aktarma işleminden sonra .html uzantılı dosyayı Google Chrome ya da Mozilla Firefox gibi web tarayıcılarında çalıştırabilirsiniz. <br />
# Oyun Oluşum
 * JavaScript, CSS, HTML kullanılarak oluşturulmuştur. <br />
 * HTML canvas özelliği kullanılarak oyunun sayfada bulunacağı alan oluşturulmuştur. <br />
 * Uzaklık, şekil ve oyunun işleyişinde minimum matematiksel ve mantıksal denklemler kullanılmıştır. <br />
# Oyun Görselleri
 * index.html dosyası herhangi bir web tarayıcıda açıldığında ekranda görünecek oyun sayfası; <br />
    ![oyun1](https://user-images.githubusercontent.com/56195071/117902920-32819d00-b2d7-11eb-8d1c-a5b5faaa132e.PNG)
 * Start tuşuna basıldıktan sonra topun engeli kırarak oyun içindeki hareketi; <br />
    ![oyun2](https://user-images.githubusercontent.com/56195071/117903020-6e1c6700-b2d7-11eb-9642-5a1db097442e.PNG)
 * Topun kontrol edilen yapıya değilde yere değdiği anda oyunun bittiğini gösteren "Game Over" yazısı; <br />
    ![oyun3](https://user-images.githubusercontent.com/56195071/117903186-c3587880-b2d7-11eb-98b4-35cfb9523cd6.PNG)
# Proje Hakkında
 * Proje tek bir dosyadan oluşmaktadır. HTML dili içerisinde 'style' ve 'script' tanımlamalarıyla CSS ve JavaScript eklenmiştir. Proje üzerinde değişiklik yapmak için ya da gelişmiş bir hale getirmek için proje içerisinde tanımlanan terim ve fonksiyonlar hakkında detaylar aşağıdadır;
   * createBrickArray() : Oluşturulan tuğla engellerinin matris şeklinde diziliminin sağlanması.
   * drawBricks() : tuğla engellerin oluşturulması.
   * paddleNavigation() : Oynayan kişi tarafından kontrol edilen yapının ne ile kontrol edileceğini ve nasıl bir şekilde kontrol edileceğinin ayarlanması.
   * Collision() : topun tuğla yapılar ile çarpıştığı anı ve çarpıştığında tuğlaların gideceğini belirten fonksiyon.
   * checkGameover() : oyunun bittiğini ve bittiğinde 'game over' yazısını ortaya çıkaran fonksiyon.
   * drawBall() : oynanan karakteri oluşturma.
   * drawPaddle() : kontrol edilen yapıyı oluşturma.
