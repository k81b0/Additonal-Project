Labview Projesinin amacı;
	-1 Label üzerinden tek bir arinc429 mesajı transmit edilicektir.
	-Xml dosyasında oluşturulmuş data yapısını Arinc 429 data formatına çevirip ilgili channeldan yollamaktır.
	-Yolladığımız mesajın formatını çözümleyebilmemiz için birkaç vi kullanarak 32 bit word formatındaki arinc429 mesajı içerisinden data alma, sign bitini alma, ssm bitini alma, label alma gibi manipülasyonlar yapılmıştır. 