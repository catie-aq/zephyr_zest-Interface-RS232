# Zest_Interface_RS232

Zest_Interface_RS232 board support for Zephyr OS.

## Usage
The zest-interface-rs232-uart alias is exposed by the overlay, allowing to use the RS232 interface with the default 6TRON uart interface (sixtron_uart).

Shield name: zest_interface_rs232.

## Sample Output 
This is the output from the JLink UART on the 6tron zest_core_stm32l4a6rg board.

*** Booting Zephyr OS build v3.7.0 ***

 ```shell
  main: UART device MAX3227IDBR is ready, sending message...
  ```
 ```shell
  main: Message sent!
  ```