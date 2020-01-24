[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![Build Status](https://travis-ci.com/epernia/firmware_v3.svg?branch=master)](https://travis-ci.com/epernia/firmware_v3) (Estado de Travis CI)

# Firmware pada desarrollo de Sistemas Embebidos en C/C++ 

## IMPORTANTE

**�Este entorno est� en construcci�n!**

**Utilice siempre las versiones [release](../../../../releases) debido a que todos los ejemplos est�n testeados sobre las plataformas de hardware y la documentaci�n de la API es consistente. La rama master puede contener inconsistencias debido a que este entorno esta continuamente en desarrollo. Vea el estado de Travis CI en la etiqueta de arriba para conocer el estado actual del repositorio.**

## Acerca de firmware_v3

**firmware_v3** es un proyecto en base a *makefile* que act�a como framework para el desarrollo de *firm*ware para sistemas embebidos en lenguajes C/C++. Soporta *toolchain*, bibliotecas y ejemplos para m�ltiples plataformas de *hardware*.

## Plataformas de hardware soportadas

- [CIAA-NXP (LPC4337)](documentation/CIAA_Boards/NXP_LPC4337/CIAA-NXP/CIAA-NXP%20v1.0%20Board%20-%202019-01-04%20v3r0.pdf).
- [EDU-CIAA-NXP (LPC4337)](documentation/CIAA_Boards/NXP_LPC4337/EDU-CIAA-NXP/EDU-CIAA-NXP%20v1.1%20Board%20-%202019-01-03%20v5r0.pdf).

## Ejemplos

[Ver ejemplos](../firmware/examples/examples-es.md).

## Toolchains soportados

- gcc-arm-none-eabi 

## Bibliotecas disponibles:

- CMSIS 5.4.0 (Core y DSP). [Repositorio de CMSIS_5](https://github.com/ARM-software/CMSIS_5) (en ingl�s).
- LPCOpen v3.02 [Sitio web de NXP de la plataforma de desarrollo de software LPCOpen para LPC43XX NXP](https://www.nxp.com/design/microcontrollers-developer-resources/lpcopen-libraries-and-examples/lpcopen-software-development-platform-lpc43xx:LPCOPEN-SOFTWARE-FOR-LPC43XX) (en ingl�s).
- LPCUSBlib. [Documnetaci�n de LPCUSBlib](http://67.222.144.123/lpcopen/v1.03/group___l_p_c_u_s_blib.html) (en ingl�s).
- sAPI v0.5.2. [Referencia de la API de la biblioteca sAPI](../../libs/sapi/documentation/api_reference_es.md).
- Arduino (wiring). [Gu�a de Referencia de Arduino](https://www.arduino.cc/reference/es/).
- Elm-Chan FatFS R0.13b. [FatFS documentation](http://elm-chan.org/fsw/ff/00index_e.html) (en ingl�s). M�dulo de sistema de archivos FAT gen�rico con soporte para los discos: tarjeta SD (SSP) y Pendrive (USB MSD).
- FreeRTOS Kernel V10.0.1. [FreeRTOS_Reference_Manual_V10.0.0.pdf](../../examples/c/freertos_book/FreeRTOS_Reference_Manual_V10.0.0.pdf) (en ingl�s).
- RKH 3.2.3 [RKH Reference Manual](https://vortexmakes.com/rkh/) (en ingl�s).

## Utilizaci�n de firmware v3

- [Utilizaci�n b�sica de firmware_v3](../firmware/usage/usage-es.md).
- [Ejecutar *targets* de *makefile* con la Terminal](../firmware/terminal/targets-es.md).
- Utilizaci�n de firmware_v3 con Embedded IDE:
  - [Abrir el proyecto firmware_v3 en Embedded IDE](../firmware/embedded_ide/open/open-es.md).
  - [Ejecutar *targets* de *makefile* en Embedded IDE](../firmware/embedded_ide/targets/targets-es.md).

- Utilizaci�n de firmware_v3 con Eclipse:
  - [Abrir proyecto firmware_v3 en Eclipse](../firmware/eclipse/open/open-es.md).
  - [Compilar y descargar un programa del proyecto firmware_v3 en Eclipse](../firmware/eclipse/build/build-es.md).
  - [Depuraci�n de un programa sobre la plataforma de hardware con Eclipse](../firmware/eclipse/debug/debug-es.md).
  - [Configurar y ejecutar *targets* de de *makefile* en Eclipse](../firmware/eclipse/targets/targets-es.md).



[Volver al README principal](../../README.md).