# check_temper
Control de temperatura mediante dispositivos USB Temper (pcsensor)

Puede utilizarse como un plugin para **Icinga** y **Nagios**

check_temper -w warning -c critical

- warning: Valor en grados celsius para estado WARNING
- critial: Valor en grados celsius para estado CRITICAL

# Instalación

    1. Descargar plugin ```git clone https://github.com/fmbrieva/check_temper```
    2. Instalar plugin  ```.\check_temper_install```

# PCsensor USB Temper 
USB Temper probados:
- PCsensor TEMPerGold (1a86:e025)
- PCsensor TEMPer2 (3553:a001)

# Créditos
**check_temper** utiliza componentes del repositorio https://github.com/edorfaus/TEMPered para instalar la utilidad **hid-query**. Reconocemos y agradecemos a los desarrolladores su contribución al código abierto.

**check_temper** uses components from the repository https://github.com/edorfaus/TEMPered to install **hid-query** utility. we acknowledge and are grateful to these developers for their contributions to open source.

