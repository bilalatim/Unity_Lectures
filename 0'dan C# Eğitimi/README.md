# 0'dan C# Eğitimi

### Variables(Değişkenler)

  >**İçinde bilgi saklayan bir kutu gibi düşünebilirsiniz. Bu kutunun bir adı ve type'ı(türü) olmak zorunda. İçinde depoladığı şey ise value yani değeri.  Peki nedir type? Bu kutunun içinde tutacağımız değerin türünün ne olduğunu bilgisayara belirtmemizi sağlar temelde 4 çeşit type vardır:**
  * integer(sayı)             => **int can = 5;**
  * float(küsüratlı sayı)     => **float hız = 5.15f;**  
  * string(yazı)              => **string ad = "Bilal";** 
  * bool(doğru ya da yanlış olabilen ifade) =>**bool yasıyor = true;**
  
  >**NOT: float değerini yazdıktan sonra "f" kullanmamız gerekiyor.**
  >
  >**NOT: stringler her zaman "" işaretleri arasına yazılır.**
  
  >**Peki neden variableları kullanıyoruz?**
  >
  >**Örneğin kodda canı 1 azaltmak istiyoruz. Bunu yapmak için öncelikle o can değerini bir yerde depolamamız ve daha sonra 1 azaltıp tekrar depolamamız gerekiyor aksi takdirde can değerini değiştiremeyiz. Ayrıca kodumuzun rakam ve yazı karmaşasından kurtulmasını sağlar.**
  
### Functions(Fonksiyonlar)

  >**Fonksiyonlar basitçe organize, esnek, ve tekrardan kullanılabilir bir kod grubudur. Peki ne işe yararlar?** 
  >
  >**Belli bir görevi yerine getirmekle görevli bir makine gibi düşünebilirsiniz. Örneğin oyundaki zıplama foksiyonu karakterin zıplamasını sağlar.**
  >
  >**Yazdığımız fonksiyonun görevini yapması için o fonksiyonu herhangi bir yerde çağırmalıyız. Aksi halde fonksiyon malesef çalışmaz. Bu sebeple Unity'de yazdığımız fonksiyonları Start(), Update() gibi unitynin temel fonksiyonları içerisinde ihtiyacımızı karşılayacak uygun bir yerde çağırmalıyız. Nedir bu temel fonksiyonlar?**
  >
  - **Start() fonksiyonu scriptin bulunduğu obje aktifleştiği anda çalışır. Obje oyun başladığında aktif ise oyun başlar başlamaz çalışması gereken kodları veya fonksiyonları bu fonksiyon içerisine yazarız. Genellikle variable tanımlamaları vs yapılır.**
  - **Update() fonksiyonu saniyede 30 veya 60 defa çalışan bir fonksiyondur. Örneğin kullanıcıdan input alma kodunu veya objelerin hareket kodunu bu fonksiyon içerisinde kullanabiliriz.**
  - **Bu fonksiyonlar gibi farklı durumlarda çalışan birçok fonksiyon var ancak bunları örneklerle yeri geldiğinde öğreneceğiz.**
  >
  >**Bu kodu fonksiyon kullanmadan da yazabiliriz. Peki neden fonksiyon kullanmalıyız?**
  >
  >**Bu sorunun cevabı sürekli kendimizi tekrar etmemek için. Örneğin "A" karakteri 1 kere zıplayabiliyor ama "B" karakteri iki kere zıplayabiliyor. Aynı kodu çok ufak değişikliklerle iki kere yazmak yerine bir fonksiyon yazıyoruz. Peki bu fonksiyonun "A" karakterinin 1 kere "B" karakterinin 2 kere zıplamasını sağlaması için ne kullanıyoruz?**
  >
  >**Parametre kullanıyoruz. Parametre kısaca fonksiyona dışarıdan verilen bir variable yani değişken. Örneğin zıplama fonksiyonumuza biz zıplama sayısı adında bir int(sayı) değişkeni veriyoruz. Fonksiyon bu değer bir ise bir kere zıplamasını sağlıyor, 2 ise 2 kere zıplamasını sağlıyor. Bu değeri ne zaman yazıyoruz peki? Tabiki fonksiyonu çağırdığımız zaman kaç zıplama olacağını da yazıyoruz.** 
  >
  >Örneğin: **void zıplama_fonksiyonu(2)** parametre olarak 2 sayısını almış.
  >
  >Örneğin: print() de bir fonksiyondur. Consola bir şey yazdırma görevi için kullandığımız bir fonksiyondur. İçerisine yazdığınız değeri veya yazıyı yazdırır.
  >
  
  //buraya resim gelecek
  
  
  
  
  
