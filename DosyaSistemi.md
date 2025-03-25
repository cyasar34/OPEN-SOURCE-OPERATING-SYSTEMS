## Linux Dosya Sistemi
<p align="justify">Linux’un dosya sistemi, Windows’un dosya sisteminden farklıdır. Genel olarak incelersek Microsoft sistemlerinde birbirinden bağımsız kök dizinler(root) bulunur. Mesela C dizini hard diskin ilk bölümünü gösterirken D dizini, 2. bölümü gösterir. Ayrıca disket ve USB için de ayrı ayrı kök dizini bulunur. Ancak Linux işletim sisteminde hiyerarşik bir klasör yapısı vardır. Bu hiyerarşik yapıda en üst dizin kök dizini (root directory) olarak bilinir ve “/” ile gösterilir. Tüm dosya sistemleri, programlar hatta sonradan eklenen disk bölümleri(partition) bile kök dizininin alt dizinlerinde yer alır. Kök dizini önyükleme esnasında hafızaya yüklenen ilk bölümdür.
</p>

#### Linux Dosya Sistemi Görüntüsü
![DosyaSistemi](https://github.com/cyasar34/OPEN-SOURCE-OPERATING-SYSTEMS/blob/main/linux_dosya_sistemi.png)

### Linux Dosya Sistemi Açıklamaları
<li>/bin: Temel komut dosyalarını barındıran dizindir.</li>
<li>/sbin: Sistem administratorleri tarafından kullanılan komut dosyalarını barındırır.</li>
<li>/etc: Sistemde kullanılan tüm servis ve programlarının yapılandırma dosyalarını içerir.</li>
<li>/dev: Fiziksel donanıma erişim gerekli dosyaları barındırır. Boot sırasında kullanılır.</li>
<li>/proc: Sistem süreçlerinin bilgisinin bulunduğu sanal dosya sisteminin dosyalarının bulunduğu dizin.</li>
<li>/var: Dinamik olarak boyutu değişen log, mailbox gibi dosyaların barındıran dizindir.</li>
<li>/tmp: Geçici dosyaların tutulduğu dizindir.</li>
<li>/usr: Programların, dosyaları ve dokümanları için kullanılan alt dizinlerini barındıran dizindir.</li>
<li>/home: Lokal kullanıcıların dosyalarının barındırıldığı ana dizindir. Kullanıcıların kişisel dosyaları burada tutulur. </li>
<li>/boot: Kernel’in boot etmesi gereken bütün dosya ve dizinleri içerir.</li>
<li>/lib: Programların ihtiyacı olan kütüphane (library) dosyalarının bulunduğu dizindir.</li>
<li>/opt: Uygulamaların opsiyonel olarak kullandığı paketler için kullanılır.</li>
<li>/media: Dosya sistemine dahil edilen harici depolama cihazları kullanılır.</li>








 
