EROL KPSS • HARİTA MODU DÜZELTİLDİ

Sorun:
Önceki sürüm haritayı assets/turkiye-bolgeler.png dosyasından çağırıyordu.
GitHub'a yalnız index.html yüklendiği için görsel 404 veriyor ve ekranda alt metin görünüyordu.

Düzeltme:
- Harita doğrudan index.html içine SVG olarak gömüldü.
- Artık assets klasörüne ihtiyaç yok.
- GitHub Pages'te tek index.html ile çalışır.
- Harita modalı daha geniş açılır.
- Mevcut arayüz korunmuştur.

GitHub:
Mevcut index.html dosyasını bu paketteki index.html ile değiştir.
