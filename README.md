# AJAX nedir, nasıl çalışır?
- Sunucuya gelen herhangi bir isteği arkaplanda işleyerek web uygulamalarının eşzamanlı olmadan çalışmasına olanak sağlayan bir takım web geliştirme teknikleridir.
- Ajax kullanan herhangi bir web uygulaması tüm sayfayı yenileme ihtiyacı olmadan veri yollayabilir ve alabilir.

## Ajax'ın pratik örnekleri
- Google’un otomatik tamamlama özelliğini düşünün. Siz anahtar kelimelerinizi yazarken o size onları tamamlamanıza yardım eder. Sayfa aynı kalırken anahtar kelimeler gerçek zamanlı olarak değişir. 
![1](https://github.com/asuf29/ajax/blob/main/img/1.png)
- AJAX veri değişimi ve sunuş katmanının birbirlerinin fonksiyonlarına karışmadan aynı anda çalışmalarına olanak sağlar.

### Günlük hayatımızda gördüğümüz örnekler:
#### Oylama ve puanlama sistemi 
- Online olarak aldığımız bir ürün için verdiğimiz puan, online bir oynama formu doldurmamız gibi işlemlerde AJAX kullanılır. Puanlama veya oylama tuşuna tıkladığımızda, web site hesaplamayı güncelleyecek ancak bütün sayfa değişmemiş kalacaktır.
#### Sohbet odaları
- Bazı web siteleri ana sayfalarında müşteri desteği memurlarından biriyle konuşabileceğimiz yerleşik bir sohbet odası kullanır. Eğer aynı anda sayfada dolaşmak istiyorsak AJAX, her mesaj attığımızda ve aldığımızda sayfamızı yenilemeyecektir.
#### Twitter’ın gündem bildirimi
- Belirli gündem konuları hakkında her yeni tweet atıldığında, Twitter ana sayfayı etkilemeden yeni rakamları güncelleyecektir.

## AJAX nasıl çalışır?
1. Bir web sayfasında bir olay meydana gelir (sayfa yüklenir, bir düğmeye tıklanır).
2. JavaScript tarafından bir XMLHttpRequest nesnesi oluşturulur.
3. XMLHttpRequest nesnesi bir web sunucusuna istek gönderir.
4. Sunucu isteği işler.
5. Sunucu, web sayfasına bir yanıt gönderir.
6. Yanıt JavaScript tarafından okunur.
7. Uygun eylem (sayfa güncelleme gibi) JavaScript tarafından gerçekleştirilir.
![2](https://github.com/asuf29/ajax/blob/main/img/ajax.png)

## Klasik model ile AJAX modelini karşılaştıralım.

| Klasik model | AJAX modeli |
| ------------ | ----------- |
| 1.Web tarayıcıdan sunucuya bir HTTP isteği yollanır. | 1. Tarayıcı bir JavaScript çağrısı yaratır, bu çağrı da daha sonra XMLHttpRequest’i aktif eder. |
| 2.Sunucu isteği alır ve sonradan veriye erişir. | 2.Arkaplanda, web tarayıcısı sunucu için bir HTTP isteği yaratır. |
| 3.Sunucu istenilen veriyi web tarayıcısına yollar. | 3. Sunucu veriyi alır, erişir ve web tarayıcısına geri yollar. |
| 4. Web tarayıcısı veriyi alır ve veriyi göstermek için sayfayı yeniler. | 4. Web tarayıcısı istenilen veriyi alır, veri ise sayfada direkt olarak gözükür. Sayfayı yenilemek gerekmez. |
