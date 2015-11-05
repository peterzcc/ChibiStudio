*****************************************************************************
*** Installation                                                          ***
*****************************************************************************

There is no setup nor settings to do:
1) Unpack the archive under C:\ in order to have C:\ChibiStudio as
   installation path.
2) Copy the shortcut "C:\ChibiStudio\Chibi Studio" on your desktop.
3) Use the shortcut to launch ChibiStudio.

You may need to install the drivers for your JTAG probe, OpenOCD has some
drivers under C:\ChibiStudio\tools\openocd\drivers. Please consult the
OpenOCD documentation in C:\ChibiStudio\tools\openocd\OpenOCD User’s Guide.pdf
and the documentation of your JTAG probe.

*****************************************************************************
*** Components                                                            ***
*****************************************************************************

- Eclipse Luna 4.4.1 (http://www.eclipse.org) with the following
  optional components installed:
  - Eclipse CDT 8.6.0.
  - C/C++ GDB Hardware Debugging 8.6.0.
  - Eclipse XML Editors and Tools 3.6.1.
  - Target Management Terminal 3.7.0.
  - ChibiOS Eclipse Tools to 2.0.0.
  - Embedded Systems Register View plugin 0.2.5.
- GCC ARM toolchain (https://launchpad.net/gcc-arm-embedded)
  gcc-arm-none-eabi-4_7-2014q2.
- GCC ARM toolchain (https://launchpad.net/gcc-arm-embedded)
  gcc-arm-none-eabi-4_9-2015q3.
- YAGARTO Tools (http://www.yagarto.de).
- OpenOCD 0.9.0-dev-150204220259 (http://http://www.freddiechopin.info/).
- ChibiOS/RT 2.6.9 stable.
- ChibiOS 3.0.2 stable.

*****************************************************************************
*** Releases                                                              ***
*****************************************************************************

*** Preview 14 ***
- Updated ChibiOS Eclipse Tools to 2.0.1.
- Updated trunk code to revision 8391.

*** Preview 13 ***
- Updated ChibiOS Eclipse Tools to 2.0.0.
- Updated ChibiOS 3 to 3.0.2 stable.
- Updated alternate compiler to gcc-arm-none-eabi-4_9-2015q3.
- Updated OpenOCD to be able to use STM32F7/L0/L4.
- Added another workspace for ChibiOS trunk code.

*** Preview 12 ***
- Updated ChibiOS 3 to 3.0.1 stable.
- Updated ChibiOS/RT to 2.6.9 stable.
- Updated alternate compiler to gcc-arm-none-eabi-4_9-2015q2.

*** Preview 11 ***
- Updated ChibiOS 3.0.0 to preview 5.
- Updated to ChibiOS/RT 2.6.8 stable.
- Added more MSYS commands in order to support the new "smart build" mode.

*** Preview 10 ***
- Updated ChibiOS 3.0.0 to preview 2.
- Updated alternate compiler to gcc-arm-none-eabi-4_9-2015q1.
- Updated the configuration plugin to 1.6.1.
- ChibiOS 3.0 workspace now is the default one.

*** Preview 9 ***
- Updated to ChibiOS/RT 2.6.7 stable.
- Updated ChibiOS 3.0.0 to revision 7707.
- Updated OpenOCD to openocd-0.9.0-dev-150204220259.
- Re-added the missing RXTX Serial Connector to the terminal window.

*** Preview 8 ***
- Updated to ChibiOS/RT 2.6.6 stable.
- Added ChibiOS 3.0.0 development including RT, NIL and HAL.
- Updated to Eclipse Luna.
- Added gcc-arm-none-eabi-4_9-2014q4 as alternate compiler, removed
  bleeding edge toolchain.
- Now there are two workspaces, one for ChibiOS 2.6 another one for 3.0.
- Java 7 is a minimum requirement.
- Added debug and configuration support for ChibiOS 3.0.
- In order to save space now projects are no more pre-indexed, you have to
  re-index projects after compiling them the first time.

*** Preview 7 ***
- Updated to ChibiOS/RT 2.6.5 stable.

*** Preview 6 ***
- Updated to ChibiOS/RT 2.6.4 stable.
- Updated to OpenOCD 0.8.0.
- Updated to gcc-arm-none-eabi-4_7-2014q2.
- Added alternate compiler: bleeding-edge-toolchain-140405 4.8.3.
  Use C:\ChibiStudio\start2.bat in order to use the alternate compiler.

*** Preview 5 ***
- Updated to ChibiOS/RT RC2.

*** Preview 4 ***
- Updated to ChibiOS/RT RC1.

*** Preview 3 ***
- Updated to ChibiOS/RT 2.5.1.
- Updated to ChibiOS/RT configuration plugin 1.2.1
- Updated to OpenOCD 0.7.0dev.
- Updated to gcc-arm-none-eabi-4_6-2012q4.

*** Preview 2 ***
- Removed some unused files.
- Updated to ChibiOS/RT 2.5.0.
- Added ChibiOS/RT configuration plugin 1.1.0.
- Updated to OpenOCD 0.6.0-rc2.

*** Preview ***
- Initial release.
