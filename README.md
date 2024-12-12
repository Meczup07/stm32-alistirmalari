
# stm32-alistirmalari

STM32F407G-DISC geliştirme kartı için yapılan basit alıştırmalar.
Farklı kartlara kodlar çekilerek uygulamalar denenebilir. STM32 üzerinde yeni başlayanlara yol göstermesi açısından bu repo oluşturulmuştur.

![image](https://github.com/user-attachments/assets/0d45851e-03c5-47fd-baa7-2f85aeb12203)
<img src="https://github.com/user-attachments/assets/0d45851e-03c5-47fd-baa7-2f85aeb12203" alt="image" width="400">


Çalışma Konuları
1) Interrupt
2) Timer
3) ADC
4) DAC
5) Mod alma
6) RTOS
7) QT Designer ile STM32 arasında haberleşecek arayüz tasarımı


STM32F407G-DISC User Manual : https://www.st.com/resource/en/user_manual/um1472-discovery-kit-with-stm32f407vg-mcu-stmicroelectronics.pdf

STM32F407G-DISC Schematic Documentary: https://www.st.com/resource/en/schematic_pack/mb997-f407vgt6-b02_schematic.pdf

1)Interrupt: Mikrodenetleyicide belirli bir olay gerçekleştiği zaman, o olay olurken dönen iş akışını durdurup belirli olay özelinde işlem yapmasını sağlayan mekanizmadır. Bütün bilgisayar ve mikrodenetleyicilerde kesme bulunur. Önceliği yüksek işlerin mikrodenetleyici tarafından ana program akışı kesilerek yapılmasına kesme (interrupt) denir. Normal program akışı, kesme işleyicisi (interrupt handler) tamamlandıktan sonra kaldığı yerden devam eder.
   
![image](https://github.com/user-attachments/assets/d9d497c9-0247-4d5b-a22f-655ce04255e3)

Kullanılan STM32F407G-Disc kartında; 82 adet maskelenebilir kesme kanalı, programlanabilir 16 öncelik seviyesi, kısa gecikme süreli kesme erişimi, güç kontrol kesmeleri ve sistem kontrol kesmeleri bulunmaktadır.

   
