# ozdevinirler_kuramı_odev

Bu projede veri gönderme yöntemi olarak POST ile dummy endpoint kullanımını tercih ettim. Form verilerini https://httpbin.org/post adresine method="POST" ve enctype="multipart/form-data" kullanarak gönderdim.

Bu yöntemi seçme nedenim, gönderilen verilerin JSON formatında tarayıcıda açık şekilde görüntülenebilmesi ve form verilerinin gerçekten sunucuya iletildiğinin doğrulanabilmesidir. Ayrıca mailto: yöntemine göre daha güvenilir ve platform bağımsız çalışmaktadır.

Bu sayede hem dosya yükleme işlemini test edebildim hem de backend mantığının temel çalışma prensibini gözlemleme fırsatı buldum.
