9x
==

Firmware files for FS-TH9X

3dr-original-iris.eepe
  -- firmware settings almost as they came from the factory
   * enabled knobs for gimbal
   * set low battery alarm for Li-Po

3dr-original-iris.bin
  -- Firmware as shipped from 3dr
   er9x-r803
   V1.1481-Mike
   07.08.2103
   19:29:08

https://code.google.com/p/er9x/ is GPL code so this should be licensed the same.  This is mostly intended as a backup that I can go back to.

tools I used to get flashing up to telemetry:
  eepe-amd64.deb -- debian package of Eepe
  avrdude_6.1%2Bsvn1343_amd64.deb.zip -- updated version of avrdude to fix 0x0100 corruption issues
  er9x-frsky.hex -- Dec 12 2014 version of er9x with telemetry support