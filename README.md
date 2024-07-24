天气数据使用彩云api，预警信息使用和风api

107和465行换成自己的api密钥和经纬度。

例如：
把 https://api.caiyunapp.com/v2.6/密钥/经纬度/weather?unit=metric:v2&callback=displayWeather
换成： https://api.caiyunapp.com/v2.6/abcdefg/120.20,30.33/weather?unit=metric:v2&callback=displayWeather 即可

https://devapi.qweather.com/v7/warning/now?location=经纬度&key=密钥

彩云免费api只能看最近两天的预报，我也没招，能用就行。

彩云API申请：https://docs.caiyunapp.com/weather-api/index.html 免费1w次/天
和风API申请：https://dev.qweather.com 免费1k次/天

经纬度获取：https://api.map.baidu.com/lbsapi/getpoint/index.html

本地html，直接保存到本地用记事本改完api密钥和经纬度用浏览器打开就行。
![image](https://github.com/user-attachments/assets/fdefc378-d64c-49b5-ba1a-9b0b6f5715df)
![image](https://github.com/user-attachments/assets/485e14de-e84d-43d5-b32a-25c7ffd32a9e)

