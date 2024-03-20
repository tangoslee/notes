Cisco SPA122

## Enntering configuration mode
```
****
```

## What the device IP is
```
****
110#
```

## turn on the web interface.
dial **** from the phone connected to your ATA,
then dial 7932#
and then dial 1 to turn on the web interface.
```
****
7932#
```


## Reset Device
```
****
73738#
```


## Default dial plan
### Origin
```
(*xx|[3469]11|0|00|[2-9]xxxxxx|1xxx[2-9]xxxxxxS0|xxxxxxxxxxxx.)
```
### After
```
{ x+ | \+x+ | *x+ | *xx*x+ }
```

## How to enable serial port for Raspberry PI

- Start configuration
```
raspi-config
```
- Interface interface > Serial Port
```
Would you like a login shell to be accessbile over serial? => No
Would you like the serial port hardware to be enabled? => Yes
```


Raspberry Pi for unlocking, you’ll want to start up raspi-config, go to ‘Interface Options’, ‘Serial Port’, disable the shell, but enable the hardware


## How to connect SPA122 to Raspberry PI

```
2 (TX) ->  10 (RX)
3 (RX) ->   8 (TX)
5 (GNC) ->  6 (GND)
```

![Screenshot from 2024-03-20 15-57-31](https://github.com/tangoslee/notes/assets/42908571/ed07bad6-6874-4fb0-862c-78404fe7f56a)

![pi](https://github.com/tangoslee/notes/assets/42908571/f975d3c6-b7e0-4951-b9b1-07addc479002)
![rpi4-pinout](https://github.com/tangoslee/notes/assets/42908571/08dc5d58-c378-4987-804a-b0b49093cc2f)


## Cisco SPA112 2-Port Phone Adapter
### Analog Telephone Adaptor (ATA) Firmware

[SPA112-SPA122_1.4.1SR5_FW.zip](https://github.com/tangoslee/notes/files/14553149/SPA112-SPA122_1.4.1SR5_FW.zip)

### Profile Compiler (SPC) Tool
[SPA112_SPA122_SPA232D_SPA302D_1.4.1_SPC.zip](https://github.com/tangoslee/notes/files/14553151/SPA112_SPA122_SPA232D_SPA302D_1.4.1_SPC.zip)


## References

- https://www.williamreading.com/2021/09/26/unlocking-a-spa122.html
- https://www.insentricity.com/a.cl/277/unlocking-a-cisco-spa122-for-use-with-any-provider
- https://pinout.xyz/
