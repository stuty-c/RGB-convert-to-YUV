### 程序说明

将 RGB888 格式的颜色数据转化为 YUV 格式的数据输出

### 编译执行

    paul@maziot:~/work/maziot/RGB-convert-to-YUV$ ./app 0xFF0000
    y = 0x4c(h), 76(d), 76.245003(f)
    u = 0x55(h), 85(d), 84.904999(f)
    v = 0xff(h), 255(d), 255.500000(f)

    paul@maziot:~/work/maziot/RGB-convert-to-YUV$ ./app 0x00FF00
    y = 0x96(h), 150(d), 149.684998(f)
    u = 0x2c(h), 44(d), 43.595001(f)
    v = 0x15(h), 21(d), 21.155001(f)

    paul@maziot:~/work/maziot/RGB-convert-to-YUV$ ./app 0x0000FF
    y = 0x1d(h), 29(d), 29.070000(f)
    u = 0xff(h), 255(d), 255.500000(f)
    v = 0x6b(h), 107(d), 107.345001(f)

    paul@maziot:~/work/maziot/RGB-convert-to-YUV$ ./app 0xFFFFFF
    y = 0xff(h), 255(d), 255.000000(f)
    u = 0x80(h), 128(d), 128.000000(f)
    v = 0x80(h), 128(d), 128.000000(f)

    paul@maziot:~/work/maziot/RGB-convert-to-YUV$ ./app 0x000000
    y = 0x0(h), 0(d), 0.000000(f)
    u = 0x80(h), 128(d), 128.000000(f)
    v = 0x80(h), 128(d), 128.000000(f)

### 参考资料

<https://blog.csdn.net/liyuanbhu/article/details/68951683>