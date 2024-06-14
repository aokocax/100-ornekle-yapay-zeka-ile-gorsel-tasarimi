<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Fotoğraftaki insanların pozlarını belirleme

Yapay zeka ile oluşturulan bir fotoğraftaki insanların pozlarını genellikle promptlar üzerinden belirlemeye çalışıyoruz ancak bunda biz ne kadar uğraşsak da istediğimiz sonuçlara tamamen ulaşmak mümkün değil. Bu noktada bize bir başka controlnet modeli olan OpenPose yardıma koşuyor. Her ne kadar henüz Midjourney, Firefly gibi araçlarla kullanmak mümkün olmasa da, Stable Diffusion'da yaklaşık 1 yıldır kolaylıkla bu işlemi yapabiliyoruz. Örneğimiz genelinde A1111 kullandık ancak ComfyUI ile de OpenPose modeli kullanılabilir.

![alt text](/gorseller/open-pose-1.png)



Öncelikle OpenPose kullanmak için 1.5 ve XL sürümlerine özel versiyonlarını indiriyoruz;

1.5 https://huggingface.co/lllyasviel/ControlNet-v1-1/resolve/main/control_v11p_sd15_openpose.pth
XL https://huggingface.co/thibaud/controlnet-openpose-sdxl-1.0/resolve/main/OpenPoseXL2.safetensors?download=true

Dosyalarımızı A1111 için
/extension/sd-webui-controlnet/models 

dizinine kopyalıyoruz.

OpenPose'un A1111 üzerinde kullanımına geçelim. Şimdi txt2img bölümüne girerek aşağıdaki onay kutucuklarından openpose'u seçiyoruz. Referans olarak daha önce çekilmiş bir fotoğrafı ya da yukardaki çöp adam benzeri iskelet görselimizi verebiliriz. Eğer iskeleti görselimizi verirsek PreProccessor alanın boş olduğundan emin olunuz.

Kaynak olarak bu görseli kullandık;

![alt text](/gorseller/open-pose-kaynak-1.png)

Controlnet alanımız;
![alt text](/gorseller/open-pose-2.png)


Promptumuz; (Realistic Vision 6 (SD 1.5 versiyonu) kullandık ) https://huggingface.co/SG161222/Realistic_Vision_V6.0_B1_noVAE/resolve/main/Realistic_Vision_V6.0_NV_B1_fp16.safetensors?download=true

`RAW photo a man drinking tea on a bench`

Sonuç;
![alt text](../gorseller/open-pose-sonuc-1.png)

Şimdi sadece iskelet üzerinden görsel oluşturalım. 

![alt text](/gorseller/open-pose-3.png)

Yeni promptumuz;

`RAW photo a man drinking tea on a bench`

Sonuç;
![alt text](/gorseller/open-pose-sonuc-2.png)


Eğer XL model ile OpenPose kullanacaksak XL'modele özel Controlnet modelinin seçili olduğundan emin olunuz.

