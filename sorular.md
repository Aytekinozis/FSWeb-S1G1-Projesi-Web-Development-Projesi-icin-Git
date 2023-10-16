# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
git local ile cloud arasında bağlantı kurmamızı sağlayan yazdığımız kodların versiyonlarını kontrol etmemiz, push-pull atmamızı sağlayan kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
github repoların bulunduğu izni olanların dosyalar üzerinde değişim yapabildiği veya veri çekebildiği yer iken buradaki ver alış verişini sağlayan ara uygulama git dir.
3. Neden bir branch oluşturuyoruz?
işleyen bir kod dizini bozulmasın diye yeni yazdığımız kodları, özellikleri denediğimiz dallar oluşturuyoruz.
4. Pull Request'in amacı nedir?
yaptigimiz degisiklikleri yetkili kisiye pull etmesi icin istek atmamizdir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
gıt checkout yazarak branch değiştiriyoruz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git merge branchleri birleştirir. git pull clouddan local e yeni veriyi çeker. git fetch ise yapilan değişiklikleri gösterir.
7. Merge conflict nedir?
iki farklı kişi aynı satırı değiştirirse merge hata verir. iki farklı kod çakışıyor anlamına gelir.
8. Merge conflict'i nasıl çözeriz?
aynı dosya üzerinde çalışan insanalr beraber farklılıkları düzeltip sonra merge etmelidir.