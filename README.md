# check_temper
Plugin para control de temperatura mediante dispositivos USB Temper (pcsensor) para **Icinga** y **Nagios**

check_temper -w warning -c critical

- warning: Valor en grados celsius para estado WARNING
- critical: Valor en grados celsius para estado CRITICAL

# Instalación

- Descargar plugin ```git clone https://github.com/fmbrieva/check_temper```
- Instalar plugin
   - ```cd check_temper```
   - ```chmod +x check_temper check_temper_install```
   - ```./check_temper_install```

# PCsensor USB Temper 
USB Temper probados:
- PCsensor TEMPerGold (1a86:e025)
- PCsensor TEMPer2 (3553:a001)

El calor generado por el ordenador puede afectar la lectura del sensor de temperatura si se conecta directamente, por eso es recomendable conectar el sensor de temperatura mediante un cable USB para evitar cualquier alteración en los resultados.

# Créditos
**check_temper** utiliza componentes del repositorio https://github.com/edorfaus/TEMPered para instalar la utilidad **hid-query**. Reconocemos y agradecemos a los desarrolladores su contribución al código abierto.

**check_temper** uses components from the repository https://github.com/edorfaus/TEMPered to install **hid-query** utility. we acknowledge and are grateful to these developers for their contributions to open source.

