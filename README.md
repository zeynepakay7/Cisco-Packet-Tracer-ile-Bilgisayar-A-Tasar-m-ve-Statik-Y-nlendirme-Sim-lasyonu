# MBLP119 - Bilgisayar Ağ Sistemleri Final Projesi 🌐

Bu proje, **MBLP119 Bilgisayar Ağ Sistemleri** dersi Güz Dönemi final projesi kapsamında geliştirilmiş bir ağ tasarımı ve yönlendirme (routing) simülasyonudur. Projenin temel amacı, ağ donanımlarının çalışma prensiplerini anlamak ve farklı ağlar arası iletişimi sağlamak için **Statik Yönlendirme (Static Routing)** yapılandırmasını uygulamaktır.

## 📝 Proje İçeriği ve Özellikler
Bu simülasyon kapsamında aşağıdaki ağ teknolojileri ve konfigürasyonlar kullanılmıştır:
- **Ağ Topolojisi Tasarımı:** Gerçek dünya senaryolarına uygun ağ cihazı (Router, Switch, PC) yerleşimleri.
- **IP Adreslendirme ve Alt Ağlar (Subnetting):** Cihazlar arası tutarlı ve kurallara uygun IP planlaması.
- **Statik Yönlendirme (Static Routing):** Router'lar arasında manuel rotaların yazılması ve paketlerin doğru hedefe ulaştırılması.
- **Bağlantı Testleri:** Uçtan uca (End-to-End) başarılı Ping ve ICMP paket iletimi.

## 🛠️ Kullanılan Teknolojiler
- **Cisco Packet Tracer** (Ağ Simülasyonu)
- Ağ Donanımları: Cisco Router'lar, Switch'ler ve End-Devices (Son kullanıcı cihazları)

## 📂 Dosya Yapısı
- `[Proje_Adiniz].pkt`: Cisco Packet Tracer proje/simülasyon dosyası.
- `Ekran_Goruntuleri/`: Ağın başarıyla çalıştığını ve cihazlar arası ping atılabildiğini gösteren kanıt niteliğindeki test ekran görüntüleri.

## 🚀 Kurulum ve Çalıştırma
Projedeki ağ simülasyonunu bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Bu depoyu bilgisayarınıza indirin ve klasöre çıkartın.
2. Bilgisayarınızda **Cisco Packet Tracer** (tercihen güncel bir sürüm) kurulu olduğundan emin olun.
3. Çıkarttığınız klasörün içindeki `.pkt` uzantılı dosyaya çift tıklayarak projeyi Packet Tracer üzerinde açın.
4. Ağ cihazlarının yeşil renkte (aktif) olduğunu gördükten sonra, bilgisayarların (PC) Command Prompt ekranını açarak diğer ağlardaki bilgisayarlara `ping [hedef_IP]` komutu ile bağlantı testi yapabilirsiniz.i

---
*Bu proje akademik amaçlarla tasarlanmış ve geliştirilmiştir.*
