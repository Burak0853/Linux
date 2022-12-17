# Temel-Linux
### Terminal Nedir ?
Kabuk(Shell) ile etkileşime geçmek için kullandığımız grafik arabirimidir.

Kabuk(Shell) kullanarak komut ve programları çalıştırırız.

Terminal ekranı, çalışan komutların çıktılarını görmemizi sağlar.

#### Komutlar

`Whoami` : Makine üzerinde oturumu açan kullanıcının adı yazar.

`uname` : Sistem özelliklerini okumamıza yarayan bir program.

`uname -a` : Sistem özelliklerini ayrıntılı bir şekilde yazar.

`~ (Tilda)` : Terminalde ki bu işaret Kullanıcının ana dizinini beliritir.

`$` : Terminalde ki bu işaret terminali kullananın kullanıcı yetkisinde olduğunu belirtir.

`date` : Tarih ve zamanı gösterir.

`-` : kodumuza paramtreler eklemek için kullanırız

## Dosya Sisteminde Gezinme ve Listeleme 

`ls` :  Bir dizindeki dosya ve klasörleri listelemek için kullanılan koddur.

`ls -a` : Gizli dosya ve klasörleri listelemek için kullanıyoruz.

`cd` : Gitmek istediğimiz dizin için kullanırız.

`pwd` : Bulunduğumuz klasörün hangi dizinler altında olduğunu gösterir.

`ls -l` : Ayrıntılı bir listeleme için kullanılır.

`cd ..` : Bir üst dizine çıkmak için kullanılır.

## Dosya ve Dizin Oluşturma 

`mkdir` : Yeni dizin oluşturmak için kullanıcağımız komut. Oluşturma örnek 'mkdir [oluşturmak istediğimiz dizin adı]'

`touch` : Yeni dosya oluşturmak için kullanıcağımız komut. Oluşturma örnek 'touch [oluşturmak istediğimiz dosya adı ve uzantısı örneğin= metin.txt ]'

## Dosya ve Dizinleri Silme

`rm` : Dosya silmek için kullanılan komut.

`rm -r` : Dizin silmek için kullanılan parametre.

## Dosya ve Dizinleri Kopyalama

`cp` : Dosya kopyalama komutu. İlk önce kopyalınacak dosyanın adı ve sonrasında klasörünü belirtmek ve yeni ad belirtmek olabilir.

`cp -r` : Dizin kopyalama komutu.  İlk önce kopyalınacak klasörün adı ve sonrasında klasörünü belirtmek

## Dosya ve Dizinleri Taşıma

`mv` : Dosya ve Dizin taşımak için kullanılan komut.

## Dosya ve Dizinleri Yeniden Adlandırma

`mv` : Dosya yeniden adlandırmak içinde kullanılır.

## Dosya ve Dizinleri Arşivleme-Çıkarma

`tar cvf` : Dosyaları arşivlemek için kullanılan komuttur.

`tar xvf` : Dosyaları arşivden çıkarmak için kullanılan komuttur.

`gzip` : Dosyaları sıkıştırmak için kullanılan komuttur.

`gunzip` : Dosyaları çözme  için kullanılan komuttur.

`tar -zcvf` : Dosya veya dizin sıkıştırıp arşivlemek için kullanılan komuttur.

`tar -zxvf` : Dosya veya dizin arşivden çıkarmak için kullanılan komuttur.

## Nano ile dosya düzenleme

Terminal üzerinde çalışan metin düzenliyicisidir.

`nano dosya.txt` : Dosya oluşturmak için yazıyoruz.

## Dosya Düzenleyiciler

vim 

gedit grafik arabirimi olan dosya düzenleyici

## Dosyaları Okuma

`cat` : Dosya okuma komutudur.

`cat -n` : satır rakamlarını kaç satır görüntülemek için kullanılan komutudur.

`cat -E` : satır sonlarını görüntülemek için kullanılan komutudur.

`tac` : Dosyayı sondan başa görüntülemek için kullanılan komutudur.

## Farklı Dosyaları Okuma İşlemleri

`head` : Dosyayının ilk 10 satırını görmek için kullanılan komutudur.

`head -n5` : Dosyayının ilk 'n' parametresinin yanındaki sayı kadar satırı görmek için kullanılan komutudur.

`tail` : Dosyayının son 10 satırını görmek için kullanılan komutudur.

`tail -n5` : Dosyayının ilk 'n' parametresinin yanındaki sayı kadar satırı görmek için kullanılan komutudur.

`tail -f` : Dosyayı canlı olarak izlemek için kullanılır.

`tail -f` : Dosyayı canlı olarak izlemek için kullanılır.

`more` : Terminal ekranına sığmayan metinleri okumayı kolaylaştırır.

`nl` : Boş olan satırlar hariç diğer satırlara satır numarası ekler.

## Dosyalar Hakkında Bilgi Alma

`file` : Dosyanın türü hakkında bilgi almamızı sağlar.

`wc` : Dosya hakkında satır sayısı, kelime ve boyutunu belirtir.

`wc -w` : Dosya hakkında satır sayısı belirtir.

`wc -l` : Dosya hakkında kelime sayısını belirtir.

`wc -c` : Dosyanın boyutunu belirtir.

`wc -L` : Dosyanın içindeki en uzun satırı belirtir.

## Verileri Sıralama

`sort` : Dosyaları sıralamamızı sağlar.

`sort -k` : Parametresi dosyaları belirttiğimiz sütundan sıralamamızı sağlar.

`sort -c` : Parametresi bir listenin sıralı olup olmadığını öğrenmmemizi sağlar.

`sort -r` : Parametresi bir listeyi tersten sıralamamızı sağlar.

`sort -o` : Parametresi bir listenin sıralmasını kaydetmemizi sağlar.

## Dosya İçinde Arama

`grep` : Dosya içerisinde arama yapmamızı sağlar.

`grep -v` : Dosya içerisinde aradığımız şeyin bulunmadığı satırları gösterir.






















