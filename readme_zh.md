# 在使用43 radiance 87 之前请阅读此文档

## 43 radiance 87 支持via、rgb轴灯和底灯

对于via的配置，首先你需要安装via-1.3.1，然后点击via左上角的file，接着import keymap，选中43_87.json，如果这个时候via没有识别到键盘，你可以把键盘从电脑上面拔下来，接着重新将键盘连接电脑。

需要注意的是，如果你将43 radiance 87 接在usbhub上面，那么可能会因为供电不足而导致键盘不可使用。所以尽量将键盘直接与电脑连接。

RGB轴灯的配置：
![](readme_md_files/f216f0d0-fd30-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)
你可以在via里面切换到QMK_LIGHTING页面，上图片中红色的箭头所指的都是RGB轴灯的控制按键。

轴灯键值：
Keycode| Function
-------- | -----
RGB_Toggle| Switch light
RGB_Mode-//RGB_Mode+| Switch light effect
Hue- | Reduce hue 
Hue+ | Increase hue
Sat- | Reduce saturation 
Sat+ | Increase Saturation
Bright- | Reduce brightness
Bright+ | Increase brightness
EffectSpeed- | Reduce speed
EffectSpeed+ | Increase speed

RGB底灯配置：
RGB底灯配置相对较麻烦，你需要使用到via special 页面里面的Any来配置，如下图：
![](readme_md_files/7cead680-fd32-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

使用Any键入键值，像下图这样：
![](readme_md_files/8ecbdd40-fd32-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

底灯键值：
Keycode| Function
-------- | -----
0x5d10 | Switch light
0x5d0b | Switch light effect
0x5d09 | Reduce hue 
0x5d0a | Increase hue
0x5d0c | Reduce saturation 
0x5d0d | Increase Saturation
0x5d11 | Reduce brightness
0x5d12 | Increase brightness
0x5d0e | Reduce speed
0x5d0f | Increase speed

如果你想往电脑上插上键盘的时候via能够自动识别到键盘，你需要借助VIAGenerator工具，我将他放在此仓库里面，你可以自行下载使用，方法如下：
第一步：打开VIAGenerator.exe
![](readme_md_files/599773e0-fd33-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

第二步：点击箭头所指的按钮
![](readme_md_files/81981570-fd33-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

第三步：选择43_87.json
![](readme_md_files/b40dde90-fd33-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

第四步：点击箭头所指按钮
![](readme_md_files/d1563510-fd33-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)
