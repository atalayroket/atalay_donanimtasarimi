# atalay_donanimtasarimi

<br>

> **Roket Yarışması**

Teknofest Roket Yarışması Orta İrtifa Kategorisi için hazırlanılmıştır. Kart çizimi yapılırken Altium programı üzerinden tüm ürün gruplarında elektronik komponentlerin bulunduğu şematik ve pcb [kütüphanesi](https://github.com/atalayroket/atalay_karttasarimi/tree/main/Atalay_KartTasarimi_Library) oluşturulmuştur. Kartlar yurt dışında üretilip, dizgisi kendi takım atölyemizde yapılmıştır.

<details>
<summary>Özellikleri</summary>
 
- Kartların arka yüzünde STM32F103RB işlemci olup olup ön yüzünde ise kullanacağımız sensörler, gps, haberleşme, ateşleme devresi ve voltaj regülatörü bulunuyor. 
- Kartımız 7-12V ile beslenmekte ve üzerinde güç ledi bulunmaktadır. 
- Voltaj regülatörü 3.3V çıkış vermektedir.
- Ateşleme devresi için mosfet ile optoptokuplör kullanılmıştır. 
- Sensör için BME280 basınç sensörü ile ADXL345 ivme sensörü, gps modülü olarak NEO-6M, yer istasyonu ile haberleşmek için LORA modülü kullanılmıştır. 
</details>

<img src="https://user-images.githubusercontent.com/104703949/211793118-0c35d59b-5b11-4253-a0f4-9dae601a29e2.png" width="1000">


<br>

> **Altium ile PCB Çizimi**
 
Karabük Üniversitesi öğrencilerine yönelik [Karabük Teknoloji ve İnovasyon Derneği](https://www.instagram.com/kartekinder/) üzerinden takım arkadaşlarımız [Cengizhan Topçu](https://www.linkedin.com/in/cengizhantopcu53/) ile  [Ferdi Ayhan](https://www.linkedin.com/in/ferdiayhann/) tarafından 21-22 Mayıs tarihlerinde ücretsiz olarak iki gün boyunca temel seviye pcb eğitimi verilmiştir.

<details>
 <summary>Eğitim İçeriği</summary>
 
   1. Programın Kurulması
   2. Kütüphane Oluşturma
   3. Şematik Tasarım
   4. PCB Tasarımı
   5. Üretim Dosyalarını Oluşturma
</details>

<img src="https://user-images.githubusercontent.com/104703949/180171973-0adf0bc6-bcd4-4074-b656-5cc029cb3bbe.png">
