### Simple create QR Image

``` git
git submodule add https://github.com/nghuyy/qrhelper.git

```


``` gradle
implementation fileTree(include: [ '*.aar'], dir: '../qrhelper')
implementation ("com.journeyapps:zxing-android-embedded:3.6.0")

```

``` JAVA
//Show qrcode with height 256
imageview.setImageBitmap(QR.createQR("data",256));
```
