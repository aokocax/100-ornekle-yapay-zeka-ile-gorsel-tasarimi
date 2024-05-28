<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Headswap ile bir fotoğraftaki kafayı değiştirin.

Faceswap'taki yüz değiştirmenin aksine bazen fotoğraftaki kişinin saçlarına kadar tüm detayları almamız gerekiyor. Bunu gerçekleştirmek için ise faceswap ile beraber controlnet (ip-adapter-face) modelleri yardımımıza geliyor.

Öncelikle reactor kurulumu için A1111 uygulamamızı açtıktan sonra Extension bölümüne giriyoruz ve "Available" sekmesine geçip Load From düğmesine basıyoruz.

![alt text](/gorseller/faceswap-1.png)

Daha sonra metin kutusu alanına "reactor" yazıp Sağdaki install butonuna tıklıyoruz.

![alt text](/gorseller/reactor-3.png)

Kurulum tamamlandıktan sonra Installed sekmesine geri dönerek "Apply and Restart UI" düğmesine tıklıyoruz.

![alt text](/gorseller/reactor-4.png)

Bu işlem sonrasında txt2img, img2img ve Extras sekmelerimizde bir alt bölüm olarak Reactor alanı geliyor olacak.

Biz faceswap'ta olduğu gibi John Wick film posterini kullanacağız.

![alt text](/gorseller/reactor-1.png)

İlk olarak img2img sekmesine gelip inpainting'e geçerek fotoğrafımızı yüklüyoruz ve görselimizdeki kafa alanını seçiyoruz.

![alt text](/gorseller/headswap-1.png)

img2img ayarlarını bu şekilde yapıyoruz.

![alt text](/gorseller/headswap-2.png)

Daha sonra controlnet alanına geçerek, değiştireceğimiz kişinin fotoğrafını girip ip-adapter tercihimizi görseldeki gibi yapıyoruz.

![alt text](/gorseller/headswap-3.png)

Son olarak tekrar reactor kullanarak faceswap için görselimizi tekrar giriyoruz.

![alt text](/gorseller/headswap-4.png)

Create diyerek görselimizi oluşturuyoruz, sonuç bu şekilde oluştu.

![alt text](/gorseller/headswap-5.png)

Denoising değerini düşürüp seçim alanını büyüterek ve daha fazla prompt girerek ilgili görsele daha iyi yedirilmiş sonuçlara ulaşabilirsiniz.



