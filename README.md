# hx711-lcd

```
apt-get install i2c-tools
apt-get install python-smbus
```

sudo vim /etc/modules
```
i2c-bcm2708
i2c-dev
```

sudo vim /etc/rc.local
```
...
python /home/pi/hx711py/example.py &
```

to test I2C devices
```
i2cdetect -y 1 
```
