It does not work anymore.

# fivem-status
FiveM sunucu durumu için PHP framework



1-) Kullanımı gayet basit FTP / CPanel aracılığı ile sunucu dosyalarınızda public_html veya alt alan adını (örn: status.alii.biz) adlı dizine atarak kurulumun ilk aşamasını tamamlayabilirsiniz



2-) Kurulumun diğer kısmı ise index.php klasörüne girip $settings ayarlarınızı yapılandırmak kalıyor.
   
    $settings['title'] = "Sunucu adı";
    
    
    $settings['ip'] = "000.000.000.000"; // Sunucu Ip'si
    
    
    $settings['port'] = "30120"; // Standart port 30120 olmalı (eğer değiştirilmediyse)
    
    
    $settings['max_slots'] = 128; // Kullanıcı slotu (Varsayılan 32)
  
   Bu şekilde yapılandırmanız gerekmektedir 
   
   
   
   
3-) Hiç bir şekilde server IP adresinize ulaşım sağlanamaz yazdığınız sadece size kalır   
