## STM32 I2C Scanner, RadioOperator modified version !!!  

Simple I2C scanner with USB CDC output interface.  

Based on stm32f103c8t6 'BluePill' board.  

![in use](/pic.jpg)

### USB VCP testing output:  

STM32 I2C Scanner    V0.01 :  

PB6 -> I2C1_SCL
PB7 -> I2C1_SDA

type 's' to scan

SCAN...
       100KHz 200KHz 300KHz 400KHz  
0x01   ---    ---    ---    ---  
0x02   ---    ---    ---    ---  
0x03   ---    ---    ---    ---  

..................................


0x64   ---    ---    ---    ---  
0x65   ---    ---    ---    ---  
0x66   ---    ---    ---    ---  
0x67   ---    ---    ---    ---  
0x68    V      V      V      V   
0x69   ---    ---    ---    ---  
0x6A   ---    ---    ---    ---  
0x6B   ---    ---    ---    ---  
0x6C   ---    ---    ---    ---  
0x6D   ---    ---    ---    ---  
0x6E   ---    ---    ---    ---  
0x6F   ---    ---    ---    ---  
0x70   ---    ---    ---    ---  
0x71   ---    ---    ---    ---  
0x72   ---    ---    ---    ---  
0x73   ---    ---    ---    ---  
0x74   ---    ---    ---    ---  
0x75   ---    ---    ---    ---  
0x76    V      V      V      V   
0x77   ---    ---    ---    ---  
0x78   ---    ---    ---    ---  
0x79   ---    ---    ---    ---  
0x7A   ---    ---    ---    ---  
0x7B   ---    ---    ---    ---  
0x7C   ---    ---    ---    ---  
0x7D   ---    ---    ---    ---  
0x7E   ---    ---    ---    ---  
0x7F   ---    ---    ---    ---  

