<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Yapay zeka ile üç boyutlu derinlikten iç mekan tasarımı

Bu örneğimizde varolan bir mekanı 3D derinlik haritası üzerinden üretken yapay zeka ile yeniden tasarlayacağız. Örneğimizde A1111 kullanacağız ve RealVis modelini kullanacağız.

Model indirme, controlnet  için sanat.ai üzerindeki dersler bölümümüze bakabilirsiniz.

İlk olarak referans olarak kullanacağımız oturma odası görselini seçiyoruz. 

![alt text](../gorseller/oturma-odasi-ref.jpg)

Görselimizi Contrlnet fotoğraf alanında seçtikten sonra Depth modelini seçiyoruz. 

![alt text](/gorseller/3d-controlnet-oturma-odasi.png)



Dept modeli odamınız 3D ısı derinlik haritasını çıkarıyor.

Daha sonra prompt alanına 

![alt text](/gorseller/derinlik-haritasi.png)

`chinese living room,  ((best quality)),((masterpiece)),((realistic)), soft light, soft light`

Negatif prompt alanına ise 

`logo, text,word,cropped,low quality,normal quality,username,watermark,signature,blurry,soft,soft line,sketch,ugly,logo,pixelated,lowres, FastNegative`

yazıp diğer ayarları bu şekilde ayarlayarak görselimizi oluşturuyoruz.

![alt text](/gorseller/oturma-odasi-2.png)

Sonuçlarımız bu şekilde oldu.

![alt text](../gorseller/3d-oturma-1.png)

![alt text](../gorseller/3d-toruma-2.png)

Görselinizdeki herhangi bir alanı değiştirmek isterseniz bu yazımızın son kısmına bakabilirsiniz.[text](ic-mekan-tasarimi.md)

