# HX711
HX711 Unit for Pascal/Lazaru/Delphi.

There are three source files in this repo.

BEWARE - PROJECT IS FOR BARE METAL PROGRAMMING!!! 
This is not a complete project. These are just SOME of the Pascal source files from a larger project that you can use as a base for GPIO
with Lazarus/FPC on the Raspberry Pi 3+.

There is a GPIO unit, and a globals unit ( You'll want to look through this and see which parts you want/need ) and then of course
the guts HX711 source file.

NOTE - Multithreading was used to poll the HX711 chip which made readings FAR more accurate and faster!

THERE IS NO WARRANTY WHAT SO EVER WITH THIS CODE. If you need help, please reach out and ask. I will try and assist.
