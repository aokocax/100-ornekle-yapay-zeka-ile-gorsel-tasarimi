<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Yapay zeka ile fotoğraflar üzerinde düzenleme yapma

[Bir önceki örneğimizde](https://github.com/aokocax/100-ornekle-yapay-zeka-ile-gorsel-tasarimi/blob/main/ornekler/fotograf-nesne-cikarma.md) fotoğraftan istemediğimiz bir nesneyi kaldırmıştık. Bu örneğimizde ise var olan bir nesneyi başka bir nesne ile değiştireceğiz.

# Stable Diffusion ile fotoğrafta düzenleme yapma (A1111)

Görsel düzenlemelerimizde herhangi bir modeli kullanabiliriz ancak inpaint için özelleştirilmiş modeller kullanarak daha başarılı sonuçlar alabilirsiniz. 

Biz örneğimizde [Juggernaut XL Inpainting ](https://civitai.com/models/403361/juggernaut-xl-inpainting) modelini kullanacağız. 

İlk olarak A1111'i açarak txt2img sekmesine girerek alt bölümden inpainting düğmesine basıyoruz ve fotoğraf yükleme alanından üzerinde değişiklik yapmak istediğimiz görselimizi yüklüyoruz.

![alt text](/gorseller/fotograf-nesne-cikarma-1.png)

Aynı fotoğraf üzerinde düzenleme yapmak isterseniz [buradan](https://pixabay.com/photos/apple-computer-browser-business-2568755/) indirebilirsiniz.

İlk olarak görselimizdeki koku şişesini masamızdan kaldıracağız. 

![alt text](/gorseller/fotograf-nesne-cikarma-2.png)

Bunun için ilgi görseli fırçamızla seçiyoruz ve daha sonra prompt alanına 

`a cup of coffee` yazıyoruz.

Dilerseniz ilgili alana daha büyük seçerek diğer ışık ve yansıma alanlarını da dahil edebilirsiniz.


Varsayılan ayarlarda sadece Inpaint Area kısmını, "Only Masked" olarak değiştiriyor ve görselimizin ölçülerini almak için gönye ikonuna basıyoruz.

![alt text](/gorseller/fotograf-duzenleme-yapma-1.png)

Generate düğmesine basarak görselimizi oluşturuyoruz

Görselinizde göre denoising ayarınızla oynayarak daha iyi sonuçlar elde edebilirsiniz. Biz bu sonucu elde ettik;

![alt text](../gorseller/fotograf-duzenleme-sonuc-1.png)


# Photoshop üzerine değişiklik

Benzer değişikliği yapmak ise Photoshop'ta nispeten daha kolay. Bu noktada daha iyi sonuç almak adına öncelikle nesneyi görselimizden çıkarıyor ve sonrasında istediğimiz yeni nesneyi ekliyoruz.

Görselimizde dilediğimiz alanı lasso tool aracılığıyla seçtikten sonra generative fill alanına "a cup of coffee with shadow" promptunu yazarak Generate düğmesine bazıyoruz.


![alt text](/gorseller/fotograf-duzenleme-yapma-2.png)

Sonucumuz bu şekilde oluştu.

![alt text](../gorseller/fotograf-duzenleme-sonuc-2.png)















