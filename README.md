YAZILIM TEST DOKÜMANI
PROJE ADI: FİTYAŞAM
15.02.2018
YAZILIM TEST UZMANI
MELTEM KÖKSAL ÖZDEMİR


1.İÇİNDEKİLER

1.1.Projenin Tanıtımı ve Testin Amacı
	
1.2.Test Planı 

1.3.Test Cases

1.4.Test Raporu
 


1.1.Projenin Tanıtımı ve Testin Amacı

      Proje, fityasam.denemepaketi.com adresinde tasarlanmıştır. Hedef kitle bireysel kullanıcılardır. Amaç, üye girişi için kullanıcı testinin yapılmasıdır.



1.2.Test Planı

       Yazılım bileşenlerinin tamamı risk seviyelerine göre sınıflandırılarak, test edilebilecek bileşenler belirlenmiştir. Fityaşam test dokümanında kullanıcı giriş eylem testine yer verilecektir.



1.3.Test Cases

       Testin yürütülmesi ile ilgili esaslar aşağıdaki tabloda detaylandırılmıştır.


Amaç			Kullanıcının sisteme giriş eyleminin test edilmesi
Girdiler		Kullanıcı adı bilgisi
Kullanıcı 		şifre bilgisi
Beklenen çıktılar	Kullanıcının doğru kullanıcı adı ve şifresi ile sisteme giriş yapması.
Kriterler		
			Kullanıcının kullanıcı adı alanına sadece büyük ve küçük harflerden oluşan text değeri belirtmesi. 
			Kullanıcının parola alanına büyük/küçük harf ve tek basamaklı doğal sayılardan oluşan parola değeri 
			belirtmesi Belirtilen kullanıcı adı ve parola değerlerinin sistemde kayıtlı olan değerler ile eşleşmesi.
			Kullanıcının kullanıcı adı ve parola alanına uygun değerler dışında değer belirtmesi.
			Belirtilen değerlerin sisteme kayıtlı değerlerle eşleşmemesi. Sistemin herhangi bir teknik nedenle 
			veri tabanına bağlantı işlemini gerçekleştirememiş olması. 


Tabloda belirtilen kriterler doğrultusunda gerçekleştirilen test koşumu aşağıda ki gibidir;

Test Case No	Test Case Başlık	Girdiler	Beklenen 	Çıktılar	Test Verisi	Gerçekleşen
Çıktılar	Durum	Hata No	Hata
1	Geçerli kullanıcı adı ile sisteme giriş	Tanımlı bir kullanıcı adı ve parolası girildikten sonra giriş butonuna basılır.	Uygulama ana ekranına sorunsuz giriş sağlanması.	Kullanıcı adı: aaa
Şifre:123	Uygulama ana ekranına sorunsuz giriş sağlandı.	Başarılı	-	
2	Geçersiz kullanıcı adı ile sisteme giriş	Geçersiz bir kullanıcı adı ve parolası girildikten sonra giriş butonuna basılır.	Kullanıcı adı ve/ veya şifre yanlış uyarısının görüntülenmesi	Kullanıcı adı: aaa
Şifre:123	Uygulama ana ekranına giriş yapıldı.	Başarısız	1	Şifre yanlış girilmesine rağmen sisteme giriş yapıldı.

1.4.Test Raporu

        Hazırlanan test planı dahilinde, kullanıcı testi gerçekleştirilmiştir. 
Belirlenen kriterler ile oluşturulan senaryo için 1 adet hata saptanmıştır. Hata ikinci senaryoda tespit edilmiştir. 
Tanımlı olmayan kullanıcı adı ve şifre bilgisi ile sisteme giriş yapılmak istendiğinde beklenen sonuç 
“hatalı kullanıcı adı ve/ veya şifre “ uyarısıdır ancak  bu uyarı alınmamış ve giriş başarılı olmuştur. 

 

MELTEM KÖKSAL ÖZDEMİR
