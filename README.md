# Fichas técnicas y manuales — Estación de carga solar

Este repositorio reúne las **fichas técnicas y los manuales de referencia** de los componentes documentados durante el desarrollo del proyecto de tesis sobre el diseño y la validación de una estación de carga vehicular con energía solar, almacenamiento en baterías y respaldo de red.

Su propósito es facilitar la consulta de características técnicas, conexiones, especificaciones y recomendaciones de los fabricantes que sirven como soporte a la selección, integración y verificación de componentes.

## Organización del repositorio

La carpeta [`Datasheets`](Datasheets/) contiene **20 documentos PDF**, distribuidos en siete categorías:

| Carpeta | Documentación |
|---|---|
| [`01_GENERACION_FOTOVOLTAICA`](Datasheets/01_GENERACION_FOTOVOLTAICA/) | Ficha técnica del módulo fotovoltaico considerado en el proyecto. |
| [`02_CONTROLADORES_MPPT`](Datasheets/02_CONTROLADORES_MPPT/) | Fichas técnicas y manuales del sistema de regulación de carga solar. |
| [`03_ALMACENAMIENTO_Y_CONVERSION`](Datasheets/03_ALMACENAMIENTO_Y_CONVERSION/) | Documentación de la batería y del inversor de corriente. |
| [`04_SENSORES_Y_MEDICION`](Datasheets/04_SENSORES_Y_MEDICION/) | Documentación de sensores, convertidores analógico-digitales y equipos de medición. |
| [`05_COMUNICACIONES`](Datasheets/05_COMUNICACIONES/) | Fichas de los circuitos de interfaz utilizados o evaluados para la comunicación de datos. |
| [`06_CONTROL_Y_CARGA`](Datasheets/06_CONTROL_Y_CARGA/) | Documentación de la plataforma de procesamiento y del controlador de carga para vehículos eléctricos. |
| [`07_PROTECCIONES_Y_MANIOBRA`](Datasheets/07_PROTECCIONES_Y_MANIOBRA/) | Fichas de los dispositivos de protección y conmutación. |

## Documentos disponibles

### Generación fotovoltaica

- [`Panel Solar Suntech 550W.pdf`](Datasheets/01_GENERACION_FOTOVOLTAICA/Panel%20Solar%20Suntech%20550W.pdf) — Ficha técnica del módulo fotovoltaico Suntech de 550 W.

### Controladores MPPT

- [`Ficha_tecnica_Controlador_MPPT_sr_ml_12_24-LCD.pdf`](Datasheets/02_CONTROLADORES_MPPT/Ficha_tecnica_Controlador_MPPT_sr_ml_12_24-LCD.pdf) — Ficha técnica del controlador de carga solar MPPT.
- [`manual-Controlador-mppt-12-24.pdf`](Datasheets/02_CONTROLADORES_MPPT/manual-Controlador-mppt-12-24.pdf) — Manual del controlador MPPT de 12/24 V.

### Almacenamiento y conversión

- [`datasheet-inversor-belttt.pdf`](Datasheets/03_ALMACENAMIENTO_Y_CONVERSION/datasheet-inversor-belttt.pdf) — Ficha técnica del inversor Belttt.
- [`Ficha-tecnica-bateria-AGM-12-18Ah.pdf`](Datasheets/03_ALMACENAMIENTO_Y_CONVERSION/Ficha-tecnica-bateria-AGM-12-18Ah.pdf) — Ficha técnica de batería AGM de 12 V y 18 Ah.
- [`manual-de-usuario-inversor-onda-pura-1000w-12v-belttt-.pdf`](Datasheets/03_ALMACENAMIENTO_Y_CONVERSION/manual-de-usuario-inversor-onda-pura-1000w-12v-belttt-.pdf) — Manual del inversor Belttt de onda pura de 1000 W y 12 V.

### Sensores y medición

- [`ACS758.PDF`](Datasheets/04_SENSORES_Y_MEDICION/ACS758.PDF) — Ficha técnica del sensor de corriente ACS758.
- [`ads1015.pdf`](Datasheets/04_SENSORES_Y_MEDICION/ads1015.pdf) — Ficha técnica del convertidor analógico-digital ADS1015.
- [`ads1115.pdf`](Datasheets/04_SENSORES_Y_MEDICION/ads1115.pdf) — Ficha técnica del convertidor analógico-digital ADS1115.
- [`DS18B20.PDF`](Datasheets/04_SENSORES_Y_MEDICION/DS18B20.PDF) — Ficha técnica del sensor digital de temperatura DS18B20.
- [`FL2-shunt.pdf`](Datasheets/04_SENSORES_Y_MEDICION/FL2-shunt.pdf) — Documentación de la resistencia shunt FL-2.
- [`ina228.pdf`](Datasheets/04_SENSORES_Y_MEDICION/ina228.pdf) — Ficha técnica del monitor de corriente y potencia INA228.
- [`Medidor-de-Energia-Potencia-Voltaje-Corriente-RS485-Modbus-PZEM-016.pdf`](Datasheets/04_SENSORES_Y_MEDICION/Medidor-de-Energia-Potencia-Voltaje-Corriente-RS485-Modbus-PZEM-016.pdf) — Documentación del medidor eléctrico PZEM-016 con comunicación RS-485/Modbus.

### Comunicaciones

- [`MAX3232.PDF`](Datasheets/05_COMUNICACIONES/MAX3232.PDF) — Ficha técnica del transceptor MAX3232 para interfaz RS-232.
- [`MAX485.PDF`](Datasheets/05_COMUNICACIONES/MAX485.PDF) — Ficha técnica del transceptor MAX485 para interfaz RS-485.
- [`SC16IS740.PDF`](Datasheets/05_COMUNICACIONES/SC16IS740.PDF) — Ficha técnica del circuito de interfaz UART SC16IS740.

### Control y carga

- [`Controlador_de_Carga_EVSE_EKEPC2.pdf`](Datasheets/06_CONTROL_Y_CARGA/Controlador_de_Carga_EVSE_EKEPC2.pdf) — Documentación del controlador de carga EVSE EKEPC2.
- [`RP-008359-DS-1-raspberry-pi-zero-2-w-product-brief.pdf`](Datasheets/06_CONTROL_Y_CARGA/RP-008359-DS-1-raspberry-pi-zero-2-w-product-brief.pdf) — Resumen de producto de Raspberry Pi Zero 2 W.

### Protecciones y maniobra

- [`EKL6-100B_Type_B_RCCB.pdf`](Datasheets/07_PROTECCIONES_Y_MANIOBRA/EKL6-100B_Type_B_RCCB.pdf) — Ficha técnica del interruptor diferencial tipo B EKL6-100B.
- [`EKMF Din AC Modular Contactor.pdf`](Datasheets/07_PROTECCIONES_Y_MANIOBRA/EKMF%20Din%20AC%20Modular%20Contactor.pdf) — Ficha técnica del contactor modular EKMF.

## Cómo consultar los documentos

1. Seleccionar una de las categorías anteriores.
2. Abrir la ficha técnica o el manual correspondiente en formato PDF.
3. Contrastar sus especificaciones con el componente identificado en el diseño, los planos o los protocolos de prueba de la tesis.

> **Nota:** Los documentos del repositorio incluyen referencias de componentes y modelos evaluados durante el proyecto. La presencia de una ficha técnica no implica necesariamente que ese modelo sea el utilizado en la versión final del prototipo. Para citar una especificación, se debe comprobar que el modelo y la revisión del documento correspondan al componente analizado.

