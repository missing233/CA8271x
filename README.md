# Hacking CA8271x XGS-PON Stick

Some information has been created with the help of `@stich86_0046`. Thanks!

- Rewrite S/N, Loid, PLOAM, etc… for your ISP FTTx
- Rewrite cheap 10G-EPON Stick to XGS-PON Stick

# XGS-PON ONT

| 10GE/XGS-PON ONT | Form | Vender | SoC | OEM | Mgmt IP | Mgmt | URL |
| --- | --- | --- | --- | --- | --- | --- | --- |
| XG-99S | SFP+ | CIG | CA8271S | -   | 192.168.100.1 | UART/Telnet | [Link](https://www.cigtech.com/product_portfolio/xg-99x-3/) |
| EN-XGSFPP-OMAC | SFP+ | E.C.I Networks | CA8271S | CIG XG-99S | 192.168.100.1 | UART/Telnet | [Link](https://ecin.ca/xgs-pon-sfp-stick-module-xgspon-ont-w-t-mac-function-mounted-on-sfp-package/) |
| EN-XGSFPP-OMAC-V2<br><br>***Not CA8271x SoC*** | SFP+ | E.C.I Networks | ***MxL PRX126*** | WAS-110 | 192.168.11.1 | Telnet/Web | [Link](https://ecin.ca/custom-xgs-pon-sfp-stick-module-xgspon-ont-w-t-mac-function-mounted-on-sfp-package/) |
| XGS-ONU-25-20NI | SFP+ | FS.com | CA8271S | CIG XG-99S | 192.168.100.1 | UART/Telnet | [Link](https://www.fs.com/jp/products/185594.html) |
| LTF-726x-BH+ | SFP+ | Hisense | CA8271S | -   | 192.168.0.1 | UART/SSH/Web | [Link](https://www.taobao.com/list/item/658650417501.htm) |
| XG-99M | ONT | CIG | CA8271A | -   | 192.168.0.1 | UART/Telnet | [Link](https://www.cigtech.com/product_portfolio/xg-99m/) |
| FOX222 | ONT | Frontier | CA8271A | CIG XG-99M | 192.168.188.1 | UART | -   |

# Menu

- [UART pin](/doc/UART.md)
- [ONT Login Password](/doc/Password.md)
- [How to get root CLI & root Shell](/doc/rootShell.md)
- [ONT scfg.txt files (CORTINA SoC Configuration file)](/doc/scfg_files.md)
- [ONT Configuration](/doc/Configuration.md)

* * *

# This document is a work in progress. More updates will follow.