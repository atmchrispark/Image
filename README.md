### WILC1000 Driver options
When kernel configure, can set options for WILC1000 driver.  
Choose the Atmel SmartConnect menu, “`Device Driver -> Network device support -> Wireless LAN -> Atmel SmartConnect Wireless cards Driver`”. The option WILC1000 driver can be set to either “`M`”or “`*`” as depicted in the below.  
![](https://github.com/atmchrispark/Image/blob/master/kernel_smartconnect.jpg)  

   * WILC1000 support  : Wi-Fi device (wilc1000)  
   * Bus Type          : Can choose one of the two Interface SDIO SPI.  
   * Memory Allocation : Heap area shortage in the system may affect wifi operate.  
Therefore, according to the resource status user can choose one of the three below.  
      * When bootup system.  
      * When driver loading.  
      * Driver running fluidly.  
   * Use out of band interrupt : If you would want to use an external interrupt instead of SDIO interrupt. Can select this option.  
   * Export defugfs for WILC1000 status : If you would want to know WILC1000 status.  
