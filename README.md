# BMX055-raspberry
型号CJMCU-900F
3.3v接树莓派3.3v
GND接树莓派GND
SCL接树莓派SCL.1
SDA接树莓派SCL.1
PS接树莓派3.3v

连接后使用sudo i2cdetect -y 1查看IIC地址
修改对应的ACC_ADDRESS，GYR_ADDRESS，MAG_ADDRESS
