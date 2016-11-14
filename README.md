# ducky-scripts
Assorted (Harmless) [USB Rubber Ducky](http://usbrubberducky.com/) Script Payloads

```
      _      _      _      USB       _      _      _
   __(.)< __(.)> __(.)=   Rubber   >(.)__ <(.)__ =(.)__
   \___)  \___)  \___)    Ducky!    (___/  (___/  (___/
```

Usage:
```
java -jar lib/encoder.jar -l us -i <ducky-script>.txt -o '/Volumes/NO NAME/inject.bin'
```

To emulate an Apple keyboard, place the `vidpid/apple-aluminum-ansi/vidpid.bin`
at the root of the ducky.

To Generate Keyboard Vid Pid files for other keyboards, use this generator
or a hex editor:
https://lucidox.com.au/vidpid/
