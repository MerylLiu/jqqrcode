# jqqrcode
可以生成带logo的二维码的js库。

## 调用方式: ##
    1. 引用jquery.qrcode.min.js;
    2. 编写js:
        $('#output').qrcode({
            text: "TEST",
            height: 250,
            width: 250,
            logo: 'logo.png'//这里配置Logo的地址即可。
        });
    
