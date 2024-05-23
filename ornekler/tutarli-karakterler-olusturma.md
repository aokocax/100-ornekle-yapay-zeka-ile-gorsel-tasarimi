<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>


Üretken yapay zeka yardımıyla görsel oluştururken en büyük problemlerden biri tutarlı karakterler oluşturmaktı. Her ne kadar harika karakterler oluşturabilsekte aynı karakteri başka karelerde farklı biçimlerde kullanamıyorduk. Bir çocuk hikayesi yazdığımızı varsayarsak oluşturduğumuz karakteri futbol veya tenis oynarken ya da bir ağaca tırmanırken görselleştirmek istediğimizde karakterimiz değişiyor ve bütünlük kayboluyordu. Bu yazımızda Midjourney ve Stable Diffusion üzerinde nasıl tutarlı karakterler oluşturabileceğinizi bu bölümde anlatmaya çalışacağız.
![Alt text](/gorseller/tutarli-all.jpeg)

## Midjourney


Yaklaşık 1.5 ay kadar önce (Mart 2024) Midjourney bizlere “—cref” parametresini sundu. Promptumuzda –cref’i kullanarak bir görsel vererek. Görsel içindeki karakterin bu karaktere benzemesini sağlayabiliyoruz. Ayrıca bu parametre ile birlikte kullanılabilen “—cw” parametresine 0-100 arasında bir değer vererek karakterin ağırlığını değiştirebiliyorsunuz (varsayılan 100). Vakit kaybetmeden haydi kendi örneğimize başlayalım.

İlk olarak karakterimizi oluşturmak için bu promptu giriyoruz.

A young boy drawing, wears hat and t-shirt playing soccer
Oluşturulan görsellerden beğendimiz birini U ile upscale ederek, tarayıcıda açarak dosya konumunu kopyalıyoruz.

![Alt text](/gorseller/tutarli-1.png)

Daha sonra tekrar prompt yararak –cref parametresini ekliyoruz ve promptumuzu hikayemiz doğrultusunda güncelliyoruz.

A young boy drawing, wears hat and t-shirt playing tennis –cref https://gorseladresi


![Alt text](/gorseller/tutarli-2.png)
Farklı promptlarla hikayemizi güncelleyerek yeni görseller üretebilirsiniz.

A young boy drawing, wears hat and t-shirt climbing a tree --cref


--cref olarak daha fazla görsel vererek karakteri daha iyi öğrenmesini sağlayabilirsiniz
karakteriniz hakkında daha detaylı promptlar girerek tutarlılığı arttırabilirsiniz (örneğin şapkasında M harfi var, gözleri çekik, arka plan bej rengi v.b.)
--cref ile birlikte --sref parametresini girerek stil referası olarak yine fotoğraf verebilirsiniz.

## Stable Diffusion
(Hazırlanızyor) //todo

