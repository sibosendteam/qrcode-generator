
# qrcode-generator
&emsp;&emsp;这是一个java服务端的二维码生成器，可以根据参数生成各式各样的二维码，其中包括定制内容的形状和颜色，码眼的形状和颜色，以及添加logo。

# Install
* jdk1.8 
* eclipse / Intellij IDEA

# Run
该项目是采用main函数带参，打成jar包后将工程的res文件夹和jar包放在同一目录下，进入到根目录使用命令行运行：
*  java -jar xxx.jar 参数1 参数2 参数3 参数4 参数5 参数6 参数7 参数8

   * 参数1：二维码内容
   * 参数2：二维码图片保存地址（eg: D:/image OR D:）
   * 参数3：logo地址（有则输入logo路径，没有则输入N/n）
   * 参数4：二维码内容形状（0:液态状，1-8:矩形到圆点）
   * 参数5：二维码码眼类型（1-8对应不同形状，大于8默认为1）
   * 参数6：二维码内容区颜色（16进制RGB eg:39e8fa）
   * 参数7：码眼外框颜色（16进制RGB eg:39e8fa）
   * 参数8：码眼内框颜色（16进制RGB eg:39e8fa）

# UI
![code1](https://github.com/sibosend/qrcode-generator/blob/master/screenshot/qrCode1.png)
![code2](https://github.com/sibosend/qrcode-generator/blob/master/screenshot/qrCode2.png)
![code3](https://github.com/sibosend/qrcode-generator/blob/master/screenshot/qrCode3.png)
![code4](https://github.com/sibosend/qrcode-generator/blob/master/screenshot/qrCode4.png)
![code5](https://github.com/sibosend/qrcode-generator/blob/master/screenshot/qrCode5.png)