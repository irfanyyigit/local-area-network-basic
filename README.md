# local-area-network-basic
Bu depo, Cisco Packet Tracer üzerinde simüle edilmiş temel bir Yerel Alan Ağı (LAN) tasarımını içermektedir proje, küçük ve orta ölçekli bir şirket ortamı için güvenli ve yapılandırılmış bir ağ bölümlendirmesini (segmentasyon) göstermektedir

## ağ mimarisi 

Topoloji, hiyerarşik bir ağ tasarımı kullanılarak şu bileşenlerle oluşturulmuştur:
*   **1 x Router (Yönlendirici):** VLAN'lar arası yönlendirmeyi (Inter-VLAN Routing) sağlar ve dış ağ/internet bağlantısını yönetir.
*   **1 x Core Switch (Omurga Anahtar - Layer 3):** Ağın ana omurgası olarak görev yapar, departmanlar arasındaki yüksek hızlı veri trafiğini yönetir.
*   **4 x Access Switch (Erişim Anahtarı):** Son kullanıcı cihazlarını ağa bağlamak için her departmana özel olarak atanmış switchler.

## departman bölümlendirmesi (bütün VLAN'lar)

Ağ güvenliğini ve trafik yönetimi acisindan mantık 4 bölümden olusur

1.  **IT (Bilgi Teknolojileri):** Ağ yönetimi ve teknik destek cihazları için yüksek yetkilere sahip güvenli bölge.
2.  **Accounting (Muhasebe):** Finansal veriler ve muhasebe bilgisayarları için izole edilmiş güvenli bölge.
3.  **Marketing (Pazarlama):** Pazarlama ekipleri ve dışa dönük kurumsal cihazlar için standart bölge.
4.  **Guest (Misafir):** Şirket ağına erişimi kısıtlanmış, sadece ziyaretçilerin internete çıkması için ayrılmış izole bölge.

## Projede Uygulanan Özellikler
*   VLAN (Sanal Yerel Alan Ağı) kullanılarak ağın bölümlendirilmesi.
*   Router veya Core Switch üzerinde VLAN'lar arası yönlendirme (Inter-VLAN Routing) yapılandırması.
*   Temel switch ve router konfigürasyonları.
