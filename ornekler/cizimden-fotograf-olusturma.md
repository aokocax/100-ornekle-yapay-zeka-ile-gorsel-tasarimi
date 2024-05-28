<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Çizimlerinizi fotoğrafa dönüştürün

Bu çalışmamızda elle ya da dijital oluşturmuş bir çizi gerçek görsele dönüştüreceğiz. Çalışmamız Stable Diffusion ve Firefly kullandık. Maalesef 2024 Mayıs itibariyle Midjourney bu konuda hala iyi durumda değil.

# Stable Diffusion

Görselimizi fotoğrafa dönüştürmek için "Canny" modelini kullanacağız. Çizim olarak pixabaydan indirebileceğiniz bu kuş görselini kullandık. https://pixabay.com/illustrations/bird-hummingbird-drawing-nature-7553736/

![alt text](/gorseller/cizim-kus.png)

Controlnet ayarlarımız bu şekilde, dilerseniz Canny yerine lineart da kullanabilirsiniz.

![alt text](/gorseller/cizim-kus-controlnet.png)

`RAW photo of a bird, flying, masterpiece, 8k, fujifilm, depth of field`

Negatif promptlarımız;

`drawing, painting`

Sonuç fotoğraflarımız böyle oluştu.

![alt text](/gorseller/kus-cizim-sonuc-1.png)


![alt text](/gorseller/kus-cizim-sonuc-2.png)


# Firefly

İlk olarak yapı alanına yukardaki görselimizi ekliyoruz ve kuvvet değerini maksimuma getiyoruz.

![alt text](/gorseller/cizim-firefly-1.png)

Promptlarımı;

`a realistic bird photo, flying`

Sonuç. (Çizimin detayları çok olduğunda firefly iyi sonuç veremeyebiliyor ve kuş görselimizin kanatlarındaki detayları Firefly'ı zorladı)

![alt text](../gorseller/cizim-kus-firefly-1.jpg)

# Midjourney
