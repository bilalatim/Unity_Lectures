# UNITY PANELLERİ VE GENEL ARAYÜZ TANITIMI
## PANELLERİN ORTAK ÖZELLİKLERİ
**Unity'de window kısmından yanlışlıkla kapatığımız bir paneli tekrar açabiliriz. Pencerelerde değişiklik yaptıysak ve eski görünüme dönmek istiyorsak Window -> Layouts -> Default kısmından Unity'nin ilk açıldığı haldeki görünümüne tekrar dönebiliriz. Sürükle bırak yöntemi ile panellerin yerini değiştirebilir veya kenarlarından sürükleyerek boyutlarını ayarlayabiliriz.**

![unity-interface](https://user-images.githubusercontent.com/82322653/201726420-b0f7a9c3-6499-400a-a038-e65925c472b0.png)

### **Temel Paneller:**
>1) Hierarchy Paneli
>2) Scene Paneli
>3) Inspector Paneli
>4) Project Paneli
>5) Game Paneli
>6) Package Manager(My Assets)
>7) Console Paneli
>8) Toolbar (Bonus)

### Hierarchy Paneli
>**Sahnemizde bulunan objelerin listelendiği penceredir. Bu pencerede varolan bir objeyi kopyalayabilir, silebilir veya yeni bir objeyi oluşturabiliriz. Objelerin adını değiştirebiliriz. Sahnemize ışık, kamera gibi objeleri ekleyebiliriz. Objelerin sahnede görünürlüğünü kapatabiliriz. Objeler arasında child/parent (çocuk/ebeveyin) ilişkisi oluşturabiliriz.** 

![HierarchyParenting1](https://user-images.githubusercontent.com/82322653/201725769-48da526c-df82-4a9b-a502-34d36401b983.png)

### Scene Paneli
>**Oyunumuzdaki tüm objelerin konumlarını, boyutlarını, yönlerini ayarlayabildiğimiz ve oyun geliştirirken en çok kullanacağımız panellerden biri Scene Paneli. Bize oyunda görünmeyecek ancak oyun geliştirirken bize yardımcı olacak gizmoz çizgilerini görebilmemizi sağlar. Oyun çalışırken de sahne kısmından oyuna müdahale edibiliyor ve düzenlemeler yapabiliyor olacağız.** 
>
>**(NOT: Oyun çalıştığı esnada yapılan değişiklikler kaydedilmez.)**

![scene-view](https://user-images.githubusercontent.com/82322653/201728546-9e455c5e-e6ab-4468-b115-e9bc28773a61.png)

### Inspector Paneli
>**Inspector kısmı bizim için en önemli yerlerden biri. Burada oyunumuzdaki objelerin özelliklerini görebiliyor ve bunları değiştirebiliyoruz. Bu özelliklere "Component" adı veriliyor. Objelerinize yeni componenleri bu pencereden ekliyoruz veya çıkartıyoruz. C# Scriptleri ile de genelde objelerimizin sahip olduğu componentleri ve bu componentlerin özelliklerini değiştireceğiz.**

![InspectorWindowCallout](https://user-images.githubusercontent.com/82322653/201730515-443bb0eb-60a5-46f2-904d-d3a93848a5c8.jpg)

### Project Paneli
>**Bu panel proje konumundaki dosyalarımızı (resimler, animasyonlar, prefab(hazır objeler), ses dosyaları, C# script dosyaları vb.) gösterir. Buraya masaüstünden veya herhangi bir konumdan dosya sürükleyip bırakarak o dosyayı projeye dahil edebiliriz. Sağ tıklayıp create kısmına gelerek obje, dosya veya script(kod dosyası) oluşturabiliriz.**

![project-window-wide-layout](https://user-images.githubusercontent.com/82322653/201731199-66595d39-b8d3-4ce7-b7e0-9314d4ca84b3.png)

### Game Paneli
![Editor-PlayButtons](https://user-images.githubusercontent.com/82322653/201734044-e037cbdb-bc48-4834-9752-387f9baf0712.png)

>**Play tuşuna basıldıktan sonra oyunun simülasyonu (aslında oyunun kendisidir :smile:) diyebiliriz. Oyunu oynayan kullanıcının görebildiklerini görebiliriz. Etkileşimimiz sınırlıdır. Bu pencerede sadece kullanıcıların yapabildiklerini yapabiliriz.**

![game-view-window](https://user-images.githubusercontent.com/82322653/201734071-761a3502-be06-4b0f-9903-b19e7fd8a741.png)

### Package Manager(Asset Store/My Assets)

>**"Unity Asset Store" Unity'de kullanılabilecek 3B model, hazır proje, ses, görsel vb. ücretli ve ücretsiz birçok kaynağın bulunduğu bir web sitesi. Burada hazır kullanabileceğimiz birçok kaynak var ancak burada bunları kullanmadan önce lisans izinlerine dikkat etmeliyiz. Bazı lisanslar ticari kullanıma izin vermemekte. Burada bulunan paketleri kendi projenize dahil ederek kullanabilirsiniz.**
>
>**Elbette özgün işler çıkarmak için kendinize özgü kaynak üretmeniz çok önemli ancak tek başınıza her şeyi yapmak zor olacaktır. Biz de eğitimlerimizde hazır Unity Assetlerini kullanacağız.**

![image](https://user-images.githubusercontent.com/82322653/201735106-d10fdc8f-16ab-41b2-a928-f9e01d18b89f.png)

### Console Paneli

>**Console paneli oyundaki hataları görmemizi sağlayan penceredir. Oyun esnasında kodda debug(hata ayıklama) yaparken bu pencereyi çok sık kullanacağız. Bu pencerede uyarı, mesaj, hata metinleri ile karşılaşacağız. Uyarılar oyunun çalışmasını engellemez ancak oyunda negatif etkiye sahip şeyler olduğunu söyler. Mesajlar bizim koda yerleştirdiğimiz bize mesaj veren durumlardır. Bu durumlar gerçekleştiğinde Console kısmında mesajları görebiliriz. Mesajlar oyunun çalışmasına engel oluşturmaz. Hatalar oyunun çalışmasına engel olurlar. Hatalar çözülmeden oyun devam etmez veya başlamaz. Console kısmından bu hataların neden kaynaklandığını görebilir ve çözebiliriz.**

![image](https://user-images.githubusercontent.com/82322653/201738593-c42c276d-d2f0-4ff1-bb48-4b79d257be6a.png)

### Toolbar

>**Unity hesabımızın, Unity bulut hizmetinin, oyunu başlat, durdur butonlarının, geçmiş kısmının, arama kutucuğunun, Layers, Layout bölümlerinin bulunduğu bölüme verilen addır. Bu kısımda en çok kullanacağımız yer oyunu başlat ve durdur kısmı olacaktır muhtemelen :smile:**

![image](https://user-images.githubusercontent.com/82322653/201739123-5d899d50-f9a1-4c85-a327-2acc4e9e9c15.png)








