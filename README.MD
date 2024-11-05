# Wireshark Paket Yakalama ve Analiz Çalışması

Bu proje, Wireshark kullanılarak gerçekleştirilen bir paket yakalama ve analiz çalışmasını içermektedir. Amacımız, ağ trafiğini analiz ederek protokol davranışlarını incelemek ve temel filtreleme işlemlerini öğrenmektir.

## İçerik

- **21100011016_Odev1.pdf**: Analiz sonuçlarını ve bulguları içeren yazılı rapor.
- **21100011016_Odev1.pcapng**: Wireshark kullanılarak yakalanan ağ trafiğinin .pcapng formatındaki dosyası.

## Projede Yapılan Çalışmalar

1. **Paket Yakalama Süresi**: Toplam 20.906 saniye boyunca ağ trafiği yakalandı. Bu süre, Wireshark'ın Capture File Properties menüsünden elde edilmiştir.
2. **Başlangıç ve Bitiş Zamanları**: Paket yakalama işleminin gerçek başlangıç ve bitiş zamanları görüntülendi.
3. **Toplam Yakalanan Paket Sayısı**: 7523 adet paket yakalanarak analiz edildi.
4. **Trafik Hızı Hesaplama**: Paket başına düşen trafik hızı, 7523 paket / 20.906 ms olarak hesaplandı.
5. **Protokol Analizi**: TCP, DNS ve HTTP protokollerine ait örnek paket bilgileri detaylandırıldı.
6. **HTTP Filtreleme**: HTTP protokolüne ait paketler, Wireshark'ta “http” filtresi kullanılarak görüntülendi.
7. **Paket Alışverişi**: HTTP paketleri arasında gerçekleşen diğer paket alışverişleri gözlemlendi.

## Kullanılan Araçlar

- **Wireshark**: Paket yakalama ve analiz işlemleri için kullanıldı. [Wireshark'ı indirin](https://www.wireshark.org/)
- **Kaynaklar**: [Wireshark Labs](http://gaia.cs.umass.edu/wireshark-labs/INTRO-wireshark-file1.html) web sitesi üzerinden veri analizi için kullanılan kaynak.

## Nasıl Kullanılır?

1. **Wireshark Dosyasını Açın**: `21100011016_Odev1.pcapng` dosyasını Wireshark ile açarak kendi analizlerinizi gerçekleştirebilirsiniz.
2. **PDF Raporunu İnceleyin**: `21100011016_Odev1.pdf` dosyasında, analiz sonuçları ve yapılan çalışmalara dair detaylı açıklamalar yer almaktadır.

---

Bu çalışma, ağ protokollerinin nasıl işlediğini anlamak ve ağ trafiğini analiz etme becerilerini geliştirmek için hazırlanmıştır.

