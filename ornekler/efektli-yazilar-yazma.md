<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Metin efekleri ile yazılar yazma (Ücretsiz)

Yapay zekanın en faydalı olduğu alanlardan biri efektli yazılar yazma. Eskiden photohop, blender gibi araçlarla saatler sürecek ya da tek bir efekt için dahi satın alma yaparak yapabileceğiniz tasarımları yapay zeka yardımıyla saniyeler içinde yapabilmektesiniz. 2004 (Haziran) itibariyle hala uzun yazılar yazmak (özlü sözler v.s.) mümkün olmasa da, kısa metinlerde çok başarılı olmakta.
Bu örneğimizde ücretsiz Stable Diffusion 3 modeli ile özel çalışmalar yapacağız. 
Öncelikle SD3 modelini indirmek için bu adrese bakabilirsiniz https://huggingface.co/stabilityai/stable-diffusion-3-medium/tree/main (Lisans onayı vermeniz gerekebilir) Repository'den https://huggingface.co/stabilityai/stable-diffusion-3-medium/resolve/main/sd3_medium_incl_clips_t5xxlfp16.safetensors?download=true bu dosyayı indiriyoruz.

ComfyUI uygulamamızı kullanacağımız için indirdiğimiz dosyayı 
models/checkpoints dizinine kaydediyoruz

ComfyUI uygulamamızı güncellemeyi unutmayalım.

Şimdi görsellerimizi üretmeye geçelim. İlk olarak [bu workflow'umuzu](../gorseller/workflow/sanat3d.json) ComfyUI'ya sürükleyip bırakalım.

Promptumuz;

`"Sanat.ai" text written in 3D on a black background, 3D letters were created with water drops and paints, there are slight reflections from the ground in yellow, blue and burgundy colors`

Siz promptta özellik nitelik ifade eden '3D, water drops and paints, yellow, blue and burgundy colors' gibi ifadeleri değiştirerek farklı görseller oluşturabilirsiniz.

Sonuç;

![alt text](../gorseller/efektli-yazi-sonuc-1.png)


Başka promptlar ve elde ettğimiz sonuçlar;

`3d tiny "Sanat.ai" hand writing chrome text written on a blue harley davidson body`

![alt text](../gorseller/efektli-yazi-sonuc-2.png)

`"Sanat.ai" text written in 3D in a crystal box, transparent color, on a marble table, shiny and reflections`

![alt text](../gorseller/efektli-yazi-sonuc-3.png)

`"Sanat.ai" text written by ice and some snow on the letters, inside a wonderful glass ball, snowflakes, trees, a botanical garden, reflections on the glass ball, like a game studio work`

![alt text](../gorseller/efekli-yazi-sonuc-4.png)