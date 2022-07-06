[中文版](./readme_zh.md)

# Please read this document before using 43 radiance 87

## 43 radiance 87 supports via, RGB axis lights and bottom lights

For the configuration of via, first you need to install via-1.3.1, then click file in the upper left corner of via, then import keymap, and select 43_ 87.json, if via doesn't recognize the keyboard at this time, you can unplug the keyboard from the computer, and then reconnect the keyboard to the computer.

It should be noted that if you connect 43 radiance 87 to the USBhub, the keyboard may not be used due to insufficient power supply. So try to connect the keyboard directly to the computer.

Configuration of RGB axis lamp:
![](readme_md_files/f216f0d0-fd30-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)
You can switch to the "QMK_LIGHTING" page in via. The red arrows in the picture refer to the control keys of RGB axis lights.

Axis light key value:
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

RGB bottom light configuration:
RGB bottom light configuration is relatively troublesome. You need to use any in the via special page to configure it, as shown in the following figure:
![](readme_md_files/7cead680-fd32-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

Use any to type the key value, as shown in the following figure:
![](readme_md_files/8ecbdd40-fd32-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

Bottom light key value:
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

If you want to insert the keyboard into the computer, via can automatically recognize the keyboard. You need to use viagenerator tool. I put it in the warehouse, and you can download it by yourself. The method is as follows:
Step 1: open viagenerator exe
![](readme_md_files/599773e0-fd33-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

Step 2: click the button indicated by the arrow
![](readme_md_files/81981570-fd33-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

Step 3: select 43_ 87.json
![](readme_md_files/b40dde90-fd33-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)

Step 4: click the button indicated by the arrow
![](readme_md_files/d1563510-fd33-11ec-b397-8bf224dd317c.jpeg?v=1&type=image)
