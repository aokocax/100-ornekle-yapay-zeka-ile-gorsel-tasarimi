<a href="/">< Dizine dön</a> | <a href="/ornekler">< Örneklere dön</a>

# Ürün Fotoğrafları İçin Işık ve Arkaplan Hazırlama

Bu örneğimizde IC-Light projesini kullanarak ürün fotoğraflarımızın arkaplanını ve üzerindeki ışıklandırmayı değiştireceğiz. 
https://github.com/lllyasviel/IC-Light adresinden de ulaşabileceğiniz proje aslında kişisel biligsayarınıza da indirip çalıştırılabilmekte (8Gb+ ekran kartı önerilir) ancak biz Huggingface üzerinde özel olarak oluşturulmuş alanda işlemlerimizi yapacağız. Unutmadan, model dosyaları indirilerek ComfyUI üzerinden de çalıştırılabiliyor, başka bir örneğimizde bunu da sizlerle paylaşmayı planlıyoruz.

Çalışmamızda referans olarak bu görseli kullanacağız. (Cihazınıza indiriniz)

![alt text](/gorseller/sanatai-parfum.png)

İlk olarak Huggingface'teki özel bölüme (space) bu adresten giriyoruz.

https://huggingface.co/spaces/lllyasviel/IC-Light

Şimdi dosya yükle bölümüne tıklayarak değişiklik yapmak istediğimi görselimizi seçiyoruz.
![alt text](/gorseller/ic-light1.jpg)

Daha sonra 
1) Aşağıdaki metin bölümüne gelerek İngilizce olarak nesnemizi tanımlıyoruz
2) Işığımız yönünü seçme için (Lighting Preference) bir yön seçiyoruz 
3) Alttaki prompt oluşturma düğmelerinden istediğimiz bir veya birden fazlasına basarak promptumuzu tamamlıyoruz.

![alt text](/gorseller/ic-light2.png)

4) Alltaki "Relight" düğmesine tıklayarak görselimizi oluşturuyoruz.
Bu bölümdeki Images sayısını arttırarak aynı anda birden fazla görsel oluşturabilir, görselinizin yüksekliğini ve genişliğini değiştirebilirsiniz.

![alt text](/gorseller/ic-light3.png)
