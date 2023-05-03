# STM32Nucleo Clock

This is a repost from my GitLab account to keep everything in the same place, here on GitHub. The original repo is [here](https://gitlab.com/lekxka/stm32nucleoclock).

### Text of the assignment in Croatian:

Korištenjem STM32L053 mikroupravljača i CubeMX i Atollic razvojne platforme (može i CubeIDE) treba napraviti sat koji će se upravljati putem UARTa. Sat mora imati mogućnost postavljanja vremena putem UART veze, kao i ispisivanje sata svake minute ili slanjem komande „SHOW CLOCK“. Za sat koristiti integrirani RTC modul unutar mikroupravljača koji koristi vanjski kristal od 32.768kHz.

Općenita pravila za realizaciju zadatka su:
1. Nije dozvoljeno koristiti Arduino IDE.
2. Treba paziti na urednost koda.
3. Kod treba biti strukturiran.
