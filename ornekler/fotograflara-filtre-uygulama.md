<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Fotoğraflara filtre uygulama

Bu örneğimizde yapay zekaya verdiğimiz fotoğraflara çeşitli sanatsal filtreler uygulamayı göreceğiz. Örnek boyunca Stable Diffusion (A1111) kullanacağız.

Örneğimizde CardosXL modelini kullandık modeli buradan indirebilirsiniz https://civitai.com/models/155140/cardos-xl
Controlnet modeli olarak da Canny Diffusers (mid) modeli kullanıldı, bu adreseten indirebilirsiniz https://huggingface.co/diffusers/controlnet-canny-sdxl-1.0-mid/blob/main/diffusion_pytorch_model.safetensors modelimizi controlnet-canny-sdxl-1.0-mid.safetensors ismiyle
/extensions/sd-webui-controlnet/models dizini altına kaydediyoruz.

Örneğimizde İstanbul Kız Kulesi'ni çeşitli sanatsal filtreler uygulayacağız. Baz görselimizi bu adresten indirebilirsiniz. https://pixabay.com/photos/istanbul-leanderturm-turkey-tourism-5202424/

İlk olarak controlnet alanına giderek fotoğrafımız yüklüyoruz ve canny'i seçiyoruz. Görsele bakarak seçimlerinizi yapabilirsiniz.

![alt text](/gorseller/filtre-1.png)

Şimdi checkpoint alanından cardosxl modelini seçtikten sonra promptumuzu giriyoruz. Filtrenin daha belirgin olması için "Hires. fix" özelliğini de açtık, yine görselden tüm ayarlarımızı görebilirsiniz.

![alt text](/gorseller/filtre-2.png)

Promptlarımız;

`a tower painting, impasto style`

Negatif promptlarımız;

`photo, blurry`

İlk sonucumuz bu şekilde oluştu;

![alt text](../gorseller/filtre-sonuc-1.png)

Şimdi sırasıyla diğer sanat stiller için girdiğimiz promptları ve sonuçarını paylaşıyoruz;

`a tower painting, pointilsm`

`a tower drawing, hand drawing, sketch, monochrome`

`a tower painting, oil painting`



![alt text](../gorseller/filtre-sonuc-2.png)

![alt text](../gorseller/filtre-sonuc-3.png)

![alt text](../gorseller/filtre-sonuc-4.png)



