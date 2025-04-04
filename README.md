 Global Değişkenler:
maxf ve maxm: Bu iki değişken, sistemde eklenebilecek maksimum film (maxf) ve müşteri (maxm) sayısını belirliyor. Bu sayılar sabitlenmiş, ancak isterseniz dinamik hale getirebilirsiniz.

filmadi, filmsure, filmtur: Bu diziler filmlerin adını, süresini (dakika cinsinden) ve türünü saklıyor.

musteriad, musteriemail: Bu diziler, müşteri isimlerini ve email adreslerini saklıyor.

biletler: Bu iki boyutlu dizi, her müşteri için izlediği filmleri saklar. Her satır bir müşteri, her sütun bir film olarak düşünülür.

2. main Fonksiyonu:
Kullanıcıdan hangi işlemi yapmak istediği sorulur.

5 seçenek sunuluyor: Film ekleme, müşteri ekleme, bilet kaydı, biletleri listeleme ve çıkış yapma.

Kullanıcı bir seçenek girer ve ilgili fonksiyon çağrılır. Bu işlem, kullanıcı "Çıkış" yapana kadar döngü halinde devam eder.

3. filmekle Fonksiyonu:
Bu fonksiyon, kullanıcıdan film bilgilerini alır ve filmleri filmadi, filmsure, ve filmtur dizilerine ekler.

Eğer mevcut film sayısı (filmler değişkeni) maxf değerini aşarsa, daha fazla film eklenmesine izin verilmez.

Film eklendikten sonra, başarıyla eklendiğine dair bir mesaj gösterilir.

4. musteriekle Fonksiyonu:
Bu fonksiyon, kullanıcıdan müşteri bilgilerini alır ve bunları musteriad ve musteriemail dizilerine ekler.

Eğer mevcut müşteri sayısı (musteriler değişkeni) maxm değerini aşarsa, daha fazla müşteri eklenmesine izin verilmez.

Müşteri başarıyla eklendiğinde, bir mesaj gösterilir.

5. biletkayit Fonksiyonu:
Bilet kaydı yapmak için önce müşteriler ve filmler listelenir.

Kullanıcı, hangi müşteri ve hangi film için bilet almak istediğini seçer.

Müşteri ve film doğru seçildiyse, biletler dizisine, bu müşterinin izlediği film kaydedilir.

Eğer müşteri veya film seçimi geçerli değilse, uygun hata mesajları gösterilir.

6. biletlistele Fonksiyonu:
Bu fonksiyon, her müşteri için izlediği filmleri listeler.

biletler dizisinde hangi filmler kaydedilmişse, o filmler kullanıcıya gösterilir.

Eğer bir müşteri herhangi bir film izlemediyse, "Hiç film yok" mesajı gösterilir.

Kodun Genel İşleyişi:
Başlangıçta, kullanıcıya film ekleyebilir, müşteri ekleyebilir veya bilet kaydı yapabilir.

Film ekleme: Kullanıcı bir film adı, süresi ve türü girerek film ekler.

Müşteri ekleme: Kullanıcı adını ve e-posta adresini girerek yeni bir müşteri ekler.

Bilet kaydı: Kullanıcı, bir müşteri ve bir film seçerek bilet kaydı yapar. Bu işlem, ilgili müşteri için seçilen filme bilet kaydeder.

Biletleri listeleme: Sistem, her bir müşterinin izlediği filmleri gösterir.
