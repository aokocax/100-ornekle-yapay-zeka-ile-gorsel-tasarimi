<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Infinite zoom (sonusz yakınlaştırma) videosu oluşturma

Sosyal medyada sıkça gördüğümüz sonsuz yakınlaştırma videolarını yapay zekayla da hazırlayabileceğinizi biliyor muydunuz? Bu örneğimizde Stable Diffusion yardımıyla sonsuz yakınlaştırma videosu yapacağız.

İlk olarak Extension bölümüne ve ardından Avaliable sekmesine giriyoruz ve "Load from" düğmesine basarak eklentilerimizi listeyliyoruz. Daha sonra arama alanına infinite yazarek görseldeki eklentiyi "Install" diyerek kuruyoruz. En son olarak tekrar Installed alt sekmesine geçerek "Apply and RestartUI" düğmesi ile A1111'i tekrar başlatıyoruz.

![alt text](/gorseller/infinite-zoom-1.png)

A1111 tekrar başladıktan sonra Infinite Zoom sekmesine geliyoruz. Hiç bir ayara dokunmadan test amacıyla "Generate Video" düğmesine basarak ilk videomuzu oluşturalım. Ekran kartınızın performansına bağlı olarak bu işlem 1-5 dakika alacaktır. 

![alt text](/gorseller/infinite-zoom-2.png)

Videonuz sorunsuz olarak oluştuysa şimdi alanlarımızı açıklamaya başlayalım ve kendi sonsuz yakınlaştırma videomuzu oluşturalım.

Total video length: Videonuzun süresi (varsayılan 5 saniye)

Common Prompt Prefix: Videonuzdaki her sahne için girilecek ön prompt
Start at second: İlgili saniyede gelecek görselin promptu
Common Prompt Suffix: Vidonuzdaki her sahne için promptunuzun sona eklenecek prompt
Negative Prompt: Promptlarınız için kullanacağınız negatif prompt

Diğer ayarlara bu aşamada dokunmuyoruz ama dilerseniz çözünürlüğünüzü ve sampling metodunuzu değiştirerek daha keskin sonuçlar elde edebilirsiniz.

Şimdi yeni videomuz için promptlarımızı girelim. İlk olarak Clear prompts düğmesine basıyoruz

Common Prompt Prefix: `photo of`

0. `a lemon`
1. `empty wall picture`
2. `living room`
3. `livingroom wide angle`


Common suffix: `ultra realistic, 8k, masterpiece, HDR`

Negatif promptlarımız;

 `cartoon, painting, illustration, (worst quality, low quality, normal quality:1)`

![alt text](/gorseller/infinite-zoom-3.png)

Sonucumuz;

![video](../gorseller/infinite-zoom-sonuc-1.mp4)


