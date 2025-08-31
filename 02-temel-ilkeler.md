# 2. Temel İlkeler

İstem mühendisliği, yalnızca yapay zekaya soru sormak değildir; doğru biçimde, net, bağlamı belirlenmiş ve yönlendirilmiş istemler yazmaktır. Bu bölümde, iyi bir istemin sahip olması gereken temel ilkeleri ele alacağız.

---

## 2.1 Açıklık ve Netlik

Belirsiz bir istem, belirsiz bir yanıt doğurur.  
Örneğin:  

- "Bana tarih hakkında bir şey anlat."  (-)
+ "Osmanlı İmparatorluğu’nun yükselme dönemindeki ekonomik yapısını 3 ana başlıkta açıkla."  (+)

Açıklık, yapay zekanın odaklanacağı alanı sınırlar ve çıktıyı daha kaliteli hale getirir.  

---

## 2.2 Bağlam Sağlama

Yapay zeka, insan gibi sezgilerle düşünmez; bağlama ihtiyaç duyar. Ona hangi durumda, hangi rolü üstlenmesi gerektiğini belirtmeliyiz.  

Örneğin:  
- "Sen bir öğretmensin. Lise öğrencilerine yönelik olarak Newton’un hareket yasalarını açıkla."  (+)
- "Sen bir yazılım geliştiricisin. Python’da dosya okuma ve yazma işlemlerini örnek kodlarla açıkla." (+) 

Bağlam, cevabın hem dilini hem de ayrıntı seviyesini belirler.  

---

## 2.3 Rol Atama

Yapay zekaya bir **rol vermek**, üreteceği içeriği büyük ölçüde değiştirir.  

Örneğin:  
- Gazeteci gibi yaz demek yerin = "Bir gazeteci gibi tarafsız, haber diliyle yaz."  
- Doktor gibi yaz demek yerine = "Bir doktor gibi açıklama yap, ama anlaşılır bir dille."  
- Yazılım uzmanı gibi yaz demek yerine = "Bir yazılım uzmanı gibi, adım adım açıklamalar yap."  

Rol atama, özellikle profesyonel çıktılar elde etmek için en etkili yöntemlerden biridir.  

---

## 2.4 Adım Adım İstemleme (Chain of Thought)

Karmaşık görevleri tek bir istemle çözmeye çalışmak yerine adımlara bölmek çok daha verimlidir.  

Örneğin:  
- "Bana bir iş planı yaz."  (-)
+ "Önce iş planı için 5 ana başlık öner. Ardından her başlık için alt maddeleri yaz. Son olarak da tümünü bir rapor formatında birleştir."  (+)

Adım adım istemleme, hem hataları azaltır hem de daha mantıklı bir yapı ortaya çıkarır.  

---

## 2.5 Çıktı Formatı Belirtme

İstediğiniz çıktının biçimini açıkça yazmalısınız. Liste mi, tablo mu, JSON mu, yoksa bir makale mi istiyorsunuz?  

Örneğin:  
- "Sonucu tablo halinde ver."  
- "Yanıtı JSON formatında döndür."  
- "5 maddelik bir liste olarak yaz."  

Bu yöntem, çıktıyı doğrudan kullanılabilir hale getirir.  

---

## 2.6 Özet (!!!)

İyi bir istemin temel ilkeleri şunlardır:  
1. Açık ve net olun.  
2. Bağlam sağlayın.  
3. Yapay zekaya rol verin.  
4. Karmaşık işleri adımlara bölün.  
5. Çıktı formatını belirtin.  

📌 Bir sonraki bölümde, bu ilkeleri  nasıl uygulayabileceğimizi göreceğiz.
