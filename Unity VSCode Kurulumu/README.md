# Unity Hub / Unity / Visiual Studio Cod Kurulumu

### 1. Adım: Unity Hub'ı indirme

  >[**https://unity3d.com/get-unity/download**](https://unity3d.com/get-unity/download) **tıklayarak Unity'nin resmi sitesini açıyoruz ve Unity Hub' ı indiriyoruz.** 
  
  >İndirdiğimiz **UnityHubSetup** dosyasını açıyoruz. Bu uygulamanın cıhazınızda değişiklik yapmasını onaylıyor musunuz sorusuna **EVET** cevabını veriyoruz. 
  
  >Lisans Sözleşmesini **Kabul Ediyorum** > Unity Hubın kurulacağı yeri dilersek seçip **Kur** > Kurulum tamamlandıktan sonra **Bitir** diyoruz. 
  
  >Unity Hub'ı açtığımızda bazen Windows Güvenlik Duvarı Erişim için uyarı verebiliyor **Erişime İzin Ver** dedikten sonra Unity Hub'ı açıyoruz

![image](https://user-images.githubusercontent.com/82322653/201467807-3124d1ca-c877-4fea-88ca-c09435efc521.png)

### 2. Adım: Visual Studio Code'u indirme

  >[**https://code.visualstudio.com/Download**](https://code.visualstudio.com/Download) tıklayarak Visiual Studio Cod'u indirebilirsiniz.
  
  >İndirdiğimiz **VSCodeUserSetup** dosyasını açıyoruz. Lisans anlaşması kısmında ***Anlaşmayı kabul ediyorum*** diyerek ***sonraki*** kısmına geçiyoruz.

  >VSCode'un kurulacağı yeri dilersek seçip ***sonraki*** kısma geçiyoruz. 

  >Başlat menüsü klasörü dilersek değiştirip ***sonraki*** kısma geçiyoruz.
  
  >Ek işlemler kısmında **tüm kutucukları işaretleyip** ***sonraki*** kısma geçiyoruz.
  
  >**Kur** diyerek kurulumu tamamlıyoruz ve **Bitir** kısmına tıklayarak kurulumu tamamlayıp VSCode' u açıyoruz.

![image](https://user-images.githubusercontent.com/82322653/201472661-939ceea9-9379-4997-b248-2cb96e241ac1.png)

### 3. Adım: .Net 6.0'ı indirme

  >[**https://dotnet.microsoft.com/en-us/download**](https://dotnet.microsoft.com/en-us/download) tıklayarak .NET 6.0 ı indireceğiz. Daha sonra bilgisayarı kapat aç yapmalıyız. %PATH% etkilenmesi için
  
  >dotnet-sdk-6.0.exe dosyasını açarak kurlumu yapıyoruz.
  
  >arama kısmına cmd yazarak terminali(komut istemini) açıyoruz. Daha sonra **dotnet** yazıyoruz karşımıza **usage, options, path** kısımları çıkıyorsa kurulumu başarılı bir şekilde gerçekleştirmişiz demektir. 

![image](https://user-images.githubusercontent.com/82322653/201496750-2a282142-8289-4732-9d03-e76813377f34.png)

### 4. Adım: Unity'de aktif lisans alma ve son sürümü indirme
  >Unity indirmek için üyelik oluşturmanız gerekiyor. [https://id.unity.com/account/new](https://id.unity.com/account/new) kısmına tıklayarak üyelik oluşturabilir ve öğrenci veya bireysel üyelik açarak lisansınız edinebilirsiniz. 
  
  >Unity Huba giriş yaparak son sürüm Unity'i indirebilirsiniz.

  >Daha sonra yeni proje kısmında 2D veya 3D kısmını seçerek ilk projemizi oluşturup Unity'i açıyoruz.(Projenin ilk açılması biraz uzun sürebilir.)

![image](https://user-images.githubusercontent.com/82322653/201497327-2bcecb78-80d3-4dfe-87e5-c31fe4a2335a.png)

### 5. Adım Visiual Studio Code uzantılarını yükleme
  
  >Unity içerisinden > Edit > Preferences > External Tools > External Script Editor kısmına geliyoruz ve Visiual Studio Code kısmını seçiyoruz.(Dosyalarımızın visual studio code içerisinde açılmasını sağlamak için bunu yapıyoruz.)

  >Unity içerisinden > Package Manager > Visiual Studio Code Editor > install kısmına tıklayarak en güncel sürümünü yüklüyoruz.

  >Extensions kısmını açıp > C#, Unity Tools, Unity Code Snippets,  .NET  uzantılarını yüklüyoruz. Bu araçlar kod yazmamızı ve yazdığımız kodu anlamamızı kolaylaştırıyor.

### 6. Adım .Net 4.7.1'i indirmek (VSCode kısmında otomatik doldurma için)

  >[**https://dotnet.microsoft.com/en-us/download/dotnet-framework/net471**](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net471) tıklayarak .Net 4.7.1 Developer Framework'ü indiriyoruz (bunu yüklemediğimizde otomatik doldurma vs yapamıyoruz her şeyi harf harf yazmak çok sinir bozucu o yüzden indirmeliyiz)

  >Asset > Open C# project or File > Preferences >External Tools > Regenerate Project File (Bu şekilde projeyi Visual Studio Code içerisinde açıyoruz.)

![image](https://user-images.githubusercontent.com/82322653/201497413-84523ab6-cedd-45d3-a57b-d8ea1f830849.png)


**Hepsi Bu Kadar Hadi Oyun Yapmaya Başlayalım** 😸
