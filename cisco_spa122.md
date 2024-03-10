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

## How to connect SPA122 to Raspberry PI

```
2 (TX) ->  10 (RX)
3 (RX) ->   8 (TX)
5 (GNC) ->  6 (GND)
```
![12415](https://github.com/tangoslee/notes/assets/42908571/6f984a57-e1f6-4e2f-9a72-5a7827968159)

![pi](https://github.com/tangoslee/notes/assets/42908571/f975d3c6-b7e0-4951-b9b1-07addc479002)


## References

- https://www.williamreading.com/2021/09/26/unlocking-a-spa122.html
- https://www.insentricity.com/a.cl/277/unlocking-a-cisco-spa122-for-use-with-any-provider
- https://pinout.xyz/
