# README

This example program sends some characters on USART3 on the ST STM32-based
[Olimex STM32-H103 eval board](http://olimex.com/dev/stm32-h103.html).

The terminal settings for the receiving device/PC are 38400 8n1.

The sending is done in a blocking way in the code, see the usart\_irq example
for a more elaborate USART example.

