# BLM101_24360859039_EnesSaricalar

**İsim:** Enes SARICALAR

**Numara:** 24360859039

**Konu:** Ağlar, İnternet ve HTML (5. Grup)


**PROJE DOKÜMANTASYONU: PYTHON İLE OTOMATİK HTML OLUŞTURUCU**

**1. PROJE HAKKINDA** 

Bu proje, kullanıcının konsol üzerinden girdiği kişisel bilgileri (isim, biyografi, ders listesi) işleyerek, modern CSS tasarımlı ve anında görüntülenebilir bir web sayfası (index.html) üreten bir **Python** otomasyon aracıdır. 

**Projenin temel amacı;** Python'un "String manipülasyonu" (metin işleme) ve "Dosya Yazma" (File I/O) yeteneklerini kullanarak dinamik içerik üretimini simüle etmektir. 

**2. KULLANILAN KÜTÜPHANELER** 

Bu projede harici bir kütüphane kurulumu gerekmemiştir. Python'un kendi standart araçları kullanılmıştır: 

**os Modülü:** İşletim sistemi ile iletişim kurmak ve dosyanın kaydedildiği konumu kullanıcıya göstermek için kullanılmıştır. 

**Temel Fonksiyonlar:** input(), print(), open(), split() ve strip() gibi temel komutlar kullanılmıştır. 

**3. ALGORİTMA MANTIĞI** 

**Program şu 4 adımı izler:** 

**Veri Toplama:** Program kullanıcıya sorular sorar (Adın ne? Hangi dersleri alıyorsun?). 

**Veri İşleme:** Kullanıcının yan yana virgülle yazdığı dersler (Örn: Matematik, Fizik), program tarafından parçalanarak bir listeye dönüştürülür. Ardından HTML formatına uygun hale getirilir. 

**Şablon Hazırlama:** Python'un "f-string" özelliği kullanılarak, önceden hazırlanmış HTML ve CSS kodlarının içine kullanıcının bilgileri yerleştirilir. 

**Dosya Yazma:** Bilgisayarda "index.html" isminde yeni bir dosya oluşturulur ve hazırlanan kodlar bu dosyaya kaydedilir. 
