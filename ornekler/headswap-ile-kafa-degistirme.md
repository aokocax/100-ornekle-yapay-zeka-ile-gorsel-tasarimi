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

Şimdi ilk olarak extras bölümünde kolaylıkla herhangi bir görselde yüz değişikliği yapmayı görelim. 

![alt text](/gorseller/reactor-7.png)

Üzerinde değişiklik yapacağımız görsel John Wick filminin görseli bunu dosya yükleme bölümünden seçiyoruz.
