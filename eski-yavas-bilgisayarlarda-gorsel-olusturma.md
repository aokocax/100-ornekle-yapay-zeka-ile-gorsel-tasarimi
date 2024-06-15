<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Eski ve yavaş bilgisayarlarda görsel oluşturma

Kişisel bilgisayarınızda görsel oluşturmak için ya da başka bir ifadeyle Stable Diffusion'ı çalıştırmak için en az 4b+ üstü bir ekran kartına ihtyiaç duyulmakta. 
gelgelelim böyle bir bilgisayarınız olsa bile tek bir görselin üretimi dahi onlarca saniye hatta dakikalar alabilmekte. Yine M1, M2 serisi Mac bir bilgisayarınız varsa da aynı şekilde görsel üretimi uzun sürebilmekte. Bu örneğimizde Stable Diffusion Turbo modeli ile bu tarz eski bir bilgisayarda nasıl görsel üretebileceğimizi göreceğiz.  ComfyUI kurulumu için kitabımzın başındaki kurulum kısmına bakabilirsiniz.

İlk olarak SD Turbo modelini bu adresten indiriyoruz https://huggingface.co/stabilityai/sdxl-turbo/blob/main/sd_xl_turbo_1.0_fp16.safetensors
Dosyayı models/checkpoints dizinine kopyalıyoruz.

Şimdi workflowumuzu [buradan](gorseller/workflow/sanatai_sd_turbo.json) indirerek ComfyUI üzerien sürükleyip bırakıyor ya da "Load" düğmesiyle workflowumuzu seçiyoruz.

Eğer ekran kartınızın ram'i düşüsek ComfyUI'yı başlatırken  --lowvram parametresiyle başlatabilirsiniz.

Şimdi workflowumuzu çalıştıralım. 10 fotoğrafı oluşturması yaklaşık 1sn aldı (Nvidia RTX 4070TI)

![alt text](/gorseller/sd-turbo-1.png)


Sonuçlarımız;

![alt text](/gorseller/sd-turbo-2.png)

![alt text](/gorseller/sd-turbo-3.png)


Step ve Cfg Scale'ini arttırarak daha iyi sonuçlar alabilirsiniz. Bilgisayarınızın hızına göre bu denemeleri yapmanızı tavsiye ederiz.




