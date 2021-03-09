# tuya-mcu-sdk devices.
This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.
For more information, please check Tuya Developer Website.
一，方案标题 智能蜜蜂养殖系统
二，方案应用场景 养蜂场
    地点：养蜂场
    背景：蜜蜂喜欢生活在黑暗，干燥，安静的环境下，并且巢虫对蜜蜂的危害特别大。
    功能：本设计采用mcu采集光敏电阻的阻值，从而判定蜂箱内的光线是否达到标准，通过采集的电压值进行确定，通常为零最好，并且上报给手机APP，
    检测干燥程度和温度采用dht11，首先先通过mcu读取出温湿度，通过查找蜜蜂生存的最适合的温湿度，当温度低于最适温湿度时，mcu将发出报警，以点亮led等作为警告。
    检测周围的环境是否符合蜜蜂的生存，采用声音传感器，当声音超过一定分贝时，将不适合蜜蜂的生存，在此时用蜂鸣器作为警报器，检测蜂巢内是否有巢虫，采用红外检测，首先测出蜂箱的长度，并用mcu测出实际距离，当测出的实际距离小于蜂箱的长度时，此时将会上传警示，蜜蜂养殖人员只需在家就能知道风场的情况。
三，开发计划
  3月12号前完成整体设计
  3月18号前完成物料准备并按自己思路连接好电路
  3月26号前完成开发
  
