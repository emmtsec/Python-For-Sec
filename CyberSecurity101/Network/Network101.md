<span style="color: green"> **Network Fundamentals** </span>

<span style="color: red"> ***What is network?*** </span>

> ***Ağ iki veya daha fazla cihazların birbirleri ile iletişim, bağlantı oluşturduğu yapıdır.***

<span style="color: red"> ***Domain Name Hosting Subdomain And Some Terms*** </span>
- Domain

>  Her bir site bir IP ye sahiptir bunları hatırlamak zordur, bu sebeple site sahipleri alan adı almaktadır; **Örn: github.com**

- Hosting

> Kısacası bir sitede depolanan verilerin tutulduğu, siteyi aktifleştiren 7/24 aktif olan bir sistemdir. Bir bilgisiyar üzerinden depoları tutuyor olsaydık bilgisiyar kapandığında sitenin depolama hizmeti duracaktı, bunun önüne geçmek için hosting serverlar üretildi.

- Subdomain

> Subdomain; Ana domainin ek bir domaini diyebiliriz, sitemizin ek bölümleri için Subdomaine ihtiyacımız vardır. Örnek verecek olursak bir siteye giriş yaptınız üye ol bölümüne girdiniz ilk başta site **banka.com** olarak gözükecektir, üye ol girişi yaptığınızda **üyegiris.banka.com** olacaktır işte bu bir Subdomaindir.

- NS(Name Server)

> Alan adını sorgulamasında kullanılan, Domain ile IP adresi arasında ki bağlantıyı sağlayan sunuculardır. Name Server domain hizmeti aldığınız Hosting firması tarafından domaininize(alan adı) atanır.

- isimkayit.com/index.php/knowledgebase/166/NS-Name-Server-Nedir.html
- https://www.guzel.net.tr/blog/genel/nameserver-ns-nedir.html
- https://www.niobehosting.com/blog/nameserver-ns-nedir/

<span style="color: red"> Introduction to Network Hardware </span>

- İnternet Kartı(NIC)

> Cihazların internete erişmesini sağlar, **IP** ve **MAC** adres bilgilerini tutar.

- Switch

> Birçok cihazın ağa bağlanmasını sağlar, kendi aralarında haberleşmelerine olanak sağlar. OSI katman modelinde ikinci katman olan **Veri İletim(Data link)** katmanında çalışır yeni dağıtıcılarda OSI 3.Katman olan **Ağ(Network)** Katmanında da çalışabilir.

- Bridge(Köprü)

> İki bilgisiyar ağını birbirlerine bağlayan Ağ aygıtıdır. [Köprü ve Köprüleme hakkında yazılmış dolgun kaynak][1]

- Hub(Göbek)

> Görevi sinyalleri güçlendirip kabloya iletmektir. [Buda detaylı ve dolgun bir kaynak][2]

- Modem

> En aşina olduğumuz ağ aygıtıdır. Cihazları tek bir ağa bağlar kablolu ve kablosuz olarak bağlantı sağlar, Ağ olarak **LAN** kullanır. Belirli bir admin paneli vardır ve genellikle`192.168.1.1`şeklindedir. Admin paneline erişmek için modemin **LAN **ağında bulunmanız gerekmektedir.

- Firewall

> **Ağ(Network)** güvenliğinden sorumludur, paketleri inceler ve tehdit oluştaracak bir unsur yakalarsa **bloklar**. İki türk Firewall vardır; **Donanımsal Firewall** ve **Yazılımsal Firewall** Güvenlik duvarı gibi diyebiliriz.

<span style="color: red"> ***Basic Network Knowledge*** </span>


https://github.com/LuNiZz/siber-guvenlik-sss/blob/master/Belgeler/Dokumanlar/Network_Baslangic.md#top








[1]: https://en.wikipedia.org/wiki/Network_bridge "Bridge"
[2]: https://networkgiller.wordpress.com/hub/ "Hub"
