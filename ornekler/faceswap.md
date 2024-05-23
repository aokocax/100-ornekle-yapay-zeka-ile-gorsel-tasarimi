<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Faceswap ile fotoğraflardaki yüzleri değiştirin

Bu örneğimizde yapay zeka yardımıyla herhangi bir fotoğraftaki yüzü değiştirmeyi göreceğiz. Öğrneğimizde Stable Diffusion A1111 kullandık ancak ComfyUI üzerinden de benzer nodeları kullanarak bu işlemi gerçekleştirebilirsiniz. Şu an için Midjourney, Dall-e ve Firefly bu imkanı bize sağlamıyor (Mayıs 2024).

A1111 web arabiriminin kişisel bilgisayara ya da uzak sunucuya kurulumu için bu adrese bakabilirsiniz https://github.com/aokocax/100-ornekle-yapay-zeka-ile-gorsel-tasarimi/blob/main/kurulumlar/a1111.md

A1111 uygulamamızı açtıktan sonra ilk olarak Extension bölümüne giriyoruz ve "Available" sekmesine geçip Load From düğmesine basıyoruz.
![alt text](/gorseller/faceswap-1.png)

Daha sonra metin kutusu alanına "reactor" yazıp Sağdaki install butonuna tıklıyoruz.
![alt text](/gorseller/reactor-3.png)
Kurulum tamamlandıktan sonra Installed sekmesine geri dönerek "Apply and Restart UI" düğmesine tıklıyoruz.

![alt text](/gorseller/reactor-4.png)
Bu işlem sonrasında txt2img, img2img ve Extras sekmelerimizde bir alt bölüm olarak Reactor alanı geliyor olacak.

Şimdi ilk olarak extras bölümünde kolaylıkla herhangi bir görselde yüz değişikliği yapmayı görelim. 


![alt text](/gorseller/reactor-1.jpg)

Üzerinde değişiklik yapacağımız görsel John Wick filminin görseli bunu dosya yükleme bölümünden seçiyoruz. 
Daha sonra Upscale'i 1 getirip Alttaki bölümden kimin yüzünü koyacaksak onu seçiyoruz. Diğer ayarlara dokunmuyoruz.
![alt text](/gorseller/reactor-2.png)

Burada eğer kaynak görselimizde birden fazla yüz varsa yüz sırasını değiştirmek için 1,2 gibi rakamları girebilirsiniz 0,1,2 aynı anda yazarsanız 3 farklı yüz varsa hepsine yerleştirecektir
![alt text](/gorseller/reactor-5.png.png)

Son olarak sonuç görüntümüz, burada ben kendimi yerleştirdim.
![alt text](../gorseller/reactor-6.png)


