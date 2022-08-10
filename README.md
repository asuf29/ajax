# AJAX nedir, nasıl çalışır?
- Sunucuya gelen herhangi bir isteği arkaplanda işleyerek web uygulamalarının eşzamanlı olmadan çalışmasına olanak sağlayan bir takım web geliştirme teknikleridir.
- Ajax kullanan herhangi bir web uygulaması tüm sayfayı yenileme ihtiyacı olmadan veri yollayabilir ve alabilir.

## Ajax'ın pratik örnekleri
- Google’un otomatik tamamlama özelliğini düşünün. Siz anahtar kelimelerinizi yazarken o size onları tamamlamanıza yardım eder. Sayfa aynı kalırken anahtar kelimeler gerçek zamanlı olarak değişir. 
![1](https://github.com/asuf29/ajax/blob/main/img/1.png)
- AJAX veri değişimi ve sunuş katmanının birbirlerinin fonksiyonlarına karışmadan aynı anda çalışmalarına olanak sağlar.

### Günlük hayatımızda gördüğümüz örnekler:
- Oylama ve puanlama sistemi 
> Online olarak aldığımız bir ürün için verdiğimiz puan, online bir oynama formu doldurmamız gibi işlemlerde AJAX kullanılır. Puanlama veya oylama tuşuna tıkladığımızda, web site hesaplamayı güncelleyecek ancak bütün sayfa değişmemiş kalacaktır.
- Sohbet odaları
> Bazı web siteleri ana sayfalarında müşteri desteği memurlarından biriyle konuşabileceğimiz yerleşik bir sohbet odası kullanır. Eğer aynı anda sayfada dolaşmak istiyorsak AJAX, her mesaj attığımızda ve aldığımızda sayfamızı yenilemeyecektir.
- Twitter’ın gündem bildirimi
> Belirli gündem konuları hakkında her yeni tweet atıldığında, Twitter ana sayfayı etkilemeden yeni rakamları güncelleyecektir.

## AJAX nasıl çalışır?
- Ana dili için HTML/XHTML ve sunum için CSS.
- Dinamik görüntü verisi ve etkileşimi için *Document Object Model (DOM)*.
- Veri değişimi için XML ve manipülasyonu için ise XSLT. 
> Birçok geliştirici **JSON** kullanmaya başladı. Çünkü şeklen JavaScript'e daha yakın.
- Eşzamansız iletişim için **XMLHttpRequest objesi**.
- Son olarak bütün bu teknolojileri bir araya getirmek için **JavaScript**.
