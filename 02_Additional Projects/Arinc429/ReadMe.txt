OmniBusII Ballar Örneği Projesi;

Hem Transmit hemde Receive örneklerini içermektedir.
Programları çalıştırmadan önce Rt Target cihazı içerisine Channel xml ve Core xml Dosyalarının atılması gereklidir. 
Bu dosyaları FileZilla programı kullanılarak Rt Target içerisindeki dosya klasörlerini göreceksin;

Not= Bağlantıdan önce Hostpc'nin Rt target ile aynı networkte olduğuna emin ol...

FileZilla arayüzünde;
- Host = RtTarget IP(10.41.87.40)
- Username = admin
- Password = (Boş kalıcak)
- Port = 22 

yukarıdaki adımlar izlenerek Rt target içerisine bağlanılacaktır. Daha sonra Rt target içerisinden '/home/lvuser/natinst/bin' ilgil path gidilerek çalışılıcak olan xml dosyaları buraya atılmalı aksi halde hata alınıcaktır. 