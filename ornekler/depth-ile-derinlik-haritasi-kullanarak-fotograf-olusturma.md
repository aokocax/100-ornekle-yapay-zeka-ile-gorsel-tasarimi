<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# 3D derinlik haritası kullanarak fotoğraf oluşturma

Daha önce oda tasarımı yaparken kullandığımız Controlnet "Depth" modelini bu kez daha farklı tasarımları yaparken kullanacağız. Depth modeli oyun varlıklarının oluşturulmasından, makyaj modeli yapmaya kadar bir çok alanda oldukça faydalı olabiliyor. Yapay zeka araçlarından şu anda Depth modelini sadece Stable Diffusion ile kullanabiliyorsunuz. Biz de örneğimizde A1111 yardımıyla Depth modelini kullanacağız.

Eğer yüklü değilse Depth modelini (SD 1.5) bu adresten indirebilirsiniz https://huggingface.co/lllyasviel/ControlNet-v1-1/resolve/main/control_v11f1p_sd15_depth.pth
Dosyayı bu konuma yüklemeniz gerekmekte;

`extensions/sd-webui-controlnet/models`


İlk çalışmamızda bir heykel yüzünü kullanarak fotoğraf oluşturacağız.

![alt text](/gorseller/depth-1.png)

Fotoğrafımızı controlnet alanına yükleyerek görseldeki gibi "Depth" modelini seçiyoruz
![alt text](/gorseller/depth-2.png)


Model olarak Realistic Vision kullandık https://huggingface.co/SG161222/Realistic_Vision_V6.0_B1_noVAE/resolve/main/Realistic_Vision_V6.0_NV_B1_fp16.safetensors?download=true
Promptumuz;

`a child face photo`


Sonuç;

![alt text](/gorseller/depth-sonuc-1.png)

Dilerseniz PreProcessor olarak depth_keres++ kullanarak görseldeki gibi daha detaylı haritalar çıkartabilirsiniz.

![alt text](/gorseller/depth-3.png)

Bu örneğimizde ise bir kitap görselinin 3D haritasından yola çıkarak tekrar fotoğraf oluşturacağız. Görseli [buradan indirebilirsiniz](../gorseller/depth-4.png)

Promptlarımız;

`realistic RAW photo of  an open book on a wooden tabler`

Sonuç;

![alt text](/gorseller/depth-sonuc-2.png)





